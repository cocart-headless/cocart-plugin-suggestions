<h1 align="center">CoCart - Plugin Suggestions</h1>

<p align="center"><img src="https://cocart.xyz/wp-content/uploads/2021/11/cocart-home-default.png.webp" alt="CoCart Logo" /></p>

These plugin suggestions are pulled into the CoCart plugin when the user views the "CoCart" tab on the "Add Plugin" page. They are fetched once a week and cached.

## Instructions

When you have tested a plugin developed by either third party or a WooCommerce extension then add it to the JSON file `suggestions.json` like so.

```json
"woocommerce-name-your-price": {
    "name": "WooCommerce Name Your Price",
    "slug": "woocommerce-name-your-price",
    "author": "Kathy Darling",
    "search_terms": "nyp, name your price, pay what you want, product page feature, enhancements",
    "short_description": "Let customers pay what they want with Name Your Price",
    "logo": "https://suggestions.cocartapi.com/images/kia-logo.png",
    "requirement": false,
    "requires": "4.4",
    "tested": "5.3",
    "requires_php": "7.0",
    "rating": 0,
    "num_ratings": 0,
    "active_installs": 0,
    "last_updated": "",
    "learn_more": "https://woocommerce.com/products/name-your-price/",
    "third_party": true
},
```

Remember that you need to provide name, search terms, requirements, a logo and anything else that will help identify the plugin.

New additions will be uploaded to `https://suggestions.cocartapi.com/plugin/1.0/suggestions.json` when made available.
