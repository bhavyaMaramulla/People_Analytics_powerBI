<h1 align="center">📊 People Analytics Dashboard | End-to-End Data Project</h1>

<p align="center">
From raw web data to actionable HR insights — built using Power BI
</p>

<hr>

<h2> Project Description </h2>
<p>
This project is a complete <b>end-to-end data analytics solution</b> where I transformed unstructured workforce data into a decision-making engine.
</p>

<p>
Instead of relying on pre-clean datasets, I simulated a real-world business scenario:
<b>extracting employee data from an external confidential source, cleaning it, and building a powerful reporting system.</b>
</p>

<hr>

<h2> Data Acquisition (Web Scraping)</h2>
<p>
The dataset was sourced through <b>web scraping</b> from a confidential agency-based platform.
</p>

<ul>
<li>Extracted structured employee-related data from web sources</li>
<li>Ensured data relevance and usability for analytics</li>
<li>Simulated real-world data collection challenges</li>
</ul>

<p>
This step reflects real industry workflows where analysts often work with <b>raw, messy, externally sourced data</b> rather than clean datasets.
</p>

<hr>

<h2> Data Cleaning & Transformation (Power BI)</h2>

<p>
Once the data was collected, the focus shifted to making it analysis-ready using <b>Power BI (Power Query)</b>.
</p>

<ul>
<li>Removed duplicate records to maintain data integrity</li>
<li>Handled missing and null values</li>
<li>Standardized column formats (salary, ratings, etc.)</li>
<li>Renamed columns for clarity and consistency</li>
<li>Filtered irrelevant or noisy data</li>
<li>Created calculated columns for better analysis</li>
</ul>

<p>
This phase ensures that insights are built on <b>clean, reliable, and structured data</b>.
</p>

<hr>

<h2> Data Modeling & DAX</h2>

<ul>
<li>Built relationships between datasets (if applicable)</li>
<li>Created measures using DAX for dynamic calculations</li>
<li>Optimized data model for performance and scalability</li>
</ul>

<p><b>Key Measures:</b></p>

<pre>
Total Employees = COUNT(Employee[ID])
Average Salary = AVERAGE(Employee[Salary])
Average Rating = AVERAGE(Employee[Performance Rating])
</pre>

<hr>


<h3> KPI Metrics</h3>
<ul>
<li>Total Employees</li>
<li>Average Salary</li>
<li>Average Performance Rating</li>
</ul>

<h3> Core Visualizations</h3>
<ul>
<li>Department-wise employee distribution</li>
<li>Salary analysis across roles</li>
<li>Performance rating breakdown</li>
<li>Experience vs performance insights</li>
</ul>

<h3> Interactivity</h3>
<ul>
<li>Slicers for dynamic filtering</li>
<li>Drill-down capabilities</li>
<li>User-friendly navigation</li>
</ul>

<hr>

<h2> Key Insights Derived</h2>

<ul>
<li>Identified high-performing departments contributing most to organizational success</li>
<li>Detected salary inconsistencies across similar roles</li>
<li>Found weak correlation between experience and performance in certain segments</li>
<li>Highlighted potential attrition risk groups (low salary + low rating)</li>
</ul>

<hr>

<h2> Business Impact</h2>

<ul>
<li>Enables HR teams to make data-driven decisions</li>
<li>Supports fair compensation and promotion strategies</li>
<li>Helps identify and retain top talent</li>
<li>Improves workforce planning and performance tracking</li>
</ul>

<hr>

<h2>🛠️ Tools & Technologies</h2>

<ul>
<li>Power BI (Dashboard & Visualization)</li>
<li>Power Query (Data Cleaning)</li>
<li>DAX (Data Modeling & Calculations)</li>
<li>Web Scraping (Data Collection)</li>
</ul>

<hr>

<h2>Workforce Analytics & Business Insights</h2>

<p>
This dashboard is designed to address key HR and business challenges related to workforce planning, performance management, and compensation optimization. Each analysis focuses on solving a specific business problem using structured data insights.
</p>

<hr>

<h3>Employee Distribution by Age, Joining Trends & Department</h3>

<p><b>Analysis Included:</b></p>
<ul>
<li>Count of employees by Age Group</li>
<li>Count of Date Joined by Department</li>
</ul>

<p><b>Business Problem:</b><br>
Organizations often lack clarity on hiring patterns and workforce age distribution, making it difficult to plan future recruitment and succession strategies.
</p>

<p><b>Solution Provided:</b><br>
This analysis helps identify hiring trends across departments and understand workforce age composition. It supports workforce planning, age diversity strategies, and long-term talent pipeline decisions.
</p>

<img width="1167" height="658" alt="Screenshot 2026-03-24 201047" src="https://github.com/user-attachments/assets/0c5f85e0-bdf2-4526-8cc1-c7f87f0335d5" />


<hr>

<h3>Geographic & Gender Distribution</h3>

<p><b>Analysis Included:</b></p>
<ul>
<li>Count of Employees by Country</li>
<li>Count of Gender Distribution</li>
</ul>

<p><b>Business Problem:</b><br>
Limited visibility into workforce diversity across locations can impact inclusion strategies and global workforce planning.
</p>

<p><b>Solution Provided:</b><br>
This analysis provides a clear view of employee distribution across regions and gender, helping organizations track diversity metrics and improve inclusive hiring practices.
</p>

<img width="1167" height="658" alt="Screenshot 2026-03-24 201047" src="https://github.com/user-attachments/assets/deb6381e-dffc-4ddb-88b5-2412435ca43a" />


<hr>

<h3>Department-wise Headcount Analysis</h3>

<p><b>Analysis Included:</b></p>
<ul>
<li>Headcount by Department</li>
</ul>

<p><b>Business Problem:</b><br>
Uneven workforce distribution across departments can lead to inefficiencies, overstaffing, or resource shortages.
</p>

<p><b>Solution Provided:</b><br>
This view highlights how employees are distributed across departments, enabling better resource allocation and workforce balancing.
</p>

<img width="1150" height="647" alt="Screenshot 2026-03-24 201105" src="https://github.com/user-attachments/assets/072ea766-098f-4ced-b084-ff121b5b31cc" />


<hr>

<h3>Performance Rating by Department</h3>

<p><b>Analysis Included:</b></p>
<ul>
<li>Count of Employees by Rating</li>
<li>Rating Distribution across Departments</li>
</ul>

<p><b>Business Problem:</b><br>
Organizations often struggle to identify which departments are performing well and which require improvement.
</p>

<p><b>Solution Provided:</b><br>
This analysis evaluates performance distribution across departments, helping management identify high-performing teams and areas needing training or intervention.
</p>

<img width="1156" height="652" alt="Screenshot 2026-03-24 201115" src="https://github.com/user-attachments/assets/b470f36b-cb3a-4028-8cbc-e89060f77dca" />


<hr>

<h3>Department Payroll Analysis</h3>

<p><b>Analysis Included:</b></p>
<ul>
<li>Total Payroll by Department</li>
</ul>

<p><b>Business Problem:</b><br>
Lack of visibility into how salary budgets are allocated can result in inefficient spending and cost imbalances.
</p>

<p><b>Solution Provided:</b><br>
This analysis shows how payroll is distributed across departments, enabling better financial planning and cost control.
</p>

<img width="1154" height="643" alt="Screenshot 2026-03-24 201128" src="https://github.com/user-attachments/assets/a3ee42c3-2676-457c-8f2d-c4f8f896189a" />

<hr>

<h3>Pay-for-Performance Analysis</h3>

<p><b>Analysis Included:</b></p>
<ul>
<li>Salary vs Performance Rating</li>
<li>Department-wise Pay vs Rating Comparison</li>
</ul>

<p><b>Business Problem:</b><br>
Misalignment between employee performance and compensation can lead to dissatisfaction and attrition.
</p>

<p><b>Solution Provided:</b><br>
This analysis evaluates whether higher-performing employees are compensated appropriately, supporting fair and performance-driven salary structures.
</p>

<img width="1154" height="647" alt="Screenshot 2026-03-24 201144" src="https://github.com/user-attachments/assets/31c729ef-0d9e-49a5-94d3-e2e0544d936f" />

<hr>

<h3>Budget vs Performance Analysis</h3>

<p><b>Analysis Included:</b></p>
<ul>
<li>Department Budget vs Average Rating</li>
</ul>

<p><b>Business Problem:</b><br>
Organizations need to ensure that financial investments in departments are generating proportional performance outcomes.
</p>

<p><b>Solution Provided:</b><br>
This analysis compares budget allocation with performance levels to identify whether resources are being effectively utilized.
</p>

<img width="1148" height="639" alt="Screenshot 2026-03-24 201157" src="https://github.com/user-attachments/assets/b05a6eab-da8b-429d-9822-1b77d0799f0e" />

<hr>

<h3>Payroll Distribution by Department</h3>

<p><b>Analysis Included:</b></p>
<ul>
<li>Salary Distribution across Departments</li>
</ul>

<p><b>Business Problem:</b><br>
Salary imbalances across departments can indicate inefficiencies or inequities in compensation structure.
</p>

<p><b>Solution Provided:</b><br>
This view helps identify variations in salary allocation and supports equitable compensation planning.
</p>

<img width="1071" height="648" alt="Screenshot 2026-03-24 201211" src="https://github.com/user-attachments/assets/e27bbc94-d1d6-462d-9ae6-ceaeadfc3e73" />

<hr>

<h3>Gender Breakdown by Department</h3>

<p><b>Analysis Included:</b></p>
<ul>
<li>Gender Distribution across Departments</li>
</ul>

<p><b>Business Problem:</b><br>
Lack of gender balance across departments can affect diversity goals and organizational inclusivity.
</p>

<p><b>Solution Provided:</b><br>
This analysis highlights gender representation within departments, enabling targeted diversity and inclusion initiatives.
</p>

<img width="1088" height="649" alt="Screenshot 2026-03-24 203923" src="https://github.com/user-attachments/assets/b393c39b-131f-4ad0-a380-b89dc797fe5e" />

<hr>

<h2> Dashboard Preview</h2>

<p><i>Add your dashboard screenshots below</i></p>

<img width="1161" height="655" alt="Screenshot 2026-03-24 205128" src="https://github.com/user-attachments/assets/7c5af7a3-4bc4-40bd-ac1c-573d4f5c3704" />
<img width="1155" height="647" alt="Screenshot 2026-03-24 205138" src="https://github.com/user-attachments/assets/a442f49d-5127-4a18-bffe-20f10cb75c70" />

<hr>

<h3>Overall Problem Solved</h3>

<p>
This project addresses the core challenge of fragmented and unstructured HR data by converting it into a unified analytics solution.
</p>

<ul>
<li>Improves visibility into workforce composition and hiring patterns</li>
<li>Enables performance-based evaluation across departments</li>
<li>Aligns compensation with employee performance</li>
<li>Supports efficient budget allocation and cost control</li>
<li>Strengthens diversity and workforce planning strategies</li>
</ul>

<p>
The dashboard enables stakeholders to move from reactive decision-making to a structured, data-driven approach.
</p>

<h2>How to Use</h2>

<ol>
<li>Download the <b>.pbix</b> file from the repository</li>
<li>Open it using <b>Power BI Desktop</b></li>
<li>Navigate through report pages and use filters for detailed analysis</li>
</ol>

<hr>

<h2>Conclusion</h2>

<p>
This project demonstrates the ability to build a structured analytics solution by integrating data preparation, modeling, and visualization techniques.
</p>

<p>
It highlights key competencies in:
</p>

<ul>
<li>Data Cleaning and Transformation</li>
<li>Data Modeling and DAX</li>
<li>Exploratory Data Analysis</li>
<li>Business-Oriented Problem Solving</li>
<li>Dashboard Design in Power BI</li>
</ul>

<p align="center">
Data-driven insights for workforce decision-making
</p>
