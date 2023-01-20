# Optimization of Sending Postal Parcels
![python 3.10.7](https://img.shields.io/pypi/pyversions/pandas?color=green&label=python)
![pandas 1.5.2](https://img.shields.io/badge/pandas-1.5.2-blue)
![sqlite](https://img.shields.io/badge/sqlite-3.37.2-brightgreen)

### **Introdution**
This project looks like a template for analyzing the work of postal companies. Here, analysis methods will be analyzed using the built-in DBMS - "sqlite", which is easily interpreted for other DBMS. The project will consist of several goals that will help find ways to optimize the workflow of postal companies.

### **The designation of columns in the datasets:**
1. Aggregated information about postal parcels:
- parcel_id — unique ID of the parcel;
- accept_date — accept the date of the parcel;
- index_id — the postcode where the parcel was accepted;
- weight — parcel weight in grams;
- price — the tariff paid for sending the parcel in cents;
- client_type — type of client (individual, legal entity).
2. Information about objects:
- index_id — the postcode;
- area — area where there is the post office;
- population — the popelation of the locality in which the post office is located.