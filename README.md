<div align="center">

<!-- HEADER BANNER -->
[![Header](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=200&section=header&text=Sneha%20E&fontSize=50&fontColor=fff&animation=twinkling&fontAlignY=35&desc=Flutter%20Developer%20%7C%20Clean%20Architecture%20%7C%20Scalable%20Apps&descAlignY=55&descAlign=50)](https://github.com/Snehae15)

<!-- SOCIAL BADGES -->
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/snehae15)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:snehae15@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Snehae15)
[![Profile Views](https://komarev.com/ghpvc/?username=Snehae15&style=for-the-badge&color=38bdf8&label=PROFILE+VIEWS)](https://github.com/Snehae15)

</div>

---

## 👩‍💻 About Me

```dart
class SnehaE extends FlutterDeveloper {

  final String name      = "Sneha E";
  final String role      = "Flutter Developer";
  final String company   = "Nexteons LLP, Malappuram";
  final int    exp       = 2; // years of professional experience
  final String focus     = "Clean Architecture · Scalability · Quality";

  final List<String> domains = [
    "🏢 Enterprise SaaS & Multi-Tenant B2B Platforms",
    "🚗 Fleet & Ride Management Systems",
    "🏗️ Construction Project Management",
    "🛒 E-Commerce & Delivery Applications",
    "📊 Cross-Platform Admin Dashboards",
  ];

  final Map<String, dynamic> currentWork = {
    "project"    : "Full-Featured E-Commerce Application",
    "state_mgmt" : "GetX",
    "pattern"    : "Clean Architecture (Domain / Data / Presentation)",
    "backend"    : "Node.js + Firebase",
  };

  final List<String> strengths = [
    "BLoC / Cubit  —  predictable, testable state flows",
    "GetX          —  state, routing & DI full ecosystem",
    "Melos Monorepo —  shared packages across multi-app workspaces",
    "GraphQL & REST —  Dio interceptors, token refresh, offline sync",
    "Firebase       —  Auth, FCM, Firestore, Crashlytics, Analytics",
  ];

  String get motto => "Code with purpose. Design with empathy. 🚀";
}
```

---

## 🏆 What Makes Me Stand Out

| | Skill | Why It Matters |
|---|---|---|
| 🏗️ | **Clean Architecture** | Maintainable, testable codebases that scale as teams grow |
| 📦 | **Melos Monorepo** | Shared packages with zero duplication across multi-app workspaces |
| 🔄 | **BLoC + GetX + Provider** | Right tool for every state management scenario |
| 🔌 | **GraphQL & REST** | Production-grade API integration with token refresh & error handling |
| 🧪 | **Manual QA Ownership** | I own quality — functional, UI/UX, API, and performance testing |
| 📱 | **Cross-Platform** | Android · iOS · Web from a single, clean Dart codebase |
| 🎨 | **Custom UI** | CustomPainter, Lottie animations, dynamic theming, SVG |
| 📄 | **Report Generation** | Automated PDF exports with Syncfusion (used in production) |

---

## 🚀 Featured Projects

---

### 🚗 Autrix — Fleet Management SaaS *(Multi-Tenant · Production)*

> Real-time, multi-tenant SaaS fleet management platform serving enterprise clients across **Android, iOS, and Web**.

**What I Built**

- 🚘 Real-time vehicle tracking with Check-in / Check-out lifecycle management
- 🔧 Complete Tyre Management — rotation schedules, resoling, maintenance lifecycle
- ⛽ Fuel expense monitoring & trip allowance tracking
- 📊 Interactive dashboards — FL Chart + Syncfusion DataGrid with live data
- 📄 Automated PDF report generation (syncfusion_flutter_pdf + printing package)
- 🔔 Firebase FCM push alerts for insurance & document expiry deadlines
- 🎨 Lottie animations, custom SVG assets, GoRouter deep-linking

**Tech Stack**

`Dart` `Flutter` `GetX` `GraphQL` `REST (Dio)` `Firebase` `GoRouter` `Syncfusion` `FL Chart`

---

### 🏗️ Eons Build — Construction Management *(Monorepo · B2B · Multi-Role)*

> B2B construction platform connecting firms and clients with real-time project tracking, financial transparency, and on-site issue resolution.

**What I Built**

- 🗂️ Melos monorepo — `next_ui_component` & `build_model_api` shared packages
- 🐛 Snag Management — photo + audio issue tracking with full resolution lifecycle
- 🎙️ Voice recording & audio waveform visualizations (flutter_sound)
- 💰 Financial module — payment schedules, digital receipts, payment tracking
- 📡 Firebase FCM — automated push notifications for project milestones
- 📴 Offline-first with Hive local caching for low-connectivity construction sites
- 🎨 CustomPainter widgets, dynamic theme switching, Lottie, GoRouter deep-linking

**Tech Stack**

`Dart` `Flutter` `BLoC/Cubit` `Melos` `Node.js` `Firebase` `Hive` `GoRouter` `GetIt` `Audio Processing`

---

### 🛒 E-Commerce Application *(Active · Clean Architecture)*

> Full-featured cross-platform commerce app — product discovery, cart, real-time order tracking, payment integration, and admin panel.

**Key Features**

- 🛍️ Product catalog with search, filter & category navigation
- 🛒 Cart management, multi-step checkout & payment gateway integration
- 📦 Real-time order tracking & delivery status updates
- 🔔 Firebase FCM push notifications
- 📊 Admin panel — product, order & user management

**Tech Stack**

`Dart` `Flutter` `GetX` `Node.js` `Firebase` `Clean Architecture` `REST (Dio)`

---

### 🛵 Delivery & Logistics App *(Multi-Role)*

> Three-sided platform — **customer · rider · admin** — with real-time delivery tracking, route optimization, and earnings analytics.

**Tech Stack**

`Dart` `Flutter` `Node.js` `Firebase` `Google Maps API` `REST (Dio)`

---

### 📊 Admin Dashboard *(Cross-Platform · Web + Mobile)*

> Responsive, unified admin dashboard for user, order, report, and analytics management — zero code duplication across web and mobile.

**Tech Stack**

`Dart` `Flutter Web` `Node.js` `REST (Dio)` `Syncfusion`

---

## 🗂️ Monorepo Architecture (Eons Build)

```
📦 eons-access-monorepo/             # Melos workspace
├── 📱 apps/
│   ├── client_app/                  # Client-facing Flutter mobile app
│   └── contractor_app/              # Contractor / firm Flutter app
│
├── 📦 packages/
│   ├── next_ui_component/           # Shared design system & custom widgets
│   └── build_model_api/             # Shared API models & data entities
│
└── melos.yaml                       # Workspace config & script automation
```

> **Why Monorepo?**  
> Shared `next_ui_component` and `build_model_api` packages guarantee a single source of truth for UI and data contracts — consistent updates, zero duplication, faster iteration.

---

## 🧪 Quality Engineering — Manual Testing

I integrate testing throughout the development lifecycle, not as an afterthought. Every project I ship includes structured testing across four dimensions:

### 🔬 Functional Coverage

```
✅ Auth Flows      — Login · Register · Forgot Password · Token Expiry
✅ Business Flows  — Cart · Checkout · Payment · Order Tracking · Fleet Ops
✅ Role-Based      — Admin vs Client vs Contractor permission boundaries
✅ Edge Cases      — Empty states · Network loss · Invalid inputs · Offline mode
```

### 🎨 UI/UX Checklist

| Area | What I Verify |
|---|---|
| **Responsiveness** | Layout integrity across small, medium, large screen sizes |
| **Cross-Platform** | Visual parity between Android & iOS builds |
| **Navigation** | Back stack, deep links, GoRouter route transitions |
| **Loading States** | Lottie, shimmer, skeleton screens, error widgets |
| **Dark / Light Mode** | Theme consistency, no hardcoded colors |
| **Accessibility** | Font scaling, contrast ratios, tap target sizes |

### 🔌 API Testing (Postman)

```
✅ Request payloads match Node.js / GraphQL backend contract
✅ Response structures & status codes (200 · 400 · 401 · 404 · 500)
✅ Token flows — access token expiry & refresh token handling
✅ Paginated endpoints & list loading behaviour
✅ Network failure simulation — timeout, no internet, slow connection
✅ Error messages propagate correctly to the UI layer
```

### ⚡ Performance Profiling

```
📊 Flutter DevTools  — Frame rendering (target: 60fps / 16ms per frame)
🧠 Memory Profiler   — Leak detection in long lists, images & audio streams
🚀 Cold Start Time   — Launch performance on low-end & mid-range devices
📴 Offline Integrity — Hive cache on reconnect (Eons Build)
📄 PDF Export Speed  — Syncfusion report generation under load (Autrix)
```

---

## 🛠️ Tech Stack

### 📱 Mobile & Core
![Flutter](https://img.shields.io/badge/Flutter-%230256b9.svg?style=for-the-badge&logo=Flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-%230175C2.svg?style=for-the-badge&logo=dart&logoColor=white)

### ⚙️ State Management & Architecture
![BLoC](https://img.shields.io/badge/BLoC-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![GetX](https://img.shields.io/badge/GetX-8B5CF6?style=for-the-badge&logo=dart&logoColor=white)
![Provider](https://img.shields.io/badge/Provider-0EA5E9?style=for-the-badge&logo=dart&logoColor=white)
![Melos](https://img.shields.io/badge/Melos_Monorepo-0EA5E9?style=for-the-badge&logo=git&logoColor=white)

### 🔥 Backend & Cloud
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-%23039BE5.svg?style=for-the-badge&logo=firebase)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)

### 🌐 APIs & Networking
![GraphQL](https://img.shields.io/badge/-GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)
![REST](https://img.shields.io/badge/REST_API-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

### 🎨 UI, Reporting & Tooling
![Syncfusion](https://img.shields.io/badge/Syncfusion-0D6EFD?style=for-the-badge&logo=flutter&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)
![Git](https://img.shields.io/badge/Git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">

[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Snehae15&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&show_icons=true&rank_icon=github)](https://github.com/Snehae15)
[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Snehae15&theme=tokyonight&hide_border=true&layout=compact&count_private=true)](https://github.com/Snehae15)

[![GitHub Streak](https://nirzak-streak-stats.vercel.app/?user=Snehae15&theme=tokyonight&hide_border=true)](https://github.com/Snehae15)

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=Snehae15&theme=tokyo-night&hide_border=true&area=true)](https://github.com/Snehae15)

[![GitHub Trophies](https://github-profile-trophy.vercel.app/?username=Snehae15&theme=tokyonight&no-frame=true&margin-w=6&column=7)](https://github.com/Snehae15)

</div>

---

## 🐍 Contribution Activity

![github-snake](https://raw.githubusercontent.com/Snehae15/Snehae15/output/github-snake.svg)

---

## 💼 Open to Opportunities

I'm a Flutter Developer with **3+ years of production experience** building enterprise SaaS, B2B platforms, and consumer apps. I bring clean architecture thinking, strong QA discipline, and end-to-end ownership from design handoff to deployment.

If your team is building ambitious mobile products, I'd love to connect.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Connect%20on%20LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/snehae15)
[![Email](https://img.shields.io/badge/Send%20an%20Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:snehae15@gmail.com)

*"Architecture is not just about structure — it's about making the next change easier."*

[![Footer](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=120&section=footer)](https://github.com/Snehae15)

</div>
