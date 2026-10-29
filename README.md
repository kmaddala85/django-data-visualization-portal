# Django Data Visualization Portal

A Django-based analytics and visualization application demonstrating how Python, data processing and modern JavaScript visualization libraries can be combined to build interactive dashboards and geospatial analysis tools.

The project brings together backend development, data integration, interactive visualization and reporting in a single web application.

## Screenshots

### Interactive Analytics Dashboard
![Analytics Dashboard](screenshots/Screenshot_dashboard.png)

### Geospatial Network Analysis
![Geospatial Analysis](screenshots/map.png)

### Data exploration
![Data Exploration](screenshots/dashboard.png)

## Key Features

### 1. Interactive Data Analytics
- Interactive charts and tables using Plotly and Bokeh.
- Exploratory data analysis using Pandas and PyGWalker.
- JavaScript-based charting examples.
- Sorting and filtering of analytical data.

### 2. Geospatial Visualization
- Interactive spatial visualizations using Kepler.gl and PyDeck.
- Map-based analysis using Leaflet and MapLibre.
- Spatial data processing using GeoPandas.
- Examples of working with large geospatial datasets.

### 3. Reporting and Export
- PDF report generation examples.
- Chart and data export workflows.
- Interactive analytical tables.

### 4. Backend Application
- Django-based application structure.
- Python data processing using Pandas and NumPy.
- Environment-based application configuration.
- Django URL routing, views and templates.

## Technology Stack

| Area | Technologies |
|---|---|
| Backend | Python, Django |
| Data Processing | Pandas, NumPy |
| Frontend | JavaScript, HTML5, CSS3, Bootstrap 5 |
| Visualization | Plotly, Bokeh, PyGWalker, Chart.js |
| Geospatial | GeoPandas, Kepler.gl, PyDeck, Leaflet, MapLibre |
| Reporting | WeasyPrint, Matplotlib, jsPDF |
| Database | SQLite (default development configuration) |

## Project Structure

```text
django-data-visualization-portal/
│
├── app_inputs/          # Application input files
├── dashboard/           # Django dashboard application
├── demo_portal/         # Django project configuration
├── screenshots/         # Application screenshots
├── static/              # CSS, JavaScript and static assets
├── templates/           # Django templates
│
├── manage.py
├── requirements.txt
└── README.md
```

## Getting Started

### Prerequisites
- Python 3.12 (tested configuration)
- Git

### 1. Clone the repository

```bash
git clone https://github.com/kmaddala85/django-data-visualization-portal.git
cd django-data-visualization-portal
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

Windows PowerShell:

```powershell
.\.venv\Scripts\Activate.ps1
```

Linux / macOS:

```bash
source .venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure environment variables

Create a `.env` file in the project root using `.env.example` as a template.

Do not commit your actual `.env` file.

### 5. Apply migrations

```bash
python manage.py migrate
```

### 6. Start the development server

```bash
python manage.py runserver
```

Open:

http://127.0.0.1:8000/

## Configuration and Data

The repository uses SQLite as its default development database.

Use synthetic or sanitized sample datasets when demonstrating the application. Do not commit company data, customer information, network configurations or credentials.

## Project Scope

This repository is a portfolio and demonstration project showcasing Django development, data analytics and visualization techniques.

It is not presented as a production deployment.

## License

MIT License.
