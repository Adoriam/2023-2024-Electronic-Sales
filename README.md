# 2023-2024-Electronic-Sales
Trends for 2023/2024 Electronic Sales on Gender and Payment methods

While credit cards are a popular payment method, concerns about security persist. Compared to credit cards, PayPal and bank transfers are often perceived as safer options for online transactions. The increasing threat of credit card fraud reinforces the preference for these alternative methods. Although cash and card payments may be quicker, prioritizing security through PayPal and bank transfers is advisable.

According to the pivot table, women tend to use cash and debit cards more frequently than men. This suggests that a significant percentage of women prefer cash transactions over other payment methods.

I started by importing the required libaries in my Jupyter Notebook.
 
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

I downloaded the 2023/2024 electronic sales CSV file from Kaggle and uploaded it to Jupyter Notebook.
data = pd.read_csv()

I displayed the first few rows of the dataset.
print(data.head())
![Screenshot 2024-10-25 at 7 07 02 AM](https://github.com/user-attachments/assets/ab1f30f6-7059-41f5-afe1-6f474814d778)


Using seaborn and Matplotlib, I created a data visualization of Payment Methods by Gender.
sns.barplot(data=data, x='Payment Method', hue='Gender')
plt.xlabel('Payment Method')
plt.ylabel('Gender')
plt.title('Payment Method by Gender')
plt.show()

![Screenshot 2024-10-25 at 9 01 38 AM](https://github.com/user-attachments/assets/4bf98d22-2855-41c3-b62a-e54935c0a90f)


 In conclusion, I used Power BI to create a standard visual.
 ![Screenshot png](https://github.com/user-attachments/assets/c1a17406-4b96-4207-a513-35a40b505c56)
