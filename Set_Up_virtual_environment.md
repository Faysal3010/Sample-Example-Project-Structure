# Set up Virtual Environment Manuel or Automate

# Option 1 :
## 🛠️ Step 1: Python ও VS Code install 

- 🔍 Check Python:  
  `python --version` or `python3 --version`

- 🔍 Check pip:  
  `pip --version`

- 🔍 Download VS Code :  
  if it's not install → [https://code.visualstudio.com](https://code.visualstudio.com) then download

---

## 🧪 Step 2: Virtual Environment Setup (venv)

```bash
python -m venv myenv
```

it's create a `myenv` folder, this a **isolated Python environment** — So that , main Python system will not be affect.


## ▶️ Step 3: Environment Activate 

### 🪟 Windows:
```bash
myenv\Scripts\activate
```

### 🐧 Linux/Mac:
```bash
source myenv/bin/activate
```

✅ Terminal- it will be showed that in the prefix `(myenv)` → means Python command it's running in the environment system

---
## 📦 Step 4: add `requirements.txt` for dependency manage

```bash
pip freeze > requirements.txt
```


# Option 2 :

## 🧩 Step 1: VS Code Integration

1. Open a project folder in vscode
2. 🔎 Ctrl + Shift + P → type : `Python: Select Interpreter`
3.  Click
   ```
   .venv\Scripts\python.exe
   ```
4. Then activate it into Terminal

---

## 📦 Step 2: add `requirements.txt` for dependency manage

```bash
pip freeze > requirements.txt
```
