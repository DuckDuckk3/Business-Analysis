# I. Must-Master (Highest Priority)
You cannot analyze a business if you cannot read its scoreboard. These subjects form the financial and quantitative bedrock of your toolkit.

---  

## I.1 Principles of Accounting
### 1. Overview:
If business is a sport, `Accounting` is the scoreboard. To be effective, you must understand whether a company is making or losing money, or what it owns versus what it owes. It is the source of truth for any business. You cannot analyze what you cannot read, and accounting is the alphabet of the corporate world.  
### This is one of the single most important subjects in the entire curriculum, and is essential in every situation of your working life.
### To master accounting, you must understand these pillars:
## A. Foundational Assumptions (The Framework):
These are the `ground rules` that define the boundaries and environment in which accounting operates.
| Concept | Description |
| :--- | :--- |
| **Business Entity** | The business is legally and financially separate from its owners. Crucial for data isolation and multi-tenancy. |
| **Money Measurement** | Only transactions quantifiable in a monetary unit are recorded. Non-monetary events (e.g., employee morale) are excluded. |
| **Going Concern** | The assumption that the company will operate indefinitely, justifying long-term asset depreciation over immediate expensing. |
| **Accounting Period** | The life of a business is divided into artificial time intervals (months, quarters, years) for periodic reporting. |

---

## B. Operational Principles (playing rules):
These rules dictate how transactions are measured, recorded, and reported to ensure consistency and reliability.

- `Dual Aspect (The Binary Logic):`
  - Every transaction affects at least two accounts. This is the origin of the Fundamental Accounting Equation: `Assets = Liabilities + Equity`  
  - This ensures the "scoreboard" always stays in balance through Double-Entry bookkeeping.

- `Recognition and Measurement:`
  - `Historical Cost:` Assets are recorded at their original purchase price. This provides an objective "anchor" in the database, preventing subjective market-value manipulation.
  - `Revenue Recognition:` Revenue is recorded when it is **earned** (goods delivered or services rendered), regardless of when the cash is received.
  - `Matching Principle:` Every dollar of revenue must be matched with the expenses incurred to generate it within the same period. 
  - `Accrual Basis:` The combination of the two above; recording financial effects when they occur rather than when cash changes hands.

---

## C. Qualitative Constraints:
These constraints ensure that the information provided is useful, ethical, and not misleading.

- `Full Disclosure:` All information that could influence a user's understanding of the financial statements must be disclosed (usually in footnotes).
- `Materiality:` Accounting rules can be ignored if the amount is so small it wouldn't influence a decision-maker (e.g., a $5 stapler in a $50M company).
- `Consistency:` Once an accounting method is chosen, it must be used consistently over time to allow for meaningful trend analysis.
- `Prudence (Conservatism):` When in doubt, record expenses and liabilities immediately, but only record revenues when they are certain. *"Anticipate no profit, but provide for all possible losses."

---

## D. The Accounting Cycle:
The systematic process (ETL - Extract, Transform, Load) of turning raw business transactions into audited financial reports.

- `Transaction Analysis:` Identifying economic events from source documents.
- `Journalizing:` Recording transactions chronologically in the General Journal.
- `Posting:` Transferring journal entries to the General Ledger (categorizing by account).
- `Trial Balance:` Verifying that total Debits equal total Credits.
- `Adjusting Entries:` Applying Accrual/Matching principles at the end of the period.
- `Financial Statements:` Generating the final reports for stakeholders.
- `Closing Entries:` Resetting **Temporary Accounts** (Revenue/Expenses) to zero for the next period.

---

## E. Financial Statements (Exceptionally Important)
### The final products used by investors, creditors, and management to make informed decisions.  
- `Financial Statements` are far more than just "end-of-year paperwork"—they are the ultimate, high-fidelity dashboard where every `operational decision`, every `database entry`, and every `process optimization` finally meets the cold of reality. In the world of `Business Analysis`, these statements serve as the definitive `"Unit Test"` for your entire organizational logic; you can design the `best-on-paper` project ever, but if it doesn't eventually translate into a `healthier bottom line` on the `Income Statement` or a `stronger cash position` on the `Cash Flow Statement`, your project has failed its primary business objective.   
- For investors and creditors, these documents act as a `non-negotiable` X-ray that cuts through corporate marketing hype to reveal the actual solvency and scalability of a firm, where the relationship between the "Holy Trinity"—`the Balance Sheet` ($Assets = Liabilities + Equity$), the `PnL (Profit and Loss)`, and the `Cash Flow` must reconcile perfectly to prove data integrity.  
- From a `quantitative research` or `investment perspective`, mastering these statements is what allows you to `differentiate` between `"paper profit"` (an accounting opinion based on the Revenue Recognition principle) and `"actual cash"` (a physical fact), ensuring you don't back a `company` that is `technically profitable` but `functionally starving` for `liquidity`.  
- Ultimately, if you don't understand the final product that the CEO and the board use to make `multi-million dollar decisions`, you are merely a `"technical observer"` rather than a `true strategic partner`.  
### Financial Statements are the only language that truly scales from the database level all the way to the boardroom.

| Statement | Time Nature | Purpose |
| :--- | :--- | :--- |
| **Balance Sheet** | Snapshot | Shows the financial position (Assets, Debt, Equity) at a specific point in time. |
| **Income Statement** | Period | Measures profitability (Revenue - Expenses) over a specific duration. |
| **Cash Flow Statement**| Period | Reconciles net income to actual cash generated/used in operations, investing, and financing. |
| **Retained Earnings** | Period | Tracks how much profit is kept in the business vs. paid out to owners. |

---

### 2. Application:
When you build an inventory management software, accounting knowledge helps you understand why the system must use "First-In, First-Out" (FIFO) and how an inventory scan automatically triggers a journal entry in the General Ledger.
*   **Accounting is not Math, it’s Logic:** Do not fear the numbers; fear putting them in the wrong column. A great BA knows how to look at a weird number on a dashboard and trace it all the way back to the specific operational process that generated it (this is called the Audit Trail).
*   **Learn the T-Account:** In the industry, if you want to understand how data flows through massive ERP systems like SAP or Oracle, mastering the visual T-Account is your ultimate cheat code.

### 3. Recommended Sources
*   **"The Accounting Game: Basic Accounting Fresh from the Lemonade Stand" by Darrell Mullis:** A brilliant, stress-free book that teaches complex accounting concepts by simulating how to run a childhood lemonade stand. 
*   **YouTube - "Accounting Stuff":** Excellent, highly visual breakdowns of Debits, Credits, and Financial Statements for absolute beginners.

---

## I.2 Managerial Accounting & Corporate Finance

### 1. Overview
While *Principles of Accounting* looks at the past (reporting to the government), **Managerial Accounting** and **Corporate Finance** look into the future. They provide the financial justification for your BA projects and help internal management make strategic choices.
*   **Cost-Volume-Profit (CVP) Analysis:** Finding the break-even point. "How many units do we need to sell just to cover the cost of this new software?"
*   **Variance Analysis:** Why did we spend $50,000 more than we budgeted? 
*   **Capital Budgeting (NPV/IRR):** Deciding which projects are mathematically worth funding.
### 2. Application
