# National-Health-Expenditure-GIS-
📌 Project Overview
A specialized Geographic Information System (GIS) developed for the National Ministry of Public Health of the Democratic Republic of Congo. This application tracks, maps, and evaluates the expenditures of various health programs executed across all 26 provinces of the DRC.

By providing a centralized digital "command center," the platform allows health officials to monitor financial flows and program efficiency in real-time.
🇨🇩 The Challenge: Financial Transparency Across 26 Provinces
The DRC's health system is vast and decentralized. Before this solution, the Ministry faced several critical gaps:

Fragmented Data: Expenditure data was siloed within different programs and provinces.

Invisible Deficits: Identifying which provinces were under-funded or over-budget required weeks of manual report consolidation.

Efficiency Gaps: No easy way to compare the "cost-vs-impact" of programs between different regions.
🛠 Technical Solution
I built a robust web-based GIS using a modern Python stack to ensure scalability and ease of use for non-technical officials.

Core Stack:
Backend: Django (Python) for secure, rapid development and robust API management.

Database: PostgreSQL with PostGIS extension for handling spatial data and provincial coordinates.

Frontend GIS: Interactive map rendering with filters and dynamic legends.

Data Layer: Custom ETL scripts to aggregate spending data from various health programs.
Key Features:
Interactive National Map: A dynamic map of the DRC allowing users to click on any province to view detailed financial data.

Advanced Filtering: Filter expenditures by program type, funding source, or time period (quarterly/annually).

Deficit Detection: Automated highlighting of provinces experiencing funding shortages or critical program delays.

One-Click Reporting: Instantly generate provincial summaries for ministerial briefings.
Impact & Results
Resource Rationalization: Enabled the Ministry to reallocate funds to deficit provinces based on real-time data visualizations.

Increased Efficiency: Reduced the time needed for national budget evaluation from months to seconds.

Transparency: Provided a "Single Source of Truth" for all international and national health program expenditures.
Technical Showcase
[!IMPORTANT]

Privacy Note: Screenshots below use anonymized figures to comply with Ministry data security protocols
<img width="1880" height="868" alt="Image" src="https://github.com/user-attachments/assets/0f45ba6b-5450-4aae-9933-3b4d6ffa21ec" />
<img width="1904" height="877" alt="Image" src="https://github.com/user-attachments/assets/ad73100d-03fb-489e-94fa-06dcd0441275" />
<img width="1908" height="873" alt="Image" src="https://github.com/user-attachments/assets/08da6b05-7d45-4109-8d6f-029d54e2401d" />
<img width="1905" height="868" alt="Image" src="https://github.com/user-attachments/assets/5c3caf25-570c-43ca-b0ff-aafef632d924" />
Repository Structure
/backend: Django project structure (Models, Views, GIS Logic).

/spatial_data: GeoJSON/Shapefiles for DRC provincial boundaries.

/docs: Functional specifications and user manual for Ministry staff.

/screenshots: UI/UX walk-throughs.
📫 Contact
For inquiries regarding GIS implementation for public governance or health-tech:
Alpha Mubay - lucmubay@gmail.com
