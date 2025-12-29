**📉 Customer Churn & Retention Strategy Dashboard**
**📌 Project Overview**
Customer churn is one of the most critical metrics for subscription-based businesses. This project utilizes **Power BI** to perform a deep-dive analysis into customer behavior, identifying the **root causes of attrition**. By mapping demographics against contract types and service usage, the dashboard provides a roadmap for reducing churn and protecting recurring revenue.

**🛠️ Technical Stack**
**Analytics Tool: Power BI Desktop**

**Data Engineering: Power Query** (ETL, advanced data cleaning, and normalization of categorical variables).

**Data Modeling:** Implementation of a **Star Schema** with dedicated Fact and Dimension tables for optimized performance.

**DAX Scripting:** Developed complex measures for **Churn Rate %**, **Retention Rate**, and **Month-over-Month (MoM) churn growth**.

**🔍 Key Business Questions Addressed**
**The Bottom Line:** What is the current **Churn Rate**, and how has it trended over the last quarter?

**Risk Profiling:** Which segments **(Age, Gender, Tenure)** are most susceptible to leaving?

**Contractual Impact:** How do **Month-to-Month** vs. **Long-term contracts impact** customer loyalty?

**Service Correlation:** Are specific service gaps (e.g., lack of Tech Support) driving customers away?

**📈 Dashboard Features**
**Executive Summary:** High-level KPI cards for **Total Customers**, **Churn Count**, and **Estimated Revenue Leakage**.

**Demographic Deep-Dive:** Visual breakdown of churn by seniority, partner status, and dependents.

**Account Analysis:** Correlation analysis between **Payment Methods**, **Paperless Billing**, and tenure.

**Risk Assessment Matrix:** A specialized view to identify **"At-Risk"** customers based on low tenure and high monthly charges.

**💡 Strategic Business Insights**
**The "Month-to-Month" Trap:** Customers on short-term contracts represent the **highest churn risk**, contributing to nearly 60% of total attrition.

**The Critical Window:** Analysis shows a significant **"Early Churn"** trend within the first **6 months** of the customer lifecycle.

**Value-Added Services:** Customers without **Online Security** or **Tech Support** services churn at a **20% higher rate**, suggesting that bundling these services could improve retention.

**📂 Project Structure**
**Churn Data Analytics.pbix —** **The Core Power BI File** (Interactive Dashboard).

**Data/ —** Source dataset containing subscriber transaction history.

**Screenshots/ —** High-resolution images of the **Executive** and **Risk Analysis pages**.

**🚀 How to Use**
**Clone** this repository.

Open the .pbix file in **Power BI Desktop**.

Use the **Contract Type** and **Tenure** slicers to see how specific variables influence the churn probability.
