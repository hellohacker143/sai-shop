# SAI Kirana Store — Thermal Receipt Maker

An editable, mobile-friendly thermal receipt website based on the supplied SAI KIRANA STORE reference.

## Open the website

After GitHub Pages is enabled for this repository, open: **https://hellohacker143.github.io/sai-shop/receipt-template/**

The website source is in [`receipt-template/index.html`](receipt-template/index.html).

## Features

- Reference-style black-and-white receipt with dashed dividers and bold grand total.
- Sample receipt starts with American, Chams, Kings, and Rrcoin.
- Edit shop name, bill number, cashier, date, time, product names, quantities, rates, discount, and footer messages.
- Add/remove products (up to 10 rows).
- Automatic amount, subtotal, quantity and grand-total calculations.
- Open a clean receipt in a new browser tab and print or save as PDF.
- Choose 58 mm or 80 mm thermal paper.

## Publish using GitHub Pages

In the repository, open **Settings → Pages**, select **Deploy from a branch**, choose the `main` branch and `/ (root)` folder, and save. Once GitHub Pages finishes publishing, visit the link above.

Note: line amounts are calculated as quantity × rate. The example values in the reference image may not all reconcile, so totals are recalculated by the website.