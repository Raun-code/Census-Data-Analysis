
# **Mock Census Data Analysis – Real-World Data Science Project**

This repository contains my full analysis and recommendations based on a simulated census dataset, designed as a real-world application of data cleaning, exploration, and decision-making using data science principles. The goal of this project is to provide data-driven guidance to a fictional local government in the UK regarding urban development and public investment.

---

## 🏙️ **Project Overview**

Every ten years, the UK conducts a population census to support effective policy development and resource allocation. For this project, a **mock census** was created using the **Python Faker library**, structured similarly to the historic **1881 UK census**, but including some modern adaptations (e.g., current job titles, religions).

As part of a **local government advisory team**, I was tasked with:

1. Cleaning and analysing the mock census data.
2. Identifying key demographic, social, and occupational trends.
3. Making a recommendation for how to **develop an unoccupied plot of land** in the town.
4. Recommending **an area of public investment** based on population needs.

---

## 📋 **Data Features**

The dataset mimics a household-level census and includes the following columns:

* `Street Number` – Identifies unique dwellings.
* `Street Name` – Location within the town.
* `First Name`, `Surname` – Names of occupants.
* `Age` – Age of each person in the household.
* `Relationship to Head` – Defines family/household hierarchy.
* `Marital Status` – (Single, Married, Divorced, Widowed, N/A for minors).
* `Gender` – (Male or Female, reflecting 1881 conventions).
* `Occupation` – Reflects a modern job title list.
* `Infirmity` – Includes conditions such as blindness or mental illness.
* `Religion` – Includes real-world religions, for diversity analysis.

---

## 🧹 **Data Cleaning & Preprocessing**

Before analysis, the data required extensive cleaning:

* Identified and handled **missing values** and **outliers**.
* Corrected **invalid or inconsistent categories**.
* Standardised textual entries (e.g., occupations, relationships).
* Verified **data integrity across households** and **age-based rules** (e.g., minors not being heads of households).

This stage was critical for ensuring that the downstream analysis was valid, trustworthy, and meaningful.

---

## 🎯 **Objectives and Analytical Focus**

### 🔧 Development Proposal for a Plot of Land

A currently vacant area in the town is slated for development. Options include:

* High-density housing (for expanding populations)
* Low-density/family housing (for affluent residents)
* A train station (to support commuting populations)
* A religious building (to support growing religious diversity)
* A minor emergency medical facility (based on future health needs)
* Any other infrastructure supported by the data

The selected option had to be justified with evidence from the data, based on a comprehensive analysis of:

* **Population growth and age pyramid**
* **Household size and occupancy rates**
* **Religious affiliation trends**
* **Prevalence of health conditions and pregnancy indicators**
* **Commuter occupations or student presence**

---

### 💸 Recommendation for Public Investment

The second goal was to recommend one area for increased public spending, choosing between:

* **Employment and training** (for areas of high unemployment)
* **Old age care** (based on aging population trends)
* **Education and schooling** (to meet needs of younger families or new births)
* **General infrastructure** (if overall population growth is observed)

Each of these was evaluated using statistical insights, such as:

* **Unemployment rates by age group**
* **Number and distribution of school-aged children**
* **Projected retirement trends**
* **Overall population density and distribution**

---

## 📊 **Analysis Techniques**

Key techniques applied throughout the analysis:

* **Descriptive statistics** (mean, median, mode, distributions)
* **Data visualisation** using Matplotlib/Seaborn (age pyramids, bar charts, heatmaps)
* **Occupational analysis** to identify potential commuters
* **Household analysis** to examine family structures and housing pressure
* **Religious demography** to evaluate demand for faith-based facilities
* **Trend identification** based on age, gender, and occupation combinations

Where applicable, statistical reasoning or basic **hypothesis testing** was used to support the findings.

---


## 🧪 Tools & Libraries Used

* **Python 3.x**
* **Pandas** for data manipulation
* **NumPy** for numerical operations
* **Seaborn** and **Matplotlib** for data visualisation
* **Faker** (used to generate the original dataset)
* **Jupyter Notebook** for interactive analysis

---

## 📌 Key Outcomes

* Proposed the **best-suited development** for the available land, backed by data.
* Recommended a **priority investment area** for public funds.
* Delivered **cleaned datasets**, **visual reports**, and a **written justification** of all decisions using real-world data science practices.

---

