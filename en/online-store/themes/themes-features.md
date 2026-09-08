# Themes Features

This document list the available features in the Shoppego theme.

## Global Layout

Source: `layout.html`, `application.js`, `style.css`

* Provides a responsive site shell shared by all pages.
* Includes a global header, main content area, cart drawer, search modal, footer, scripts, metadata, and analytics area.
* Supports dynamic page title, meta description, favicon, Open Graph metadata, and page/product image metadata.
* Supports optional custom meta tags from theme settings.
* Supports page builder fonts, CSS, JavaScript, and body content when page builder data is available.
* Uses a configurable design system for colors, typography, spacing, and component styling.
* Supports icon rendering for navigation, search, pagination, and action buttons.
* Includes optional analytics script support.

### Header and Navigation

* Displays a store logo from theme settings when available.
* Falls back to the store name when no logo image is configured.
* Includes desktop navigation for main menu links.
* Supports simple menu links, first-level dropdown menus, and second-level flyout menus.
* Switches to a mobile hamburger menu when the screen size or menu length requires it.
* Provides a full-screen or drawer-style mobile menu.
* Supports expandable nested menu items on mobile.
* Includes a search button that opens the search interface.
* Includes a cart button that opens the cart drawer.
* Displays a cart item count badge when the cart has items.

### Search

* Provides a modal or drawer search interface.
* Includes a search input with autofocus when opened.
* Allows search submission by button click.
* Allows search submission with the Enter key.
* Redirects searches to the products listing page with the search query in the URL.
* Supports closing by close button, backdrop click, or Escape key.
* Locks body scrolling while the search overlay is open.

### Cart Drawer

* Provides a slide-in cart drawer from the side of the screen.
* Shows an empty cart state with a continue shopping action.
* Lists regular cart items with product image, product name, variant/options, quantity, line total, and remove action.
* Lists bundle cart items with parent product details, nested bundle item details, bundle quantities, compare-at prices, and savings.
* Shows cart total or subtotal.
* Provides actions to view cart, update cart, and proceed to checkout.
* Can reopen automatically after an add-to-cart flow so users immediately see cart feedback.
* Locks body scrolling while the cart drawer is open.

### Footer

* Supports an optional footer menu.
* Shows dynamic copyright year.
* Shows store name.
* Supports platform or store attribution links when required.

## Homepage

Source: `home.html`

* Displays a product-focused landing section.
* Shows a responsive product grid.
* Links each product card to the product detail page.
* Shows product image with placeholder fallback.
* Uses lazy loading for product images.
* Shows product name.
* Shows product price.
* Shows a sold-out badge or label for unavailable products.
* Shows an empty state when no products are available.

## Products Page

Source: `products.html`, `application.js`

* Displays a product listing page with a responsive grid.
* Shows a page title.
* Provides category or collection filters.
* Provides an All Products link.
* Generates category links dynamically from available categories or collections.
* Highlights the active category or collection.
* Supports pagination.
* Provides previous and next pagination controls.
* Shows product image hover behavior when suitable.
* Shows product name.
* Shows product price.
* Shows compare-at price when a discount exists.
* Shows variable-price indicator when product prices vary.
* Shows sold-out badge or label for unavailable products.
* Uses lazy loading for product images.
* Shows placeholder product cards or an empty state when no product data exists.
* Shows clear empty-state copy when no products are available.

### Products Search Results

* Supports filtering products by a search query from the URL.
* Repopulates the search input with the current search query.
* Filters product cards by product name or searchable product text.
* Shows a found-results message with result count and searched term.
* Handles singular and plural result wording.
* Shows a no-results state when no matching products are found.
* Provides a link back to all products from the no-results state.
* Hides normal listing headers when a no-results state needs full focus.

## Product Page

Source: `product.html`, `application.js`

* Provides a responsive product detail layout.
* Uses a two-column layout on larger screens and stacked layout on smaller screens.
* Displays all product images in a carousel or gallery.
* Includes variant images in the gallery when available.
* Provides placeholder fallback when no product image exists.
* Provides previous and next gallery controls when multiple images exist.
* Provides thumbnail navigation for product and variant images.
* Supports touch swipe interaction for mobile galleries.
* Updates the gallery when selecting a variant or option with related imagery.
* Shows breadcrumb navigation back to product listing and category when available.
* Shows product title.
* Shows product price.
* Shows compare-at or discount price when available.
* Shows sold-out state when product is unavailable.
* Shows product description as rich content.
* Shows related products when available.
* Related product cards include image, name, price, discount display, sold-out state, and hover behavior.

### Standard Product Purchase

* Provides an add-to-cart form.
* Provides a buy-now or express-checkout action.
* Supports asynchronous add-to-cart behavior when the platform allows it.
* Opens the cart drawer or gives clear cart feedback after successful add to cart.
* Validates required selections before add to cart.
* Validates required selections before buy now.
* Shows a disabled sold-out button for unavailable products.
* Stores variant data for client-side variant resolution.
* Shows an option alert when required selections are missing.
* Scrolls to the alert when needed.
* Validates required custom options.
* Provides a quantity selector with plus and minus buttons.
* Allows direct numeric quantity entry.
* Restricts quantity entry to numeric values.
* Respects stock limits for managed-stock variants.
* Supports unlimited quantity behavior for variants without managed stock.
* Recalculates product price when variant or quantity changes.
* Recalculates compare-at price when quantity changes.
* Shows available stock quantity when stock is managed.

### Variant and Option Features

* Supports direct variant selection when a product has multiple variants.
* Supports selectable product options such as radio, select, and swatch.
* Supports color swatches.
* Supports one-color and two-color swatch display.
* Supports option buttons with optional images.
* Visually disables sold-out option values.
* Prevents sold-out option values from being selected.
* Refreshes option availability based on the current partial selection.
* Supports legacy dropdown variant selectors where needed.
* Supports legacy dropdown option selectors where needed.
* Supports custom option field types:
  * Date
  * Datetime
  * Text input
  * Textarea with `maxlength="255"`
* Validates required custom option fields before add to cart or buy now.

### Wholesale Pricing

* Displays wholesale or bulk pricing when configured.
* Shows quantity ranges.
* Shows unit price for each range.
* Shows saving per unit.
* Updates product price based on the selected quantity and matching wholesale tier.

### Bundle Product Features

* Supports bundle add-to-cart forms.
* Stores bundle variant data for client-side updates.
* Stores bundle price, compare-at price, saved price, stock, fixed quantity, availability, and image data.
* Shows a bundle summary message with total savings or a fallback promotion message.
* Displays bundle product rows with thumbnail, product name, price, variant selector, availability, and quantity controls.
* Shows a variant dropdown when a bundled product has multiple variants.
* Uses a hidden variant input when a bundled product has only one variant.
* Shows out-of-stock messages per bundle variant.
* Updates bundle thumbnail when the selected variant has an image.
* Shows a fixed quantity badge when a bundle variant has fixed quantity.
* Hides quantity controls when fixed quantity applies.
* Provides plus, minus, and numeric quantity inputs for bundle items.
* Respects managed-stock limits for bundle quantities.
* Updates bundle item price dynamically.
* Updates bundle compare-at price dynamically.
* Updates bundle saved amount dynamically.
* Updates total bundle price dynamically.
* Updates total bundle savings dynamically.
* Validates all required bundle selections before add to cart or buy now.
* Gives clear error feedback when bundle submission fails or times out.

## Cart Page

Source: `cart.html`

* Provides a dedicated cart page.
* Displays cart content only when cart items exist and checkout is enabled.
* Shows cart error messages when available.
* Provides a cart update form.
* Lists regular cart items with image, product link, variant/options, quantity input, line total, and remove action.
* Lists bundle cart items with parent product, bundle savings copy, parent quantity, total, and remove action.
* Shows nested bundle item breakdown.
* Nested bundle items include product image, product or variant name, option details, quantity, compare-at price, total, and saved amount.
* Shows cart total.
* Shows a shipping or tax note when checkout calculates additional costs later.
* Provides Update Cart action.
* Provides Continue Shopping action.
* Provides Checkout action.
* Shows empty cart state when the cart has no items or checkout is unavailable.
* Provides product image fallback behavior.

## Custom Page

Source: `page.html`

* Supports page builder output when page builder content is enabled.
* Provides a standard content page fallback.
* Shows page title.
* Renders page body as rich content.
* Maintains a minimum content height for short pages.
* Supports readable rich text styling for headings, paragraphs, lists, links, blockquotes, images, tables, inline code, and code blocks.

## 404 Page

Source: `404.html`

* Provides a clear not-found page.
* Shows an optional themed icon.
* Provides an inline icon fallback.
* Shows a large 404 heading.
* Shows a short page-not-found message.
* Provides a Back to Home action.

## Styling and Theme Behavior

Source: `style.css`

* Uses a consistent responsive layout system.
* Keeps custom CSS focused on theme-specific component needs.
* Provides styled product option dropdowns.
* Provides styled product quantity controls.
* Provides placeholder image or SVG styling.
* Supports smooth scrolling for anchor navigation.
* Provides carousel styles for product galleries.
* Provides rich text styling for WYSIWYG content.
* Provides table styling for content pages and product descriptions.
* Provides code block styling for content pages.

## Javascript Utilities and interactions

Source: `application.js`

* Provides shared overlay show and hide helpers.
* Provides body scroll lock helper.
* Provides icon replacement or icon initialization helper.
* Provides search redirect helper.
* Provides cart drawer reopen helper after add-to-cart.
* Handles mobile menu open and close behavior.
* Handles nested mobile submenu toggles.
* Handles search modal open, close, submit, and keyboard behavior.
* Handles cart drawer open and close behavior.
* Handles carousel slide, thumbnail, arrow, and touch swipe behavior.
* Handles smooth scrolling for anchor links.
* Handles variant and option selection.
* Handles product quantity updates.
* Handles bundle quantity updates.
* Provides price parsing and formatting helpers.
* Updates product prices dynamically.
* Updates wholesale prices dynamically.
* Updates bundle prices dynamically.
* Validates bundle selections.
* Validates required custom options.
* Intercepts add-to-cart actions when asynchronous cart behavior is needed.
* Validates buy-now actions before form submission.
