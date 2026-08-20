<div align="center">

```
   _____      __                     ___         __ _                        __  
  / ___/ ____/ /___  ______ _____   /   |  _____/ /(_)___ _____  ______  __ /_/  
  \__ \ / __  / __ \/ ___/ / __ `/  / /| | / ___/ __/ / __ `/ __ \/ ___/ / / /    
 ___/ // /_/ / /_/ / /  / / /_/ /  / ___ |/ /  / /_/ / /_/ / / / (__  ) /_/ /     
/____/ \__,_/\__,_/_/  /_/\__,_/  /_/  |_/_/   \__/_/\__,_/_/ /_/____/\__, /      
                                                                      /____/       
```

**`sofyan@umm-informatics`** — booting developer profile...

</div>

<br/>

```bash
sofyan@umm-informatics:~$ dmesg | tail -12
```

```
[    0.000001] Booting Sofyan Ardiansyah v3.0 (build: semester-6)
[    0.041203] Kernel: informatics-engineering-umm.ko loaded
[    0.089510] Mounting /skills, /projects, /curiosity as rw
[    0.132877] Detected peripherals: keyboard, coffee-mug, second-monitor(pending)
[    0.201044] Loading module: problem-solving.ko ......... OK
[    0.244190] Loading module: backend-development.ko ..... OK
[    0.287322] Loading module: database-design.ko .......... OK
[    0.330012] Loading module: patience.ko .................. loading (slow)
[    0.402555] Starting service: continuous-learning.service
[    0.455901] Starting service: open-to-opportunities.service
[    0.500000] Reached target: ready-for-internship.target
[    0.512300] System ready. Welcome.
```

<br/>

```bash
sofyan@umm-informatics:~$ whoami
```

```
Sofyan Ardiansyah
Informatics Engineering Student — Universitas Muhammadiyah Malang
Status   : [ ACTIVE ]  Open to internship / junior developer roles
Location : Malang, East Java, Indonesia
Uptime   : 3rd year of study, building things that (mostly) don't crash
```

<br/>

```bash
sofyan@umm-informatics:~$ cat about.md
```

> I'm an Informatics Engineering student who treats every bug as a puzzle instead of a punishment. Most of my time goes into backend logic, database design, and figuring out *why* something works — not just making it work. I like small, well-structured projects more than big messy ones, and I'm currently pushing myself deeper into web development and systems programming.
>
> Outside of class, I spend a lot of time reading other people's code, breaking my own code on purpose to understand it better, and slowly building a portfolio worth showing to a real engineering team — not just a grader.

<br/>

<table width="100%">
<tr><td>

```bash
sofyan@umm-informatics:~$ npm list --depth=0 skills/
```

</td></tr>
<tr><td>

```
skills/
├── languages/
│   ├── python@learning     — scripting, automation, basic data handling
│   ├── java@intermediate   — OOP fundamentals, coursework projects
│   ├── c@intermediate      — memory, pointers, low-level logic
│   ├── csharp@learning     — desktop apps, .NET basics
│   └── php@intermediate    — server-side scripting, CRUD apps
│
├── web/
│   ├── html5@solid
│   ├── css3@solid
│   └── javascript@learning — DOM, basic interactivity
│
├── database/
│   └── mysql@intermediate  — schema design, joins, normalization
│
└── tooling/
    ├── git+github@solid
    ├── vscode@daily-driver
    └── postman@as-needed

5 language(s), 8 tool(s) installed. 0 vulnerabilities found (still learning, though).
```

</td></tr>
</table>

<br/>

```bash
sofyan@umm-informatics:~$ ps aux | grep "currently_learning"
```

```
PID   USER      %FOCUS  COMMAND
1001  sofyan     35%    struktur-data-dan-algoritma --deepen
1002  sofyan     25%    backend-development --stack=php,csharp
1003  sofyan     20%    database-design --practice=mysql
1004  sofyan     15%    rest-api --status=exploring
1005  sofyan      5%    docker --status=queued
```

<br/>

```bash
sofyan@umm-informatics:~$ ls -la ~/projects/
```

<table width="100%">
<tr>
<th align="left" width="28%">drwxr-xr-x</th>
<th align="left" width="42%">description</th>
<th align="left" width="30%">stack</th>
</tr>
<tr>
<td><code>project-one/</code></td>
<td>Ganti dengan nama & deskripsi proyek asli — sistem CRUD atau aplikasi web yang pernah kamu bangun.</td>
<td><code>PHP · MySQL · Bootstrap</code></td>
</tr>
<tr>
<td><code>project-two/</code></td>
<td>Ganti dengan proyek berbasis desktop / C# — aplikasi tugas kuliah atau proyek pribadi.</td>
<td><code>C# · .NET</code></td>
</tr>
<tr>
<td><code>project-three/</code></td>
<td>Ganti dengan proyek eksplorasi Python — otomasi, data kecil, atau tools sederhana.</td>
<td><code>Python</code></td>
</tr>
</table>

<div align="center">

*Ganti nama repo di atas dengan repo asli kamu, lalu pin kartunya di bawah ini —*
*`github-readme-stats` akan menariknya otomatis begitu file ini live di GitHub.*

<a href="https://github.com/sofyan35142/project-one"><img src="https://github-readme-stats.vercel.app/api/pin/?username=sofyan35142&repo=project-one&theme=nightowl&hide_border=true" height="150"/></a>
<a href="https://github.com/sofyan35142/project-two"><img src="https://github-readme-stats.vercel.app/api/pin/?username=sofyan35142&repo=project-two&theme=nightowl&hide_border=true" height="150"/></a>

</div>

<br/>

```bash
sofyan@umm-informatics:~$ git log --oneline --graph --stat
```

```
* 2026 ── refactor(life): fokus proyek backend & persiapan magang
* 2025 ── feat(web): eksplorasi PHP + MySQL, bangun aplikasi CRUD pertama
* 2024 ── feat(core): pelajari C, Java, Python — fondasi logika pemrograman
* 2023 ── init: masuk Teknik Informatika, Universitas Muhammadiyah Malang
```

<br/>

```bash
sofyan@umm-informatics:~$ tree ~/skills --dirsfirst -L 3
```

```
skills
├── languages
│   ├── python
│   │   ├── syntax.ok
│   │   ├── automation-scripts.ok
│   │   └── data-handling.in-progress
│   ├── java
│   │   ├── oop-fundamentals.ok
│   │   └── coursework-projects.ok
│   ├── c
│   │   ├── pointers-and-memory.ok
│   │   └── low-level-logic.ok
│   ├── csharp
│   │   ├── desktop-apps.ok
│   │   └── dotnet-basics.in-progress
│   └── php
│       ├── server-side-scripting.ok
│       └── crud-applications.ok
│
├── web
│   ├── html5.ok
│   ├── css3.ok
│   └── javascript.in-progress
│
├── database
│   └── mysql
│       ├── schema-design.ok
│       ├── joins-and-queries.ok
│       └── normalization.ok
│
└── tooling
    ├── git-github.ok
    ├── vscode.ok
    └── postman.in-progress

12 files marked .ok, 3 files marked .in-progress
```

<br/>

```bash
sofyan@umm-informatics:~$ crontab -l
```

```
# m  h  dom mon dow   command
  0  6  *   *   *     read_one_documentation_page
  0  9  *   *   1-5   attend_lectures --focus=informatics
  0  14 *   *   *     solve_dsa_problem --source=leetcode-or-similar
  0  20 *   *   *     work_on_side_project --stack=php,mysql
  0  23 *   *   0     review_week --write_notes=true
```

<br/>

```bash
sofyan@umm-informatics:~$ tail -n 6 /var/log/lessons_learned.log
```

```
[2024-03-12] WARN   copy-paste code without understanding it → came back to bite me on the exam
[2024-06-01] INFO   started writing comments BEFORE code, not after → fewer logic errors
[2024-09-20] INFO   learned that 90% of bugs are typos or off-by-one, not "the compiler is broken"
[2025-02-14] INFO   pair debugging with a friend cut my debugging time roughly in half
[2025-08-03] WARN   underestimated database normalization → had to redesign schema mid-project
[2026-01-10] INFO   writing README/docs first now clarifies scope before writing a single line of code
```

<br/>

```bash
sofyan@umm-informatics:~$ cat package.json
```

```json
{
  "name": "sofyan-ardiansyah",
  "version": "3.0.0-student",
  "description": "Informatics Engineering student, backend-leaning developer",
  "main": "consistency.js",
  "scripts": {
    "study": "node deepen.js --topic=algorithms,backend,database",
    "build": "npm run learn && npm run practice && npm run ship",
    "test": "jest --coverage --topic=self-doubt --expect=fail-forward"
  },
  "dependencies": {
    "curiosity": "^999.0.0",
    "patience": "^4.2.0",
    "coffee-or-tea": "^2.0.0"
  },
  "devDependencies": {
    "impostor-syndrome": "^1.0.0 (being slowly deprecated)"
  },
  "license": "Open-to-collaboration"
}
```

<br/>

```bash
sofyan@umm-informatics:~$ ./run_diagnostics.sh --module=github-stats
```

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=sofyan35142&show_icons=true&theme=nightowl&hide_border=true&count_private=true&include_all_commits=true" height="165"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sofyan35142&layout=compact&theme=nightowl&hide_border=true" height="165"/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=sofyan35142&theme=nightowl&hide_border=true" width="70%"/>

<img src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg" width="90%"/>

</div>

<br/>

```bash
sofyan@umm-informatics:~$ cat roadmap.todo
```

```
[x] Kuasai dasar algoritma & struktur data
[x] Bangun aplikasi CRUD sederhana (PHP + MySQL)
[x] Terbiasa dengan Git/GitHub workflow
[ ] Pelajari REST API & satu backend framework secara mendalam
[ ] Coba containerization dasar (Docker)
[ ] Kontribusi ke minimal 1 proyek open source
[ ] Bangun 1 proyek portofolio skala menengah dari nol
```

<br/>

```bash
sofyan@umm-informatics:~$ ifconfig organizations0
```

```
organizations0: flags=UP,RUNNING  mtu=campus-scale
        role        Anggota / Staff — Nama Organisasi atau UKM Kampus
        period      2024 — sekarang
        note        ganti dengan organisasi/UKM asli yang kamu ikuti

organizations1: flags=UP  mtu=event-scale
        role        Divisi Acara / IT — Nama Kepanitiaan
        period      2025
        note        ganti dengan kepanitiaan acara kampus yang pernah kamu ikuti

organizations2: flags=DOWN
        role        (belum ada entri tambahan)
        period      -
        note        tambahkan komunitas belajar / study group jika ada
```

<br/>

```bash
sofyan@umm-informatics:~$ htop --sort=priority
```

```
  PID  USER    PRI  NI  COMMAND
    1  sofyan   20   0  finish-coursework-with-understanding-not-just-grades
    2  sofyan   19   0  build-2-3-solid-portfolio-projects
    3  sofyan   18   0  get-internship-in-backend-or-fullstack-role
    4  sofyan   15   0  contribute-to-open-source-at-least-once
    5  sofyan   12   0  keep-github-contribution-graph-alive
    6  sofyan   10   0  sleep-8-hours-per-night (currently: SIGSTOP)
```

<br/>

```bash
sofyan@umm-informatics:~$ cat certifications.log 2>/dev/null || echo "belum ada entri"
```

<table width="100%">
<tr><th align="left">cert</th><th align="left">issuer</th><th align="left">year</th></tr>
<tr><td>Nama Sertifikasi 1</td><td>Penyelenggara</td><td>20XX</td></tr>
<tr><td>Nama Sertifikasi 2</td><td>Penyelenggara</td><td>20XX</td></tr>
</table>

> Bagian ini sengaja pakai fallback command style — isi dengan sertifikasi/lomba asli kamu, atau hapus tabelnya kalau belum ada.

<br/>

```bash
sofyan@umm-informatics:~$ history | grep "biggest_wins"
```

```
 501  fixed a bug that took 3 days to find — it was a missing semicolon
 502  finally understood JOIN in MySQL without looking it up mid-query
 503  built first working CRUD app end-to-end without a tutorial open
 504  helped a classmate debug their code faster than debugging my own
 505  read someone else's codebase and actually understood the structure
```

<br/>

```bash
sofyan@umm-informatics:~$ man sofyan | head -20
```

```
NAME
       sofyan — informatics student, backend-leaning developer

SYNOPSIS
       sofyan [--collaborate] [--internship] [--open-source]

DESCRIPTION
       Prefers clean, readable code over clever one-liners. Debugs
       systematically instead of guessing. Learns fastest by breaking
       things on purpose and reading the stack trace properly.

OPTIONS
       --collaborate      Open to team projects and pair programming
       --internship       Actively looking for internship opportunities
       --open-source      Willing to read code before writing code

SEE ALSO
       linkedin(1), github(1), email(1)
```

<br/>

```bash
sofyan@umm-informatics:~$ ./test_suite.sh --category=soft-skills
```

```
RUNNING test_suite.sh...

 PASS  communication.test          → menjelaskan hal teknis ke orang non-teknis
 PASS  teamwork.test               → nyaman bekerja dalam kelompok tugas / proyek
 PASS  adaptability.test           → cepat beradaptasi dengan stack/tools baru
 PASS  problem-solving.test        → memecah masalah besar jadi langkah kecil
 SKIP  public-speaking.test        → masih dalam progres, belum stabil
 PASS  time-management.test        → deadline tugas kuliah, jarang meleset (jarang)

Test Suites: 1 passed, 1 total
Tests:       5 passed, 1 skipped, 6 total
```

<br/>

```bash
sofyan@umm-informatics:~$ trap 'echo "reached out for a chat"' SIGCOLLAB
```

```
signal handler registered.
send SIGCOLLAB (a.k.a. just message me) any time — no formal ceremony required.
```

<br/>

```bash
sofyan@umm-informatics:~$ cat /etc/contact.conf
```

<div align="center">

<a href="mailto:youremail@gmail.com"><img src="https://img.shields.io/badge/email-D14836?style=flat-square&logo=gmail&logoColor=white"/></a>
<a href="https://linkedin.com/in/your-linkedin"><img src="https://img.shields.io/badge/linkedin-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/></a>
<a href="https://instagram.com/your-instagram"><img src="https://img.shields.io/badge/instagram-E4405F?style=flat-square&logo=instagram&logoColor=white"/></a>
<a href="https://twitter.com/your-twitter"><img src="https://img.shields.io/badge/twitter-1DA1F2?style=flat-square&logo=twitter&logoColor=white"/></a>

<sub><img src="https://komarev.com/ghpvc/?username=sofyan35142&style=flat-square&color=grey&label=visits+to+this+shell"/></sub>

</div>

<br/>

```bash
sofyan@umm-informatics:~$ df -h ~/interests
```

```
Filesystem       Size  Used  Avail  Use%  Mounted on
backend-dev      100G   68G    32G   68%  /interests/primary
databases         80G   55G    25G   69%  /interests/primary
algorithms        70G   50G    20G   71%  /interests/primary
frontend-dev      60G   28G    32G   47%  /interests/secondary
mobile-dev        40G    6G    34G   15%  /interests/curious-about
game-dev          30G    3G    27G   10%  /interests/curious-about
```

<br/>

```bash
sofyan@umm-informatics:~$ ping -c 4 opportunities.internship
```

```
PING opportunities.internship: 56 data bytes
64 bytes from recruiter: icmp_seq=0 ttl=64 time=0.1 ms status=interested?
64 bytes from recruiter: icmp_seq=1 ttl=64 time=0.1 ms status=still here
64 bytes from recruiter: icmp_seq=2 ttl=64 time=0.1 ms status=ready to talk
64 bytes from recruiter: icmp_seq=3 ttl=64 time=0.1 ms status=email is below ↓

--- opportunities.internship ping statistics ---
4 packets transmitted, 4 packets received, 0% packet loss
```

<br/>

```bash
sofyan@umm-informatics:~$ uptime
```

```
 up 3 years, learning still 100%, load average: curious, focused, a bit tired
```

<br/>

```bash
sofyan@umm-informatics:~$ shutdown -h now
```

```
Broadcast message from sofyan@umm-informatics:
  Thanks for reading through the whole session.
  If any of this made you think "I'd work with this person" — my inbox is open.

system going down for graduation in T-minus a few semesters...
```

<div align="center">

`[ END OF SESSION ]`

</div>
