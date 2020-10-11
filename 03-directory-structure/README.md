- https://nuxtjs.org/guides/get-started/directory-structure
- [Open CodeSandbox](https://codesandbox.io/s/github/nuxt-academy/guides-examples/tree/master/01_get_started/03_directory_structure?file=/pages/index.vue)

These are the main directories and files that we use when building a Nuxt.js application:
- ~$ mkdir components assets static
- ~$ touch nuxt.config.js
Creating directories with these names enables features in your Nuxt.js project.

# I. Directories
# I.1. pages directory
- contains your application's views and routes
- learn more about the [pages directory](https://nuxtjs.org/guides/directory-structure/pages)

# I.2. components directory
- is where you put all your Vue.js components which are then imported into your pages
- from v2.13, Nuxt can auto import your components when used in your templates, to activate this feature, set components: true in your configuration (nuxt.config.js):
export default {<br>
  components: true<br>
}<br>
- learn more about the [components directory](https://nuxtjs.org/guides/directory-structure/components)

# I.3. assets directory
- contains your uncompiled assets such as your styles, images, or fonts
- learn more about the [assets directory](https://nuxtjs.org/guides/directory-structure/assets)

# I.4. static directory
- is directly mapped to the server root and contains files that have to keep their names (e.g. robots.txt) or likely won't change (e.g. the favicon)
- learn more about the [static directory](https://nuxtjs.org/guides/directory-structure/static)

# I.5. nuxt.config.js file
-  is the single point of configuration for Nuxt.js. If you want to add modules or override default settings, this is the place to apply the changes
- learn more about the [nuxt.config.js file](https://nuxtjs.org/guides/directory-structure/nuxt-config)

# I.6. package.json file
-  contains all the dependencies and scripts for your application


# II. More about the project structures
- including [content](https://nuxtjs.org/guides/directory-structure/content), [layouts](https://nuxtjs.org/guides/directory-structure/layouts), [middleware](https://nuxtjs.org/guides/directory-structure/middleware), [modules](https://nuxtjs.org/guides/directory-structure/modules), [plugins](https://nuxtjs.org/guides/directory-structure/plugins) and [store](https://nuxtjs.org/guides/directory-structure/store)
- To learn about all directories in detail, feel free to read the the [Directory Structure book](https://nuxtjs.org/guides/directory-structure/nuxt)