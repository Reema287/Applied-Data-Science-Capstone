# 🚀 SpaceX Launch Records Dashboard

An interactive data visualization dashboard built using **Dash** and **Plotly** to explore the launch performance of SpaceX rockets. This dashboard provides insights into successful launches, payload mass distribution, and launch site effectiveness.

---

## 📊 Dashboard Features

- Dropdown menu to filter by **launch site**
- Pie chart showing **success counts** (by site or overall)
- Interactive **range slider** to filter **payload mass (kg)**
- Scatter plot showing **payload vs. success outcome**
- Fully responsive and interactive layout

---

## 🗂 Dataset

- **File:** `spacex_launch_dash.csv`
- **Source:** Provided as part of the IBM Data Science Capstone Project
- **Key Columns:**
  - `Launch Site`: Name of the launch location
  - `Payload Mass (kg)`: Weight of payload
  - `class`: Binary outcome (1 = success, 0 = failure)
  - `Booster Version Category`: Type of booster used


---

## 🏁 Getting Started

### 🔧 Prerequisites

Make sure you have Python 3 and pip installed.

```bash
pip install pandas dash plotly```



##📌 Appendix
Built on IBM Skills Network Labs environment

Port 8060 used for deployment in the lab environment

Supports extension with real-time APIs or geospatial visualizations



##🙌 Acknowledgements
IBM Skills Network

SpaceX for public launch data

Plotly Dash Community
