# 📊 Claims & Policyholder Risk Analysis Dashboard  

## Purpose  
Identify high-risk policyholders, track claims trends, and analyze policy adjustments.  

## 🔹 Key Metrics  
- **Total Claims**: `SUM(Claims_Frequency)`  
- **Average Claims per Policyholder**: `AVERAGE(Claims_Frequency)`  
- **Claim Severity Distribution**: Low / Medium / High  
- **Claims Adjustment Impact**: `SUM(Claims_Adjustment)`  

## 📈 Visuals  
- **Bar Chart**: Claims Frequency by Age Group or Region  
- **Heatmap**: Claim Severity by Region  
- **KPI Cards**:  
  - Total Claims  
  - Average Claim Amount  
  - `Average Claim Amount = DIVIDE(SUM(‘synthetic_insurance_data'[Claims_Adjustment]), SUM(‘synthetic_insurance_data'[Claims_Frequency]), 0)`  
- **Scatter Plot**: Premium Amount vs. Claims Frequency  

## 🎯 Filters  
- Policy Type  
- Region  
- Age Group  
- Marital Status  
