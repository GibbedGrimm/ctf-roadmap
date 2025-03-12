
# 🏴‍☠️ CTF Roadmap: Веб-направление

## 🚦 Уровень 0: Подготовка
### 📌 Изучи основы веба:
- **HTTP/HTTPS, методы запросов (GET, POST, PUT, DELETE)**  
- **Куки и сессии, URL параметры**  
- **Инструменты:**  
  - 🛠 Burp Suite (перехват запросов)  
  - 🛠 Postman, cURL (отправка запросов)  

📚 **Где учить:**  
- [TryHackMe — "Intro to Web Hacking"](https://tryhackme.com)  
- [PortSwigger Academy — "HTTP Basics"](https://portswigger.net/web-security)  

---

## 🔑 Уровень 1: Базовые уязвимости  
### 🛠 **SQL Injection (SQLi)**  
- Принцип работы SQL-запросов.
- Методы поиска иньекций.
- sqlmap. 
- 🏆 **Практика:**  
  - [PortSwigger — "SQL Injection"](https://portswigger.net/web-security/sql-injection)  
  - [TryHackMe — "SQL Injection"](https://tryhackme.com)  

### 🔥 **XSS (Cross-Site Scripting)**  
- Виды XSS: Reflected, Stored, DOM-based  
- Полезный пейлоад: `<script>alert(1)</script>`  
- 🏆 **Практика:**  
  - [PortSwigger — "XSS"](https://portswigger.net/web-security/cross-site-scripting)
  - [HackTheBox - там где то есть но я не нашел](https://app.hackthebox.com/competitive/7/overview)
### 🤷‍♂️ **Command Injection**
- Как команды выполняются на сервере через параметры.
- Пейлоады: ; ls , | cat /etc/passwd.
- 🏆**Практика**
    - [TryHackMe](https://tryhackme.com/)
    - [HackTheBox](https://app.hackthebox.com/home)
###

---
##🧱 Уровень 2: Легенда
### 😱File Inclusion (LFI/RFI):
- Доступ к системным файлам ../../etc/passwd.
- 🏆 Практика:
    - [PortSwigger — "File Inclusion".](https://portswigger.net/)
    - [TryHackMe - "Inclusion Exploits".](https://tryhackme.com/)

## ⚙️ Где тренироваться:
- 🔗 [CTFtime](https://ctftime.org/)  
- 🔗 [Hack The Box](https://www.hackthebox.com/)  
- 🔗 [TryHackMe](https://tryhackme.com/)  
язвимости.
    Root Me — разнообразные задачи, есть подсказки.
