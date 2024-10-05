# Power-BI-Marathon-Project
This project is about a manufacturing company that receives and orders for raw materials for production or general maintenance for year 2018 and 2019.
# Brief Introduction
Enterprise Manufacturers Limited aim to reduce the downtime and cost caused by the raw materials received and ensure that they are of good quality. The company did not have any procurement team to look into this but has a programme management team that managed to gather data from across the plants with information around the material, defect and vendor. So, I have been tasked as an analyst to help visualize and extrapolate the findings from this data using Power BI. 
## Brief Overview of the dataset
Data was provided by Tina Okonkwo. The dataset is structured and contains 1 table in excel format. It contains 9 columns which consist of: Date, Vendor, Plant Location, Material Type, Category, etc. With 5,226 rows. Also, the dataset is easily understandable. 
## Problem Questions
*  Which vendors/plants are causing the greatest defect quantity? 
*  Which vendors/plants are causing the greatest downtime?
*  Is there a particular combination of material and vendor that perform poorly?
*  Is there a particular combination of Vendor and plant that performs poorly?
*  What is the trend of the categories with the most defect quantities?
## Tool used
Power BI
## Processes
*  Imported the excel file into Power BI.
*  Used Power Query for data cleaning, data transformation, and data modelling.
*  Created DAX measures for data analysis.
*  Data visualization
*  Report Design

## Key Insights
*  Here are some **Key Performance Indicators** from the analysis.
![Screenshot (323)](https://github.com/user-attachments/assets/f75bb378-b881-49d3-9944-c009bc03b8b3)

*  The Vendors causing the greatest defect quantities are Yombu, Avamm, and Meejo – they account for **1.7%** of the total defect quantities **(approx. 2.6 billion)**. While the Plants are Hingham, Charles City, and Twin Rocks – these account for **11%** of the total. 
![Screenshot (324)](https://github.com/user-attachments/assets/b937a42b-fa86-4b22-92cf-d85db825a2ea)
![Screenshot (325)](https://github.com/user-attachments/assets/5441d846-ee6e-4e83-8b36-556a9875aa8d)

*  The Vendors causing the greatest downtime are Avamm, Izio, and Meetz – having an aggregation of **3,446 hours** of the total downtime **(approx. 216,000 hours)**. While the Plants are Riverside, Charles City, and Twin Rocks – with a sum of **24,882 hours** of the total.
![Screenshot (326)](https://github.com/user-attachments/assets/307a60c1-ec69-43f7-a69a-14849e385da7)
![Screenshot (327)](https://github.com/user-attachments/assets/2c7d67c5-e30f-49c4-8317-e2cb4855207b)

*  The combination of **Corrugate material** and **Feedfire Vendor** performed poorly with a total downtime of **568.23 hours**.
![Screenshot (329)](https://github.com/user-attachments/assets/980ca59e-dbc9-4cdb-9895-e8bf17a47785)

*  The combination of Wikido Vendor and Middletown Plant performed poorly with a total downtime of **244.95 hours**.
![Screenshot (330)](https://github.com/user-attachments/assets/a26bc5c9-d421-4cf0-9566-7782dddec62e)

*  There has been an upward monthly trend for **Mechanicals** and **Logistics** categories over the past years (2018 and 2019).
![Screenshot (331)](https://github.com/user-attachments/assets/1427113e-c5ac-42ae-9846-7ae6f57873ea)


## Recommendation
I would suggest that Enterprise Manufacturers Limited should perform regular supplier audits for Vendors such as Yombu, Avamm, Meejo, and Feedfire to ensure they are meeting quality standards. 

Also, the company should renegotiate contracts with Vendors like Avamm, Izio, and Meetz (who cause significant downtime) to include penalties for defective materials or excessive downtime.

Moreso, the company should prioritize reducing downtime for the Corrugate material from Feedfire, as it has the highest – 568.23 hours, by investigating alternative suppliers for this material and work on improving its quality control.

Lastly, Enterprise should consider incentivizing high-performing Vendors by offering long-term contracts or increased order volumes to those with minimal defects and downtime.






 




 












