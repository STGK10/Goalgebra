# Goalgebra

Automated betting signal pipeline using **Forebet** predictions.

## Features

- Daily scraping of Forebet predictions (Over 2.5 probability)
- Live HT match scanning
- Betting strategy engine for football & hockey
- Telegram signal delivery
- SQL database for storing predictions and signals

## Folder Structure

- `src/` – Python source code
- `config/` – Configuration files
- `tests/` – Unit tests
- `data/logs/` – Signal logs

## Installation

```bash
git clone https://github.com/<your_username>/Goalgebra.git
cd Goalgebra
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
pip install -r requirements.txt
