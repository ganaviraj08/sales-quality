Design Choices:

1. Tableau Design


Tableau Public was chosen for dashboard publishing to ensure easy public access and seamless embedding into the web application.

Dashboards were designed using outlet-level relationships instead of joins to preserve data granularity and improve performance.

Key Performance Indicators (KPIs) are placed at the top of dashboards to provide immediate business visibility.

Brand colors were applied consistently to charts, KPIs, and highlights to maintain visual alignment with XYZ branding.

Simple, uncluttered layouts were used to prioritize business readability and storytelling.


2. Web Application Design


A multi-page static architecture (HTML + CSS) was used for simplicity, clarity, and ease of deployment without backend dependencies.

A sidebar-based navigation provides intuitive access to Home, Sales, Quality, and About pages.

Responsive CSS was implemented to ensure usability across desktop and mobile devices.

Tableau dashboards are embedded using iframe-based integration, keeping analytics processing decoupled from the web interface.

External CSS was used to maintain consistency and ease of maintenance across all pages.


Assumptions



The provided datasets (xyz_Sales.xlsx and xyz_Quality.xlsx) are assumed to be clean, accurate, and reliable.

Outlet identifiers are consistent across both datasets, enabling correct relational modeling.

KPIs are calculated using monthly-level aggregations to support trend analysis.

Tableau Public is available and accessible for dashboard hosting and embedding.

Users accessing the web application have an active internet connection to load embedded dashboards.


How to Run the Web Application


Prerequisites

A modern web browser (Chrome, Edge, Firefox, etc.)

No additional software or backend setup required


Steps to Run


Download or clone the project source code.

Ensure the following folder structure is maintained:
xyz-analytics-portal/
├── index.html
├── sales.html
├── quality.html
├── about.html
├── style.css
└── logo.png
Publish the Tableau dashboards to Tableau Public.

Copy the public dashboard URLs and paste them into the respective <iframe> tags in:

sales.html

quality.html

Open index.html by double-clicking it or opening it in a web browser.

Use the sidebar navigation to explore the Sales and Quality dashboards.

Public link : 
SALES DASHBOARD - https://public.tableau.com/views/SalesDashboard_17665108153500/SalesDashboard?:showVizHome=no
QUALITY DASHBOARD - https://public.tableau.com/views/QualityDashboard_17665119494060/QualityDashboard?:showVizHome=no
