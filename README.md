# Automated-Report-Generation

*Company* : CODETECH IT SOLUTIONS

*Name* : PRAGYA SANTRA

*Intern ID* : CT08NGE

*Domain* : Python

*Duration* : 4 Weeks

*Mentor* : NEELA SANTOSH

## Description 

The task involves developing an automated report generation system using Python to analyze a dataset named `sales_data_sample.csv` and generate a formatted PDF report using the `fpdf` library. The dataset contains sales-related information, including fields like `ORDERNUMBER`, `QUANTITYORDERED`, `PRICEEACH`, `SALES`, `ORDERDATE`, `STATUS`, `CUSTOMERNAME`, and other relevant columns that provide insights into customer orders and sales metrics. The goal is to create a Python script that reads and processes this data, extracts meaningful information, and presents it in a structured, visually appealing PDF document.

To achieve this, the script starts by loading the dataset using the `pandas` library. This library provides robust functionality for reading and analyzing data. It reads the CSV file and handles potential encoding issues to ensure compatibility with different file formats. Once the data is loaded, it calculates key metrics such as total sales, average sales per order, and the total number of processed orders. These metrics form the foundation of the summary section of the report, offering a quick overview of the dataset's insights.

The `fpdf` library is used to design and generate the PDF report. This library enables the creation of professional-looking PDF documents with headers, footers, and multi-page content. The report begins with a title page that includes a header labeled "Sales Report" to establish its purpose. A summary section follows, where the calculated metrics are presented in clear and concise language. This section provides decision-makers with an overview of overall sales performance and order statistics.

The report further includes a table showcasing a sample of the dataset, typically the first ten rows, to provide an example of the raw data used for the analysis. The table contains selected columns such as `ORDERNUMBER`, `QUANTITYORDERED`, `PRICEEACH`, `SALES`, and `ORDERDATE`, which are crucial for understanding individual transactions. These columns are formatted into a neat table with headers, making it easy to read and interpret. The `fpdf` library ensures that the table is aligned and styled consistently, enhancing the report's readability.

To make the report more user-friendly, the script integrates headers and footers on every page. The header includes the report title, while the footer contains page numbers, ensuring that the report remains well-organized even when spanning multiple pages. The layout and formatting are carefully designed to maintain a professional appearance, making the report suitable for presentation to stakeholders or team members.

The script also includes functionality to automatically open the generated PDF once it is created. This feature improves usability, as users can immediately view the output without manually searching for the file. Depending on the operating system, the script uses commands to open the PDF in the default viewer, ensuring cross-platform compatibility.

Overall, this task demonstrates how automated tools can streamline data analysis and reporting. By combining the data manipulation capabilities of `pandas` with the document-generation features of `fpdf`, the script effectively transforms raw sales data into a polished report. Such automation not only saves time but also minimizes errors that may arise from manual report creation. The structured approach ensures that critical sales insights are highlighted, while the inclusion of a data sample provides transparency about the dataset used for analysis.


### Screenshot of the output

![Image](https://github.com/user-attachments/assets/b2c85618-1be1-4075-b7b2-0971d08bc57a)
