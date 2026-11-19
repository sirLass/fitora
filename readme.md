# Fitora

Shopify theme for the Fitora storefront, based on [Dawn 16.2.0](https://github.com/Shopify/dawn), Shopify's reference Online Store 2.0 theme.

## Theme structure

- `assets/` — CSS, JavaScript, images, and fonts
- `config/` — theme settings and settings schema
- `layout/` — base layout files (`theme.liquid` is required by Shopify)
- `locales/` — translation files
- `sections/` — customizable storefront sections
- `snippets/` — reusable Liquid partials
- `templates/` — page, product, collection, and other templates

## Connect to Shopify

1. In Shopify admin, go to **Online Store → Themes**.
2. Click **Add theme → Connect from GitHub**.
3. Select the `sirLass/fitora` repository.
4. Select the `main` branch.
5. After the theme is imported, use **Customize** to preview it, then **Publish** when ready.

## Local development

Install [Shopify CLI](https://shopify.dev/docs/storefronts/themes/tools/cli), then run:

```sh
shopify theme dev --store your-store.myshopify.com
```

Validate the theme with:

```sh
shopify theme check
```

## License

Based on Dawn, which is released under the MIT License. See [LICENSE.md](LICENSE.md).
