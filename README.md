# CEMFI Summer School 2025 — Data Science for Economics: Mastering Unstructured Data (Practicals)

Practical sessions for the course “Data Science for Economics: Mastering Unstructured Data,” taught at CEMFI Summer School 2025.

## Schedule and location

- Practical sessions (with Jesus): Monday 18, Wednesday 20, Thursday 21 August 2025, 15:00–17:00, Room M3 (CEMFI)
- Theory sessions (with Chris): Every day, 9:30–13:00, Room M3 (CEMFI)

Please bring your laptop to class.

## Important (Colab access)

- Have a Google account ready to use Google Colab during the practicals.
- Institutional laptops/accounts may block some Colab features. If possible, use a personal laptop and personal Google account.
- If that’s not possible, you can still attend: all material will be run and explained live.

## Repository structure

TBD

## Session plan

- Session 1 (2h)
  - Intro to Python (1h)
  - Scraping + predicting professions (1h)
- Session 2 (2h)
  - RAG with LangChain: chat with your data
- Session 3 (2h)
  - LLMs: research applications and recent developments

## How to use these notebooks

### Option A: Run on Google Colab (recommended)

- Open Google Colab → File → Open notebook → GitHub tab → search for this repository (jesusvillota/CSS_DataScience_2025) and select a notebook under Session1/Session2.

- Open notebooks from my GitHub and click "Open in Colab", then, save it to your Google Drive account.

### Option B: Run locally (optional)

- Requirements: Python 3.10+ and packages: requests, beautifulsoup4, pandas, jupyter
- Create and activate a virtual environment, then install dependencies:

```bash
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install requests beautifulsoup4 pandas jupyter
jupyter lab
```

Open the desired notebook from the Session folders.

## Notes on web scraping ethics

- Check and respect each site’s robots.txt and terms of service.
- Be gentle with request rates; avoid overloading servers.
- Collect only what you’re allowed to collect and handle data responsibly.

## Contact

- Instructor: Jesus Villota Miranda
- Email: jesus.villota@cemfi.edu.es
- LinkedIn: https://www.linkedin.com/in/jesusvillotamiranda/
