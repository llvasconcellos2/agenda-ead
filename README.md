<!-- BACK TO TOP ANCHOR -->
<a id="readme-top"></a>

<!-- LOGO -->
<div align="center">
  <a href="https://leonardo-vasconcellos.vercel.app/portfolio/agenda-ead">
    <h1 align="center">📅</h1>
  </a>

  <h1 align="center">E-Learning Scheduler</h1>

  <p align="center">A PHP/MySQL web application for managing academic schedules, appointments, and activities in a distance-learning (EAD) environment.</p>

  <p align="center">// academic calendar · distance learning platform</p>

  <br />

  <a href="https://leonardo-vasconcellos.vercel.app/portfolio/agenda-ead"><strong>View it live »</strong></a>
</div>

<br />

<!-- SHIELDS -->
<div align="center">

[![Creator Website][website-shield]][website-url]
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
[![Released][year-shield]][year-url]

</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#screenshots">Screenshots</a></li>
    <li><a href="#built-with">Built With</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributors">Contributors</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Screenshot][product-screenshot]](https://leonardo-vasconcellos.vercel.app/portfolio/agenda-ead)

<!-- PROJECT INTRO: 260 chars max -->
A PHP/MySQL web application for managing academic schedules, appointments, and activities in a distance-learning (EAD) environment.
<!-- END INTRO -->

E-Learning Scheduler is a browser-based academic management platform built for distance-learning (EAD) institutions. It gives professors and students a shared scheduling environment where three types of academic activities — appointments (*compromissos*), tasks (*tarefas*), and events (*eventos*) — are tracked on a navigable calendar.

The calendar supports daily, weekly, and monthly views. Days with scheduled items are highlighted; clicking any marked date reveals the activities due that day or week. A background motor script handles automated email reminders, dispatching notifications to users ahead of their scheduled appointments.

Access is governed by a three-tier role system: administrators configure the platform and manage all users; professors create and assign activities scoped to specific courses and classes; and students see only the activities relevant to their enrollment and group membership. Personal contact lists and a built-in Q&A help panel round out the feature set.

The MySQL schema covers seven entities — appointments, tasks, events, users, courses, classes, and contact groups — all linked by course and class identifiers so that activities reach precisely the right audience.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SCREENSHOTS -->
## Screenshots

<div align="center" style="display:flex;flex-wrap:wrap;gap:8px;justify-content:center;">
  <a href="screenshots/admin-change-password.png"><img src="screenshots/admin-change-password.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshots/admin-setup.png"><img src="screenshots/admin-setup.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshots/appointment.png"><img src="screenshots/appointment.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshots/help.png"><img src="screenshots/help.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshots/new-student.png"><img src="screenshots/new-student.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshots/calendar.png"><img src="screenshots/calendar.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
</div>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- BUILT WITH -->
## Built With

**Languages**

| | Language | Version |
|---|---|---|
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" width="20" /> | PHP | 5.x |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="20" /> | JavaScript | ES3 |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="20" /> | HTML | 5 |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="20" /> | CSS | 3 |

**Frameworks & Libraries**

| | Framework | Version |
|---|---|---|
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" width="20" /> | MySQL | 5.x |

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->
## Roadmap

This project repository is for archive purposes only. No new features or issues are being tracked.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTORS -->
## Contributors

<a href="https://github.com/llvasconcellos2/agenda-ead/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=llvasconcellos2/agenda-ead" alt="Contributors" />
</a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

[Leonardo Vasconcellos](https://leonardo-vasconcellos.vercel.app/) — leonardolimadevasconcellos@gmail.com

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
[website-shield]: https://img.shields.io/badge/Creator_Website-%E2%86%97-2eba7a?style=for-the-badge
[website-url]: https://leonardo-vasconcellos.vercel.app/
[contributors-shield]: https://img.shields.io/github/contributors/llvasconcellos2/agenda-ead.svg?style=for-the-badge
[contributors-url]: https://github.com/llvasconcellos2/agenda-ead/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/llvasconcellos2/agenda-ead.svg?style=for-the-badge
[forks-url]: https://github.com/llvasconcellos2/agenda-ead/network/members
[issues-shield]: https://img.shields.io/github/issues/llvasconcellos2/agenda-ead.svg?style=for-the-badge
[issues-url]: https://github.com/llvasconcellos2/agenda-ead/issues
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white
[linkedin-url]: https://www.linkedin.com/in/llvasconcellos
[year-shield]: https://img.shields.io/badge/Released-2003-gray?style=for-the-badge
[year-url]: #
[product-screenshot]: screenshots/calendar.png
