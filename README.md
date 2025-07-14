# 🧠 Task 1 — Data Analysis with Pandas & Matplotlib

This project demonstrates data manipulation and visualization using Python, leveraging the powerful libraries **pandas** and **matplotlib**.

It serves as a foundational task in your machine learning or data science journey, focused on practical skills like data loading, preprocessing, and plotting.

---

## 📦 Included Libraries

The project uses the following Python packages:

- `pandas >= 2.3.1` – for data manipulation and analysis  
- `matplotlib >= 3.10.3` – for creating static, animated, and interactive visualizations  
- `pip >= 25.1.1` – for managing Python packages

> All dependencies are managed via [`uv`](https://github.com/astral-sh/uv), a modern Python package manager that uses `pyproject.toml`.

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YasserAlbogami/task_1.git
cd task_1
```

### 2. Set up the virtual environment

Using `uv` (recommended):
```bash
uv venv .venv
uv pip install
```

Or using plain `venv` and `pip`:
```bash
python -m venv .venv
.\.venv\Scripts\activate       # On Windows
# source .venv/bin/activate    # On Linux/macOS
pip install -r requirements.txt  # (if you export it)
```

### 3. Run the script

If the project has a main script (e.g., `main.py` or `notebook.ipynb`), run it with:

```bash
python main.py
```

Or open the notebook in VS Code or Jupyter.

---

## 📁 Project Structure

```
task_1/
├── .venv/                  # Virtual environment (ignored in Git)
├── pyproject.toml          # Dependency manager file
├── main.py                 # Your main logic script (if any)
├── README.md               # Project documentation
└── .gitignore              # Ignoring virtual env & more
```

---

## 🤝 Contributing

Pull requests and ideas are welcome. For major changes, please open an issue first.

---

## 📝 License

This project is open-source and free to use under the [MIT License](https://opensource.org/licenses/MIT).
