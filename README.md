Demo: https://ecstyletheme.myshopify.com/

# COSMETIC SHOPIFY THEME

## STANDARD SECTIONS

* Blogs
* Customizable contact form
* FAQ page
* Promo Countdown
* Newsletter popup
* Customer reviews
* Quick view
* Recently viewed
* Recommended products
* Wislish
* Compare products
* Color swatches
* Image zoom
* Product tabs
* Shipping/delivery information
* Slideshow
* Usage information

## Product discovery

* Breadcrumbs
* Collection pagination, ajax load more, infiniteScroll
* Collection view grid and list layout
* Enhanced search
* Mega menu
* Product filtering and sorting
* Recently viewed
* Recommended products
* Sticky header
 
## Cart & checkout
 
* Progress Bar Shipping
* Quick buy
* Notification popup combine a dropdown cart

## USE MENU

We have 4 layouts for megamenu. Base on Title of Top Level. If it matches with the setting in each block after that it will show below.

1. Go to Online Store -> Themes -> Customize -> Sections

2. Header sections -> Add block ( Mega menu layout 1, Mega menu layout 2, Mega menu layout 3, Mega menu layout 4 )

![COSMETIC Screenshot](docs/ecstyletheme-·-Customize-eboost-·-Shopify-menu-config.png)

### Layout 1

![COSMETIC Screenshot](docs/layout1.png)


### Layout 2

![COSMETIC Screenshot](docs/layout2.png)

### Layout 3

![COSMETIC Screenshot](docs/layout3.png)

### Layout 4

![COSMETIC Screenshot](docs/layout4.png)


## USE COUNTDOWN ON PRODUCT DETAIL PAGE

To enbable countdown on product detail page. We need follow step by step below:

![COSMETIC Screenshot](docs/Striped-Skirt-and-Top-–-ecstyletheme.png)


1. Go to Online Store -> Themes -> Customize button -> Settings

2. Expand Product tab -> click Enable Countdown? to enable this featured

![COSMETIC Screenshot](docs/ecstyletheme-·-Customize-eboost-·-Shopify-count-down.png)

3. Select option 

	- Use for all products -> If you chose this option After that go to step 4 
	- Use for different product -> If you chose this option. After that go to step 5

4. Add a deal time with a format like "2025/12/25 22:11:00". This time must be greater than the current time.

5. Go to Content->Metaobjects-> Manage definitions

![COSMETIC Screenshot](docs/Baby-Eboost-Demo-·-Metafield-definitions-·-Shopify.png)

6. Go to Products -> click Add definition button on top right 

![COSMETIC Screenshot](docs/Baby-Eboost-Demo-·-Metafield-definitions-·-Shopify-config.png)

7. Create a metafield

```bash

Namespace: custom
Key: countdown
Type: Date and time

```
![COSMETIC Screenshot](docs/Baby-Eboost-Demo-·-Product-metafield-definitions-·-Edit-countdown-·-Shopify.png)


8. Go to  products -> Select product that you would like to show count down

9. Add a deal time for this product. This time must be greater than the current time.

![COSMETIC Screenshot](docs/Baby-Eboost-Demo-·-Products-·-Selling-Plans-Ski-Wax-·-Shopify.png)

## USE PROGRESS SHIPPING (both cart drawer and cart page)

![COSMETIC Screenshot](docs/Baby-Eboost-Demo--progress-bar·-Shopify.png)


1. Go to Online Store -> Themes -> Customize button
2. Settings -> Progress Bar Shipping -> check Enable Progress Bar shipping to turn on it
3. Add total price, messages for free shipping

![COSMETIC Screenshot](docs/ecstyletheme-·-Customize-eboost-·-Shopify-progress-bar-config.png)


## SETTING TO SHOW WISHLIST


1. Go to Online Store -> Themes -> Customize button -> Settings

2. Expand Product tab -> click "Enable Wishlist?" to show wishlist icon on card product and product detail page

![COSMETIC Screenshot](docs/ecstyletheme-·-Customize-eboost-·-Shopify-wishlist-config.png)

3. Go to Sections -> Header section -> check "Enable Header Wishlist" 

![COSMETIC Screenshot](docs/ecstyletheme-·-Customize-eboost-·-Shopify-wishlist.png)

3.  Go to Online Store -> Pages -> Create wishlist page

```bash

URL and handle: wish-list
Theme template: wishlist

```

![COSMETIC Screenshot](docs/Baby-Eboost-Demo-·-Wishlist-·-Shopify.png)


## TURN ON ASK AN EXPERT POPUP

![COSMETIC Screenshot](docs/Eboost-themes-–-ecstyletheme-ask-expert.png)

1. Go to Online Store -> Themes -> Customize button -> Settings
2. Expand Product tab -> click "Enable Wishlist?" to show wishlist icon on card product and product detail page
3. Setup your setting

![COSMETIC Screenshot](docs/ecstyletheme-·-Customize-eboost-·-Shopify-aske-expert-config.png)

## TURN ON QUICK VIEW ON THE PRODUCT CARD

![COSMETIC Screenshot](docs/quick-view-.png)

1. Go to Online Store -> Themes -> Customize button -> Settings

2. Expand Product tab -> click "Enable Quick View??" to show Quick View button

![COSMETIC Screenshot](docs/ecstyletheme-·-Customize-eboost-·-Shopify-quickview.png)


## TURN ON THE COMPARISON ON THE COLLECTION PAGE

![COSMETIC Screenshot](docs/compare.png)

1. Go to Online Store -> Themes -> Customize button -> Theme settings
2. Expand Compare Products tab
3. Turn on/of. Setup color ...


![COSMETIC Screenshot](docs/ecstyletheme-·-Customize-eboost-·-Shopify-compare.png)

## TURN ON THE RECENTLY VIEWED PRODUCT POPUP

![COSMETIC Screenshot](docs/Eboost-themes-–-ecstyletheme-recently.png)

1. Go to Online Store -> Themes -> Customize button -> Theme settings
2. Recently Viewed Product Popup tab


![COSMETIC Screenshot](docs/ecstyletheme-·-Customize-eboost-·-Shopify-recently-config.png)

## SETTINGS SEARCH FORM

![COSMETIC Screenshot](docs/search.png)

1. Go to Online Store -> Themes -> Customize button -> Theme settings
2. Search Form tab


![COSMETIC Screenshot](docs/ecstyletheme-·-Customize-eboost-·-Shopify-search.png)

## ADD LOGOS FOR MULTIPLE LANGUAGE/CURRECY

![COSMETIC Screenshot](docs/language-currency.png)

1. Go to Online Store -> Themes -> Customize button -> Theme settings
2. Multiple Language / Currency Tabs

![COSMETIC Screenshot](docs/ecstyletheme-·-Customize-eboost-·-Shopify-lag.png)

## HOME PAGE

![COSMETIC Screenshot](docs/HOME.png)


## COLLECTION PAGE

![COSMETIC Screenshot](docs/PLP.png)

 
##  PRODUCT DETAIL PAGE

 ![COSMETIC Screenshot](docs/PDP.png)


##  CART PAGE

 ![COSMETIC Screenshot](docs/Cart.png)


## Bugs/Feature Requests & Contribution

Please do open a pull request on GitHub should you want to contribute, or create an issue.

## License
[BSD-4-Clause](http://directory.fsf.org/wiki/License:BSD_4Clause) - Do as you wish 👍

## Our website

https://www.eboosttech.net

[DONATE](https://paypal.me/eboost10)  `❤❤❤`
