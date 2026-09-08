# Themes Variable

## Variables in Shoppego Themes

This documentation lists all variables available in Shoppego Themes.

These variables allow theme developers to access store data, products, categories, pages, menus, and theme settings inside Twig templates.

Each variable includes a description, example value, and practical usage so you can build fully-custom themes with full control over your storefront UI and data.

### On this page

1. [Filters](themes-variable.md#filters)
2. [Home structure variables](themes-variable.md#home-structure-variables)
3. [Product structure variables](themes-variable.md#product-structure-variables)
4. [Products structure variables](themes-variable.md#products-structure-variables)
5. [Cart structure variables](themes-variable.md#cart-structure-variables)
6. [Page structure variables](themes-variable.md#page-structure-variables)
7. [404 structure variables](themes-variable.md#id-404-structure-variables)
8. [Parameters](themes-variable.md#parameters)

### Filters

| Parameter                | Description                                                                      |
| ------------------------ | -------------------------------------------------------------------------------- |
| product\_image\_size     | Returns the product image URL in the specified size (e.g., small, medium, large) |
| money                    | Formats a number into store currency format (e.g., RM120.00)                     |
| money\_without\_currency | Formats a number as price but without showing the currency symbol (e.g., 120.00) |
| placeholder\_svg\_tag    | Generates a placeholder SVG image (used when no product image is available)      |
| truncate                 | Shortens plain text to a set number of characters and adds … at the end          |
| truncate\_html           | Similar to truncate but keeps HTML tags intact while shortening text             |
| json                     | Converts a value or array into a JSON string                                     |
| json\_decode             | Converts a JSON string back into an array/object for use in Twig                 |

### Home Structure Variables

In the Home structure, you will be able to use parameters from:

1. [Store parameter](themes-variable.md#store-parameter)
2. [General parameter](themes-variable.md#general-parameter)
3. [Cart parameter](themes-variable.md#cart-parameter)
4. [Settings parameter](themes-variable.md#settings-parameter)
5. [Menus parameter](themes-variable.md#menus-parameter)
6. [Page parameter](themes-variable.md#page-parameter)
7. [Products parameter](themes-variable.md#products-parameter)
8. [Categories parameter](themes-variable.md#categories-parameter)

### Product Structure Variables

In the Product structure, you will be able to use parameters from:

1. [Store parameter](themes-variable.md#store-parameter)
2. [General parameter](themes-variable.md#general-parameter)
3. [Cart parameter](themes-variable.md#cart-parameter)
4. [Settings parameter](themes-variable.md#settings-parameter)
5. [Menus parameter](themes-variable.md#menus-parameter)
6. [Page parameter](themes-variable.md#page-parameter)
7. [Products parameter](themes-variable.md#products-parameter)
8. [Product parameter](themes-variable.md#product-parameter)
9. [Product related parameter](themes-variable.md#product-related-parameter)
10. [Product wholesale parameter](themes-variable.md#product-wholesale-parameter)
11. [Product bundle parameter](themes-variable.md#product-bundle-parameter)
12. [Categories parameter](themes-variable.md#categories-parameter)

### Products Structure Variables

In the Products structure, you will be able to use parameters from:

1. [Store parameter](themes-variable.md#store-parameter)
2. [General parameter](themes-variable.md#general-parameter)
3. [Cart parameter](themes-variable.md#cart-parameter)
4. [Settings parameter](themes-variable.md#settings-parameter)
5. [Menus parameter](themes-variable.md#menus-parameter)
6. [Page parameter](themes-variable.md#page-parameter)
7. [Products parameter](themes-variable.md#products-parameter)
8. [Categories parameter](themes-variable.md#categories-parameter)

### Cart Structure Variables

In the Cart structure, you will be able to use parameters from:

1. [Store parameter](themes-variable.md#store-parameter)
2. [General parameter](themes-variable.md#general-parameter)
3. [Cart parameter](themes-variable.md#cart-parameter)
4. [Cart bundle parameter](themes-variable.md#cart-bundle-parameter)
5. [Settings parameter](themes-variable.md#settings-parameter)
6. [Menus parameter](themes-variable.md#menus-parameter)

### Page Structure Variables

In the Page structure, you will be able to use parameters from:

1. [Store parameter](themes-variable.md#store-parameter)
2. [General parameter](themes-variable.md#general-parameter)
3. [Cart parameter](themes-variable.md#cart-parameter)
4. [Settings parameter](themes-variable.md#settings-parameter)
5. [Menus parameter](themes-variable.md#menus-parameter)
6. [Page parameter](themes-variable.md#page-parameter)
7. [Page/{slug} parameter](themes-variable.md#page-slug-parameter)

### 404 Structure Variables

In the 404 structure, you will be able to use parameters from:

1. [Store parameter](themes-variable.md#store-parameter)
2. [General parameter](themes-variable.md#general-parameter)
3. [Cart parameter](themes-variable.md#cart-parameter)
4. [Settings parameter](themes-variable.md#settings-parameter)
5. [Menus parameter](themes-variable.md#menus-parameter)
6. [Categories parameter](themes-variable.md#categories-parameter)

### Parameters

#### Store Parameter

| Parameter                         | Description                                                                                                                                          |
| --------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| store.name                        | The display name of the store. Example: "My Boutique Store".                                                                                         |
| store.description                 | A short summary or tagline describing your store. Useful for SEO and metadata display. Example: "Your trusted shop for handmade shawls and scarves." |
| store.currency\_format            | Defines how prices are displayed throughout the store, including symbol placement. Example: "$ {amount}" or "{amount} MYR".                          |
| store.timezone                    | The timezone setting used for displaying local time (e.g., in orders, reports). Example: "Asia/Kuala\_Lumpur".                                       |
| store.checkout\_enabled           | Determines whether the online checkout process is active. If set to false, users can browse products but cannot complete a purchase. Example: true.  |
| store.checkout\_minimum\_purchase | Sets the minimum total amount (in store currency) required before checkout is allowed. Example: 50 (meaning RM50 minimum).                           |
| store.category\_featured          | Lists category IDs or slugs that should appear in the “Featured Categories” section on the homepage. Example: \["shawls", "hijabs", "accessories"].  |
| store.currency.code               | The store’s ISO currency code, used for pricing, payments, and formatting. Example: "MYR" for Malaysian Ringgit or "USD" for U.S. Dollars.           |

#### General Parameter

| Parameter   | Description                                                                                                                                                                                              |
| ----------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| css         | Contains the list or inline string of CSS files/links to be loaded in the template. Example: \["/assets/css/theme.css", "/assets/css/custom.css"].                                                       |
| js          | Contains the list or inline string of JavaScript files/scripts to be included, usually before the closing tag. Example: \["/assets/js/main.js"].                                                         |
| head        | Custom HTML or meta tags to be injected inside the section of the page. Often used for SEO, analytics, or third-party integrations.                                                                      |
| head\_tag   | Allows dynamic injection of additional tags, such as tags from the backend or plugin system.                                                                                                             |
| body\_tag   | Allows dynamic injection of additional tags, such as tags from the backend or plugin system.                                                                                                             |
| csrf\_token | A security token used to protect forms from Cross-Site Request Forgery (CSRF) attacks. Must be included in forms that modify data. Example: "\<input name="\_token" type="hidden" value="1asdfe27e..."". |
| customer    | Determines whether the customer is logged in or not. If set to false, it means the customer has not logged in to your website. Example: true.                                                            |
| title       | The current page title shown in the browser tab and tag. Example: "New Arrivals – My Boutique Store".                                                                                                    |
| description | A short description or meta description for the current page, often used for SEO and social media previews. Example: "Discover our latest shawl collections crafted for elegance."                       |

#### Cart Parameter

| Parameter                             | Description                                                                                                              |
| ------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| cart.items\[]                         | A list of all items currently added to the shopping cart. Each item represents a product variant or bundle.              |
| cart.items\[].id                      | The unique identifier for the specific cart item. Used to update or remove the item from the cart.                       |
| cart.items\[].is\_bundle              | Indicates whether the item is part of a product bundle (true) or a single product (false).                               |
| cart.items\[].price                   | The unit price of the item (after any discounts). Example: 49.90.                                                        |
| cart.items\[].compare\_at\_price      | The original price before discount or promotion. Used to show a “discounted from” price. Example: 59.90.                 |
| cart.items\[].total                   | The total cost for this item, calculated as price × quantity.                                                            |
| cart.items\[].quantity                | The quantity of this product currently in the cart.                                                                      |
| cart.items\[].options                 | List of selected product options or variations (e.g., color, size).                                                      |
| cart.items\[].options\[].id           | Unique identifier of the specific option. Example: "opt\_32".                                                            |
| cart.items\[].options\[].name         | The display name of the option. Example: "Color".                                                                        |
| cart.items\[].options\[].value        | The selected value for this option. Example: "Emerald Green".                                                            |
| cart.items\[].product                 | Contains product-related information for the item in the cart.                                                           |
| cart.items\[].product.id              | The unique ID of the product.                                                                                            |
| cart.items\[].product.name            | The product’s name. Example: "Elegant Satin Shawl".                                                                      |
| cart.items\[].product.description     | Short description of the product.                                                                                        |
| cart.items\[].product.url             | Direct URL to the product’s page for quick access. Example: "/products/elegant-satin-shawl".                             |
| cart.items\[].product.images          | A list of image URLs associated with the product.                                                                        |
| cart.items\[].product.featured\_image | The main image URL displayed for the product in the cart.                                                                |
| cart.items\[].product.available       | Indicates whether the product in the cart is still available for purchase (true if it’s in stock and can be bought).     |
| cart.item\_count                      | Total number of items (quantities combined) in the cart. Example: if 2 of one product and 1 of another, item\_count = 2. |
| cart.total\_price                     | The final total cost of all items in the cart after discounts.                                                           |
| cart.total\_compare\_at\_price        | The combined original (non-discounted) total price for all cart items. Useful for showing total savings.                 |
| cart.note                             | An optional note provided by the customer (e.g., delivery instruction or gift message).                                  |

#### Cart Bundle Parameter

| Parameter                                                   | Penerangan                                                                                        |
| ----------------------------------------------------------- | ------------------------------------------------------------------------------------------------- |
| cart.items\[].bundle\_products\[]                           | A list of products included in the bundle inside the cart item.                                   |
| cart.items\[].bundle\_products\[].id                        | The unique ID of the bundled product item in the cart.                                            |
| cart.items\[].bundle\_products\[].name                      | The name of the bundled product.                                                                  |
| cart.items\[].bundle\_products\[].price                     | The selling price for this bundled product.                                                       |
| cart.items\[].bundle\_products\[].compare\_at\_price        | The original or higher price before discount for the bundled product.                             |
| cart.items\[].bundle\_products\[].total                     | The total price for the bundled product based on quantity (price × quantity).                     |
| cart.items\[].bundle\_products\[].total\_compare\_at\_price | The total original price before discount for the bundled product (compare\_at\_price × quantity). |
| cart.items\[].bundle\_products\[].options                   | The selected product options for this bundled product (e.g., color, size).                        |
| cart.items\[].bundle\_products\[].options.id                | The unique ID for the selected option.                                                            |
| cart.items\[].bundle\_products\[].options.name              | The name of the option (e.g., "Color", "Size").                                                   |
| cart.items\[].bundle\_products\[].options.value             | The selected value for the option (e.g., "Black", "M").                                           |
| cart.items\[].bundle\_products\[].quantity                  | How many units of this bundled product are included in the cart.                                  |
| cart.items\[].bundle\_products\[].based\_quantity           | The base or fixed quantity of this product that comes with the bundle (if applicable).            |
| cart.items\[].bundle\_products\[].product                   | The detailed product data for this bundled product.                                               |
| cart.items\[].bundle\_products\[].product.id                | The unique ID of the product.                                                                     |
| cart.items\[].bundle\_products\[].product.name              | The name of the product.                                                                          |
| cart.items\[].bundle\_products\[].product.description       | A short description of the product.                                                               |
| cart.items\[].bundle\_products\[].product.url               | The URL link to the product page.                                                                 |
| cart.items\[].bundle\_products\[].product.images\[]         | List of all images for this product.                                                              |
| cart.items\[].bundle\_products\[].product.featured\_image   | The main image displayed for the product.                                                         |
| cart.items\[].bundle\_products\[].product.available         | Indicates if the product is currently in stock and available for purchase.                        |

#### Settings Parameter

1. [Hartamas](themes-type/hartamas.md#variables)
2. [Solaris](themes-type/solaris.md#variables)
3. [Tampin](themes-type/tampin.md#variables)
4. [Bota](themes-type/bota.md#variables)

#### Menus Parameter

| Parameter                            | Description                                                                                                                                                      |
| ------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| menus                                | Contains all the navigation menus created for the theme (for example: main menu, footer menu, or social links menu). Each menu is grouped by its handle or name. |
| menus."menu\_name".title             | The display title of the menu. Example: "Main Menu" or "Footer Menu".                                                                                            |
| menus."menu\_name".handle            | The unique handle used to reference this menu inside templates. Example: "main\_menu".                                                                           |
| menus."menu\_name".links\[]          | A list of all links or menu items under this menu. Each item can also contain nested sub-links.                                                                  |
| menus."menu\_name".links\[].title    | The label or name of the menu link displayed to users. Example: "Home", "Shop", "Contact Us".                                                                    |
| menus."menu\_name".links\[].url      | The destination URL that the menu item points to. Example: "/products", "/contact", or an external link.                                                         |
| menus."menu\_name".links\[].active   | Indicates whether the link corresponds to the currently active page (true if user is on that page). Useful for adding “active” menu highlighting.                |
| menus."menu\_name".links\[].links\[] | Contains sub-links or child menu items (dropdowns). Follows the same structure as links\[], allowing for multi-level navigation menus.                           |

#### Page Parameter

| Parameter      | Description                                                                                                                                                         |
| -------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| page           | Contains information about the currently displayed page on your website. Used to render static content pages such as “About Us”, “Privacy Policy”, or custom pages. |
| page.name      | The display name or title of the page. Example: "About Us" or "Terms & Conditions".                                                                                 |
| page.permalink | The unique identifier (slug) of the page, usually used in the URL. Example: "about-us" or "contact".                                                                |
| page.url       | The full URL path to the page. Example: "/pages/about-us".                                                                                                          |
| page.template  | The template file used to render this page. Example: "page", "home"                                                                                                 |

#### Page/{slug} Parameter

| Parameter                    | Description                                                                                    |
| ---------------------------- | ---------------------------------------------------------------------------------------------- |
| page.id                      | The unique identifier for the page.                                                            |
| page.name                    | The internal name or handle of the page (used by the system).                                  |
| page.image                   | The main SEO image associated with the page (if any).                                          |
| page.permalink               | The custom slug or permanent link assigned to the page. Example: "about-us".                   |
| page.url                     | The full URL of the page. Example: "<https://namakedai.com/pages/about-us>".                   |
| page.template                | The template file used to display this page. Example: "page", "contact", or a custom template. |
| page.title                   | The display title of the page, usually shown at the top of the page and in browser tabs.       |
| page.body                    | The main HTML content of the page.                                                             |
| page.metafields              | Custom data fields attached to the page.                                                       |
| page.metafields.builder      | A special metafield used by the visual page builder system.                                    |
| page.metafields.builder.json | Structured JSON data generated by the page builder (represents page layout & blocks).          |
| page.metafields.builder.css  | Custom CSS generated for the page by the builder.                                              |
| page.metafields.builder.js   | Custom JavaScript generated for the page by the builder.                                       |
| page.created\_at             | The date and time when the page was first created.                                             |
| page.updated\_at             | The date and time when the page was last updated.                                              |

#### Products Parameter

| Parameter                                           | Description                                                                                                                                                 |
| --------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| products\[]                                         | A list of all products displayed on the current page (for example, in the “All Products” or “Shop” template). Each item represents a single product object. |
| products\[].id                                      | The unique identifier of the product.                                                                                                                       |
| products\[].name                                    | The name or title of the product. Example: "Satin Premium Shawl".                                                                                           |
| products\[].description                             | The product description.                                                                                                                                    |
| products\[].price                                   | The main or starting price of the product (for single variant products).                                                                                    |
| products\[].compare\_at\_price\_min                 | The lowest “original” (before discount) price among all variants. Used for showing discount comparisons.                                                    |
| products\[].compare\_at\_price\_max                 | The highest “original” (before discount) price among all variants.                                                                                          |
| products\[].url                                     | The full URL to the product page. Example: "<https://namakedai.com/products/satin-premium-shawl>".                                                          |
| products\[].images\[]                               | A list of all image URLs for the product.                                                                                                                   |
| products\[].is\_bundle                              | Indicates if the product is a bundle (contains multiple products sold together).                                                                            |
| products\[].featured\_image                         | The main or default image displayed for the product.                                                                                                        |
| products\[].available                               | Whether the product is available for purchase (true if in stock).                                                                                           |
| products\[].price\_varies                           | Indicates if the product has multiple variants with different prices.                                                                                       |
| products\[].selected\_or\_first\_available\_variant | Contains details about the currently selected variant, or the first available one if none is selected.                                                      |
| products\[].variants\[]                             | A list of all product variants (e.g., different sizes, colors). Each variant includes its own pricing, stock, and image.                                    |
| products\[].variants\[].id                          | Unique identifier for the product variant.                                                                                                                  |
| products\[].variants\[].name                        | The variant name (usually includes option values). Example: "Dusty Pink / M".                                                                               |
| products\[].variants\[].price                       | The current selling price of the variant.                                                                                                                   |
| products\[].variants\[].compare\_at\_price          | The original price of the variant before any discounts.                                                                                                     |
| products\[].variants\[].available                   | Indicates if this variant is currently available for purchase.                                                                                              |
| products\[].variants\[].inventory\_quantity         | The current stock quantity of the variant.                                                                                                                  |
| products\[].variants\[].manage\_stock               | Indicates whether stock tracking is enabled for this variant.                                                                                               |
| products\[].variants\[].image                       | The image associated with this specific variant.                                                                                                            |
| products\[].variants\[].options                     | The combination of option values (e.g., "Color": "Black", "Size": "M").                                                                                     |
| products\[].metafields                              | Custom data fields or metadata for the product (used for additional info or integrations).                                                                  |
| products\[].has\_options                            | Indicates if the product has selectable options (e.g., size, color).                                                                                        |
| products\[].reviews\[]                              | A list of customer reviews associated with the product.                                                                                                     |
| products\[].reviews\[].customer.name                | The reviewer's name who submitted the product review.                                                                                                       |
| products\[].reviews\[].variant                      | The product variant selected by the customer when they left the review (e.g., Size M, Black).                                                               |
| products\[].reviews\[].description                  | The written feedback or comment from the customer about the product.                                                                                        |
| products\[].reviews\[].rating                       | The rating value given by the customer (e.g., 1–5 stars).                                                                                                   |
| products\[].reviews\[].created\_at                  | The date and time when the review was submitted.                                                                                                            |
| products\[].has\_only\_default\_variant             | Indicates whether the product only has a single default variant (no options).                                                                               |
| products\[].has\_predefined\_options                | Indicates if the product comes with predefined option sets.                                                                                                 |
| products\[].options\[]                              | A list of all available product options (like size, color).                                                                                                 |
| products\[].options\[].id                           | Unique identifier for the product option.                                                                                                                   |
| products\[].options\[].name                         | The option name. Example: "Size", "Color".                                                                                                                  |
| products\[].options\[].type                         | The type of option selector (e.g., "dropdown", "radio", "swatch", "date", "datetime", "input" and "textarea").                                              |
| products\[].options\[].required                     | Whether selecting this option is required before adding to cart. Example: true.                                                                             |
| products\[].options\[].values\[]                    | The list of available values for this option. Example: "S", "M", "L".                                                                                       |
| products\[].options\[].values\[].name               | The name of the individual option value. Example: "Emerald Green".                                                                                          |
| products\[].options\[].values\[].metadata           | Extra metadata for the option value (e.g., color code, image URL).                                                                                          |
| products\[].paginate                                | Contains pagination data for product listings.                                                                                                              |
| products\[].paginate.next                           | The URL for the next page of products (if available).                                                                                                       |
| products\[].paginate.previous                       | The URL for the previous page of products (if available).                                                                                                   |
| products\[].q                                       | The current search query or filter term applied to the product listing.                                                                                     |

#### Product Parameter

| Parameter                                          | Description                                                                                                              |
| -------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| product\[]                                         | A list of product displayed on the current page                                                                          |
| product\[].id                                      | The unique identifier of the product.                                                                                    |
| product\[].name                                    | The name or title of the product. Example: "Satin Premium Shawl".                                                        |
| product\[].description                             | The product description.                                                                                                 |
| product\[].price                                   | The main or starting price of the product (for single variant products).                                                 |
| product\[].compare\_at\_price\_min                 | The lowest “original” (before discount) price among all variants. Used for showing discount comparisons.                 |
| product\[].compare\_at\_price\_max                 | The highest “original” (before discount) price among all variants.                                                       |
| product\[].url                                     | The full URL to the product page. Example: "<https://namakedai.com/products/satin-premium-shawl>".                       |
| product\[].images\[]                               | A list of all image URLs for the product.                                                                                |
| product\[].is\_bundle                              | Indicates if the product is a bundle (contains multiple products sold together).                                         |
| product\[].featured\_image                         | The main or default image displayed for the product.                                                                     |
| product\[].available                               | Whether the product is available for purchase (true if in stock).                                                        |
| product\[].price\_varies                           | Indicates if the product has multiple variants with different prices.                                                    |
| product\[].selected\_or\_first\_available\_variant | Contains details about the currently selected variant, or the first available one if none is selected.                   |
| product\[].variants\[]                             | A list of all product variants (e.g., different sizes, colors). Each variant includes its own pricing, stock, and image. |
| product\[].variants\[].id                          | Unique identifier for the product variant.                                                                               |
| product\[].variants\[].name                        | The variant name (usually includes option values). Example: "Dusty Pink / M".                                            |
| product\[].variants\[].price                       | The current selling price of the variant.                                                                                |
| product\[].variants\[].compare\_at\_price          | The original price of the variant before any discounts.                                                                  |
| product\[].variants\[].available                   | Indicates if this variant is currently available for purchase.                                                           |
| product\[].variants\[].inventory\_quantity         | The current stock quantity of the variant.                                                                               |
| product\[].variants\[].manage\_stock               | Indicates whether stock tracking is enabled for this variant.                                                            |
| product\[].variants\[].image                       | The image associated with this specific variant.                                                                         |
| product\[].variants\[].options                     | The combination of option values (e.g., "Color": "Black", "Size": "M").                                                  |
| product\[].metafields                              | Custom data fields or metadata for the product.                                                                          |
| product\[].has\_options                            | Indicates if the product has selectable options (e.g., size, color).                                                     |
| product\[].reviews\[]                              | A list of customer reviews associated with the product.                                                                  |
| product\[].reviews\[].customer.name                | The reviewer's name who submitted the product review.                                                                    |
| product\[].reviews\[].variant                      | The product variant selected by the customer when they left the review (e.g., Size M, Black).                            |
| product\[].reviews\[].description                  | The written feedback or comment from the customer about the product.                                                     |
| product\[].reviews\[].rating                       | The rating value given by the customer (e.g., 1–5 stars).                                                                |
| product\[].reviews\[].created\_at                  | The date and time when the review was submitted.                                                                         |
| product\[].has\_only\_default\_variant             | Indicates whether the product only has a single default variant (no options).                                            |
| product\[].has\_predefined\_options                | Indicates if the product comes with predefined option sets.                                                              |
| product\[].options\[]                              | A list of all available product options (like size, color).                                                              |
| product\[].options\[].id                           | Unique identifier for the product option.                                                                                |
| product\[].options\[].name                         | The option name. Example: "Size", "Color".                                                                               |
| product\[].options\[].type                         | The type of option selector (e.g., "dropdown", "radio", "swatch", "date", "datetime", "input" and "textarea").           |
| product\[].options\[].required                     | Whether selecting this option is required before adding to cart. Example: true.                                          |
| product\[].options\[].values\[]                    | The list of available values for this option. Example: "S", "M", "L".                                                    |
| product\[].options\[].values\[].name               | The name of the individual option value. Example: "Emerald Green".                                                       |
| product\[].options\[].values\[].metadata           | Extra metadata for the option value.                                                                                     |
| product\[].categories\[]                           | List of categories that the product belongs to.                                                                          |
| product\[].categories\[].id                        | Unique ID of the category associated with the product.                                                                   |
| product\[].categories\[].name                      | Name of the category (e.g., "Shoes", "Accessories").                                                                     |
| product\[].categories\[].permalink                 | SEO-friendly category URL slug used for linking (e.g., /category/shoes).                                                 |

#### Product Related Parameter

| Parameter                                                                         | Description                                                                                       |
| --------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- |
| product\[].related\[]                                                             | List of related products recommended alongside the main product.                                  |
| product\[].related\[].id                                                          | Unique ID of the related product.                                                                 |
| product\[].related\[].name                                                        | Name of the related product.                                                                      |
| product\[].related\[].description                                                 | Short description of the related product.                                                         |
| product\[].related\[].price                                                       | Selling price of the related product.                                                             |
| product\[].related\[].compare\_at\_price\_min                                     | Original or highest compare-at price if on sale.                                                  |
| product\[].related\[].compare\_at\_price\_max                                     | Maximum compare-at price (if price varies).                                                       |
| product\[].related\[].url                                                         | Direct product page URL.                                                                          |
| product\[].related\[].images                                                      | List of product images.                                                                           |
| product\[].related\[].featured\_images                                            | Main featured product image.                                                                      |
| product\[].related\[].available                                                   | Indicates if the related product is in stock.                                                     |
| product\[].related\[].price\_varies                                               | True if the product price changes by variant.                                                     |
| product\[].related\[].selected\_or\_first\_available\_variant                     | The first available variant (or selected variant).                                                |
| product\[].related\[].selected\_or\_first\_available\_variant.id                  | Variant ID.                                                                                       |
| product\[].related\[].selected\_or\_first\_available\_variant.name                | Variant name (e.g., Size M).                                                                      |
| product\[].related\[].selected\_or\_first\_available\_variant.price               | Variant price.                                                                                    |
| product\[].related\[].selected\_or\_first\_available\_variant.compare\_at\_price  | Variant original price before discount.                                                           |
| product\[].related\[].selected\_or\_first\_available\_variant.available           | Shows if the variant is in stock.                                                                 |
| product\[].related\[].selected\_or\_first\_available\_variant.inventory\_quantity | Stock quantity for the variant.                                                                   |
| product\[].related\[].selected\_or\_first\_available\_variant.manage\_stock       | Indicates if stock is tracked.                                                                    |
| product\[].related\[].variants\[]                                                 | List of all variants available for the related product.                                           |
| product\[].related\[].variants\[].id                                              | Variant ID.                                                                                       |
| product\[].related\[].variants\[].name                                            | Variant name.                                                                                     |
| product\[].related\[].variants\[].price                                           | Variant price.                                                                                    |
| product\[].related\[].variants\[].compare\_at\_price                              | Original price before discount.                                                                   |
| product\[].related\[].variants\[].available                                       | Variant availability.                                                                             |
| product\[].related\[].variants\[].inventory\_quantity                             | Stock quantity for that variant.                                                                  |
| product\[].related\[].variants\[].manage\_stock                                   | Shows if inventory is tracked.                                                                    |
| product\[].related\[].variants\[].image                                           | Variant image.                                                                                    |
| product\[].related\[].variants\[].options                                         | Options attached to that variant (e.g., Color, Size).                                             |
| product\[].related\[].metafield\[]                                                | Custom metafields related to the product.                                                         |
| product\[].related\[].has\_options                                                | Indicates if the product has multiple options.                                                    |
| product\[].related\[].has\_only\_default\_variant                                 | True if only one variant exists.                                                                  |
| product\[].related\[].has\_predefined\_options                                    | Shows if options were predefined by seller.                                                       |
| product\[].related\[].options\[]                                                  | List of product options (e.g., size, color).                                                      |
| product\[].related\[].options\[].id                                               | Product option ID.                                                                                |
| product\[].related\[].options\[].name                                             | Option name like “Size” or “Color”.                                                               |
| product\[].related\[].options\[].type                                             | Type of option (e.g., "dropdown", "radio", "swatch", "date", "datetime", "input" and "textarea"). |
| product\[].related\[].options\[].required                                         | Shows if customers must select an option.                                                         |
| product\[].related\[].options\[].values\[]                                        | Available option values.                                                                          |
| product\[].related\[].options\[].values\[].name                                   | Value name (e.g., “Red”, “Large”).                                                                |
| products\[].related\[].options\[].values\[].metadata                              | Extra metadata for the option value (if provided).                                                |

#### Product Wholesale Parameter

| Parameter                                          | Description                                                         |
| -------------------------------------------------- | ------------------------------------------------------------------- |
| products\[].wholesale\_prices\[]                   | List of wholesale pricing rules for bulk purchases.                 |
| products\[].wholesale\_prices\[].minimum\_quantity | Minimum quantity required to qualify for the wholesale price.       |
| products\[].wholesale\_prices\[].maximum\_quantity | Maximum quantity allowed under the specific wholesale pricing tier. |
| products\[].wholesale\_prices\[].unit\_price       | Discounted price per unit when buying in bulk.                      |
| products\[].wholesale\_prices\[].saving\_per\_unit | The amount saved per unit compared to the retail price.             |

#### Product Bundle Parameter

| Parameter                                                                                      | Description                                                                  |
| ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------- |
| products\[].bundle\_products\[]                                                                | List of products included in a bundle deal.                                  |
| products\[].bundle\_products\[].id                                                             | The ID of the product included in the bundle.                                |
| products\[].bundle\_products\[].name                                                           | Name of the product included in the bundle.                                  |
| products\[].bundle\_products\[].images\[]                                                      | Image gallery for the bundled product.                                       |
| products\[].bundle\_products\[].featured\_image                                                | Main featured image of the bundled product.                                  |
| products\[].bundle\_products\[].selected\_or\_first\_available\_variant\[]                     | The selected variant or the first available variant for the bundled product. |
| products\[].bundle\_products\[].selected\_or\_first\_available\_variant\[].id                  | Variant ID.                                                                  |
| products\[].bundle\_products\[].selected\_or\_first\_available\_variant\[].name                | Variant name (e.g., Size L / Red).                                           |
| products\[].bundle\_products\[].selected\_or\_first\_available\_variant\[].price               | Selling price for the variant in the bundle.                                 |
| products\[].bundle\_products\[].selected\_or\_first\_available\_variant\[].compare\_at\_price  | Original price of the variant before discount.                               |
| products\[].bundle\_products\[].selected\_or\_first\_available\_variant\[].available           | Indicates if the variant is available to purchase.                           |
| products\[].bundle\_products\[].selected\_or\_first\_available\_variant\[].inventory\_quantity | Number of units available in stock for the variant.                          |
| products\[].bundle\_products\[].selected\_or\_first\_available\_variant\[].fixed\_quantity     | Fixed quantity included in the bundle (if applicable).                       |
| products\[].bundle\_products\[].selected\_or\_first\_available\_variant\[].manage\_stock       | Whether stock management is enabled for this variant.                        |
| products\[].bundle\_products\[].selected\_or\_first\_available\_variant\[].image               | Image for the specific variant.                                              |

#### Categories Parameter

| Parameter                                                                       | Description                                                                                                                                          |
| ------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| categories                                                                      | Contains all the product categories available in your store. Each category is grouped under its unique name (e.g., "shawl", "bags", "new-arrivals"). |
| categories."category\_name".id                                                  | Unique identifier for the category.                                                                                                                  |
| categories."category\_name".name                                                | The display name of the category. Example: "Premium Shawl" or "Accessories".                                                                         |
| categories."category\_name".permalink                                           | The slug of the category used in the URL. Example: "premium-shawl".                                                                                  |
| categories."category\_name".url                                                 | The full URL to the category page. Example: "/categories/premium-shawl".                                                                             |
| categories."category\_name".template                                            | The template file used to render this category page (e.g., "collection", "custom-collection").                                                       |
| categories."category\_name".products\[]                                         | A list of all products that belong to this category. Each product follows the same structure as the products\[] object.                              |
| categories."category\_name".products\[].id                                      | The unique identifier of the product.                                                                                                                |
| categories."category\_name".products\[].name                                    | The name of the product. Example: "Satin Luxe Shawl".                                                                                                |
| categories."category\_name".products\[].description                             | Short product description.                                                                                                                           |
| categories."category\_name".products\[].price                                   | The current selling price of the product.                                                                                                            |
| categories."category\_name".products\[].compare\_at\_price\_min                 | The lowest original (pre-discount) price among the product variants.                                                                                 |
| categories."category\_name".products\[].compare\_at\_price\_max                 | The highest original price among the product variants.                                                                                               |
| categories."category\_name".products\[].url                                     | The product URL path. Example: "/products/satin-luxe-shawl".                                                                                         |
| categories."category\_name".products\[].images                                  | List of all image URLs for the product.                                                                                                              |
| categories."category\_name".products\[].is\_bundle                              | Indicates if the product is a bundle (true) or a single product (false).                                                                             |
| categories."category\_name".products\[].featured\_image                         | The main featured image of the product.                                                                                                              |
| categories."category\_name".products\[].available                               | Whether the product is available for purchase.                                                                                                       |
| categories."category\_name".products\[].price\_varies                           | Indicates if the product has multiple variants with different prices.                                                                                |
| categories."category\_name".products\[].selected\_or\_first\_available\_variant | Contains details of the selected variant or the first available variant of the product.                                                              |
| categories."category\_name".products\[].variants\[]                             | List of all variants for the product (e.g., size, color).                                                                                            |
| categories."category\_name".products\[].variants\[].id                          | The unique identifier for the variant.                                                                                                               |
| categories."category\_name".products\[].variants\[].name                        | The variant name. Example: "Dusty Blue / M".                                                                                                         |
| categories."category\_name".products\[].variants\[].price                       | The selling price of the variant.                                                                                                                    |
| categories."category\_name".products\[].variants\[].compare\_at\_price          | The original (before discount) price of the variant.                                                                                                 |
| categories."category\_name".products\[].variants\[].available                   | Indicates whether the variant is in stock.                                                                                                           |
| categories."category\_name".products\[].variants\[].inventory\_quantity         | The quantity of this variant in inventory.                                                                                                           |
| categories."category\_name".products\[].variants\[].manage\_stock               | Whether stock management is enabled for the variant.                                                                                                 |
| categories."category\_name".products\[].variants\[].image                       | The image associated with this variant.                                                                                                              |
| categories."category\_name".products\[].variants\[].options                     | Key-value pairs of variant options (e.g., "Color": "Maroon").                                                                                        |
| categories."category\_name".products\[].metafields                              | Contains custom data or extra metadata for the product.                                                                                              |
| categories."category\_name".products\[].has\_options                            | Indicates if the product has selectable options.                                                                                                     |
| categories."category\_name".products\[].has\_only\_default\_variant             | Indicates if the product has only one default variant.                                                                                               |
| categories."category\_name".products\[].has\_predefined\_options                | Whether the product uses predefined option sets.                                                                                                     |
