# Razorpay

Accept Razorpay payments in PeltyCMS checkout

Official **payment gateway** for [PeltyCMS](https://github.com/MythicalLTD/PeltyCMS) — identifier `gateway-razorpay`.

## Why this addon

Hosts who want customers to pay invoices without leaving Pelty checkout.

## Features

- Take invoice and checkout payments through **Razorpay**
- Signed webhook handling so paid invoices mark paid automatically
- Fits Pelty tax, credits, refunds and multi-currency
- Runs as sandboxed WASM — no custom PHP on your panel
- Keys live in Pelty secrets, not in theme code

## How it works

1. Install **Razorpay** from the [Mythical marketplace](https://market.mythicalsystems.org/marketplace/product/gateway-razorpay) (or Pelty Admin → Addons → Marketplace).
2. Open Pelty Admin and enter your Razorpay credentials in the addon settings.
3. Attach it to the products / forms / login flows you care about.
4. New orders and sign-ins use Razorpay automatically.

## Requirements

- A running PeltyCMS panel with WASM addons enabled
- Valid Razorpay API / OAuth / panel credentials (depending on the integration)
- Outbound HTTPS from the panel to Razorpay

## Get it

[Razorpay on Mythical Marketplace](https://market.mythicalsystems.org/marketplace/product/gateway-razorpay)

Free official build. Source for this package lives in this repository.

## Support

- Marketplace product page: https://market.mythicalsystems.org/marketplace/product/gateway-razorpay
- PeltyCMS core: https://github.com/MythicalLTD/PeltyCMS
- Issues for this addon: use this repo’s Issues tab
