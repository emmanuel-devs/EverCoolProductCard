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


