> [!WARNING]
> I am in the early stages of developing this repository.

# Hugo beautiful shortcodes

A beautiful collection of self-standing hugo shortcodes.

# Dependencies

- [Hugo](https://gohugo.io/): the static site generator.
- [Bootstrap](https://getbootstrap.com/): for the styling of the shortcodes. Actually the css and js are downloaded in the assets folder, so you don't need to include the whole bootstrap library in your project.

# Shortcodes

## Standalone

These shortcodes are self-standing and don't need any other dependencies (i.e. Bootstrap) to work. You can use them in any Hugo project by copying the shortcode file in your project's `layouts/shortcodes` folder.

## Bootstrap dependent

These shortcodes depend on Bootstrap for styling. You can use them in any Hugo project by copying the shortcode file in your project's `layouts/shortcodes` folder and the css and js files in the `assets` folder.
