<div align="center">

# Азамат Пердеев
### Ақпараттық қауіпсіздік • Web & Full-stack • Жүйелер • AI

<p align="center">
  <img src="https://img.shields.io/badge/Орналасуы-Қазақстан%20🇰🇿-0A66C2?style=flat-square&logo=googlemaps&logoColor=white" alt="Орналасуы" />
  <img src="https://img.shields.io/badge/Бағыты-Ақпараттық%20қауіпсіздік-8B5CF6?style=flat-square&logo=hackthebox&logoColor=white" alt="Бағыты" />
  <img src="https://img.shields.io/badge/Стек-Go%20%7C%20C%23%20%7C%20Python%20%7C%20TS%20%7C%20React-181717?style=flat-square" alt="Стек" />
</p>

<p align="center">
  <b>Қауіпсіздікке, құпиялылыққа және практикалық пайдаға бағытталған бағдарламалық өнімдер жасаймын.</b>
</p>

<!-- Жедел навигация -->
<p align="center">
  <a href="#-мен-туралы">Мен туралы</a> •
  <a href="#-не-жасаймын">Бағыттар</a> •
  <a href="#-жұмыс-тәжірибесі">Тәжірибе</a> •
  <a href="#-инженерлік-карта">Инженерлік карта</a> •
  <a href="#-негізгі-жобалар">Жобалар</a> •
  <a href="#-технологиялық-стек">Стек</a> •
  <a href="#-қазақстанға-арналған-цифрлық-өнімдер">Қазақстан</a> •
  <a href="#-байланыс">Байланыс</a>
</p>

</div>

---

<a id="-мен-туралы"></a>
## 👨💻 Мен туралы

Мен — Әбілқас Сағынов атындағы Қарағанды техникалық университетінің Ақпараттық қауіпсіздік бағыты бойынша түлегімін және бағдарламалық жасақтама әзірлеушісімін.

Web және интерфейс әзірлеумен қатар, Information Security бағыты бойынша жүйелік қауіпсіздік құралдары мен AI-қосымшаларын құрастырамын. Менің мақсатым — заманауи UI/UX дизайнын, таза архитектураны және деректер құпиялылығын біріктіретін сапалы цифрлық өнімдер жасау.

---

<a id="-не-жасаймын"></a>
## 🧩 Не жасаймын?

* 🔐 **Қауіпсіздік (Cybersecurity):** Алдамшы тұзақтар (Honeytokens), фишингтік қауіптерді сараптау және рұқсаттарды шектеу.  
  → *Жобалар:* [Canary Token Generator](#-canary-token-generator), [PhishGuard](#-phishguard)
* ⚙️ **Жүйелер (Systems & Utilities):** Windows (SMB, NTFS ACL, Firewall) және Android жүйелеріне арналған төменгі деңгейлі утилиталар.  
  → *Жобалар:* [LAN Share Manager](#-lan-share-manager), [NotificationShare](#-notificationshare)
* 🤖 **Жасанды интеллект (AI & ML):** Fine-tuned BERT трансформерлері және көпмодельді LLM API интеграциясы.  
  → *Жобалар:* [PhishGuard](#-phishguard), [ЗаңКеңес AI](#-қазақстанға-арналған-цифрлық-өнімдер)
* 🌐 **Web және Құпиялылық (Privacy-First Web):** Деректерді серверге жібермей, 100% браузер ішінде өңдейтін және жергілікті аудиторияға арналған өнімдер.  
  → *Жобалар:* [Bank Statement Analyzer](#-bank-statement-analyzer), [DentFlow KZ](#-dentflow-kz)

---

<a id="-жұмыс-тәжірибесі"></a>
## 💼 Жұмыс тәжірибесі

### 🏢 Samga Education
**Web-әзірлеуші / платформа әзірлеушісі** • *03.2026 — 06.2026*

* Білім беру платформасының web-интерфейсін React, TypeScript және Tailwind CSS арқылы әзірлеу және жетілдіру.
* Кез келген құрылғыға бейімделген (responsive design) пайдаланушы интерфейстерін құру.
* REST API интеграциясы және Supabase / PostgreSQL деректер қорымен жұмыс.
* Пайдаланушыларды тіркеу, авторизация және сессияларды қауіпсіз басқару тетіктері.
* Clean Code қағидаларын сақтау, өнімділікті оңтайландыру және release процесіне қатысу.

> *«Жұмыс барысында frontend және backend интеграцияларымен жұмыс істесем, жеке жобаларымда бұл дағдыларды киберқауіпсіздік, AI және жүйелік бағдарламалау бағыттарында қолданамын.»*

---

<a id="-инженерлік-карта"></a>
## 🗺️ Инженерлік карта

```mermaid
flowchart LR
    Me[Азамат Пердеев]
    Me --> Sec[Ақпараттық қауіпсіздік]
    Me --> Sys[Жүйелік инженерия]
    Me --> Web[Web / Full-stack]
    Me --> AI[Жасанды интеллект]

    Sec --> P1[Canary Token Generator]
    Sec --> P2[PhishGuard]
    Sys --> P3[LAN Share Manager]
    Sys --> P4[NotificationShare]
    Web --> P5[Bank Statement Analyzer]
    Web --> P6[DentFlow KZ]
    AI --> P2
    AI --> P7[ЗаңКеңес AI]

    classDef core fill:#0d1117,stroke:#8B5CF6,stroke-width:2px,color:#ffffff;
    classDef branch fill:#161b22,stroke:#3b82f6,stroke-width:1.5px,color:#ffffff;
    classDef leaf fill:#21262d,stroke:#30363d,stroke-width:1px,color:#c9d1d9;
    class Me core;
    class Sec,Sys,Web,AI branch;
    class P1,P2,P3,P4,P5,P6,P7 leaf;
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
* Алдын ала тексеру (pre-flight validation), интерактивті консоль мәзірі және 1 жолдық PowerShell орнатқышы (`irm azamaperdeev05.github.io/lsm | iex`) қамтылған.
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
* Gmail API (OAuth2) арқылы поштаны қауіпсіз тексеру, қауіпті хаттарға автоматты түрде белгі (label) қою және PDF форматында есептер шығару (ReportLab).
* Деректер базасының көші-қонын басқаратын Alembic, PySide6 жұмыс үстелі және дербес тестілеу модулі қамтылған.
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

<a id="-қазақстанға-арналған-цифрлық-өнімдер"></a>
## 🇰🇿 Қазақстанға арналған цифрлық өнімдер

Отандық пайдаланушылар мен қазақ тілді ортаға арнайы жасалған жобалар:

* **[Сөзділ (Sozdil)](https://github.com/Azamaperdeev05/sozdil):** Қазақ тіліндегі Wordle сөз табу ойыны (4, 5, 6 әріптік режимдер, сөздіктер қоры, Web және Android қосымшасы) • [Веб-сайт](https://sozdil.vercel.app)
* **[ЗаңКеңес AI (zanaikz)](https://github.com/Azamaperdeev05/zanaikz):** ҚР заңнамалық базасына негізделген, көпмодельді AI кеңесшісі • [Веб-сайт](https://zanaikz.vercel.app)
* **[Univer Platonus](https://github.com/Azamaperdeev05/univer.univers):** Қазақстан студенттеріне арналған Platonus порталының жылдам әрі ыңғайлы PWA нұсқасы • [Веб-сайт](https://univerkstu.site)
* **[Tezteru.kz](https://github.com/Azamaperdeev05/tezteru.kz):** Қазақ әліпбиіне арналған пернетақтада жылдам жазуды дамытатын тренажер • [Веб-сайт](https://tezteru-kz.vercel.app)

---

<a id="-технологиялық-стек"></a>
## 🛠️ Технологиялық стек

<p align="center">
  <img src="https://skillicons.dev/icons?i=go,cs,python,ts,react,nextjs,postgres,docker&theme=dark" alt="Негізгі стек" />
</p>

<details>
<summary><b>📋 Толық технологиялық стекті көру</b></summary>

<br/>

### Бағдарламалау тілдері
* Go, C# (.NET 8), Python, TypeScript, JavaScript (ES6+), Kotlin, SQL

### Web / Frontend
* React, Next.js, TypeScript, JavaScript, Tailwind CSS, Svelte, HTML5 / CSS3

### UI / UX
* Figma, UI/UX жобалау, Responsive Design, интерактивті прототиптер құру

### Web / No-code
* Tilda, Zero Block
* *WordPress, Webflow — жаңа жобаларға тез меңгеруге және бейімделуге дайын*

### Киберқауіпсіздік
* **Honeytokens / Deception Technology** (алдамшы ресурстар мен тұзақтар)
* **Phishing Detection** (фишингтік шабуылдарды анықтау және сараптау)
* **BERT** (мәтіндік қауіптерді талдауға арналған нейрожелілер)
* **Browser Fingerprinting** (браузердің сандық ізін анықтау)
* **NTFS ACL & Windows Firewall API** (жүйелік рұқсаттар мен желілік ережелерді автоматтандыру)
* **TOTP 2FA** (екі факторлы аутентификация)
* **Security Audit Logging** (қауіпсіздік оқиғаларын тіркеу және қауіп деңгейін бағалау)
* **Client-side Privacy** (деректерді сыртқы серверге жібермей, клиент жағында өңдеу)

### Backend және Инфрақұрылым
* Go net/http, FastAPI, Next.js API Routes, Node.js
* PostgreSQL, SQLite, Redis, Supabase
* Prisma, Alembic
* Docker, Docker Compose, Nginx, GitHub Actions (CI/CD)

### AI (жасанды интеллект)
* PyTorch, Hugging Face Transformers
* DeepSeek, Gemini, Qwen API

### Техникалық жүйелер
* CCTV, IP-камераларды баптау

</details>

---

<a id="-дизайн-және-интерфейс"></a>
## 🎨 Дизайн және интерфейс

Мен тек функционалды код жазып қана қоймай, пайдаланушыға ыңғайлы, заманауи және визуалды таза өнім жасауға баса назар аударамын:

* **Figma & UI/UX жобалау:** Ақпараттық құрылымды құру, wireframe және интерактивті прототиптеу.
* **Responsive Design:** Смартфон, планшет және үлкен экрандарға 100% бейімделген дизайн жүйелері.
* **Tilda & Zero Block:** Тез арада сапалы лендингтер құрастыру және стильдеу.
* **Микро-анимациялар мен өнімділік:** Қолданушы тәжірибесін (UX) жақсартатын жеңіл визуалды кері байланыс.

<details>
<summary><b>🔄 Жобамен қалай жұмыс істеймін? (8 кезең)</b></summary>

1. **Тапсырманы талдау:** Негізгі талаптар мен мақсатты аудиторияны айқындау.
2. **Прототиптеу:** Негізгі экрандардың сұлбасы мен логикалық құрылымын сызу.
3. **UI/UX жобалау:** Figma ортасында стильдер мен компоненттер жүйесін жасау.
4. **Frontend әзірлеу:** React / Next.js / Tailwind CSS арқылы таза код жазу.
5. **Бейімдеу:** Барлық браузерлер мен мобильді құрылғыларда мінсіз көрсетілуін қамтамасыз ету.
6. **Интеграциялар:** REST API, деректер базасы және қауіпсіз авторизацияны жалғау.
7. **Тестілеу:** Жүйенің өнімділігі мен қауіпсіздігін тексеру.
8. **Жариялау:** Өнімді серверге орналастыру (deployment) және қолдау.
</details>

---

<a id="-білім"></a>
## 🎓 Білім

### 🏛️ Әбілқас Сағынов атындағы Қарағанды техникалық университеті
**B058 — Ақпараттық қауіпсіздік**  
*Жоғары білім, бакалавриат • 2026 жылғы түлек*

<details>
<summary><b>📚 Қосымша курстар мен сертификаттар</b></summary>

* **Prompt Engineering for ChatGPT** — Coursera & Vanderbilt University *(2025)*
* **Generative AI for Everyone** — Coursera & DeepLearning.AI *(2025)*
</details>

---

## 🌐 Тілдер

* **Қазақ тілі** — жетік (ана тілі)
* **Орыс тілі** — орташа / жұмыс деңгейі
* **Ағылшын тілі** — A2 / техникалық құжаттама

---

<a id="-байланыс"></a>
## 📫 Байланыс

<p align="center">
  <a href="mailto:azamaperdeev05@gmail.com">
    <img src="https://img.shields.io/badge/Email-azamaperdeev05%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
  </a>
  &nbsp;
  <a href="https://t.me/code_improper">
    <img src="https://img.shields.io/badge/Telegram-%40code__improper-2CA5E0?style=flat-square&logo=telegram&logoColor=white" alt="Telegram" />
  </a>
  &nbsp;
  <a href="https://github.com/Azamaperdeev05">
    <img src="https://img.shields.io/badge/GitHub-Azamaperdeev05-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" />
  </a>
</p>
