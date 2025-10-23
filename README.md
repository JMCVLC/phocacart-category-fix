# 🔧 PhocaCart Category Fix

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Joomla](https://img.shields.io/badge/Joomla-5.x-blue)](https://www.joomla.org/)
[![PhocaCart](https://img.shields.io/badge/PhocaCart-5.2.x-green)](https://www.phoca.cz/phocacart)

**Fix for missing category field in PhocaCart 5.2.x with Joomla 5.x**

Free community solution - No official support provided.

---

## 📋 The Problem

After updating PhocaCart to version 5.2.x on Joomla 5.x, the **category field disappears** when editing products, making it impossible to save products since category is a required field.

This component fixes the issue by:
- Creating the missing `phocacart_content_types` table
- Adding missing database columns
- Updating incorrect values
- Clearing the cache

---

## ⚡ Quick Start

### Installation

1. **Download** the latest release: [Download ZIP](https://github.com/JMCVLC/phocacart-category-fix/releases)
2. **Install** via Joomla Extensions Manager
3. Go to **Components → PhocaCart Fix**
4. Click **"Run Fix Now"**
5. **Uninstall** the component immediately after

That's it! Your PhocaCart category field should now work.

---

## 🛠️ What It Does

This component executes the following database operations:

✅ Creates `#__phocacart_content_types` table if missing  
✅ Inserts required content type records  
✅ Adds `category_type` column to categories table  
✅ Updates `category_type` values from 0 to 1  
✅ Adds `related_type` column to related products table  
✅ Clears Joomla cache  

---

## 💻 Compatibility

- **Joomla**: 5.x
- **PhocaCart**: 5.2.x
- **PHP**: 7.4+
- **Database**: MySQL 5.7+ / MariaDB 10.2+

---

## ⚠️ Important Notes

- **BACKUP YOUR DATABASE** before running (recommended)
- Use at your own risk
- This is an **unofficial community fix**
- No official support provided
- **Uninstall immediately** after use

---

## 🤝 Contributing

Found a bug or have an improvement? Feel free to:
- Open an [Issue](https://github.com/JMCVLC/phocacart-category-fix/issues)
- Submit a Pull Request
- Share your experience in [Discussions](https://github.com/JMCVLC/phocacart-category-fix/discussions)

---

## ☕ Support the Project

If this fix saved your day and you'd like to say thanks:

[![Donate with PayPal](https://img.shields.io/badge/Donate-PayPal-blue.svg)](https://www.paypal.com/paypalme/jmcpaypal)

Your support helps maintain free community solutions!

---

## 📚 Resources

- [Phoca Forum Thread](https://www.phoca.cz/forum/) - Original bug reports
- [Joomla Extensions Directory](https://extensions.joomla.org/)
- [PhocaCart Documentation](https://www.phoca.cz/documents/)

---

## 📄 License

MIT License - see [LICENSE](LICENSE) file for details.

---

## 👤 Author

**JMC**

- Website: [nacidosdelatierra.com](https://nacidosdelatierra.com?utm_source=github&utm_medium=readme&utm_campaign=phocacart_fix)
- GitHub: [@JMCVLC](https://github.com/JMCVLC)

---

## ⭐ Show Your Support

If this project helped you, please give it a ⭐ on GitHub!

---

**Disclaimer**: This is an independent community project. Not affiliated with or endorsed by Phoca or Joomla.
