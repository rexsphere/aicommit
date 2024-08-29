# aicommit

`aicommit` is a script that automatically adds changed files in your git repository and uses a local LLM (Large Language Model) to generate concise, one-line commit messages.

## Prerequisites

- Python 3.6 or higher
- `ollama` installed locally
- `llama3.1` model available via `ollama`

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/aicommit.git
   cd aicommit
   ```

2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Ensure you have `ollama` set up locally with the `llama3.1` model.

## Usage

Run the script using Python:
```bash
python aicommit
```

For more options, use the `--help` flag:
```bash
python aicommit --help
```
