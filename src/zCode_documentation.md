
# Python Virtual Environment

Use a virtual environment to store your packages. The steps are: Create if doesn't exist -> Activate it -> Install packages if not present, either install individual package or the ones in requirements.txt. Deactivate when done.

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install <package-name>
pip install -r requirements.txt
deactivate
```
