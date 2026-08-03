# Hi there! I'm Kacper Rzepecki 👋

I'm a full-stack developer from Poland - working commercially with **Ruby on Rails** and **React.js** since 2019 💎⚛️

But calling me "a web developer" would only tell half the story. I'm the person you call when the problem sits **between** the neat boxes on the org chart: when the app needs a server, the server needs a network, the network needs a device, and the device speaks some undocumented binary protocol nobody has touched in ten years. I like being that kind of **IT multitool** 🔧

My background is in Automatics and Robotics (BEng + MEng, Lodz University of Technology), and I've never really left the hardware side behind. Microcontrollers, industrial machines, and Rails apps all live in the same toolbox for me.

## What I do

### 🌐 Web development

**Healthcare** is the domain I keep coming back to. I've worked on several medical applications over the years - used by hospitals and laboratories in the US, spanning multi-portal systems with mobile APIs, external integrations (Tableau, Moodle, clients' SSO) and background processing at scale, built on stacks ranging from classic Rails monoliths to current Rails with Hotwire and Turbo. These systems store **PHI and PII**, so they're designed around **HIPAA requirements** from day one - access control, audit trails, encryption, no shortcuts anywhere near patient data. Healthcare is a good teacher; it doesn't let you postpone the boring parts.

Elsewhere in Rails and React land:

- Extracting React components out of Rails views into **standalone SPA applications** and reshaping the API around them.
- **Legacy rescue missions** - my favourite genre. Major Ruby and Rails version jumps on production systems, hundreds of dependencies dragged forward at once, in-place PostgreSQL upgrades, applications brought back from "we can't touch it, it'll break" to something you can actually deploy on a Tuesday. Nobody cheers when it goes well, which is exactly why it has to go well.
- Also: a handful of **WordPress sites** and **WooCommerce shops** - because sometimes the right answer isn't a custom Rails app, and knowing when to say that is part of the job.

### ⚙️ DevOps & infrastructure

I don't stop at `git push`. Over the years I've been the person responsible for:

- Cloudflare configuration and WAF rules, Heroku deployments, CircleCI pipelines
- A private **SFTP server** for automated data synchronisation
- Keeping project dependencies up to date across a large codebase (all of them, all the time)
- **Cloud cost analysis** across AWS and Azure that ended in a **30%+ reduction** 💸
- **Migrating hosting between providers** - sites, mail, domains and databases moved with minimal downtime, cutting the **annual bill by 80%**. Shared hosting invoices have a way of growing quietly for years until somebody actually reads them.
- Self-hosted setups on clients' own hardware: PostgreSQL, Puma behind Linux daemons, environment configuration, backups, VPN-only access

### 🏭 Industrial applications

Some of my favourite work never touches the public internet. I've built applications that run **entirely on the client's own servers**, reachable only from the local network - VPN access at most - because that's what the factory floor requires:

- **Reporting systems** - a recurring theme in my work. The first iteration was a Rails monolith for **production reporting**, with dedicated layouts per user role, the client's own SMTP server for mail, and XLSX report templates filled in programmatically, hosted entirely on internal infrastructure. The second iteration took the same idea further: a Rails API with a fully responsive React front end, used on tablets in the field, generating reports ready to be imported straight into an external system instead of being retyped record by record. Both replaced hours of manual paperwork with a file and a click.
- A **PyQt desktop application in Python for controlling a galvo laser** - which required **reverse engineering the communication protocol** of the controller, since documentation simply didn't exist. 🔬
- A **pressure-drop detection system for a pneumatic installation**, monitoring the line and firing off SMS alerts the moment something goes wrong. Compressed air leaks are quiet, expensive, and much easier to fix at 2 PM than on Monday morning.

### 📈 Signal processing & data analysis

Not every project ends with a user interface - sometimes the deliverable is a chart that answers a question nobody could answer before:

- A **Python toolkit for analysing EMG signals in sport horses**, built for one of the leading veterinary clinics in Poland. It processes raw electromyography recordings and turns them into a clear picture of muscle activity over the course of treatment - so vets can actually **show** how a horse's condition is improving, instead of relying on impressions. Filtering, envelope extraction, comparison across sessions, readable plots. 🐎

### 🔌 Embedded & microcontrollers

- A **seed quality analysis device**: STM32F407 talking to an SPI spectrophotometer, streaming measurements over UART to an Electron/React kiosk app on a 9" Windows terminal. I owned the whole microcontroller side - SPI, UART, the measurement algorithm - plus the frontend.
- A **digital dashboard for the Eagle Two solar car** as an Embedded Developer in Lodz Solar Team: speed, battery percentage, energy balance and other indicators pulled off the **CAN bus** and rendered on a 4.3" touchscreen driven by an STM32F746G-DISCO.

### 🛠️ After hours

I run my own **homelab** - a Proxmox cluster hosting **Home Assistant**, a NAS, a media server, a print server and whatever else needs a permanent home, all on small form-factor machines drawing **under 40 W total**. Home Assistant is where most of my ESP32 projects eventually plug in, so the hobby side and the ops side keep feeding each other. Constraints make it fun: every service has to justify its memory and its watts, which turns out to be surprisingly good practice for production thinking. Everything stays on the local network, with VPN for access from outside.

The rest of the hobby projects are where the ideas come from. Lots of **ESP32**, **Raspberry Pi** and **Arduino** - home automation, sensors, small IoT contraptions, things that measure other things and complain when they're wrong. Plenty of them end up with a **3D printed** enclosure, because at that point why not.

## Toolbox

**Backend** - Ruby, Ruby on Rails, Hotwire / Turbo, Sidekiq, GoodJob, Devise, PostgreSQL, Redis, SQL\
**Frontend** - React.js, JavaScript, jQuery, HAML, HTML & CSS, MaterialUI, Bootstrap\
**Embedded & desktop** - C++, STM32, ESP32, Arduino, Raspberry Pi, SPI / UART / CAN, Python, PyQt, Electron\
**Data & signals** - Python (NumPy, SciPy, pandas, Matplotlib), EMG / sensor signal processing\
**Ops** - Heroku, AWS, Azure, Cloudflare, CircleCI, Linux, Puma, Nginx, VPN, Proxmox, Docker, self-hosted servers\
**Other** - Git, GitHub, Jira, Confluence, WordPress, WooCommerce

## A few things about how I work

- I get genuine satisfaction out of finding a **simple solution to a complicated problem**. The clever solution is rarely the good one.
- I've **mentored interns** twice at my company (2020, 2021) and represented it as a mentor for students of Lodz University of Technology in "Projekt Innowacja" (2021). Explaining something well is the best way to find out whether you actually understand it.
- I'm comfortable being the **direct line to the client** - technical support, Slack conversations, translating "it doesn't work" into a ticket.
- Languages: Polish (native), English 🇵🇱 🇬🇧

## Off the keyboard

⛵ Sailing - the one hobby with no firmware to flash\
🖨️ 3D printing - enclosures, brackets, and occasionally something useful\
📡 IoT tinkering - see above, it never really stops

---

Thanks for stopping by! If you've got a problem that spans a web app, a server and a piece of hardware that shouldn't be talking to either - that's my favourite kind. 🚀
