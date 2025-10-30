## 🧮 Issue Severity and Impact Analysis

| Issue Category   | Frequency | High | Medium | Low | Severity Weight (avg) | Impact Score |
|------------------|------------|------|---------|-----|-----------------------|--------------|
| Integration       | 9 | 6 | 3 | 0 | **2.7** | **24.3** |
| Technical Issue   | 8 | 4 | 4 | 0 | **2.5** | **20.0** |
| Analytics         | 6 | 2 | 4 | 0 | **2.3** | **13.8** |
| Notification      | 5 | 2 | 3 | 0 | **2.4** | **12.0** |
| Payment           | 5 | 3 | 2 | 0 | **2.6** | **13.0** |
| Data Sync         | 4 | 2 | 2 | 0 | **2.5** | **10.0** |
| Billing Issue     | 3 | 2 | 1 | 0 | **2.7** | **8.1** |
| Login/Access      | 3 | 3 | 0 | 0 | **3.0** | **9.0** |
| Feature Request   | 3 | 0 | 0 | 3 | **1.0** | **3.0** |
| Account Settings  | 3 | 0 | 3 | 0 | **2.0** | **6.0** |

**Method**

| IF(B2>=8,"High",IF(B2>=4,"Medium","Low"))|
| **Severity Weight (avg)** | = ((High × 3) + (Medium × 2) + (Low × 1)) / Frequency |
| **Impact Score** | = Frequency × Severity Weight (avg) |

**Key insights**

- **Integration** and **Technical Issues** have the highest overall impact.  
- **Feature Requests** are frequent but low in severity.  
- Focus on **Integration** and **Payment** for root cause analysis.

