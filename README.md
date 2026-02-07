# linco4d.github.io


# Building Meaningful Apps with Data 🛠️🌫️


Hey! This is a snapshot of what I build and think about. Most of my work sits at the intersection of **Python automation**, **scientific/data workflows**, and **turning messy real-world inputs into something a team can actually use**.
I just finished an **AQI Notifier** system I’ve been building. It's a Python-based pipeline that pulls air-quality data (e.g. for California / wildfire season), stores it, and emails updates on a schedule. It’s simple on the surface, but it touches a lot of things I care about: clean data models, reproducible scripts, and designing something that actually helps people.
I’m an undergrad at **Claremont McKenna College** (Science Management, biotech focus) with a term at **Oxford** in Philosophy & Theology. You'll see an unusual mix of projects in here 🙂

---

## 🔭 Featured Project: AQI Notifier

**What it is:**  
A Python ingestion + notification pipeline that:
- fetches AQI / air-quality data for selected locations,
- stores it in a lightweight DB,
- and emails out a digest on a fixed schedule (e.g. every 12 hours).

**Why I built it:**  
I wanted a pattern for “real” automations: pick a data source → normalize it → persist it → notify humans. It’s the same shape you’d use for market-data alerts, compliance reminders, or research ingesters.

**Tech shape:**
- `python` 
- CLI built with something like `typer` (so you can run `init_db`, `run_once`, `schedule`)
- scheduler pattern (APS-like) to run hourly/daily jobs
- local DB (SQLite-style) to persist locations + readings
- email sender for the digest

---

## 🎓 Education

**Claremont McKenna College — Claremont, CA**  
*Bachelor of Arts in Science Management (Biotechnology focus)*   
**Relevant Coursework:** Data Science, Computational Biophysics, Statistics, Linear Algebra, Python, Engineering Physics, Organic Chemistry, Virology, Molecular Biology, Cell Biology

**University of Oxford — Oxford, UK**  
*Visiting Student, Philosophy and Theology* (Worcester College)  
 
---


## 🧪 Other Roles & Leadership
- Data Automation Analyst, **Lowe Institute of Political Economy**
- Career Service Mentor (CSM of the Year), **The Soll Center for Student Opportunity**
- Tour Guide, **Claremont McKenna College**
- Humanities Lab Fellow, **Gould Center for Humanistic Studies**
- Fellow, **Randall Lewis Center for Innovation and Entrepreneurship**

These mostly show that I like making processes faster and that I actually talk to people, not just Jupyter notebooks.

---

## 🛠️ Skills

**Languages:** Python, R (intermediate)
---

## 📦 What’s in My Repos?

- **AQI Notifier** — current flagship; Python + scheduler + email + DB
- Automation scripts I’ll eventually document better
- More coming soon!



---

## 📚 What I Read

I rotate between:
- ML / neural networks (especially applied to scientific data)
- computational biophysics / molecular modeling
- finance / alternative investments 
- philosophy/theology 


---

## Contact / Collab

If you’re working on **pipelines for scientific data**, **scrapers for research**, or **small ML systems that actually ship**, I’m happy to compare architectures or trade scripts.


<a href="https://linco4d.github.io/">Lincoln's Website</a> © 2025 by <a href="https://example.com">linco4d</a> is licensed under <a href="https://creativecommons.org/licenses/by-sa/4.0/">CC BY-SA 4.0</a><img src="https://mirrors.creativecommons.org/presskit/icons/cc.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;"><img src="https://mirrors.creativecommons.org/presskit/icons/by.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;"><img src="https://mirrors.creativecommons.org/presskit/icons/sa.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;">
