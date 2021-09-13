# Doc 
> See [README_DAWN](README_DAWN.md) for more info

## Architecture
### Assets

The assets directory contains all of the assets used in a theme, including image, CSS, and JavaScript files.

Use the asset_url Liquid URL filter to reference an asset within your theme.

You can access limited Liquid functionality in non-binary asset files by appending a **.liquid** extension. Common use cases include JavaScript (**.js.liquid**) and CSS (**.css.liquid**) files. Files with this extension have access to the following features:
    - The [settings object](https://shopify.dev/api/liquid/objects#settings)
    - Liquid [filters](https://shopify.dev/api/liquid/filters)
