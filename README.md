# Angel Bakery 天使牌

Order page for Angel Bakery's handmade festive cookies and crispy snacks, in English and 中文.

- `angel-bakery.html` — the page: menu, JB gift picks, cart, and Touch 'n Go eWallet QR payment
- `angel-logo.jpg` — logo
- `payment-qr.png` — Touch 'n Go eWallet QR (payee: JMCO Trading)
- `photos/` — product photos, named after each menu item (for example `photos/pineapple-tarts.jpg`)

## Still to do

- Add prices: in `angel-bakery.html`, each item in `MENU` has `price: null` until it's set

Saving orders and payment references needs the Claude artifact runtime (`window.claude`). Opened anywhere else, the page shows the menu and cart, but placing an order shows a message that ordering isn't available.
