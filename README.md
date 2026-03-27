<h1>Telecom Customer Churn and Revenue Analysis</h1>

<h2>Overview</h2>
<p>
This project analyzes telecom customer churn, revenue patterns, contract behavior, and ZIP code population data using Python.
It combines customer churn data with population information to generate business insights through visualization and summary metrics.
</p>

<h2>Objective</h2>
<p>
The main goal of this project is to explore customer churn behavior and business performance in a telecom company through visual and statistical analysis.
</p>

<h2>Datasets</h2>
<p>This project uses two datasets:</p>
<a href='https://www.kaggle.com/datasets/shilongzhuang/telecom-customer-churn-by-maven-analytics'> Dataset Link </a>


<p>
These datasets are merged using the <b>Zip Code</b> column.
</p>

<h2>Tools and Technologies</h2>
<ul>
  <li>Python</li>
  <li>Pandas</li>
  <li>Seaborn</li>
  <li>Matplotlib</li>
  <li>Jupyter Notebook / Python Script</li>
</ul>

<h2>Workflow</h2>
<ol>
  <li>Load the telecom customer churn dataset</li>
  <li>Load the ZIP code population dataset</li>
  <li>Merge both datasets using <code>Zip Code</code></li>
  <li>Perform business analysis through charts</li>
  <li>Print summary business metrics</li>
</ol>

<h2>Analysis Performed</h2>

<h3>1. Top 10 Cities by Total Revenue</h3>
<p>
A horizontal bar chart is used to identify the top revenue-generating cities.
</p>

<h3>2. Why Customers Are Churning</h3>
<p>
A pie chart is used to show the main churn categories among customers who left the service.
</p>

<h3>3. Tenure vs Monthly Charges (Risk Analysis)</h3>
<p>
A scatter plot is used to analyze the relationship between customer tenure, monthly charges, and customer status.
This helps identify high-risk churn segments.
</p>

<h3>4. Churn Count by Contract Type</h3>
<p>
A count plot is used to compare churn distribution across different contract types.
</p>

<h2>Key Metrics</h2>
<p>The project calculates and prints the following KPIs:</p>
<ul>
  <li><b>Total Revenue</b></li>
  <li><b>Overall Churn Rate</b></li>
  <li><b>Average Population per ZIP Code</b></li>
</ul>

<h2>Key Insights</h2>
<ul>
  <li>Some cities contribute significantly more revenue than others</li>
  <li>Customer churn is concentrated in specific churn categories</li>
  <li>Customers with low tenure and high monthly charges may be more likely to churn</li>
  <li>Month-to-month contract users tend to churn more than long-term contract users</li>
</ul>

<h2>How to Run</h2>

<h3>Install Required Libraries</h3>
<pre><code>pip install pandas seaborn matplotlib</code></pre>

<h3>Run the Script</h3>
<p>
Make sure both CSV files are in the same folder as your Python script or notebook, then run your analysis file.
</p>

<h2>Output</h2>
<ul>
  <li>A 2x2 dashboard of business analysis charts</li>
  <li>Summary KPI values printed in the console</li>
</ul>

<h2>Project Structure</h2>
<pre><code>project-folder/
│
├── telecom_customer_churn.csv
├── telecom_zipcode_population.csv
├── Sales_KPI_Dashboard.ipynb
└── README.md
</code></pre>

<h2>Business Value</h2>
<p>
This project helps identify revenue-driving regions, churn causes, contract risk patterns, and customer segments that need retention strategies.
It supports better decision-making for customer retention and revenue optimization.
</p>

<h2>Author</h2>
<p><b>Ahnaf Khan</b></p>
