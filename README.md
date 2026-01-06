# Python Virtual Environment

## 1. Create a virtual environment

```bash
python -m venv myenv
```

## 2. Activate the virtual environment

### Linux / macOS

```bash
source myenv/bin/activate
```

### Windows (Command Prompt)

```bash
myenv\Scripts\activate
```

### Windows (PowerShell)

```powershell
.\myenv\Scripts\Activate.ps1
```

## 3. Install packages

```bash
pip install pandas numpy matplotlib
```

## 4. Save installed packages

```bash
pip freeze > requirements.txt
```

## 5. Install packages from requirements file

```bash
pip install -r requirements.txt
```

## 6. Deactivate the virtual environment

```bash
deactivate
```
