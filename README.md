# 🧩 LeetCode SQL Solutions

A curated collection of SQL solutions to LeetCode database problems — clean, well-structured, and organized by problem number for easy navigation.

---

## 📂 Repository Structure

Each problem lives in its own folder, named `{problem-number}-{problem-slug}`, containing the SQL solution file.

```
leetcode/
├── 176-second-highest-salary/
├── 178-rank-scores/
├── 181-employees-earning-more-than-their-managers/
├── 577-employee-bonus/
├── 584-find-customer-referee/
├── 595-big-countries/
├── 1153-product-sales-analysis-i/
├── 1258-article-views-i/
├── 1509-replace-employee-id-with-the-unique-identifier/
├── 1724-customer-who-visited-but-did-not-make-any-transactions/
├── 1801-average-time-of-process-per-machine/
├── 1827-invalid-tweets/
└── 1908-recyclable-and-low-fat-products/
```

---

## 📋 Problems Solved

| # | Problem | Difficulty | Topics |
|---|---------|------------|--------|
| 176 | [Second Highest Salary](./176-second-highest-salary) | Medium | Subquery, NULL handling |
| 178 | [Rank Scores](./178-rank-scores) | Medium | Window Functions, DENSE_RANK |
| 181 | [Employees Earning More Than Their Managers](./181-employees-earning-more-than-their-managers) | Easy | Self JOIN |
| 577 | [Employee Bonus](./577-employee-bonus) | Easy | LEFT JOIN, NULL |
| 584 | [Find Customer Referee](./584-find-customer-referee) | Easy | WHERE, NULL handling |
| 595 | [Big Countries](./595-big-countries) | Easy | WHERE, OR |
| 1153 | [Product Sales Analysis I](./1153-product-sales-analysis-i) | Easy | JOIN |
| 1258 | [Article Views I](./1258-article-views-i) | Easy | Self-reference, ORDER BY |
| 1509 | [Replace Employee ID With The Unique Identifier](./1509-replace-employee-id-with-the-unique-identifier) | Easy | LEFT JOIN |
| 1724 | [Customer Who Visited But Did Not Make Any Transactions](./1724-customer-who-visited-but-did-not-make-any-transactions) | Easy | LEFT JOIN, NULL |
| 1801 | [Average Time of Process per Machine](./1801-average-time-of-process-per-machine) | Easy | Self JOIN, AVG |
| 1827 | [Invalid Tweets](./1827-invalid-tweets) | Easy | String Functions, LENGTH |
| 1908 | [Recyclable and Low Fat Products](./1908-recyclable-and-low-fat-products) | Easy | WHERE, AND |

---

## 🛠️ Topics Covered

- **JOINs** — INNER, LEFT, and self-joins
- **Aggregations** — GROUP BY, HAVING, AVG, COUNT
- **Window Functions** — RANK, DENSE_RANK
- **Subqueries** — Nested SELECT statements
- **String Functions** — LENGTH, CHAR_LENGTH
- **NULL Handling** — IS NULL, IS NOT NULL, IFNULL, COALESCE
- **Filtering** — WHERE, AND, OR conditions

---

## 🚀 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/poojachalla-dev/leetcode.git
   ```
2. Navigate to any problem folder and open the `.sql` file.
3. Copy the query into the LeetCode SQL editor for that problem and run it.

> **Note:** All solutions are written in MySQL unless otherwise noted.

---

## 🤝 Contributing

Found a better approach or a bug? Feel free to open an issue or submit a pull request. All improvements are welcome!

---

*Happy querying! 🎯*
