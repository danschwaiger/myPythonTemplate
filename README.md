# my_python_project

Template Python project configured for Visual Studio Code.

## Quick start

```bash
# clone
git clone <your-repo-url> my_python_project
cd my_python_project

# create venv and activate (macOS)
python3 -m venv .venv
source .venv/bin/activate

# install dependencies
pip install -r requirements.txt

# run app
python -m src.my_python_project.main

# run tests
pytest -q
