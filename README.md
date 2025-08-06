# Ultra Stealth Login

Hide `wp-login.php` and `wp-admin` from bots and hackers. Allow login only through a secret URL. Built to be lightweight, secure, and developer-friendly.

![License](https://img.shields.io/badge/license-GPLv2-blue.svg)
![WP Version](https://img.shields.io/badge/WordPress-5.0%2B-blue)
![PHP Version](https://img.shields.io/badge/PHP-7.4%2B-orange)
![Built By](https://img.shields.io/badge/Built%20by-DevShubho-8a2be2)

---

## Features

- Hide `wp-login.php` and `wp-admin` from unauthorized access
-  Set a custom secret login URL (e.g. `/my-secret-login`)
- Shows clean, minimal 404 error to intruders
- Reduces brute-force attacks and bot logins
- Easy admin settings panel with UI
- Online-style indicator for active login URL
- Copy-to-clipboard button to grab login link
- ightweight, no unnecessary bloat

---

## 🧠 How It Works

Once activated:
- Anyone accessing `/wp-login.php` or `/wp-admin` without login gets a custom 404 page.
- You set a secret login slug like `/super-safe-login`.
- Only users with the correct link can access the login page.

---

## ⚙️ Usage

1. **Install Plugin**
   - Upload `ultra-stealth-login` folder to `/wp-content/plugins/`
   - Or install via WordPress Admin → Plugins → Upload Plugin

2. **Activate Plugin**

3. **Go to Settings → Stealth Login**
   - Set your custom login slug (e.g., `super-secret-door`)
   - Your login URL becomes: `https://yourdomain.com/super-secret-door`

---

## Example

| URL | Result |
|-----|--------|
| `/wp-login.php` | ❌ 404 Page |
| `/wp-admin` (unauthenticated) | ❌ 404 Page |
| `/my-secret-login` | Shows login screen |

---

## Admin UI Preview

```plaintext
🟢 Login URL is active at: https://yourdomain.com/my-secret-login   [Copy]
