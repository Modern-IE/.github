<div align="center">

# 🏛️ Modern-IE

Engineering for Every Era.  
*Bridging the gap between 2001 and today.*

[![ES3 Compatible](https://img.shields.io/badge/JavaScript-ES3_Compatible-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](#)
[![Trident Engine](https://img.shields.io/badge/Engine-Trident_(IE6--8)-0078D7?style=for-the-badge&logo=internet-explorer&logoColor=white)](#)
[![Graceful Degradation](https://img.shields.io/badge/CSS-Graceful_Degradation-1572B6?style=for-the-badge&logo=css3&logoColor=white)](#)

</div>

---

## 📖 About Us

Modern-IE is an open-source collective dedicated to the ultimate engineering challenge: running the modern web on legacy Trident engines (Internet Explorer 6, 7, and 8). 

We believe that "legacy" doesn't mean "dead". Whether it's for enterprise industrial systems that cannot be upgraded, retro-computing enthusiasts, or simply the sheer technical thrill of making modern paradigms work on 20-year-old software, we build robust, production-grade tools for the ancient web.

No modern syntax. No assumed globals. Just pure, unadulterated backwards compatibility.

---

## ⚡ Core Philosophy

1. Strict ES3 Compliance: We write and compile JavaScript that avoids all reserved words (`catch`, `class`, `delete`), trailing commas, and modern APIs. 
2. Graceful Degradation: Our UI frameworks are designed to look like Apple in Chrome, and gracefully degrade to solid, usable, standard-mode layouts in IE6.
3. Zero-Dependency Core: We rely on raw `ActiveXObject` and native DOM APIs, avoiding bloated modern polyfill chains whenever possible.
4. HasLayout Magic: We master the dark arts of `*display: inline; *zoom: 1;` to replicate modern Flexbox/Grid behaviors.

---

## 🛠️ The "Dark Arts" Stack

If you contribute here, you will learn (or remember) the forbidden knowledge:

- `['catch'](function() {})` instead of `.catch()`
- `var that = this;` instead of arrow functions
- Triggering IE's `hasLayout` to fix box-model bugs
- Handling memory leaks in circular DOM-to-Closure references
- JSONP script injection to bypass strict CORS policies

---

## 🤝 Contributing

We welcome archaeologists, retro-engineers, and modern frontend developers looking for a masochistic weekend challenge. 

1. Fork any of our repositories.
2. Ensure your code runs error-free in an IE6/IE8 virtual machine.
3. Submit a Pull Request.

*"If it runs on IE6, it runs on anything."*

<br/>
<div align="center">
  <sub>Built with ❤️ (and ActiveX) by the Modern-IE Team.</sub>
</div>
