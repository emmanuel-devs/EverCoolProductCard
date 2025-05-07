# 🛍️ EverCoolProductCard – Framer Smart Product Component

A powerful, responsive, and fully customizable **product card** built for Framer. Designed for speed, style, and seamless shopping experiences — ideal for designers and devs building e-commerce pages, MVPs, or product showcases.

---

## ✨ What It Does

- 🔢 **Add-to-Cart with Quantity Controls** (+/–)  
- 🧠 **Smart Discounts** based on quantity  
- 🎨 **Custom Typography & Color Props** for each element  
- 🖼️ **Thumbnail Image Selector** for product variants  
- 🧱 **1-Column / 2-Column Layout Toggle**  
- 💬 **Modal Support** with custom content  
- ⚙️ **Built-in Framer Property Controls** for full UI flexibility  
- 🔗 **Checkout Redirect** with `onAddToCart` callback  

---

## ⚙️ Quick Props Reference

| Prop                   | Type             | Description                        |
|------------------------|------------------|------------------------------------|
| `productTitle`         | `string`         | Main product title                 |
| `stockStatus`          | `string`         | Custom availability text           |
| `buttonText`           | `string`         | Call-to-action label               |
| `maxQuantity`          | `number`         | Max items selectable               |
| `showThumbnailSelector`| `boolean`        | Toggle image selector              |
| `enableDiscount`       | `boolean`        | Enable discount logic              |
| `discountThreshold`    | `number`         | Quantity to activate discount      |
| `discountRate`         | `number`         | Percentage off                     |
| `imageSize`            | `number`         | Main image scale                   |
| `layoutMode`           | `'1-col' \| '2-col'` | Choose layout                   |
| `showModal`            | `boolean`        | Toggle modal                       |
| `modalContent`         | `string/slot`    | Content inside modal               |
| `onAddToCart`          | `function`       | Fires on CTA click                 |

### Typography & Color Props

Each text section is fully stylable via:


```ts
fontFamily_title, fontSize_price, fontWeight_button, color_discount, ...

Applies to: title, price, stock, button, quantity, discount, modal, tab, selector, and more.
```

---

## 🧠 How to Use in Framer

- Drag component into your canvas  
- Set props in the right panel (text, colors, logic)  
- Configure `onAddToCart` to trigger checkout or events  
- Style modal or toggle layout as needed  
- Preview & ship!

---

## 📦 Ideal For

- Framer-based e-commerce landing pages  
- MVPs and prototypes for DTC brands  
- Showcasing multiple variants or SKUs  
- Product launches with fast checkout

---

## 🔗 Live Preview & Repo

- **Live Demo:** Coming Soon  
- **Clone This Repo:** [github.com/your-username/EverCoolProductCard](https://github.com/your-username/EverCoolProductCard)

---

## 🧑‍💻 Built With

- 🧩 Framer Motion  
- ⚛️ React  
- 🎨 Framer Property Controls  
- 💻 Modern Component Architecture

---

## 🙌 Contribution
Open to suggestions, issues, or feature requests.
Fork it, build on it, and submit a PR if you improve it.

---

### 🚀 Need a Custom Framer Component or Website?

I design beautiful, responsive websites and build advanced code components in Framer — tailored to your brand, product, or workflow.

Let’s work together: [Reach out on Email](samuel02emmanuel02@gmail.com)


