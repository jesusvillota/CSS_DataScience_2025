
# CEMFI Summer School 2025 — Using Textual Data in Empirical Monetary Economics (Practicals)

Practical sessions for the course “Using Textual Data in Empirical Monetary Economics,” taught at CEMFI Summer School 2025.

## Schedule and location

- Practical sessions (with Jesus): Wednesday 27, Thursday 28, Friday 29 August 2025, 11:00–13:00, Room M1 (CEMFI)
- Theory sessions (with Michael): Every day, 15:00–18:30, Room M2 (CEMFI)

Please bring your laptop to class.

## Important (Colab access)

- Have a Google account ready to use Google Colab during the practicals.
- Institutional laptops/accounts may block some Colab features. If possible, use a personal laptop and personal Google account.
- If that’s not possible, you can still attend: all material will be run and explained live.

## Repository structure

```
Session1/
  1_1_Introduction.ipynb
  1_2_Scraping.ipynb
Session2/
  2_1_BIS_Scraper_I.ipynb
  2_1_BIS_Scraper_II.ipynb
  2_2_RAG_I_Document_Loading.ipynb
  2_3_RAG_II_Document_Splitting.ipynb
Session3/
  3_1_RAG_III_Vectorstores_And_Embeddings.ipynb
  3_2_RAG_IV_Full_Pipeline.ipynb
  3_3_LLM_I_Intro.ipynb
  3_4_LLM_II_Function_Calling.ipynb
  3_5_LLM_Download_(Extra).ipynb
```

## Session plan


### Session 1
- **1_1_Introduction.ipynb**: Intro to Python
- **1_2_Scraping.ipynb**: Intro to Scraping

### Session 2
- **2_1_BIS_Scraper_I.ipynb**: Automated Scraping of BIS Central Bank Speeches: intro
- **2_1_BIS_Scraper_II.ipynb**: Automated Scraping of BIS Central Bank Speeches: production
- **2_2_RAG_I_Document_Loading.ipynb**: RAG with LangChain (I): document loading
- **2_3_RAG_II_Document_Splitting.ipynb**: RAG with LangChain (II): document splitting

### Session 3
- **3_1_RAG_III_Vectorstores_And_Embeddings.ipynb**: RAG with LangChain (III): vectorstores and embeddings
- **3_2_RAG_IV_Full_Pipeline.ipynb**: RAG with LangChain (IV): retrieval and LLM interaction
- **3_3_LLM_I_Intro.ipynb**: LLMs: introduction
- **3_4_LLM_II_Function_Calling.ipynb**: LLMs: function calling
- **3_5_LLM_Download_(Extra).ipynb.ipynb**: LLM download (extra)


## How to use these notebooks

### Option A: Run on Google Colab (recommended)

- Option A.1 (Recommended) Open notebooks from my GitHub and click "Open in Colab", then, save them to your Google Drive account.

- Option A.2 Download notebooks from either the CSS Moodle webpage or from my GitHub repository. Then, upload them  to your Google Drive and open them with Google Colab (integrated inside Google Drive).

### Option B: Run locally (more advanced)

Use [Poetry](https://python-poetry.org/) for dependency management.

Requirements: Python 3.11+ (see `pyproject.toml`)

Setup steps:

```bash
# Install Poetry if you don't have it
curl -sSL https://install.python-poetry.org | python3 -

# Install dependencies (creates and manages the virtual environment automatically)
poetry install

# Activate the Poetry shell
poetry shell
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
