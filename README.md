## 🌐 Visualization_Django

This repository hosts a web application project that seamlessly integrates the **Django** web framework (Python) with the powerful data visualization library **D3.js (Data-Driven Documents)**.

The primary goal of this project is to serve dynamic data from a database/backend and render interactive, modern visualizations directly in the browser using D3.js.

### 🌟 Project Overview

This application demonstrates a full-stack approach to data analysis and reporting:

1.  **Backend (Django):** Handles data management, routing, and serving data endpoints.
2.  **Visualization (D3.js):** Utilized within Django templates to fetch data and render complex, interactive charts.

This setup is ideal for displaying real-time or frequently updated business intelligence (BI) data via a robust web interface.

### ✨ Key Features

* **Django Integration:** Full Django project structure, including models (if any) and views to handle web requests.
* **Data Source:** Uses a CSV file (`data_ggsheet.csv`) which is likely loaded into the Django database (`db.sqlite3`) for serving via the application.
* **Dynamic D3.js:** Visualizations are rendered dynamically using D3.js, fetching data via Django views/APIs.
* **Modular App:** Includes a core Django app (`d3app`) dedicated to managing visualization logic and endpoints.
* **Template System:** Utilizes Django's built-in templating system (`templates/`) for embedding D3.js code and data context.

### 🛠️ Technologies Used

* **Backend:** Python, **Django**
* **Frontend:** HTML5, CSS3, JavaScript, **D3.js**
* **Database:** SQLite (default Django database: `db.sqlite3`)
* **Data:** CSV format (`data_ggsheet.csv`)

### 🚀 Getting Started

Follow these instructions to set up and run the project locally.

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/ArrebolPD/Visualization_Django.git](https://github.com/ArrebolPD/Visualization_Django.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd Visualization_Django
    ```
3.  **Setup Virtual Environment (Recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Linux/macOS
    venv\Scripts\activate     # On Windows
    ```
4.  **Install Dependencies:** (Assuming you have a `requirements.txt` file, if not, you may need to install Django manually: `pip install django`)
    ```bash
    pip install -r requirements.txt
    ```
5.  **Run the Django Server:**
    ```bash
    python manage.py runserver
    ```
6.  **Access the Application:** Open your browser and navigate to the local address provided (e.g., `http://127.0.0.1:8000/`).

### 📂 Repository Structure
```
Visualization_Django/
├── TQH_T8/          # Main Django Project folder (likely settings/urls for the whole project)
├── d3app/           # Core Django application containing views and logic for visualizations
├── templates/       # HTML templates where D3.js is embedded
├── data_ggsheet.csv # Initial data source file
├── db.sqlite3       # SQLite database file (automatically created/updated by Django)
└── manage.py        # Django's command-line utility for managing the project
```
### 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/ArrebolPD/Visualization_Django/issues) or submit a pull request.

### 📄 License

Distributed under the **MIT License**. See `LICENSE` for more information.

### 📬 Contact

Project Link: [https://github.com/ArrebolPD/Visualization_Django](https://github.com/ArrebolPD/Visualization_Django)
