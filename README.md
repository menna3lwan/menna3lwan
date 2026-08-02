<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=110&section=header" alt="" />

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=600&size=26&pause=1200&color=70A5FD&center=true&vCenter=true&width=800&height=60&lines=Software+Developer+%C2%B7+Flutter+Engineer;Clean+Architecture+%26+SOLID+Advocate;Building+Scalable%2C+Testable+Mobile+Systems" alt="Typing SVG" />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/menna-elwan/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/menna3lwan)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:menna3lwan@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-70A5FD?style=for-the-badge&logo=googlechrome&logoColor=white)](https://menna3lwan.github.io/Menna_Elwan.github.io/)

<br>

### ᴀʙᴏᴜᴛ

I'm a **Software Developer** whose primary focus is **Flutter** — building scalable, maintainable mobile applications guided by **Clean Architecture**, **SOLID**, and disciplined testing rather than just shipping features. I'm also a Computer Science & AI student at Benha University,  **Nationwide** in DEPI's Mobile Development track. That foundation shows up in how I work: clear separation of concerns, predictable state management, and production-grade engineering, applied across a two-sided telemedicine platform, a Bloc/Cubit exam client, and open-source contributions to packages other developers depend on.

<br>

**Education:** B.Sc. Computer Science & Artificial Intelligence, Benha University (2022 – 2026)

<br>

### ᴛᴇᴄʜɴɪᴄᴀʟ ꜱᴋɪʟʟꜱ

<table>
<tr>
<td valign="top" width="50%">

**Software Engineering**
Clean Architecture · SOLID Principles · System Design · MVVM/MVI · Repository Pattern · Dependency Injection (GetIt, Injectable) · Performance Optimization

**Flutter & Mobile**
Flutter · Android SDK · iOS · Cross-Platform Apps · Dart, Kotlin, Java, Python, C/C++

**State Management**
Bloc / Cubit · Provider · Riverpod

</td>
<td valign="top" width="50%">

**Backend & Data**
REST APIs (Dio, HTTP) · Firebase (Auth, Firestore, FCM) · Supabase

**AI & Modern Development**
AI-Assisted Development · LLM Integration · Prompt Engineering · AI Tools (ChatGPT, Claude, Cursor)

**Quality & Workflow**
Unit/Widget Testing · ISTQB Methodologies · Git & GitHub · Agile/SDLC

</td>
</tr>
</table>

<div align="center">

<img src="https://skillicons.dev/icons?i=flutter,dart,kotlin,java,firebase,supabase,androidstudio,git,github,postman,figma,vscode&theme=dark&v=2" alt="Tech stack icons" />

</div>

<br>

### ꜰᴇᴀᴛᴜʀᴇᴅ ᴘʀᴏᴊᴇᴄᴛꜱ

<table>
<tr>
<td width="50%" valign="top">

**Hen Lehen (هُنَّ لَهُنَّ)**
[Patient App](https://github.com/menna3lwan/patient_app) · [Doctor App](https://github.com/menna3lwan/doctor_app)

*Challenge:* two-sided telemedicine platform for women-only healthcare, keeping patient and doctor clients consistent in real time.
*Architecture:* Clean Architecture with a shared domain layer, Provider, Supabase sync + Firebase for auth/messaging.
*Impact:* two production Flutter apps sharing one consistent set of business rules.

`Flutter` `Firebase` `Supabase` `Provider` `Clean Architecture`

</td>
<td width="50%" valign="top">

**[Exam App — Elevate Online Exams](https://github.com/menna3lwan/exam_app)**

*Challenge:* a timed-exam client where state consistency and error handling directly affect exam validity.
*Architecture:* feature-first Clean Architecture, Bloc/Cubit for the exam-session state machine, Dio-based REST layer with typed error handling.
*Impact:* production-ready client used for real online exams end-to-end.

`Flutter` `Bloc/Cubit` `Clean Architecture` `REST API`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[Movies App](https://github.com/menna3lwan/movie_app)**

*Challenge:* keep a growing 4-person codebase maintainable as features shipped in parallel.
*Architecture:* Clean Architecture, Repository pattern, Injectable-based DI decoupling data sources from presentation.
*Impact:* new features added without touching existing layers; low collaborative churn.

`Flutter` `Provider` `Injectable` `Clean Architecture`

</td>
<td width="50%" valign="top">

**[Tasky App](https://github.com/menna3lwan/tasky_app)**

*Challenge:* encourage consistent habit-building through daily task completion.
*Architecture:* Clean Architecture, Firebase Auth/Firestore for persistence, Cloud Messaging for streak reminders.
*Impact:* persistent, real-time task state across sessions and devices.

`Flutter` `Firebase` `Clean Architecture`

</td>
</tr>
<tr>
<td width="50%" colspan="2" valign="top">

**[Fashion Store — DEPI Final Project](https://github.com/menna3lwan/Fashion-Store)**

*Challenge:* ship a complete e-commerce flow (auth, catalog, cart) as a team capstone under a fixed program deadline.
*Architecture:* Flutter + Firebase for auth and data, coordinated through shared Git workflows.
*Impact:* delivered as final DEPI Flutter-track capstone project.

`Flutter` `Firebase`

</td>
</tr>
</table>

<div align="center">

**[Personal Portfolio](https://menna3lwan.github.io/Menna_Elwan.github.io/)** · [source](https://github.com/menna3lwan/Menna_Elwan.github.io)

</div>

<br>

### ᴏᴘᴇɴ ꜱᴏᴜʀᴄᴇ & ᴀᴄʜɪᴇᴠᴇᴍᴇɴᴛꜱ

**Pull Request — [`bosskmk/pluto_grid`](https://github.com/bosskmk/pluto_grid) (745★ Flutter data-grid package)**
Root-caused a state-notification bug: `setConfiguration()` and `setTextDirection()` updated the grid's internal state but never called `notifyListeners()`, so RTL/LTR and config changes silently failed to rebuild dependent cells. [Fixed it](https://github.com/bosskmk/pluto_grid/pull/1165) with a lifecycle-aware notification strategy — immediate for build-safe calls, deferred via `notifyListenersOnPostFrame()` where notifying mid-build would violate Flutter's build-phase rules — matching the package's existing patterns with zero API changes.

- **Pull Shark** achievement for merged pull requests on other repositories
- **7th Place Nationwide** — Mobile Development Track, Digital Egypt Pioneers Initiative (2024)
- **ECPC Participant** — Egyptian Collegiate Programming Contest, 2023

<br>

### ɢɪᴛʜᴜʙ ᴀᴄᴛɪᴠɪᴛʏ

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-stats-extended.vercel.app/api?username=menna3lwan&show_icons=true&theme=tokyonight&hide_border=true" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-stats-extended.vercel.app/api?username=menna3lwan&show_icons=true&theme=default&hide_border=true" />
  <img src="https://github-stats-extended.vercel.app/api?username=menna3lwan&show_icons=true&theme=tokyonight&hide_border=true" height="165" alt="GitHub stats" />
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com/?user=menna3lwan&theme=tokyonight&hide_border=true" />
  <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com/?user=menna3lwan&theme=default&hide_border=true" />
  <img src="https://streak-stats.demolab.com/?user=menna3lwan&theme=tokyonight&hide_border=true" height="165" alt="GitHub streak stats" />
</picture>

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-stats-extended.vercel.app/api/top-langs?username=menna3lwan&layout=compact&theme=tokyonight&hide_border=true" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-stats-extended.vercel.app/api/top-langs?username=menna3lwan&layout=compact&theme=default&hide_border=true" />
  <img src="https://github-stats-extended.vercel.app/api/top-langs?username=menna3lwan&layout=compact&theme=tokyonight&hide_border=true" height="165" alt="Top languages" />
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=menna3lwan&theme=tokyo-night&hide_border=true&height=165" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=menna3lwan&theme=minimal&hide_border=true&height=165" />
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=menna3lwan&theme=tokyo-night&hide_border=true&height=165" alt="Contribution activity graph" />
</picture>

</div>

<br>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:2C5364,50:203A43,100:0F2027&height=100&section=footer" alt="" />

</div>
