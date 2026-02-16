# CallMeMaybe: Operator Efficiency Analysis 📞📊

## 📝 Project Description
This project was developed for **CallMeMaybe**, a virtual telephony provider. The primary objective is to provide supervisors with an analytical tool to identify underperforming call center operators.

An operator is classified as **inefficient** if they exhibit:
* A high volume of missed incoming calls.
* Excessive wait times for customers.
* A low number of outgoing calls (in profiles where this is their primary function).

## 🚀 Repository Structure
* `Proyecto_Final.ipynb`: Jupyter Notebook containing the full analysis (EDA, processing, and conclusions).
* `telecom_dataset_us.csv`: Call data (dates, duration, direction, etc.).
* `telecom_clients_us.csv`: Information regarding tariffs and clients.

## 🛠️ Methodology
The analysis follows these steps:
1. **Data Preprocessing:** Cleaning duplicates, managing missing values (specifically in operator IDs), and data type conversion.
2. **Exploratory Data Analysis (EDA):** Identifying behavior patterns in both incoming and outgoing calls.
3. **Metric Definition:** Establishing thresholds to measure inefficiency (wait times vs. effectiveness).
4. **Segmentation:** Classifying operators into specific profiles (e.g., "Perfectionists" vs. "Overloaded").

## 📈 Key Results
* **273 critical operators** were identified as requiring intervention.
* The average missed call rate detected is **31.55%**.
* **Profile Segmentation:**
    * **Type A (Slow/Perfectionists):** Low response time but high resolution.
    * **Type B (Impatient/Overloaded):** High customer call abandonment rates.

## 💻 Technologies Used
* **Python 3.x**
* **Pandas & Numpy:** Data manipulation and cleaning.
* **Matplotlib & Seaborn:** Data visualization and statistical charting.
* **Jupyter Notebook:** Development environment.

## 💡 Recommendations
Based on the findings, the project suggests:
* **Technical Training:** For operators with high wait times.
* **Workload Review:** For those with a high rate of missed calls.
* **KPI Monitoring:** Implementing a dashboard based on the results of this analysis.

---
*Developed as a final Data Analysis project.*
