# Bin Imran – Ladies Suits Website

## 1. Change your details
Open `public/products.js` and edit the `SITE` block at the top:
email, phone, WhatsApp number (format: 923001234567), address, free delivery amount.

## 2. Add your own pictures
- Put pictures in `public/images/` (make the folder).
- In `public/products.js`, add `img: "images/suit1.jpg"` to a product.
- Without `img`, a nice colored placeholder is shown.

## 3. Add / remove products
Copy one line inside `PRODUCTS` in `public/products.js`, change the id, name, category, price, and description.

## 4. Publish on Cloudflare (free)
Option A – Dashboard (easy):
1. Go to dash.cloudflare.com -> Workers & Pages -> Create -> "Upload your static files".
2. Upload the `public` folder. Click Deploy.

Option B – Command line:
```
npm install -g wrangler
wrangler login
wrangler deploy
```
