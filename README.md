🏴‍☠️ CTF Roadmap: Веб-направление
🚦 Уровень 0: Подготовка

    Изучи основы веба:
        HTTP/HTTPS, запросы и ответы, методы GET, POST, PUT, DELETE.
        Как работают URL, параметры запросов, куки и сессии.
        Инструменты:
            Burp Suite (перехват запросов).
            Postman, cURL (отправка запросов).
        📖 Где учить:
            TryHackMe — "Intro to Web Hacking".
            PortSwigger Academy — "HTTP Basics".

    Настрой рабочее окружение:
        Kali Linux или Parrot OS (можно виртуалку через VirtualBox/VMware).
        Установи: Burp Suite, nmap, gobuster, sqlmap.

🔑 Уровень 1: Базовые уязвимости

    SQL Injection (SQLi):
        Принцип работы SQL-запросов.
        Поиск инъекций: ' OR 1=1 --, UNION SELECT.
        Автоматизация: sqlmap.
        🏆 Практика:
            PortSwigger — "SQL Injection".
            TryHackMe — "SQL Injection".
            HackTheBox — задачи с тегом SQLi.

    Cross-Site Scripting (XSS):
        Различия Reflected, Stored и DOM-based XSS.
        Полезные пейлоады: <script>alert(1)</script>.
        🏆 Практика:
            PortSwigger — "Cross-site Scripting (XSS)".
            HackTheBox — задачи с тегом XSS.

    Command Injection:
        Как команды выполняются на сервере через параметры.
        Пейлоады: ; ls, | cat /etc/passwd.
        🏆 Практика:
            TryHackMe — "Injection Room".
            HackTheBox — поиск задач с тегом Command Injection.

🧱 Уровень 2: Средний уровень

    File Inclusion (LFI/RFI):
        Доступ к системным файлам: ../../etc/passwd.
        🏆 Практика:
            PortSwigger — "File Inclusion".
            TryHackMe — "Inclusion Exploits".

    IDOR (Insecure Direct Object Reference):
        Подмена ID в запросах для доступа к чужим данным.
        🏆 Практика:
            PortSwigger — "IDOR".
            HackTheBox — задачи с тегом IDOR.

    SSRF (Server-Side Request Forgery):
        Заставить сервер делать запросы от твоего имени.
        🏆 Практика:
            PortSwigger — "SSRF".
            TryHackMe — "SSRF Room".

💣 Уровень 3: Продвинутый уровень

    JWT (JSON Web Tokens):
        Как работают токены авторизации, их подделка.
        🏆 Практика:
            TryHackMe — "JWT Exploits".

    Race Conditions:
        Одновременное выполнение нескольких запросов для обхода защиты.
        🏆 Практика:
            HackTheBox — "Race Conditions".

    Business Logic Flaws:
        Ошибки в логике приложения, позволяющие обойти защиту.
        🏆 Практика:
            HackTheBox — "Logic Bugs".

📈 Уровень 4: Углублённое изучение (по желанию)

    Основы работы с Docker и контейнерами.
    Атаки на API (GraphQL, REST).
    Обход ограничений CORS (Cross-Origin Resource Sharing).

⚙️ Где тренироваться постоянно:

    CTFtime — календарь всех CTF-соревнований.
    Hack The Box — для всех уровней.
    TryHackMe — много учебных комнат для веба.
    PortSwigger Academy — бесплатно, охватывает все основные уязвимости.
    Root Me — разнообразные задачи, есть подсказки.
