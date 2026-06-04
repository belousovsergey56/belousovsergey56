# Hi, I'm Sergey

## About Me
Since 2022, I have been specializing in business process automation, system integration, and developing internal services.  
My core focus is on high-performance APIs, complex integrations, and data optimization. 
I help companies cut processing time by orders of magnitude and build intuitive internal tooling.

> [!NOTE]
> Open to exciting projects and new team opportunities.

## Tech Stack & Tools

**Core Stack:**

Language & Asynchrony  
- Python 3.11+ (with type hinting and async/await)  
- Asyncio + aiohttp — concurrent requests to external APIs  

Web Frameworks & Validation  
- FastAPI — building robust integration APIs  
- Pydantic — strict typing and data validation (input/output)  

Data Processing  
- Pandas — cleaning, transforming, and normalizing tabular data (xlsx, csv)  
- SQLAlchemy (async) — ORM for database interactions  
- Alembic — database schema migrations under version control  

Databases  
- PostgreSQL — primary production DBMS  
- SQLite — lightweight DB for testing and local development  

**Infrastructure:**
- Docker, Docker Compose
- Git, GitHub Actions, Pytest, Unittest
- Ruff, Black, UV
- Bash/Zsh scripting, Linux (Debian/RedHat)

**Developer Environment:**
- Kitty, tmux, Helix

---

## Experience

#### Designed and Implemented Integration with Wialon API
- Reduced object search time across multiple servers with Wialon system from several minutes down to **1 second**.
- Accelerated bulk contract activation in Wialon from **4 hours to 5 seconds**.
- Cut data processing time for 18,000+ objects from **12 hours to 20 minutes** by developing two iterations of an automated custom-fields filling tool. In the second iteration, implemented asynchronous processing and reused API sessions.
- Automated object history import, reducing processing time from **10 to 2 minutes** and eliminating the need for external file-splitting services.
- Developed a script to detect duplicate objects across company servers and generate detailed reports.
- Implemented a script for bulk object renaming with an execution time of just **1 - 2 seconds**.
- Created a unified departmental knowledge base, reducing call handling time from **10 to 5 minutes** and significantly lowering the load on L2 support.

#### Designed and Implemented Integration with CSP API
- Automated client account creation, permission provisioning for client objects/report templates, and dynamic object grouping. This reduced task execution time from **30 to 3 minutes**.
- Automated custom field updates for over 15,000+ objects:
  - Allowed clients to upload xlsx files in their native formats without needing to pre-format data according to CSP templates.
  - Solved the issue of custom fields being completely overwritten or duplicated, overriding the platform's native limitation.
  - Overcame web-platform/nginx request timeout limits (10-minute execution cap).

#### Developed a Web Service for External API Interactions
- Built a web interface and API aggregator featuring a navigation sidebar, dropdown toolsets for each API, and dedicated request execution pages.
- Enabled users to upload files, which are processed by a backend script that invokes the target API and returns the result in real time.

---

### Open Source & Personal Projects

- **[terminal-note](https://github.com/belousovsergey56/terminal-note)**  
  A CLI utility for taking notes directly in the terminal (fzf, templates, Markdown, custom editors). Perfect for quick `.md` notes.

- **[tn](https://github.com/belousovsergey56/tn#demo)**  
  The second revision of `terminal-note`, rewritten in Golang. Added Git auto-sync with remote repositories and the ability to open selected notes directly in Obsidian.

- **[my_configs](https://github.com/belousovsergey56/my_configs)**  
  Ready-to-use configuration files for quick dev-environment setup (Zsh, Neovim, Helix, Kitty, tmux).

- **[FastAPIEventNotify](https://github.com/belousovsergey56/FastAPIEventNotify)** & **[EventNotify](https://github.com/belousovsergey56/EventNotify)**  
  A Telegram bot delivering daily notifications about events and theater plays in Saint Petersburg (KudaGo API + FastAPI/Flask + APScheduler) — built for a client. The second instance was fully rewritten using FastAPI.

---

### Contact Me

- **Telegram**: [@sbelousov56](https://t.me/sbelousov56)
- **Email**: [belousovsergej56@gmail.com](mailto:belousovsergej56@gmail.com)
