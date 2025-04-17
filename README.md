# 📸 Instagram OAuth Integration – Laravel 11

This package/module enables **Instagram login/authentication** in your Laravel 11 application using **OAuth 2.0**.

---

## 🔧 Prerequisites

- Laravel 11 installed  
- PHP 8.2 or above  
- Composer  
- Instagram Developer Account  
- Instagram App created at: [Meta Developer Portal](https://developers.facebook.com/apps)

---

## 📦 Installation

```bash
composer require socialiteproviders/instagram



## 📦  Configure .env

INSTAGRAM_CLIENT_ID=your_instagram_app_id
INSTAGRAM_CLIENT_SECRET=your_instagram_app_secret
INSTAGRAM_REDIRECT_URI=https://yourdomain.com/auth/instagram/callback

## 📦  Set up config/services.php

'instagram' => [
    'client_id' => env('INSTAGRAM_CLIENT_ID'),
    'client_secret' => env('INSTAGRAM_CLIENT_SECRET'),
    'redirect' => env('INSTAGRAM_REDIRECT_URI'),
],

## 📦  Conclusion

On success, users will be redirected back and authenticated

