# adminer-gruvbox

A theme for **Adminer** inspired by [adminer-nord](https://github.com/barelyhuman/adminer-nord), but adapted to **Gruvbox** colors.

This theme provides a warm, earthy aesthetic with high readability, leveraging Gruvbox’s signature contrast between **soft yellows, browns, oranges, and muted blues**.

---

## 🚧 Disclaimer

This theme is still being refined, and some elements may still inherit styles from **adminer-nord**. If you notice any inconsistencies or areas that need better Gruvbox adaptation, **please report an issue!**

---

## 📖 Usage

### 🔧 Manual Installation

1. **Download** `adminer.css` from this repo.
2. **Rename** the file to `adminer.css` (if it isn't already).
3. **Place** it in the same directory as your `adminer.php` file.

### 🐳 Docker Setup

These instructions have been tested with [docker-adminer](https://hub.docker.com/_/adminer/):

1. Copy the themed CSS (`adminer.css`) into your directory.
2. In your **Dockerfile**, add the following line:

```dockerfile
ADD ./design.css /var/www/html/adminer.css
```

3. Restart your **Adminer** container to apply the new theme.

---

## 🏆 Credits

- [barelyhuman](https://github.com/barelyhuman/adminer-nord) for the **adminer-nord** theme that served as the base.
- [pepa-linha](https://github.com/pepa-linha/Adminer-Design-Dark) for the original **pepa-linha-dark** theme.
- The **Gruvbox color scheme** by [morhetz](https://github.com/morhetz/gruvbox).

---

## ☕ Support

If you enjoy this theme and would like to support the work:

<noscript><a href="https://liberapay.com/dotMavriQ/donate"><img alt="Donate using Liberapay" src="https://liberapay.com/assets/widgets/donate.svg"></a></noscript>

---

## ⚡ Contributing

Want to improve the theme or tweak it for better readability? Feel free to submit PRs or open an issue for suggestions!

Enjoy your **Gruvbox Adminer** experience! 🎨🔥
