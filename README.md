<div align="center">

# Азамат Пердеев
### Ақпараттық қауіпсіздік • Жүйелер • Full-stack • AI

<p align="center">
  <img src="https://img.shields.io/badge/Орналасуы-Қарағанды%2C%20Қазақстан-0A66C2?style=flat-square&logo=googlemaps&logoColor=white" alt="Орналасуы" />
  <img src="https://img.shields.io/badge/Бағыты-Ақпараттық%20қауіпсіздік-8B5CF6?style=flat-square&logo=hackthebox&logoColor=white" alt="Бағыты" />
  <img src="https://img.shields.io/badge/Тәсіл-Privacy--First%20%26%20Systems-181717?style=flat-square" alt="Тәсіл" />
</p>

<p align="center">
  <b>Қауіпсіздікке, құпиялылыққа және практикалық пайдаға бағытталған бағдарламалық өнімдер жасаймын.</b>
</p>

<p align="center">
  <a href="#-мен-туралы">Мен туралы</a> •
  <a href="#-не-жасаймын">Бағыттар</a> •
  <a href="#-инженерлік-карта">Инженерлік карта</a> •
  <a href="#-негізгі-жобалар">Жобалар</a> •
  <a href="#-технологиялық-стек">Стек</a> •
  <a href="#-қазақстанға-арналған-цифрлық-өнімдер">Қазақстан</a>
</p>

</div>

---

<a id="-мен-туралы"></a>
## 👨💻 Мен туралы

Мен — Қарағанды техникалық университетінің Ақпараттық қауіпсіздік бағыты бойынша түлегімін және бағдарламалық жасақтама инженерімін.

Негізгі бағытым — киберқауіпсіздік, жүйелік утилиталар және заманауи веб-архитектураның тоғысқан жері. Қауіпсіздікті формальды қосымша ретінде емес, өнімнің іргетасы ретінде көремін: алдамшы қорғаныс тұзақтары (deception technology), құпиялылықты сақтайтын жергілікті өңдеу құралдары мен қауіпсіз жүйелік шешімдер жасаймын.

---

<a id="-не-жасаймын"></a>
## 🧩 Не жасаймын?

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🔐 Қауіпсіздік (Cybersecurity)</h3>
      <p>Honeytokens (алдамшы ресурстар), фишингке қарсы интеллектуалды талдау, шабуылшының сандық ізін анықтау және қауіпсіз аутентификация.</p>
      <p><b>Жобалар:</b> <a href="#-canary-token-generator">Canary Token Generator</a>, <a href="#-phishguard">PhishGuard</a></p>
    </td>
    <td width="50%" valign="top">
      <h3>⚙️ Жүйелер (Systems & Utilities)</h3>
      <p>Windows және Android жүйелерінің төменгі деңгейлі тетіктерін басқару, SMB желілік ортақ бумалары, NTFS ACL және желілік брандмауэрді автоматтандыру.</p>
      <p><b>Жобалар:</b> <a href="#-lan-share-manager">LAN Share Manager</a>, <a href="#-notificationshare">NotificationShare</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🤖 Жасанды интеллект (AI & ML)</h3>
      <p>Мәтіндік қауіптерді сараптайтын fine-tuned BERT трансформерлері және көпмодельді LLM API маршрутизациясы (DeepSeek, Gemini, Qwen).</p>
      <p><b>Жобалар:</b> <a href="#-phishguard">PhishGuard</a>, <a href="#-қазақстанға-арналған-цифрлық-өнімдер">ЗаңКеңес AI</a></p>
    </td>
    <td width="50%" valign="top">
      <h3>🌐 Веб және Құпиялылық (Privacy-First Web)</h3>
      <p>Деректерді сыртқы серверге тасымалдамай, 100% клиент жағында (in-browser) өңдейтін және жергілікті аудиторияға арналған цифрлық платформалар.</p>
      <p><b>Жобалар:</b> <a href="#-bank-statement-analyzer">Bank Statement Analyzer</a>, <a href="#-dentflow-kz">DentFlow KZ</a></p>
    </td>
  </tr>
</table>

---

<a id="-инженерлік-карта"></a>
## 🗺️ Инженерлік карта

```mermaid
flowchart TD
    Me["<b>Азамат Пердеев</b><br/><i>Ақпараттық қауіпсіздік & Жүйелік инженерия</i>"]
    
    Sec["🔐 <b>Киберқауіпсіздік</b>"]
    Sys["⚙️ <b>Жүйелік бағдарламалау</b>"]
    Web["🌐 <b>Full-stack & Privacy</b>"]
    AI["🤖 <b>Жасанды интеллект</b>"]

    Me --> Sec
    Me --> Sys
    Me --> Web
    Me --> AI

    Sec --> P1["<b>Canary Token Generator</b><br/><i>Honeytoken & Deception</i>"]
    Sec --> P2["<b>PhishGuard</b><br/><i>BERT & Email Security</i>"]

    Sys --> P3["<b>LAN Share Manager</b><br/><i>C# .NET 8 • SMB & NTFS ACL</i>"]
    Sys --> P4["<b>NotificationShare</b><br/><i>Kotlin • Android Service</i>"]

    Web --> P5["<b>Bank Statement Analyzer</b><br/><i>100% Client-side Privacy</i>"]
    Web --> P6["<b>DentFlow KZ</b><br/><i>RBAC & TOTP 2FA</i>"]

    AI --> P2
    AI --> P7["<b>ЗаңКеңес AI</b><br/><i>LLM Legal Routing</i>"]

    classDef core fill:#0d1117,stroke:#8B5CF6,stroke-width:2px,color:#ffffff;
    classDef domain fill:#161b22,stroke:#3b82f6,stroke-width:1.5px,color:#ffffff;
    classDef proj fill:#21262d,stroke:#30363d,stroke-width:1px,color:#c9d1d9;
    class Me core;
    class Sec,Sys,Web,AI domain;
    class P1,P2,P3,P4,P5,P6,P7 proj;
```

---

<a id="-негізгі-жобалар"></a>
## 🚀 Негізгі жобалар

<a id="-lan-share-manager"></a>
### 🛡️ [LAN Share Manager](https://github.com/Azamaperdeev05/lan-share-manager)
Windows жүйесінде SMB желілік ортақ бумаларын баптауға, NTFS рұқсаттары мен брандмауэр ережелерін автоматтандыруға арналған жүйелік утилита.

**Стек:** C# • .NET 8 LTS • WPF • Win32 / PowerShell • GitHub Actions CI

[📦 Репозиторий](https://github.com/Azamaperdeev05/lan-share-manager) • [📖 Нұсқаулық & Құжаттама](https://azamaperdeev05.github.io/lan-share-manager/) • [🚀 Releases](https://github.com/Azamaperdeev05/lan-share-manager/releases)

<details>
<summary><b>🔍 Техникалық мәліметтер мен архитектура</b></summary>

* Таза архитектура (Clean Architecture) қағидасымен 5 дербес модульге бөлінген (`Core`, `Infrastructure`, `CLI`, `App`, `Tests`).
* Windows Firewall желілік ережелерін (TCP 445 порты) және жүйелік тілге байланысты жергілікті пайдаланушы құқықтарын автоматты түрде конфигурациялайды.
* Алдын ала қателіктерді тексеретін pre-flight тексеру жүйесі, интерактивті консоль мәзірі және 1 жолдық PowerShell орнатқышы (`irm azamaperdeev05.github.io/lsm | iex`) бар.
* 3 тілді (Қазақша, Орысша, Ағылшынша) толық қолдайды.
</details>

---

<a id="-canary-token-generator"></a>
### 🪤 [Canary Token Generator](https://github.com/Azamaperdeev05/canary-token-generator)
Жүйеге немесе файлдарға рұқсатсыз қол сұғу әрекеттерін ерте анықтайтын self-hosted Honeytoken тұзақ жүйесі.

**Стек:** Go 1.25+ • PostgreSQL 18 • Redis 7 • Docker • Nginx • Cloudflare Tunnel

[📦 Репозиторий](https://github.com/Azamaperdeev05/canary-token-generator)

<details>
<summary><b>🔍 Техникалық мәліметтер мен архитектура</b></summary>

* 7 түрлі алдамшы тұзақ құрастырады: `webbug`, `slowredirect`, дайындалған PDF/DOCX файлдары, `.env`, `kubeconfig` және нақты MySQL v10 wire-protocol форматында жауап беретін тұзақ тыңдаушы (listener).
* Тұзақ іске қосылған сәтте шабуылдаушының құрылғы ізін жинайды: Canvas FNV-1a хэші, AudioContext осцилляторы, WebRTC STUN арқылы VPN артындағы жергілікті IP-ді анықтау және экран өлшемдері.
* Асинхронды worker pool, 15 минуттық Redis анти-спам сүзгісі, GeoIP MaxMind ақпараты және HMAC қолтаңбалы Webhook / Telegram хабарламалары бар.
</details>

---

<a id="-phishguard"></a>
### 📧 [PhishGuard](https://github.com/Azamaperdeev05/PhishGuard)
Электрондық хаттар мен сілтемелердегі қауіптерді сараптауға арналған жасанды интеллект негізіндегі фишингке қарсы платформа.

**Стек:** Python 3.10+ • PyTorch • Hugging Face Transformers (BERT) • PySide6 • PostgreSQL • Alembic • Gmail API

[📦 Репозиторий](https://github.com/Azamaperdeev05/PhishGuard)

<details>
<summary><b>🔍 Техникалық мәліметтер мен архитектура</b></summary>

* Хат тақырыптарының түпнұсқалығын (SPF, DKIM, DMARC), күдікті URL бағыттарын және хат мәтінін fine-tuned BERT трансформері арқылы тексеретін кешенді pipeline.
* Gmail API (OAuth2) арқылы поштаны қауіпсіз тексеру, қауіпті хаттарға автоматты түрде белгі (label) қою және PDF форматында оқиғалық есептер шығару (ReportLab).
* Деректер базасының көші-қонын басқаратын Alembic, PySide6 графикалық жұмыс үстелі және дербес тестілеу модулі қамтылған.
</details>

---

<a id="-bank-statement-analyzer"></a>
### 📊 [Bank Statement Analyzer](https://github.com/Azamaperdeev05/bank-analizer)
Қазақстан банктерінің PDF үзінді көшірмелерін тікелей браузер жадында, 100% құпиялы түрде талдайтын қаржылық веб-құрал.

**Стек:** JavaScript (ES6+) • PDF.js • Canvas 2D • CSS3 • Vercel

[📦 Репозиторий](https://github.com/Azamaperdeev05/bank-analizer) • [🌐 Тікелей сынап көру](https://bank-analizer-beta.vercel.app)

<details>
<summary><b>🔍 Техникалық мәліметтер мен архитектура</b></summary>

* 3 200-ден астам жол таза алгоритмдік JavaScript код арқылы 5 банк үзіндісін өңдейді: Kaspi, Halyk, Forte, Jusan, BCC.
* **Client-side құпиялылық:** Қаржылық деректер мен файлдар ешқандай сыртқы серверге жіберілмейді, барлық есептеу тек жергілікті браузер жадында орындалады.
* Транзакцияларды автоматты түрде санаттарға топтайды, диаграммалар сызады және балансты математикалық тұрғыдан салыстырады.
</details>

---

<a id="-dentflow-kz"></a>
### 🦷 [DentFlow KZ](https://github.com/Azamaperdeev05/dentflow-kz)
Стоматологиялық клиникалардың жұмысын цифрландыруға арналған, рөлдік қауіпсіздік жүйесі енгізілген басқару платформасы.

**Стек:** Next.js 14 • TypeScript • Prisma ORM • NextAuth • SQLite / PostgreSQL • Vitest

[📦 Репозиторий](https://github.com/Azamaperdeev05/dentflow-kz)

<details>
<summary><b>🔍 Техникалық мәліметтер мен архитектура</b></summary>

* Рөлдік қолжетімділік (`ADMIN`, `DOCTOR`, `PATIENT`) және TOTP алгоритмімен (QR-код арқылы) екі факторлы аутентификация (2FA).
* Қауіпсіздік журналы (`SecurityAuditLog`) мен күдікті әрекеттерді тіркеу (`LoginRiskSignal`) кестелері арқылы IP және құрылғы белгілерін есепке алу.
* Науқастарды қабылдауға жазу, емдеу жоспары, медициналық файлдарды басқару және хабарлама алмасу жүйесі.
</details>

---

<a id="-notificationshare"></a>
### 📱 [NotificationShare](https://github.com/Azamaperdeev05/NotificationShare)
Android құрылғысындағы жүйелік хабарландыруларды сыртқы арналарға сүзгіден өткізіп қайта бағыттайтын ашық қолданба.

**Стек:** Kotlin 1.9 • Jetpack Compose (Material 3) • Android SDK 24+ • Coroutines • WorkManager

[📦 Репозиторий](https://github.com/Azamaperdeev05/NotificationShare)

<details>
<summary><b>🔍 Техникалық мәліметтер мен архитектура</b></summary>

* Android `NotificationListenerService` негізінде кілт сөздер арқылы сүзгілеу, қара тізім және WorkManager арқылы қайта жіберу кезегін басқару.
* Хабарландыруларды Telegram, Discord, Slack немесе жеке Webhook арқылы таратады.
* Қолданбаға кіру биометриялық сәйкестендірумен (`BiometricPrompt`) қорғалған, баптаулары шифрланған жадта (`EncryptedSharedPreferences`) сақталады.
</details>

---

<a id="-технологиялық-стек"></a>
## 🛠️ Технологиялық стек

<p align="center">
  <img src="https://skillicons.dev/icons?i=go,cs,python,ts,kotlin,postgres,docker&theme=dark" alt="Негізгі стек" />
</p>

<details>
<summary><b>📋 Толық технологиялар тізімін көру</b></summary>

<br/>

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

</details>

---

<a id="-қазақстанға-арналған-цифрлық-өнімдер"></a>
## 🇰🇿 Қазақстанға арналған цифрлық өнімдер

Отандық пайдаланушылар мен қазақ тілді ортаға арнайы жасалған жобалар:

* **[Сөзділ (Sozdil)](https://github.com/Azamaperdeev05/sozdil):** Қазақ тіліндегі Wordle сөз табу ойыны (4, 5, 6 әріптік режимдер, толық сөздіктер қоры, Web және Android қосымшасы) • [Веб-сайт](https://sozdil.vercel.app)
* **[ЗаңКеңес AI (zanaikz)](https://github.com/Azamaperdeev05/zanaikz):** Қазақстан Республикасының заңнамалық базасына негізделген, көпмодельді AI кеңесшісі • [Веб-сайт](https://zanaikz.vercel.app)
* **[Univer Platonus](https://github.com/Azamaperdeev05/univer.univers):** Қазақстан студенттеріне арналған Platonus порталының жылдам әрі ыңғайлы PWA нұсқасы • [Веб-сайт](https://univerkstu.site)
* **[Tezteru.kz](https://github.com/Azamaperdeev05/tezteru.kz):** Қазақ әліпбиіне арналған пернетақтада жылдам жазуды дамытатын тренажер • [Веб-сайт](https://tezteru-kz.vercel.app)

---

<a id="-статистика"></a>
## 📊 GitHub белсенділігі

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=Azamaperdeev05&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=8B5CF6&icon_color=8B5CF6&text_color=c9d1d9" alt="GitHub статистикасы" />
&nbsp;
<img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Azamaperdeev05&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=8B5CF6&text_color=c9d1d9" alt="Қолданылатын тілдер" />

</div>

---

<a id="-байланыс"></a>
## 📫 Байланыс

<p align="center">
  <a href="https://github.com/Azamaperdeev05">
    <img src="https://img.shields.io/badge/GitHub-Azamaperdeev05-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub профилі" />
  </a>
</p>
