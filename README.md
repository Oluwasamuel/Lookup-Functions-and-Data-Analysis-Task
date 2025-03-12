# Lookup-Functions-and-Data-Analysis-Task

### Task Overview
The task involved utilizing Excel lookup functions (VLOOKUP and XLOOKUP) to extract, match, and analyze data across multiple sheets in a dataset. The goal was to strengthen proficiency in Excel lookup functions while answering specific questions about customer segments, sales figures, and regional performance.

### Steps Taken
1. **Data Understanding**: Reviewed the dataset containing customer orders with details like customer name, order priority, quantity, sales, discount, ship mode, profit, region, customer segment, and date.
2. **Lookup Function Application**: Used VLOOKUP and XLOOKUP to retrieve specific data based on given criteria.
3. **Question Analysis**: Addressed each assignment question systematically using appropriate Excel functions.
4. **Pivot Table Creation**: Generated pivot tables to summarize and analyze data for broader insights.
5. **Formula Verification**: Ensured accuracy in formulas and cross-validated results with raw data.

### Key Insights and Answers

#### Lookup Questions
1. **Customer Segment for Muhammed MacIntyre**:
   - Formula: `=VLOOKUP("Muhammed MacIntyre", A:J, 8, FALSE)`
   - Result: Small Business

2. **Sales Amount on 5/7/2009**:
   - Formula: `=VLOOKUP("2009-05-07", J:I, 2, FALSE)`
   - Result: $2484.75

3. **Customer with Sales Figure 4158.1235**:
   - Formula: `=XLOOKUP(4158.1235, I:I, A:A)`
   - Result: Keith Dawkins

4. **Customer from Yukon Region**:
   - Formula: `=VLOOKUP("Yukon", J:A, 1, FALSE)`
   - Result: Craig Yedwab

#### Analytical Questions
1. **Total Order Quantity for Liz Pelletier**:
   - Formula: `=SUMIFS(D:D, A:A, "Liz Pelletier")`
   - Result: 88 units

2. **Order Priority with Highest Sales**:
   - Pivot Table Analysis: High priority orders generated the highest sales at $10,065.40.

3. **Sales in 2009**:
   - Formula: `=SUMIFS(I:I, J:J, ">=2009-01-01", J:J, "<=2009-12-31")`
   - Result: $11,741.71

4. **Region with Least Profit in 2012**:
   - Formula: `=MINIFS(K:K, J:J, "2012", L:L, "West")`
   - Result: Ontario region had the least profit at -$22.59.

5. **Customer Segment with Highest Sales**:
   - Pivot Table Analysis: Home Office segment accounted for the highest sales at $14,537.45.

### Deliverables
1. **Completed Excel File**: Implemented lookup functions and formulas to answer all questions accurately.
2. **Analysis Summary**: Provided a clear summary of steps taken and key insights derived from the data.

The analysis successfully utilized Excel's lookup functions to extract meaningful information and answer business-critical questions about customer behavior, sales performance, and regional profitability.
