# Authentik Login-theme: Glassmorphism ✨

A custom **glassmorphism** login theme for [Authentik](https://goauthentik.io/), designed by **VULGA**.

> ✅ Tested and fully compatible with **Authentik version 2025.10.3** (Latest)  
> ✅ Compatible with both **PatternFly v4** and **PatternFly v5** (Authentik 2024.x+)

## ✨ Features (v3.1)

- **Modern Glassmorphism Design**: A complete visual overhaul for a premium look.
- **Full Responsiveness**: Optimized for all devices, including mobile/phones.
- **Enhanced Flows**: Custom styling for TOTP setup, authentication, and recovery flows.
- **User Settings Redesign**: Beautiful and responsive user settings and profile management.
- **Admin Panel Safe**: Specific styling isolation ensures the Admin Interface remains untouched and bug-free.
- **Easy Customization**: Simple variables to change background and accent colors.
- **PatternFly v5 Support**: Dual-targeting of both `pf-c-*` (PF4) and `pf-v5-c-*` (PF5) class names for forward compatibility with newer Authentik versions.

## 📸 Login Preview
<img width="2478" height="1115" alt="login" src="https://github.com/user-attachments/assets/c5237f16-88c7-40d1-a5f7-1afbc7ffb823" />

## 📸 User Settings Preview

<img width="2482" height="1079" alt="user-settings" src="https://github.com/user-attachments/assets/90232855-780c-4004-9b5f-5d43d55808c7" />

## 📸 App Dashboard Preview
<img width="2486" height="1119" alt="app list" src="https://github.com/user-attachments/assets/99c22aac-a6c7-4305-9510-f78dfd5575df" />


## 🧑‍🎨 Author

Designed and maintained by **VULGA**  
Feel free to use, modify, or extend the theme.


## 🚀 Installation

1. Clone or download this repository.
2. Copy the CSS file content into your Authentik custom theme section:
   - Admin → System → Brands → Choose your brand and edit it → Brand settings → Custom CSS
3. Optionally customize the easy customization variables at the top of the CSS file (background image, accent color, separator text).
4. Save and refresh the login page.

## 🎨 Customization

At the top of `theme.css`, you can change these variables:

```css
:root {
    /* Background image URL */
    --ak-flow-background: url(https://i.imgur.com/zMTDTxy.jpeg);

    /* Separator text shown above social login buttons */
    --ak-social-separator-text: "or";

    /* Accent color */
    --ak-accent: #d0ced0;
}
```
   
## ⚠️ Cloudflare Notice

If you're using **Cloudflare** with a **proxied domain**, you might experience issues due to cached CSS.  
👉 In that case, **purge your Cloudflare cache** to ensure changes take effect.


## 🔓 License

This project is open source and freely available under the **MIT License**.  
You can **use, share, and modify** it without restriction.
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

---

> Made with ❤️ by [VULGA](https://github.com/VULGA01)
