# Auto-Sliding Logo Carousel

This project implements a responsive, auto-sliding logo carousel using **SwiperJS** and **Bootstrap**. The carousel continuously scrolls through company logos without user interaction.

## 🚀 Features
- Automatic sliding (every 2 seconds)
- Infinite looping
- Fully responsive (adjusts based on screen size)
- No navigation or pagination for seamless scrolling

## 📂 Installation & Setup
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-repository/logo-carousel.git
cd logo-carousel
```

### 2️⃣ Open the Project in a Code Editor
Use any editor like **VS Code, Sublime, or Atom**.

### 3️⃣ Include Required Files
Ensure the following **CDNs** are added in the HTML file:
```html
<!-- Swiper CSS -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@9/swiper-bundle.min.css">
<!-- Swiper JS -->
<script src="https://cdn.jsdelivr.net/npm/swiper@9/swiper-bundle.min.js"></script>
```

### 4️⃣ Run the Project
Simply open the `index.html` file in a browser.

## 🛠️ Implementation Details
- **SwiperJS** is used to create the scrolling effect.
- The `autoplay` and `loop` settings ensure the logos slide automatically.
- `breakpoints` adjust the number of visible logos based on screen size.

## 🔧 Customization
- **Modify Slide Speed**: Change the autoplay delay in `swiper` config:
  ```js
  autoplay: {
      delay: 2000, // Adjust as needed
      disableOnInteraction: false,
  }
  ```
- **Change Number of Visible Logos**: Adjust `slidesPerView` in breakpoints.
  ```js
  breakpoints: {
      320: { slidesPerView: 2 },
      768: { slidesPerView: 3 },
      1024: { slidesPerView: 5 }
  }
  ```

## 📜 License
This project is licensed under the **MIT License**.

---
**Happy Coding! 🚀**

