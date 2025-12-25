# WooCommerce Video Gallery Enhancer Pro

**WooCommerce Video Gallery Enhancer Pro** allows you to seamlessly integrate video content into your WooCommerce product galleries. Replace or supplement static images with YouTube, YouTube Shorts, or self-hosted videos to increase conversion rates and customer engagement by giving users a dynamic view of your products.

This Pro version provides total control over your gallery's aesthetics, allowing you to define custom thumbnails and handle modern video formats like YouTube Shorts effortlessly.

---

## 💎 Pro vs. Free: What’s the Difference?

The Pro version is built for professional stores that require a branded look and advanced URL handling:

* **Custom Thumbnail Support:** Pro allows you to upload a specific image to represent your video in the gallery strip, overriding default automated covers.
* **YouTube Shorts Integration:** Specialized logic to detect and convert `/shorts/` URLs into compatible embed formats automatically.
* **Enhanced URL Logic:** Smartly handles `watch?v=`, `embed/`, and `youtu.be` links to ensure they always display correctly as responsive iframes.
* **Dual Media Uploaders:** Dedicated buttons for both the Video file and the Thumbnail image within the product editor.

---

## 🚀 Features

* **Custom Video Thumbnails:** Upload any image via the Media Library to act as your video's placeholder.
* **YouTube Shorts Support:** Paste a YouTube Shorts link and let the plugin handle the conversion to a gallery-ready embed.
* **Multi-Platform Support:** Seamlessly integrate YouTube (Standard & Shorts) or self-hosted MP4 videos.
* **Precise Position Control:** Use the numerical position setting to place your video exactly where you want it (e.g., "1" to make the video the primary item).
* **Divi & Page Builder Compatible:** Fully tested with the **Divi Product Image Module** and other standard WooCommerce layouts.
* **Lightbox Playback:** Built-in support for **Magnific Popup** for a professional, responsive viewing experience.

---

## 📸 Screenshots

### Product Page View
![Product Page View](https://github.com/AnkushShingari/WooCommerce-Video-Gallery-Enhancer-Pro/blob/main/plugin-screenshots/WooCommerce-Video-Gallery-Enhancer-pro-screenshot-frontend-product-page-view.png?raw=true)

*The video integrates seamlessly into the gallery with a custom-defined position.*


### Backend Settings (Empty)
![Backend Settings Empty](https://github.com/AnkushShingari/WooCommerce-Video-Gallery-Enhancer-Pro/blob/main/plugin-screenshots/WooCommerce-Video-Gallery-Enhancer-pro-screenshot-backend-settings-tab.png?raw=true)

*Clean and intuitive admin interface located in the product sidebar.*


### Backend Settings (Filled)
![Custom Thumbnail Admin](https://github.com/AnkushShingari/WooCommerce-Video-Gallery-Enhancer-Pro/blob/main/plugin-screenshots/WooCommerce-Video-Gallery-Enhancer-pro-screenshot-backend-settings-tab-filled.png?raw=true)

*Easily manage Video URLs, positions, and custom thumbnail images.*


### Divi Compatibility
![Backend Settings Compatible With Divi](https://github.com/AnkushShingari/WooCommerce-Video-Gallery-Enhancer-Pro/blob/main/plugin-screenshots/WooCommerce-Video-Gallery-Enhancer-pro-screenshot-backend-compatible-with-divi.png?raw=true)

*Works perfectly within the Divi Builder environment.*

---

## 🛠 Installation

### Via WordPress Dashboard
1.  **Download** the `woocommerce-video-gallery-enhancer-pro.zip` file.
2.  Go to **Plugins** -> **Add New** -> **Upload Plugin**.
3.  Select the file and click **Install Now**, then **Activate**.

### Via FTP/SFTP
1.  **Extract** the plugin folder on your computer.
2.  Upload the `woocommerce-video-gallery-enhancer-pro` folder to the `/wp-content/plugins/` directory.
3.  Go to **WordPress Dashboard** -> **Plugins** and click **Activate**.

---

## ⚙️ Configuration

1.  **Edit** any WooCommerce Product.
2.  Locate the **Product Video Gallery** meta box in the right-hand sidebar.
3.  **Video URL:** Paste your YouTube link or click the upload icon for MP4s.
4.  **Display Position:** Enter a number (e.g., `1` for the first position).
5.  **Video Thumbnail (Pro):** Upload a custom image to act as the placeholder. *Leave empty to use automatic covers.*
6.  **Save/Update** the product.

---

## 💻 Technical Details

The plugin utilizes the `woocommerce_single_product_image_thumbnail_html` filter and enqueues **Magnific Popup** for high-performance rendering.

### Requirements:
* **PHP:** 7.4 or higher
* **WordPress:** 6.0+
* **WooCommerce:** 7.0+

---

## 👤 Author

**AnkushK2022**
* GitHub: [@AnkushShingari](https://github.com/AnkushShingari)

## 📄 License

This project is an open-source tool created and updated by the author. It is provided "as-is" for the community to use and improve.
