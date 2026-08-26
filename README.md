Project Title: Sales Analysis Dashboard

Business Problem: Why is overall profit margin only 12.5% despite $2.3M in revenue?

Questions answered :
 <br>1 Which product categories and sub-categories are losing money, and by how much?
 <br>2 Is discounting helping sales volume, or is it actively destroying profit margin?
 <br>3 Which regions are underperforming in profitability — not just in revenue?
 <br>4 Which customer segment is most valuable to prioritize for growth?
 <br>5 What are the top products to promote and which ones should be reviewed or discontinued?
 <br>6 Is revenue growth translating into proportional profit growth year over year?

Data Source: Data set form open source https://www.kaggle.com/datasets/vivek468/superstore-dataset-final/data

Key Insights: 
<br>1.Tables sub-category loses money. $207K in sales but −$17.7K in profit — a −8.6% margin. Bookcases also lose money at −3.0%. Furniture as a whole is the weakest category.

2.Discounts over 20% are toxic. Orders with 30%+ discount produce a −48.2% margin, destroying $125K in profit. Zero-discount orders hold a healthy 29.5% margin.

3.Central region is the weakest. Only 7.9% profit margin vs. West at 14.9%. Central generates $501K revenue but keeps just $39.7K — a $70K gap vs. the West on far higher revenue.

4.Copiers are the profit engine. 37.2% margin — the highest of any sub-category. The Canon imageCLASS 2200 alone generated $25.2K profit, making it the single best product in the dataset.

5.Home Office is most efficient. Smallest segment by revenue ($430K) but highest margin at 14.0%. Consumer segment is largest but least efficient at 11.5%.

6.Revenue grows, margin stagnates. Revenue rose 52% from 2011 to 2014, but margin only moved from 10.2% to 12.7% — a sign that growth is not translating into proportional profit.


Query Previews:
<br>

Duplicate search quarry <br>
<img width="483" height="345" alt="Dublicates check" src="https://github.com/user-attachments/assets/25c016de-85ce-415d-8d5a-824b09bb8381" />
<br>
Duplicates exsistance proof<br>
<img width="643" height="243" alt="Duplicate proof1" src="https://github.com/user-attachments/assets/4d078253-f387-414a-9c21-37a758cf189c" />
<br>
Checking for missing values<br>
<img width="662" height="400" alt="missing data" src="https://github.com/user-attachments/assets/ac0e4de1-0d20-471b-94d0-5f48c86ef013" />
<br>
<h2>1.Which product categories and sub-categories are losing money, and by how much?</h2>
<img width="946" height="948" alt="Y to Y dynamics Cats and sub Cats" src="https://github.com/user-attachments/assets/0e56effd-e6bf-464e-9c40-a7c3fd655352" />
<br>
<h2>2.Is discounting helping sales volume, or is it actively destroying profit margin?</h2>
<br>
 Discount band data shows profits according different discount categories
 <br>
 <img width="619" height="530" alt="discount groups data" src="https://github.com/user-attachments/assets/f78fdc6f-e43d-4647-b15d-53a619f3cad0" />
 <br>Discounting is not helping volume enough to compensate — it is actively destroying profit. The break-even is somewhere between 20–21%. Any discount above 20% costs the business money on every single order.
 <br>
 <h2>3 Which regions are underperforming in profitability — not just in revenue?</h2>
 <br>
 <img width="686" height="479" alt="Profits margin by region" src="https://github.com/user-attachments/assets/d98d7944-332a-4fd5-bc1c-a455d970db21" />
 <br>Central is the outlier — it ranks 3rd in revenue but dead last in margin, nearly half the West's rate.
 <br>
<h2>4 Which customer segment is most valuable to prioritize for growth?</h2><br>
Profit by segment<br>
<img width="1019" height="441" alt="profit by segment" src="https://github.com/user-attachments/assets/86c08c63-016c-4ba6-80a1-6301645c4c46" />
<br>
Profit by Category in Segment<br>
<img width="695" height="487" alt="profit by segment and category" src="https://github.com/user-attachments/assets/36268094-c4f0-4e90-b41d-89279d42566a" />
<br>







