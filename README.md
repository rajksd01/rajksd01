<p align="center">
  <img src="./assets/hero.svg" alt="Raj Kasaudhan, software engineer and builder shipping mobile apps, web platforms, Rust services and on-device AI, based in Bangalore India" width="100%" />
</p>

<h1 align="center">I take products from idea to production. Fast.</h1>

<p align="center">
  <strong>Raj Kasaudhan</strong> · Software engineer and builder · Bangalore, India
</p>

<p align="center">
  I build mobile apps, web apps, Rust services, multi-tenant backends, and on-device AI.
  The whole product, not one slice of it.
</p>

<p align="center">
  <strong>Engineer is the training. Builder is the habit.</strong><br />
  <strong>Obsessed with shipping.</strong> Ideas are cheap. A link you can open is not.
</p>

<p align="center">
  Nine products built. Several are live and linked below.
</p>

<p align="center">
  <a href="https://www.rajkasaudhan.com.np"><strong>Portfolio</strong></a>
  &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/raj-kasaudhan"><strong>LinkedIn</strong></a>
  &nbsp;·&nbsp;
  <a href="https://mail.google.com/mail/?view=cm&amp;fs=1&amp;to=iamrajkasaudhan@gmail.com"><strong>Email me</strong></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/rajksd01?tab=repositories"><strong>All repositories</strong></a>
</p>

<p align="center">
  <img src="./assets/proof-band.svg" alt="Nine products shipped, 137 thousand lines in production, 881 tests, eight products shipped in the last 30 days" width="100%" />
</p>

## Proof of work

### Biofe · a private journal that turns thoughts into action

<table>
  <tr>
    <td width="50%"><a href="https://biofe-v2.vercel.app"><img src="./assets/biofe-home.png" alt="Biofe mobile journal dashboard" width="100%" /></a></td>
    <td width="50%"><a href="https://biofe-v2.vercel.app"><img src="./assets/biofe-web.png" alt="Biofe live web journal" width="100%" /></a></td>
  </tr>
</table>

Writing and voice notes become mood patterns, goals, reminders, and reflection worth reading back.

**The hard part:** transcription and meaning extraction run on the user's device, so a private journal never leaves it. Mobile app, responsive web, and deployed API are all mine.

`Flutter` `Riverpod` `Next.js` `Firebase` `Cloudflare` `MongoDB` `Whisper` `Qwen` · 46K lines · **[Open live product ↗](https://biofe-v2.vercel.app)**

<br />

### Unsaid · anonymous feedback with one final verdict

<table>
  <tr>
    <td width="50%"><a href="https://unsaid-sable.vercel.app"><img src="./assets/unsaid-verdict.png" alt="Unsaid live game with a sample final verdict" width="100%" /></a></td>
    <td width="50%"><a href="https://unsaid-sable.vercel.app"><img src="./assets/unsaid-flow.png" alt="Unsaid anonymous game flow" width="100%" /></a></td>
  </tr>
</table>

Friends answer from one link with no accounts. Enough answers unlock a shareable AI verdict.

**The hard part:** anonymity and one-vote-per-person are opposite requirements. The Rust service solves it with private device identity, atomic duplicate protection, and guarded game states, covered by 101 concurrency tests.

`Rust` `Axum` `React 19` `TypeScript` `PostgreSQL` `Redis` `Gemini` · **101 tests** · **[Play Unsaid ↗](https://unsaid-sable.vercel.app)**

<br />

### SehatKit · private family health records that stay useful

<table>
  <tr>
    <td width="50%"><img src="./assets/sehatkit-dashboard.png" alt="SehatKit family dashboard with fictional sample records" width="100%" /></td>
    <td width="50%"><img src="./assets/sehatkit-trends.png" alt="SehatKit health trend using fictional sample records" width="100%" /></td>
  </tr>
</table>

Prescriptions, reports, medicines, reminders, meals, family timelines, and lab trends in one app.

**The hard part:** health data cannot be shipped to a cloud model for parsing. OCR, clinical entity extraction, and identity redaction all run on the phone. Every record pictured is fictional demo data.

`React Native` `Expo` `TypeScript` `ONNX Runtime` `ML Kit` `Firebase` `on-device NLP`

<br />

### Sathi / Dukaan · an AI salesperson for Nepali shops

<table>
  <tr>
    <td width="50%"><img src="./assets/dukaan-storefront-v2.png" alt="Sathi product-rich mobile storefront" width="100%" /></td>
    <td width="50%"><img src="./assets/dukaan-orders.png" alt="Sathi seller order operations" width="100%" /></td>
  </tr>
</table>

Sathi builds the storefront, sells in Nepali conversation, recommends products, fills the basket, takes cash-on-delivery orders, and hands the shopkeeper an operations view.

**The hard part:** the shopkeeper never writes a product description or a reply. The model does the selling and the merchant only sees orders.

`Gemini` `Node.js` `Express` `SQLite` `multilingual commerce` `embeddable widget`

<br />

### Byapar · wholesale ordering built for the local workflow

<table>
  <tr>
    <td width="50%"><img src="./assets/byapar-catalog.png" alt="Byapar wholesale catalog with fictional products" width="100%" /></td>
    <td width="50%"><img src="./assets/byapar-checkout.png" alt="Byapar live cart and checkout flow with fictional buyer details" width="100%" /></td>
  </tr>
</table>

Sellers publish price lists. Retailers browse, build wholesale quantities, order, negotiate in chat, and get status updates.

**The hard part:** retailers will not install an app to place one order, so the whole buying flow works from a link while the seller keeps a native app.

`React Native` `Expo` `Node.js` `MongoDB` `FCM` `Cloudflare`

## More systems I have shipped

- **Restro** — restaurant operating system: QR ordering, kitchen, billing, staff, inventory, purchasing, recipes, shifts, customer credit. 39K lines, 780 test cases.
- **Setu / Admitly** — multi-tenant education CRM with leads, follow-ups, RBAC, and hard tenant isolation on Rust, Axum, and Postgres.
- **Samajh** — one-tap Hindi screen translation on Android using accessibility nodes, on-device translation, and overlays.
- **[wirestat](https://github.com/rajksd01/wirestat)** — readable HTTP timing on every interactive `curl` call without contaminating command output.

<details>
  <summary><strong>Earlier products, experiments, and backend builds</strong></summary>
  <br />

- **Expense Tracker** — [API](https://github.com/rajksd01/expenseTracker) · [Web client](https://github.com/rajksd01/ExpenseTrackerWeb)
- **URL Shortener** — [Backend](https://github.com/rajksd01/urlShortner) · [Frontend](https://github.com/rajksd01/urlShortnerFrontend)
- **Netflix UI Clone** — [Demo](https://netflix-ui-clone-lemon.vercel.app) · [Code](https://github.com/rajksd01/Netflix-UI-Clone)
- **Blogging App** — [Live demo](https://blogging-app-self.vercel.app) · [Code](https://github.com/rajksd01/bloggingApp)
- **Flight booking system** — [Core API](https://github.com/rajksd01/flightBookingBackend) · [Gateway](https://github.com/rajksd01/FlightAPI_Gateway) · [Booking](https://github.com/rajksd01/bookingService) · [Notifications](https://github.com/rajksd01/NotificationService)
- **DALL·E Clone** — [Code](https://github.com/rajksd01/dalle-clone) · **Hotel Booking** — [Code](https://github.com/rajksd01/HotelBooking)
- **API Collection** — [Live demo](https://api-collection.netlify.app/) · [Code](https://github.com/rajksd01/api-collection)
- **Community builds** — [GDSC FETJU](https://github.com/rajksd01/gdsc-website) · [EERC](https://github.com/rajksd01/EERC-Final) · [Dashboard backend](https://github.com/rajksd01/DashBoardBackend) / [frontend](https://github.com/rajksd01/DashBoardFrontend)

</details>

## How I work

<p align="center">
  <img src="./assets/loop.svg" alt="The loop I run: idea, build, ship, listen, and again" width="100%" />
</p>

**Ship first, then harden.** Something real goes live in week one. Opinions about it are worth more than opinions about a document.

**Tests where state and money live.** Not coverage theatre. Unsaid has 101 tests because two people can answer the same question at the same millisecond. Restro has 780 because a bill must never be wrong.

**Privacy as an engineering constraint.** Health records, journals, and identity documents get parsed on the user's device. It costs more effort and it removes an entire class of risk from your company.

**I pick the boring option on purpose.** Clever architecture is what somebody decodes at 3am during an outage. I reach for the smallest thing that holds, and spend the saved time on the part users actually touch.

## Work with me

| You need | What you get |
| --- | --- |
| **Zero to one** | A real product in users' hands in weeks, not a slide about one. |
| **An AI feature that actually works** | On-device or hosted, wired into your product, evaluated, not demoed once. |
| **A stalled build rescued** | I read the codebase, find what is actually blocking, and ship the next release. |

<details>
<summary><b>&rsaquo;&nbsp;&nbsp;what week one actually looks like</b></summary>

<br />

| Day | What happens |
| --- | --- |
| **1** | I read your product and your code. No meetings. |
| **2** | We agree on the one thing that should exist by Friday. |
| **3 – 4** | I build it. You get a link every evening, not a status update. |
| **5** | It is live. We pick week two. |

</details>

Based in Bangalore, working with teams anywhere. Open to ambitious products, strong teams, and founder conversations.

<p align="center">
  <a href="https://mail.google.com/mail/?view=cm&amp;fs=1&amp;to=iamrajkasaudhan@gmail.com"><strong>Start a conversation ↗</strong></a>
</p>

## What I build with

**Languages** · TypeScript, JavaScript, Rust, Python, Dart, Java, C, C++, SQL, PHP, HTML, CSS<br />
**Products** · React, Next.js, React Native, Expo, Flutter, Angular, Tailwind CSS, Bootstrap, WordPress<br />
**Backend & data** · Node.js, Express, Axum, PostgreSQL, MongoDB, MySQL, Redis, Prisma, RabbitMQ<br />
**AI** · Gemini, Qwen, Whisper, ONNX Runtime, ML Kit, OCR, RAG, NLP, computer vision<br />
**Infrastructure** · Docker, AWS, Cloudflare, Firebase, GitHub Actions, Linux, Vercel, CI/CD<br />
**Also used** · Postman, NumPy, Pandas, Power BI, Arduino, MATLAB, Git

## GitHub activity

<p align="center">
  <a href="https://github.com/rajksd01?tab=overview"><img src="./assets/contribution-graph.svg" alt="Raj Kasaudhan GitHub contribution graph including anonymous private work" width="100%" /></a>
</p>

<p align="center">
  <a href="https://mail.google.com/mail/?view=cm&amp;fs=1&amp;to=iamrajkasaudhan@gmail.com"><strong>iamrajkasaudhan@gmail.com</strong></a>
  &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/raj-kasaudhan">LinkedIn</a>
  &nbsp;·&nbsp;
  <a href="https://www.rajkasaudhan.com.np">Portfolio</a>
</p>

<details>
<summary><b>&rsaquo;&nbsp;&nbsp;you scrolled all the way down</b></summary>

<br />

So did I, on every product up there, at 2am, wondering why the build went red.

If you are building something and need a second pair of hands that actually ships, the email is a few lines up.

</details>
