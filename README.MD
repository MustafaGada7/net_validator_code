GMNS Network Readiness Validator Script:
This Python script automates the validation of GMNS-compatible transportation network datasets across multiple directories. It uses the GMNS_Plus_Readiness_Validator library to check the readiness of each network up to Level 7 validation, including node.csv, link.csv, and optionally demand.csv.

Features:

- Recursively scans for folders containing link.csv files.

- Auto-detects required input files.

- Executes validation logic and generates structured reports in JSON.

- Skips backup, hidden, and irrelevant folders automatically.

📁 Example use: validate networks under /networks/I-17 with one command.

🛠️ Ideal for researchers and engineers preparing GMNS data for simulation or integration.
