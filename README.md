# Winter 2022 Data Science Intern Challenge

For proper formatting, please view the notebook using Jupyter nbviewer at this [**link**](https://nbviewer.jupyter.org/github/nefrank/Shopify-Technical-Challenge-Winter2022/blob/main/Intern-Challenge-Winter-2022.ipynb?flush_cache=true "Noah Frank Intern Challenge - nbviewer.jupyter.org"). 

## Question 1 Answers

**a) Think about what could be going wrong with our calculation. Think about a better way to evaluate this data.**

What was wrong in the naive average order value calculation was that the mean was heavily skewed due to a few extreme outliers. A better way to evaluate the data would be to recalculate the mean with the outliers removed, or to use a different metr

**b) What metric would you report for this dataset?**

For this dataset, I would report the **median order value (MOV)**. The median is much less succeptible to the effects of large outliers. In addition, once the outliers were removed, the new median was **\$280.00**, compared to the original median of **\$284.00**. This shows that we could have simply reported the original **MOV** instead of the **AOV**.

**c) What is its value?**

The value of the reported metric, the **median order value** is **\$284.00** from the original dataset.

## Question 2 Answers

**a) How many orders were shipped by Speedy Express in total?**

**Speedy Express** shipped **54** orders in total.

**b) What is the last name of the employee with the most orders?**

The last name of the employee with the most orders is **Peacock** with **40** orders.

**c) What product was ordered the most by customers in Germany?**

The most ordered product by german customers was **Boston Crab Meat** with **160** total units ordered.
