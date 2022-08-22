<p align="center">
    <a href="https://hyva.io/" target="_blank">
        <img src="./images/hyva-snippets-logo.png" alt="Hyvä snippets" width="225" height=100" />
    </a>
</p>

# Hyvä Themes VSCode Snippets

A collection of **Hyvä themes** code snippets for Visual Studio Code.

If you don't know yet **Hyvä themes**, it's a **brand-new frontend for Magento 2** with a best DevExperience, Performance and Time to Market. Check it out on [hyva.io/](https://hyva.io/).

Most part of the snippets are inspired by the [Hyvä Documentation](https://docs.hyva.io/) itself.

## Installation

- Open the extension panel (`Ctrl + Shift + X` or `Cmd + Shift + X`)
- Search for **Hyvä Code Snippets**
- Click on Install
- Enjoy :)

## Snippets

### Alpine.js

| Snippet  | Purpose                                                                                            |
| :------- | :------------------------------------------------------------------------------------------------- |
| `hyva.alpine.consoleLogObject` | Console log object in Alpine.js                                              |
| `hyva.alpine.createComponent` | Create new Alpine.js component                                                |
| `hyva.alpine.dispatchAuthentication` | Dispatch Hyvä toggle authentication event                              |
| `hyva.alpine.dispatchCustomEvent` | Dispatch custom event with Alpine.js                                      |
| `hyva.alpine.dispatchReloadCustomerSectionData` | Dispatch Hyvä reload customer section data event            |
| `hyva.alpine.dispatchToggleCart` | Dispatch Hyvä toggle cart event                                            |
| `hyva.alpine.dispatchToggleMobileMenu` | Dispatch Hyvä toggle mobile menu event                               |
| `hyva.alpine.listenToCustomEvent` | Listen to custom event with Alpine.js                                     |
| `hyva.alpine.listenToPrivateContentLoaded` | Listen to private content loaded event with Alpine.js            |
| `hyva.alpine.listenToProductFinalPrice` | Listen to update product final price event with Alpine.js           |

### JavaScript

| Snippet  | Purpose                                                                                            |
| :------- | :------------------------------------------------------------------------------------------------- |
| `hyva.js.dispatchCustomEvent` | Dispatch custom event                                                         |
| `hyva.js.dispatchMessages` | Display Hyvä notification banner (success, notice, warning or error)             |
| `hyva.js.fetchAjaxRequest` | Use the fetch API to simulate an Ajax request with the XMLHttpRequest object     |
| `hyva.js.fetchFormPostRequest` | Fetch form post request with JSON data                                       |
| `hyva.js.formatPrice` | Formats and returns the given value using the current currency                        |
| `hyva.js.getBaseUrl` | Base URL builder                                                                       |
| `hyva.js.getBrowserStorage` | Returns either the native localStorage if it is available or tries to fall back to the sessionStorage object |
| `hyva.js.getCookie` | Get a given cookie value                                                                |
| `hyva.js.getCurrentStoreCode` | Buld current store code                                                       |
| `hyva.js.getFormKey` | Returns the current form key value                                                     |
| `hyva.js.loadExternalLibrary` | Load vanilla JavaScript library from vanilla JavaScript                       |
| `hyva.js.postForm` | Creates a new ```<form>``` element then adds hidden fields for a given data object and finally submits the created form |
| `hyva.js.replaceDomElement` | Replaces the DOM element specified by targetSelector with the HTML string content |
| `hyva.js.setCookie` | Skip setting the domain on the cookie                                                   |
| `hyva.js.strf` | Replaces positional parameters like %0 with the additional argument in the matching position |

### Template

| Snippet  | Purpose                                                                                            |
| :------- | :------------------------------------------------------------------------------------------------- |
| `hyva.template.createModal` | Create new modal with Hyvä Modal ViewModel                                      |
| `hyva.template.echoHeroiconsIcon` | Echo Heroicons icon with Heroicons ViewModel                              |
| `hyva.template.echoLoader` | Echo Hyvä UI loader                                                              |
| `hyva.template.echoSvgIconsIcon` | Render SVG icon with SvgIcons ViewModel                                    |
| `hyva.template.echoTranslation` | Echo escaped Magento 2 translation                                          |
| `hyva.template.echoTranslationWithVariable` | Echo escaped Magento 2 translation with variable                |
| `hyva.template.escapeHtml` | Add Magento 2 HTML escaper                                                       |
| `hyva.template.escapeHtmlAttr` | Add Magento 2 HTML attribute escaper                                         |
| `hyva.template.escapeJs` | Add Magento 2 JavaScript escaper                                                   |
| `hyva.template.escapeUrl` | Add Magento 2 URL escaper                                                         |
| `hyva.template.getChildHtml` | Add Magento 2 getChildHtml() to render child block                             |
| `hyva.template.getFileUrl` | Use Magento 2 getFileUrl() method to render a file                               |
| `hyva.template.getUrl` | Use Magento 2 getUrl() method to render the page path                                |
| `hyva.template.formatPrice` | Use Magento 2 formatPrice() method to formats and returns the given value using the current currency |
| `hyva.template.isCustomerLoggedIn` | Use Magento 2 isCustomerLoggedIn() method to check if customer is logged in |
| `hyva.template.isProductInStock` | Use Magento 2 isProductInStock() method to check if product is in stock    |
| `hyva.template.requireCustomerViweModel` | Require customer ViewModel                                         |
| `hyva.template.requireHericonsOutlineViewModel` | Require Heroicons outline ViewModel                         |
| `hyva.template.requireHericonsSolidViewModel` | Require Heroicons solid ViewModel                             |
| `hyva.template.requireModalViewModel` | Require Hyvä Modal ViewModel                                          |
| `hyva.template.requireProductPriceViewModel` | Require product price ViewModel                                |
| `hyva.template.requireProductStockItemViewModel` | Require product stock item ViewModel                       |
| `hyva.template.requireSvgIconsViewModel` | Require product stock item ViewModel                               |

## Licence

MIT License, refer to license file.
