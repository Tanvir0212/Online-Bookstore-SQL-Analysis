<img width="1598" height="836" alt="home" src="https://github.com/user-attachments/assets/45549568-b2fd-4241-9d65-e719734d1302" />

# Project Insights & Recommendations

---

## Executive Summary

This report presents key findings and strategic recommendations derived from SQL analysis of the Online Bookstore database, covering 500 books, 500 customers, and 500 orders. Total revenue stands at **$75,628.66** across all transactions, with a healthy inventory of **25,056 units** in stock.

**Key Performance Indicators:**
| Metric | Value |
|---|---|
| Total Books in Catalog | 500 |
| Total Customers | 500 |
| Total Orders | 500 |
| Total Revenue | $75,628.66 |
| Total Stock Available | 25,056 units |
| Avg Remaining Stock per Book | 44.7 units |
| Books with Zero/Negative Stock | 36 |
| Repeat Customers (2+ Orders) | 139 (27.8%) |

---

## 1. Sales Performance by Genre

Mystery leads all genres in units sold, followed closely by Science Fiction and Fantasy. Fiction and Biography trail significantly.

| Genre | Units Sold | Revenue | Revenue Rank |
|---|---|---|---|
| Mystery | 504 | $12,788.45 | #2 |
| Science Fiction | 447 | $11,770.51 | #3 |
| Fantasy | 446 | $11,238.38 | #5 |
| Romance | 439 | $13,086.98 | #1 |
| Non-Fiction | 351 | $11,603.06 | #4 |
| Biography | 285 | $7,870.06 | #6 |
| Fiction | 225 | $7,271.22 | #7 |

**Key Insights:**
- Romance generates the highest revenue ($13,086.98) despite ranking 4th in units sold — indicating higher average prices.
- Mystery dominates in volume (504 units) but sits behind Romance in revenue, suggesting competitive pricing.
- Fiction and Biography are underperformers in both volume and revenue and warrant strategic attention.


## 2. Inventory & Stock Health

36 books have zero or negative remaining stock after fulfilling all orders, roughly 7.2% of the catalog.

**Key Insights:**
- 36 titles are out of stock after order fulfillment, representing missed sales and potential customer dissatisfaction.
- Average remaining stock is 44.7 units, suggesting overall healthy inventory but unevenly distributed.
- The book with the lowest stock (0 units) should be flagged for urgent restocking.
- The most expensive book ("Proactive system-worthy orchestration" at $49.98, Mystery) should be closely monitored.


## 3. Customer Analysis

139 out of 500 customers (27.8%) have placed at least 2 orders. The top spender, Kim Turner (Customer #457), spent $1,398.90.

| Metric | Value |
|---|---|
| Repeat Customers (2+ Orders) | 139 (27.8%) |
| Top Spender | Kim Turner — $1,398.90 |
| Customers from Canada | 3 |
| Orders Exceeding $20 | 473 out of 500 (94.6%) |

**Key Insights:**
- 94.6% of all orders exceed $20, confirming strong average order value.
- Canada has only 3 customers, a major untapped market opportunity.
- High-value customers like Kim Turner warrant a dedicated VIP loyalty program.


## 4. Fantasy Genre Deep Dive

Fantasy ranks 3rd in units sold but 5th in revenue, with an average price of $25.98.

| Title | Price |
|---|---|
| Stand-alone content-based hub | $49.90 |
| Innovative 3rd-generation database | $49.23 |
| Optimized even-keeled analyzer | $48.97 |

**Key Insights:**
- Fantasy's average price ($25.98) is mid-range, with room to introduce premium titles to lift revenue.
- Strong unit sales suggest a loyal readership that can be further monetized.


## 5. Top Author Performance

| Author | Total Units Sold |
|---|---|
| Patrick Contreras | 28 |
| Melissa Taylor | 27 |
| Emily James | 24 |
| Thomas Trujillo | 24 |
| Valerie Moore | 23 |


## 6. Strategic Recommendations

**A. Inventory Management**
- Immediately restock the 36 out-of-stock titles, prioritizing Mystery and Science Fiction.
- Set automated low-stock alerts at 10 units to prevent future stockouts.
- Conduct seasonal demand forecasting, November 2023 saw 25 orders, suggesting holiday surges.

**B. Revenue Growth**
- Introduce premium pricing for Romance titles, which show price-inelastic demand.
- Bundle slow-moving Fiction and Biography titles with popular genres to increase turnover.
- Expand the Fantasy catalog with higher-priced titles to close the gap between its unit sales rank (#3) and revenue rank (#5).

**C. Customer Retention & Acquisition**
- Launch a VIP loyalty program targeting the 139 repeat customers.
- Personalize marketing to high-spenders like Kim Turner with tailored recommendations.
- Run a Canada-focused campaign, the market is essentially untapped with only 3 customers.
- Offer subscription or bulk purchase discounts to encourage larger orders.

**D. Author & Content Strategy**
- Negotiate promotional campaigns with top authors like Patrick Contreras and Melissa Taylor.
- Consider expanding into new genres such as Thriller, Self-Help, or Children's books.
- Invest in contemporary titles, books published after 1950 make up 58.4% of the catalog, aligning with modern reader preferences.





