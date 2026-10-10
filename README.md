

\# Study Assistant



A starter repository for the CSC10014 Smart Virtual Assistant project.



\## Setup



\### 1. Clone the repository



```bash

git clone https://github.com/tree312-coder/lab01-tree312-coder.git

cd lab01-tree312-coder

```



\### 2. Create and activate a virtual environment



On Windows (Command Prompt):



```cmd

py -m venv .venv

.venv\\Scripts\\activate.bat

```



\### 3. Install dependencies



```bash

python -m pip install --upgrade pip

pip install -r requirements.txt

pip install -e .

```



\## Run



Ask the assistant a question:



```bash

python -m assistant "where is the IT helpdesk?"

```



Expected output:



```text

IT Helpdesk: room E.005, open Mon-Fri 08:00-17:00.

```



\## Test



Run the automated tests:



```bash

pytest -q

```



\## Project structure



\- `data/`: Project data files.

\- `docs/`: Project documentation.

\- `scripts/`: Helper and environment-check scripts.

\- `src/`: Application source code.

\- `tests/`: Automated tests.

\- `ui/`: User interface files.

\- `pyproject.toml`: Project configuration.

\- `requirements.txt`: Python dependencies.



