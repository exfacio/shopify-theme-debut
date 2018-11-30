# Ex Facio Shopify Theme

## 🚨 Caution

As of right now modifying the theme via `npm run dev` will update the live site. We'll need to setup an actual dev store post launch.

## Getting Started with Shopify Themes

https://github.com/Shopify/slate

## Development

1. Get `config.yml` file that contains app secrets.
2. `npm i`
3. `npm run dev`

### Notes

- When editing scss files, always edit `*.scss.liquid`. The liquid files have access to theme settings from the Shopify store and will automatically be converted from liquid to scss, then from scss to css.

### Resources 

- [Theme Settings & settings_schema.json](https://help.shopify.com/en/themes/development/theme-editor/settings-schema)
- [Understanding Shopify Theme Styles and Presets With settings_data.json](https://www.shopify.com/partners/blog/shopify-theme-styles-and-presets)
