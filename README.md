> [!WARNING]
> I am in the early stages of developing this repository.

# Hugo beautiful shortcodes

A beautiful collection of self-standing hugo shortcodes.
The main aim behind this project is to give a collection of shortcodes that can be used as building blocks for your website.

# Dependencies

- [Hugo](https://gohugo.io/): the static site generator.
- [Bootstrap](https://getbootstrap.com/): not required for every shortcode styles. Actually, the CSS and JavaScript are downloaded in the assets folder, thus you do not need to include the entire Bootstrap library in your project if you use this repo as a template.

# Shortcodes

## Standalone

These shortcodes are self-standing and don't need any other dependencies (i.e. Bootstrap) to work. You can use them in any Hugo project by copying the shortcode file in your project's `layouts/shortcodes` folder.

## Bootstrap dependent

These shortcodes depend on Bootstrap for styling. You can use them in any Hugo project by copying the shortcode file in your project's `layouts/shortcodes` folder and the css and js files in the `assets` folder.

{% include image.html url="http://www.storywarren.com/wp-content/uploads/2016/09/space-1.jpg" description="A space image for testing" %}
