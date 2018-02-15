# shopify-stock-checker
Will check stock levels of Shopify powered online stores.

Many shopify powered websites (GymShark, for example) make a call on their product page to [product-url].js which returns a JSON object containing additional information on the product not often displayed on the page. This app will display the stock levels available for the given product if given the URL.

## How to use this app
Open the index.html file in browser, the app is quite small so the script has just been inserted into the head of the file. Go to the product page on a shopify powered web store and copy-paste the URL into the input field and submit.

It has not been extensively tested, only across a couple of websites which exhibit this behaviour.
