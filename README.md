# 🛍️ Fashion Store — Responsive E-commerce Website

A responsive fashion e-commerce website with sections for men, women and kids, a promotions page, product pages and a checkout page.

**🔗 Live demo:** [am4iir.github.io/fashion-store](https://am4iir.github.io/fashion-store/)

> University team project (DAW). This repository is a fork of the original team repository — see [Team & credits](#team--credits).

---

## Features

- 🏠 **Landing page** with hero banner, categories and featured products
- 👔 **Category pages** — Men, Women, Kids, each with product grids
- 🏷️ **Promotions page** for seasonal offers
- 🛍️ **Product page** with images, price and details
- 💳 **Checkout page** with order summary
- 📱 **Responsive design** — desktop, tablet and mobile
- ⚙️ **Express + EJS backend** included as a starting point

---

## Pages

| Page | File |
|---|---|
| Home | `main.html` |
| Men | `men.html` |
| Women | `women.html` |
| Kids | `children.html` |
| Promotions | `promotion.html` |
| Product | `product-page/product-page.html` |
| Checkout | `pay-page.html` |

---

## Tech stack

- **HTML5** — semantic pages
- **CSS3** — custom responsive layouts, flexbox and grid
- **JavaScript** — DOM interactions (`project-daw.js`)
- **Node.js + Express + EJS** — backend demo in `backend/`
- **Font Awesome** — icons

---

## Run locally

### Static version

Open `index.html` in your browser (it redirects to `main.html`).

### With the Express server

```bash
cd backend
npm install
npm run dev
```

The server runs on `http://localhost:3000` (see `backend/src/index.js`).

---

## Project structure

```
.
├── backend/              # Express + EJS demo server
├── children/             # kids category pages
├── men/                  # men category pages
├── women/                # women category pages
├── product-page/         # product details
├── image-*/              # product and category images
├── main.html             # home page
├── index.html            # redirect to main.html
├── promotion.html        # promotions page
├── pay-page.html         # checkout page
├── style-*.css           # page styles
└── project-daw.js        # client-side interactions
```

---

## Team & credits

This project was built as part of a university web development course (DAW).

- Original team repository: [ranim-123/project-daw](https://github.com/ranim-123/project-daw)
- **Amir Abada** — [add your contribution here]
- [Teammate name] — [contribution]

---

## Roadmap

- [ ] Persist products and orders in a database
- [ ] Add a working shopping cart
- [ ] Product search and filters
- [ ] Admin panel for products
- [ ] Replace placeholder social links with real ones

---

## License

This project is shared for learning purposes. Contact the authors before reusing the design or assets.
