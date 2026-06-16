On the Daily Stripe-ready version.

Menu:
Classic Matcha $7
Classic Coffee $7
Matcha Lemonade $7
Blueberry Coffee $7
Add-ons $1 each

To turn orders off:
Open config.js and change ORDERS_OPEN: true to ORDERS_OPEN: false, then redeploy.

To connect Stripe:
In Netlify, add environment variable STRIPE_SECRET_KEY with your own sk_live_... secret key.
Never share your secret key in chat.
Then redeploy.
