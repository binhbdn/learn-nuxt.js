https://nuxtjs.org/guides/get-started/routing

# #1. Automatic Routes
- Most websites will have more than one page (i.e. a home page, about page, contact page etc.). In order to show these pages, we need a Router. That's where vue-router comes in.
- When working with the Vue application, you have to set up a configuration file (i.e. router.js) and add all your routes manually to it.
- All you have to do to have routing in your application is to create .vue files in the pages folder.
- Nuxt.js automatically generates the vue-router configuration for you, based on your provided Vue files inside the pages directory, you never have to write a router config.
- Nuxt.js also gives you automatic code-splitting for all your routes.

# #2. Navigation
- To navigate between pages of your app, you should use the NuxtLink component.
- This component is included with Nuxt.js and therefore you don't have to import it as you do with other components.
-  It is similar to the HTML <a> tag, except that instead of using a href="/about" we use to="/about".
- If you have used vue-router before, you can think of the <NuxtLink> as a replacement for <RouterLink>

- For all links to pages within your site, use <NuxtLink>.
- If you have links to other websites you should use the <a> tag.

# #3. Learn more about [Routing](https://nuxtjs.org/guides/features/file-system-routing)
# #4. Learn more about the [NuxtLink component](https://nuxtjs.org/guides/features/nuxt-components#the-nuxtlink-component)