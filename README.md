# Hack The Box — Titanic

<div align="center">
  <img src="Titanic/assets/HTB/1.png" width="250">
</div>

Writeup for the Hack The Box machine **Titanic** (Linux, Easy/Medium).  
The box involves **web exploitation**, **credential cracking**, and **privilege escalation** through an **ImageMagick vulnerability**.

---

## 📝 Summary
- **Initial foothold:** Path traversal → file disclosure → hidden vhost  
- **User access:** Extracting + cracking Gitea database credentials → SSH  
- **Privilege escalation:** Exploiting ImageMagick (CVE-2024-41817) via cronjob → root shell  

---

## 📂 Files
- `Titanic_writeup.md` — full detailed writeup with screenshots  
- `assets/HTB/` — screenshots used in the writeup  

---

## 🔗 References
- [Hack The Box](https://www.hackthebox.com/)  
- [CVE-2024-41817 PoC](https://github.com/Dxsk/CVE-2024-41817-poc)  

---

⚠️ **Disclaimer:** For educational purposes only. Do not test on systems without permission.
