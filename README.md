<div align="center">

# Азамат Пердеев
### Ақпараттық қауіпсіздік • Жүйелер • Full-stack • AI

<p align="center">
  <img src="https://img.shields.io/badge/Орналасуы-Астана%2C%20Қазақстан-0A66C2?style=flat-square&logo=googlemaps&logoColor=white" alt="Орналасуы" />
  <img src="https://img.shields.io/badge/Бағыты-Ақпараттық%20қауіпсіздік-8B5CF6?style=flat-square&logo=hackthebox&logoColor=white" alt="Бағыты" />
  <img src="https://img.shields.io/badge/Стек-Go%20%7C%20C%23%20%7C%20Python%20%7C%20TS-181717?style=flat-square" alt="Стек" />
</p>

<p align="center">
  Қауіпсіздікке, құпиялылыққа және практикалық пайдаға бағытталған бағдарламалық өнімдер жасаймын.
</p>

</div>

---

## 👨💻 Мен туралы

Мен — Қарағанды техникалық университетінің Ақпараттық қауіпсіздік бағыты бойынша түлегімін және бағдарламалық қамтамасыз ету әзірлеушісімін.

Негізгі қызметім киберқауіпсіздік, жүйелік бағдарламалау және заманауи веб-технологиялардың түйіскен тұсында шоғырланған. Қауіпсіздікті қосымша қабат ретінде емес, архитектураның негізгі өзегі ретінде қарастыра отырып, деректер құпиялылығы сақталатын құралдар, алдамшы қорғаныс жүйелері мен пайдалы цифрлық өнімдер құрастырамын.

---

## 🛠️ Технологиялық стек

### Бағдарламалау тілдері
* Go, C# (.NET 8), Python, TypeScript, JavaScript (ES6+), Kotlin, SQL

### Киберқауіпсіздік
* **Honeytokens / Deception Technology** (алдамшы ресурстар мен тұзақтар)
* **Phishing Detection** (фишингтік шабуылдарды анықтау және сараптау)
* **BERT** (мәтіндік қауіптерді талдауға арналған нейрожелілер)
* **Browser Fingerprinting** (браузердің сандық ізін анықтау)
* **NTFS ACL & Windows Firewall API** (жүйелік рұқсаттар мен желілік ережелерді автоматтандыру)
* **TOTP 2FA** (екі факторлы аутентификация)
* **Security Audit Logging** (қауіпсіздік оқиғаларын тіркеу және қауіп деңгейін бағалау)
* **Client-side Privacy** (деректерді сыртқы серверге жібермей, клиент жағында өңдеу)

### Backend (серверлік бөлік)
* Go net/http, FastAPI, Next.js API Routes, Node.js
* PostgreSQL, SQLite, Redis
* Prisma, Alembic

### Frontend (клиенттік бөлік)
* React, Next.js, Svelte, Tailwind CSS
* Jetpack Compose (Android)
* HTML5 Canvas

### Инфрақұрылым
* Docker, Docker Compose
* Nginx
* GitHub Actions (CI/CD)

### AI (жасанды интеллект)
* PyTorch, Hugging Face Transformers
* DeepSeek, Gemini, Qwen API

---

## 🚀 Негізгі жобалар

### [LAN Share Manager](https://github.com/Azamaperdeev05/lan-share-manager)
Windows жүйесінде SMB желілік ортақ бумаларын баптауға, NTFS құқықтары мен брандмауэрді автоматтандыруға арналған жүйелік утилита.
* **Технологиялар:** C# (.NET 8 LTS), WPF, Win32 / PowerShell автоматизациясы, GitHub Actions CI
* Таза архитектура (Clean Architecture) қағидасымен бөлінген модульдер (`Core`, `Infrastructure`, `CLI`, `App`, `Tests`).
* Windows Firewall желілік ережелерін (TCP 445 порты) және жүйелік тілге байланысты пайдаланушы құқықтарын автоматты түрде конфигурациялайды.
* Интерактивті CLI мәзірі, бір жолдық PowerShell орнатқышы (`irm azamaperdeev05.github.io/lsm | iex`) және 3 тілді (KZ, RU, EN) интерфейсі бар.

[GitHub репозиторийі](https://github.com/Azamaperdeev05/lan-share-manager) • [Құжаттамасы мен нұсқаулығы](https://azamaperdeev05.github.io/lan-share-manager/) • [Релиздер](https://github.com/Azamaperdeev05/lan-share-manager/releases)

---

### [Canary Token Generator](https://github.com/Azamaperdeev05/canary-token-generator)
Желіге немесе файлдарға рұқсатсыз қол сұғуды ерте анықтауға арналған Honeytoken жүйесі.
* **Технологиялар:** Go 1.25+, PostgreSQL 18, Redis 7, Docker, Nginx, Cloudflare Tunnel
* 7 түрлі алдамшы тұзақ құрастырады: `webbug`, `slowredirect`, арнайы дайындалған PDF/DOCX файлдары, `.env`, `kubeconfig` және нақты MySQL v10 хаттамасында жауап беретін тұзақ сервис.
* Тұзақ іске қосылған сәтте шабуылдаушының браузерлік сандық ізін жинайды: Canvas FNV-1a хэші, AudioContext, WebRTC арқылы VPN артындағы жергілікті IP-ді анықтау және экран өлшемдері.
* Redis арқылы қайталанатын спамды сүзгіден өткізіп (15 минуттық терезе), GeoIP мәліметтерімен байытылған HMAC қолтаңбалы Webhook және Telegram хабарламаларын жедел жібереді.

[GitHub репозиторийі](https://github.com/Azamaperdeev05/canary-token-generator)

---

### [PhishGuard](https://github.com/Azamaperdeev05/PhishGuard)
Электрондық хаттар мен сілтемелерді сараптауға арналған жасанды интеллект негізіндегі фишингке қарсы жүйе.
* **Технологиялар:** Python 3.10+, PyTorch, Hugging Face Transformers (BERT), PySide6 (Qt), PostgreSQL, Alembic, Gmail API
* Хат тақырыптарының түпнұсқалығын (SPF, DKIM, DMARC), күдікті URL бағыттарын және хат мәтінін арнайы оқытылған BERT моделі арқылы талдайтын кешенді құбыр (pipeline).
* Gmail API (OAuth2) арқылы пошта жәшігін қауіпсіз тексеру, қауіпті хаттарға автоматты түрде белгі (label) қою және оқиғалар бойынша PDF есептер жасау.
* Деректер базасының көші-қонын басқаратын Alembic жүйесі, PySide6 графикалық интерфейсі және дербес тестілеу жиынтығы бар.

[GitHub репозиторийі](https://github.com/Azamaperdeev05/PhishGuard)

---

### [Bank Statement Analyzer](https://github.com/Azamaperdeev05/bank-analizer)
Қазақстан банктерінің PDF үзінді көшірмелерін тікелей браузерде, деректер құпиялылығын сақтай отырып талдайтын веб-құрал.
* **Технологиялар:** Vanilla JavaScript (ES6+), PDF.js, Canvas 2D, CSS3
* 3 200-ден астам жол таза алгоритмдік код арқылы 5 отандық банктің (Kaspi, Halyk, Forte, Jusan, BCC) көшірмелерін құрылымдайды.
* **Құпиялылыққа негізделген архитектура:** Барлық операциялар пайдаланушының құрылғысында (браузер жадында) жүреді; құжаттар мен қаржылық деректер ешқандай сыртқы серверге жіберілмейді.
* Транзакцияларды автоматты түрде санаттарға топтайды, шығыстар кестесін сызады және қаржылық балансты математикалық тұрғыдан салыстырады.

[GitHub репозиторийі](https://github.com/Azamaperdeev05/bank-analizer) • [Тікелей сынап көру](https://bank-analizer-beta.vercel.app)

---

### [DentFlow KZ](https://github.com/Azamaperdeev05/dentflow-kz)
Стоматологиялық клиниканың жұмысын цифрландыруға арналған басқару жүйесі.
* **Технологиялар:** Next.js 14, TypeScript, Prisma ORM, NextAuth (Auth.js v5), SQLite / PostgreSQL, Vitest
* Рөлдерге негізделген қолжетімділік (`ADMIN`, `DOCTOR`, `PATIENT`) және TOTP алгоритмімен (QR-код арқылы) екі факторлы қауіпсіздік қорғанысы.
* Қауіпсіздік журналы (`SecurityAuditLog`) мен күдікті әрекеттерді тіркеу (`LoginRiskSignal`) кестелері арқылы IP және құрылғы белгілерін есепке алу.
* Науқастарды қабылдауға жазу, емдеу карталары, медициналық құжаттарды жүктеу және клиникаішілік байланыс функционалы.

[GitHub репозиторийі](https://github.com/Azamaperdeev05/dentflow-kz)

---

### [NotificationShare](https://github.com/Azamaperdeev05/NotificationShare)
Android құрылғысындағы хабарландыруларды сыртқы арналарға бағыттайтын ашық бастапқы кодты қолданба.
* **Технологиялар:** Kotlin 1.9, Jetpack Compose (Material 3), Android SDK 24+, Coroutines, WorkManager
* Android `NotificationListenerService` қызметі негізінде кілт сөздер бойынша сүзгілеу, қара тізім және WorkManager арқылы қайта жіберу кезегін басқару.
* Хабарландыруларды Telegram, Discord, Slack немесе Webhook арқылы таратады.
* Қолданбаға кіру биометриялық сәйкестендірумен (`BiometricPrompt`) қорғалған, баптаулары шифрланған жадта (`EncryptedSharedPreferences`) сақталады және 10 тілде оқшауланған.

[GitHub репозиторийі](https://github.com/Azamaperdeev05/NotificationShare)

---

## 🇰🇿 Қазақстанға арналған цифрлық өнімдер

Отандық пайдаланушылар мен қазақ тілді ортаға арнайы жасалған ашық бастапқы кодты жобалар:

* **[Сөзділ (Sozdil)](https://github.com/Azamaperdeev05/sozdil):** Қазақ тіліндегі Wordle сөз табу ойыны (4, 5, 6 әріптік режимдер, толық сөздіктер қоры, Web және Android нұсқалары) • [Веб-сайт](https://sozdil.vercel.app).
* **[ЗаңКеңес AI (zanaikz)](https://github.com/Azamaperdeev05/zanaikz):** Қазақстан Республикасының заңнамалық базасына негізделген, көпмодельді жасанды интеллект кеңесшісі • [Веб-сайт](https://zanaikz.vercel.app).
* **[Univer Platonus](https://github.com/Azamaperdeev05/univer.univers):** Қазақстан университеттерінің студенттеріне арналған Platonus деректерін көрсететін ыңғайлы PWA порталы • [Веб-сайт](https://univerkstu.site).
* **[Tezteru.kz](https://github.com/Azamaperdeev05/tezteru.kz):** Қазақ әліпбиіне арналған пернетақтада жылдам жазуды дамытатын тренажер • [Веб-сайт](https://tezteru-kz.vercel.app).

---

## 📊 GitHub белсенділігі

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=Azamaperdeev05&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=8B5CF6&icon_color=8B5CF6&text_color=c9d1d9" alt="GitHub статистикасы" />
&nbsp;
<img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Azamaperdeev05&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=8B5CF6&text_color=c9d1d9" alt="Қолданылатын тілдер" />

</div>

---

## 📫 Байланыс

<p align="center">
  <a href="https://github.com/Azamaperdeev05">
    <img src="https://img.shields.io/badge/GitHub-Azamaperdeev05-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub профилі" />
  </a>
</p>
