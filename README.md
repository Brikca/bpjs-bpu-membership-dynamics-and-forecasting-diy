# BPJS BPU Membership Dynamics and Forecasting (DIY)

## Overview

This project analyzes the **dynamics and forecasting of active Bukan Penerima Upah (BPU) membership** in **BPJS Ketenagakerjaan, Yogyakarta Special Region (DIY)**, using monthly data from **January 2016 to July 2025**.

The analysis focuses on understanding **long-term trends**, **short-term fluctuations**, **participant retention issues**, and **future projections** using **time series analysis**, particularly the **ARIMA (Autoregressive Integrated Moving Average)** model.

This project was developed as part of **Kerja Praktik (Internship Program)** in the **Statistics Undergraduate Program, Faculty of Mathematics and Natural Sciences, Universitas Gadjah Mada**, and is presented here as a **data analytics portfolio project**.

---

## Objectives

* Analyze the **trend and pattern** of active BPU membership over time
* Measure **membership dynamics** using:

  * Net Growth
  * Churn Rate
* Identify the **best ARIMA model** for BPU membership data
* Generate **short-term forecasts** to support policy and strategic planning

---

## Data Description

* **Type**: Secondary data
* **Frequency**: Monthly
* **Period**: January 2016 – July 2025
* **Variable**: Number of active BPU participants
* **Source**: BPJS Ketenagakerjaan – Yogyakarta Branch Office

> ⚠️ Note: Due to data confidentiality, raw data is not publicly shared.

---

## Methodology

1. **Descriptive Analysis**
   - Visualization and summary statistics to identify overall patterns and fluctuations

2. **Membership Dynamics Analysis**

   - Net Growth (monthly participant change)
   - Churn Rate (participant loss indicator)

3. **Time Series Modeling (ARIMA)**

   - Stationarity testing
   - ACF & PACF analysis
   - Model estimation and selection
   - Residual diagnostics (Box-Jenkins procedure)

4. **Forecasting**
   - Projection of future BPU membership levels based on the best-performing model

---

## Key Results

* BPU membership shows **long-term increasing trends** with notable short-term fluctuations  
* Net growth and churn rates vary significantly, influenced by **observed economic conditions** and **income stability of informal workers**  
* **ARIMA(0,1,3)** was selected as the **best model**, based on information criteria and diagnostic tests  
* Forecast results indicate **potential future growth**, with moderate uncertainty  

---

## Tools & Technologies

* R (Google Colab)
* tidyverse (dplyr, ggplot2, tidyr, readr)
* forecast (ARIMA, time series modeling)
* readxl (import/export Excel data)

---

## Repository Structure

```
├── Analisis_Data_Kepesertaan_BPU_BPJS_TK_DIY.ipynb
├── README.md
```

---

## Author

**Brikca Kristal Desfingka**
Undergraduate Student – Statistics
Universitas Gadjah Mada

---

## Related Links

* [Google Colab Notebook](https://colab.research.google.com/drive/1oZN3uDN71MUJr1FeKEYCfNAdlht9QDw5?usp=sharing)
* GitHub Profile: [https://github.com/Brikca](https://github.com/Brikca)

---

## Notes

This project is intended for **academic and portfolio purposes**. Insights derived from this analysis are expected to support **data-driven decision-making** in social security and informal labor protection policies.
