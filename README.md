# FINAL-PR-DATA-INTELLIGENCE-DASHBOARD
<!-- ✦ Data Intelligence Dashboard • README ✦ -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,19,24&height=230&section=header&text=Data%20Intelligence%20Dashboard&fontSize=46&fontColor=ffffff&fontAlignY=38&animation=twinkling&desc=%E2%9C%A6%20Raw%20Data%20%E2%86%92%20Insights%20%E2%86%92%20Decisions%20%E2%9C%A6&descSize=20&descAlignY=60" width="100%" alt="Data Intelligence Dashboard banner"/>

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3200&pause=900&color=9B7EDE&center=true&vCenter=true&width=720&lines=%E2%9C%A7+Welcome+to+my+Excel+Analytics+Universe+%E2%9C%A7;%E2%9D%80+250+Transactions+%E2%80%A2+50+Customers+%E2%80%A2+9+Sheets+%E2%9D%80;%E2%98%85+Live+Formulas+%E2%80%A2+Charts+%E2%80%A2+Dashboard+%E2%98%85;%E2%9C%A6+Turning+numbers+into+stories+%E2%9C%A6" alt="Typing animation"/></a>

<br/>

<img src="https://img.shields.io/badge/Tool-Microsoft%20Excel-E6E6FA?style=for-the-badge&logo=microsoftexcel&logoColor=7B5EA7&labelColor=D8BFF8"/>
<img src="https://img.shields.io/badge/Type-Data%20Analytics-D8BFF8?style=for-the-badge&logoColor=7B5EA7&labelColor=E6E6FA"/>
<img src="https://img.shields.io/badge/Formulas-1750%2B%20Live-E6D9FA?style=for-the-badge&labelColor=C9B3F2"/>
<img src="https://img.shields.io/badge/Charts-12-DCCBFA?style=for-the-badge&labelColor=E6E6FA"/>
<img src="https://img.shields.io/badge/Status-Completed-E6E6FA?style=for-the-badge&labelColor=C9B3F2"/>

<br/><br/>

> ### ✧･ﾟ: *✧･ﾟ:*  💭 *Thought of the Day*  *:･ﾟ✧*:･ﾟ✧
> **“Without data, you’re just another person with an opinion.”**
> — W. Edwards Deming

</div>

<br/>

<img src="https://capsule-render.vercel.app/api?type=soft&color=E6D9FA&height=75&section=header&text=%E2%9C%A6%20About%20the%20Project&fontSize=30&fontColor=6B4FA0&animation=fadeIn&fontAlignY=50" width="100%" alt="About the Project"/>

**Data Intelligence Dashboard** ek complete, end-to-end **Excel data analytics project** hai. Isme ek sales-transactions dataset (250 rows) ko clean, analyse aur visualise kiya gaya hai — sab kuch **live formulas** ke saath, taaki data badalte hi saare tables, charts aur report khud update ho jaayein. ✨

Project ek hi workbook me yeh sab cover karta hai:

- 📊 **KPI summary** aur pivot-style analysis tables (SUMIFS / COUNTIFS / SUMPRODUCT)
- 👥 **Customer analysis** — value tiers, top customers, list comparison
- 🕒 **Date & time functions**, dynamic filter aur auto-timestamp
- 🎯 **What-If analysis** — scenario manager style + Goal Seek
- 📈 **Regression** — ToolPak-style output LINEST se
- 🎨 **8 charts** + interactive **dashboard** + storytelling **report**

<br/>

<img src="https://capsule-render.vercel.app/api?type=soft&color=E6D9FA&height=75&section=header&text=%E2%9D%80%20Project%20Objectives&fontSize=30&fontColor=6B4FA0&animation=fadeIn&fontAlignY=50" width="100%" alt="Project Objectives"/>

| ✦ | Objective |
|:-:|:--|
| 1 | Raw sales data ko saaf, structured aur analysis-ready banana |
| 2 | Region, category, product, payment aur segment ke hisaab se performance samajhna |
| 3 | High-value customers ko identify karna aur unhe tiers me baantna |
| 4 | Time-based trends aur month-over-month growth track karna |
| 5 | Scenarios (Best / Base / Worst) se future revenue aur profit ka andaaza lagana |
| 6 | Ek single dashboard me saare KPIs aur charts dikhana |
| 7 | Data se **insights aur recommendations** nikaalna |

<br/>

<img src="https://capsule-render.vercel.app/api?type=soft&color=E6D9FA&height=75&section=header&text=%E2%98%85%20Dataset%20Overview&fontSize=30&fontColor=6B4FA0&animation=fadeIn&fontAlignY=50" width="100%" alt="Dataset Overview"/>

<div align="center">

| 📅 Period | 🧾 Transactions | 👥 Customers | 📦 Products | 🌍 Regions |
|:-:|:-:|:-:|:-:|:-:|
| 11 Apr 2024 – 11 Apr 2025 | 250 | 50 | 10 | 5 |

</div>

### 🗂️ Raw Data — Columns

| Column | Description |
|:--|:--|
| `Transaction_ID` | Har transaction ki unique ID |
| `Date` | Transaction ki date |
| `Customer_ID`, `Customer_Name` | Customer ki pehchaan |
| `Product_ID`, `Product_Name`, `Category` | Product details (Electronics / Furniture / Appliances) |
| `Quantity`, `Unit_Price` | Kitni units aur kis price par |
| `Payment_Method` | Cash / Credit Card / Debit Card / PayPal |
| `Region` | Central / East / North / South / West |
| `Customer_Segment` | Basic / Standard / Premium |
| `Customer_Since` | Customer kab judaa |
| `Total_Amount` | Quantity × Unit_Price |

**⚙️ Helper columns (formulas):** `Month_Start`, `Month_End`, `Tenure_Yrs`, `Days_Since_Purchase`, `Name_Count`, `Purchase_Type` (First / Repeat), `Filter_Seq`

<br/>

<img src="https://capsule-render.vercel.app/api?type=soft&color=E6D9FA&height=75&section=header&text=%E2%9C%A7%20Workbook%20Structure&fontSize=30&fontColor=6B4FA0&animation=fadeIn&fontAlignY=50" width="100%" alt="Workbook Structure"/>

```text
📘 PR_Final_Project_Data_Intelligence_Dashboard.xlsx
 │
 ├── 📄 Raw Data          → 250 transactions + helper formula columns
 ├── 📊 Analysis          → KPI & pivot-style summary tables
 ├── 👥 Customer Analysis → GroupBy, tiers, top 10, list comparison
 ├── 🕒 DateTime_Filter   → Date functions, dynamic filter, timestamp
 ├── 🎯 What-If           → Scenario summary + Goal Seek
 ├── 📈 Regression        → LINEST-based regression output
 ├── 🎨 Visualizations    → 8 charts (bar, line, pie)
 ├── 🧭 Dashboard         → KPI cards, indicators, top-5 tables, charts
 └── 📝 Report            → Insights, storytelling & recommendations
```

<br/>

<img src="https://capsule-render.vercel.app/api?type=soft&color=E6D9FA&height=75&section=header&text=%E2%9D%80%20Sheet-by-Sheet%20Details&fontSize=30&fontColor=6B4FA0&animation=fadeIn&fontAlignY=50" width="100%" alt="Sheet by Sheet Details"/>

<details>
<summary><b>📊 1. Analysis</b> — formula-based summary tables</summary>
<br/>

- **KPI Summary:** Total Revenue, Transactions, Units Sold, Average Order Value, Unique Customers, Revenue per Customer
- **Sales by Region** — revenue, orders, units, % share, AOV, performance index
- **Sales by Category** and **Sales by Product** (with rank & abbreviation)
- **Monthly Sales Trend** with MoM % change and month labels
- **Sales by Payment Method** and **Customer Segment**
- **Repeat vs First-time** purchases, most-sold / highest-revenue product
- **Top 5 Most Sold Products**

</details>

<details>
<summary><b>👥 2. Customer Analysis</b> — know your customers</summary>
<br/>

- Customer-wise **orders, units, revenue, AOV** and **revenue rank**
- **Value Tiers** — High / Mid / Low (percentile threshold is an input cell)
- Customer **initials** and auto-generated **customer code**
- **Top 10 customers** and tier-wise revenue summary
- **Compare Two Lists** — Electronics buyers vs Furniture buyers (matching names extracted)

</details>

<details>
<summary><b>🕒 3. DateTime_Filter</b> — time functions & dynamic filter</summary>
<br/>

- `TODAY`, `NOW`, `DATEDIF`, `EOMONTH` ke practical use
- **Dynamic filter:** Region (dropdown) + minimum amount choose karo, matching rows khud aa jaati hain
- **Auto-timestamp:** entry likhte hi `NOW()` ka time freeze ho jaata hai (iterative calculation se)

</details>

<details>
<summary><b>🎯 4. What-If</b> — scenarios & Goal Seek</summary>
<br/>

- Base / Best / Worst scenarios (price change, volume change, discount)
- Scenario dropdown (1 / 2 / 3) se **Selected** column badalta hai
- Projected Revenue, Cost, **Profit**, Profit Margin aur Base se comparison
- **Goal Seek:** target revenue growth paane ke liye kitna volume change chahiye

</details>

<details>
<summary><b>📈 5. Regression</b> — ToolPak-style output</summary>
<br/>

- `Y = Total_Amount`, `X1 = Quantity`, `X2 = Unit_Price`
- Multiple R, R², Adjusted R², Standard Error, ANOVA, Coefficients, t-Stat, P-value, 95% limits
- Fitted-equation se **prediction** + scatter chart with trendline

</details>

<details>
<summary><b>🎨 6. Visualizations & 🧭 7. Dashboard</b></summary>
<br/>

**Charts:** Revenue by Region • Revenue Share by Category • Monthly Revenue Trend • Top 10 Customers • Units Sold by Product • Revenue Share by Payment Method • Revenue by Customer Segment • Orders by Region

**Dashboard:** 5 KPI cards, last-month vs previous-month indicators (with direction icons), regional pivot-style table, Top 5 customers, Top 5 products aur 4 charts — ek hi screen par.

</details>

<details>
<summary><b>📝 8. Report</b> — insights & storytelling</summary>
<br/>

Summary insights, top customers, most-sold products, regional sales, aur 10-point **data story** (Overview → Regions → Categories → Products → Customers → Time trend → Payments → Loyalty → Regression → What-If) with final **recommendations**.

</details>

<br/>

<img src="https://capsule-render.vercel.app/api?type=soft&color=E6D9FA&height=75&section=header&text=%E2%9C%A6%20Key%20Insights&fontSize=30&fontColor=6B4FA0&animation=fadeIn&fontAlignY=50" width="100%" alt="Key Insights"/>

<div align="center">

| 💰 Total Revenue | 🧾 Transactions | 📦 Units Sold | 🛒 Avg Order Value | 👥 Customers |
|:-:|:-:|:-:|:-:|:-:|
| **229,192** | **250** | **753** | **916.77** | **50** |

</div>

- 🌍 **East** sabse strong region hai (~59.3K revenue, ≈26%), uske baad **North** (~50.8K); **South** sabse kam (~36.4K).
- 💻 **Electronics** akela ≈ **75%** revenue deta hai; **Appliances** ka hissa sirf ≈ 4% hai.
- 🏆 **Laptop** aur **Smartphone** lagbhag barabar top performers hain (~67K each).
- 👑 Top customer **Mark Carter** hai (~15.7K), uske baad Edward Mitchell aur Barbara Young.
- 💳 Payment methods me revenue lagbhag balanced hai — **Credit Card** thoda aage.
- ⭐ **Premium** aur **Standard** segments milkar revenue ka bada hissa banate hain.

> 📌 *Numbers dataset ke current snapshot par based hain; workbook me sab kuch live formulas se update hota hai.*

<br/>

<img src="https://capsule-render.vercel.app/api?type=soft&color=E6D9FA&height=75&section=header&text=%E2%9D%80%20Excel%20Skills%20Used&fontSize=30&fontColor=6B4FA0&animation=fadeIn&fontAlignY=50" width="100%" alt="Excel Skills Used"/>

| 🧩 Category | ✨ Functions / Features |
|:--|:--|
| **Aggregation** | `SUMIFS` `COUNTIFS` `SUMPRODUCT` `AVERAGE` `MEDIAN` `PERCENTILE` |
| **Lookup** | `INDEX` `MATCH` `CHOOSE` |
| **Date & Time** | `TODAY` `NOW` `DATEDIF` `EOMONTH` |
| **Text** | `UPPER` `LEFT` `MID` `FIND` `TEXT` `RIGHT` |
| **Logic** | `IF` `AND` `IFERROR` `RANK` |
| **Statistics** | `LINEST` `FDIST` `SQRT` |
| **Features** | Data Validation (dropdowns) • Conditional Formatting • Tables • Scenario & Goal Seek • Charts (Bar / Line / Pie / Scatter) |

<br/>

<img src="https://capsule-render.vercel.app/api?type=soft&color=E6D9FA&height=75&section=header&text=%E2%9C%A7%20How%20to%20Use&fontSize=30&fontColor=6B4FA0&animation=fadeIn&fontAlignY=50" width="100%" alt="How to Use"/>

1. 📥 **Download** karke `PR_Final_Project_Data_Intelligence_Dashboard.xlsx` ko **Microsoft Excel** me kholo.
2. 🧭 Sabse pehle **Dashboard** sheet dekho — poora summary wahin hai.
3. 🔽 **DateTime_Filter** me Region dropdown aur minimum amount change karke dynamic filter try karo.
4. 🎯 **What-If** me scenario number (1 / 2 / 3) badalke projected revenue & profit dekho.
5. 📝 Aakhir me **Report** sheet padho — insights aur recommendations wahin hain.

### ⚠️ Important Notes

- 🔁 **Auto-timestamp** ke liye: `File → Options → Formulas → Enable iterative calculation` ON karo.
- 📅 `TODAY()` / `NOW()` volatile hain, isliye *Days Since Purchase* jaise columns roz badalte rahenge.
- 📉 **Apr 2025** ek *partial month* hai (data 11 Apr 2025 tak hi hai), isliye MoM comparison me dhyan rakho.
- 📐 Regression me `Total_Amount = Quantity × Unit_Price` hota hai, isliye straight-line model sirf ek approximation hai.
- 💡 What-If ka *cost %* ek **assumption** hai, dataset me cost data nahi tha.

<br/>

<img src="https://capsule-render.vercel.app/api?type=soft&color=E6D9FA&height=75&section=header&text=%E2%98%85%20Recommendations%20%26%20Future%20Scope&fontSize=30&fontColor=6B4FA0&animation=fadeIn&fontAlignY=50" width="100%" alt="Recommendations and Future Scope"/>

**💡 Recommendations**
- High-Value customers aur top region par marketing focus karo.
- Slow-moving **Appliances** ko bundles / offers me jodo.
- Repeat purchases badhane ke liye loyalty ya segment-based offers do.

**🚀 Future Scope**
- Real **Slicers** aur **Timeline** add karna
- Power Query / Power Pivot se bade datasets handle karna
- Forecasting (trend / seasonality) jodna
- Power BI dashboard version banana

<br/>

<div align="center">

<img src="https://img.shields.io/badge/Made%20with-Excel%20%26%20Curiosity-E6E6FA?style=for-the-badge&labelColor=C9B3F2"/>
<img src="https://img.shields.io/badge/Data-Analytics-D8BFF8?style=for-the-badge&labelColor=E6E6FA"/>
<img src="https://img.shields.io/badge/Dashboard-Live%20Formulas-E6D9FA?style=for-the-badge&labelColor=C9B3F2"/>
<img src="https://img.shields.io/badge/Open%20Source-Learning%20Project-DCCBFA?style=for-the-badge&labelColor=E6E6FA"/>

<br/><br/>

> ### ✧･ﾟ: *✧･ﾟ:*  💭 *Closing Thought*  *:･ﾟ✧*:･ﾟ✧
> **“Data is the new canvas — and every chart is a little piece of art.”** 🎨

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3500&pause=1000&color=9B7EDE&center=true&vCenter=true&width=620&lines=%E2%9C%A6+Thank+you+for+visiting+my+project+%E2%9C%A6;%E2%9D%80+Keep+learning%2C+keep+analysing+%E2%9D%80;%E2%98%85+Made+with+love+%26+lots+of+formulas+%E2%98%85" alt="Typing animation"/></a>

<br/>

### ✍️ Author — **Kavita Khushalani**

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,19,24&height=140&section=footer&animation=twinkling" width="100%" alt="footer banner"/>

</div>
