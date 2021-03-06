<p align="center">
	<img src="/.github/orbit.png" width="175">
</p>

# Orbit
Orbit is a Vue.js UI Component Library built on a beautiful, cohesive design system.

Orbit includes over 50 easy to use components and enables you to quickly construct clean and scalable applications.

## Documentation
- [Contribution Guide](/src/CONTRIBUTING.md) - Learn about Orbit component development, testing, and release steps

## Quick start
#### #1 Add Orbit as a dependency
```
npm install --save @square/orbit
```

#### #2 Import the CSS
Import the following CSS file as an asset to your build. <strong>Do not</strong> @import them into the style tag of your App.vue, as doing so will unecessarily pre-process them.

<ul>
<li><strong>@square/orbit/styles.css</strong>: includes all the base css for orbit components</li>
</ul>

#### #3 Import an Orbit component
<p>Update /src/App.vue with the following:</p>

```
<template>
  <div id="app">
    <h1>Orbit v2</h1>
    <o-button>Button</o-button>
  </div>
</template>

<script>
  // Components are imported individually as needed.
  // Note the object {} syntax. 'import OButton' will not work.
  import { OButton } from '@square/orbit/components/Button';

  export default {
    name: 'app',
    components: { OButton }
  }
</script>
```

## Browser Support
Orbit supports [all evergreen browsers](/.browserslistrc).

## Changelog
Every release and their changes are documented in [Releases](https://github.com/square/orbit/releases).

## License
[Apache-2.0](./LICENSE)
