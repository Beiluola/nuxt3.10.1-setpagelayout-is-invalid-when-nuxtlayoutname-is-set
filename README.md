## Steps

1. `pnpm i`
2. `pnpm dev`
3. open `/test` page, the `default layout` text is displayed
4. open `app.vue`, delete `name` attribute
5. open `/test` page, the `empty layout` text is displayed

this is document content about `NuxtLayout name`:

> name: Specify a layout name to be rendered, can be a string, reactive reference or a computed property. It must match the name of the corresponding layout file in the layouts/ directory.

this is document content about `setPageLayout`:

> setPageLayout allows you to dynamically change the layout of a page.

I'm not sure if this is a feature or a bug.
