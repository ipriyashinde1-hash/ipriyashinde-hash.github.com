<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Priya Atul Sawant - Data Analyst Portfolio</title>
    <style>
        @page {
            size: A4;
            margin: 0;
            background-color: #ffffff;
        }
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
            line-height: 1.5;
        }
        .header {
            background-color: #1a365d;
            color: white;
            padding: 40px 50px;
            text-align: left;
        }
        .header h1 {
            margin: 0;
            font-size: 26pt;
            letter-spacing: 1px;
        }
        .header p {
            margin: 5px 0 0 0;
            font-size: 14pt;
            opacity: 0.9;
        }
        .container {
            display: table;
            width: 100%;
        }
        .sidebar {
            display: table-cell;
            width: 30%;
            background-color: #f7fafc;
            padding: 30px;
            vertical-align: top;
            border-right: 1px solid #e2e8f0;
        }
        .content {
            display: table-cell;
            width: 70%;
            padding: 30px 50px;
            vertical-align: top;
        }
        h2 {
            color: #2b6cb0;
            font-size: 14pt;
            border-bottom: 2px solid #2b6cb0;
            padding-bottom: 5px;
            margin-top: 0;
            text-transform: uppercase;
        }
        .section {
            margin-bottom: 25px;
        }
        .skill-list {
            list-style: none;
            padding: 0;
        }
        .skill-list li {
            background: #edf2f7;
            margin-bottom: 5px;
            padding: 5px 10px;
            border-radius: 4px;
            font-size: 10pt;
            font-weight: bold;
        }
        .project {
            margin-bottom: 20px;
        }
        .project-title {
            font-weight: bold;
            font-size: 12pt;
            color: #1a365d;
        }
        .project-tools {
            font-size: 9pt;
            color: #718096;
            font-style: italic;
        }
        .contact-item {
            font-size: 10pt;
            margin-bottom: 10px;
        }
        .edu-item {
            margin-bottom: 15px;
        }
        .edu-title {
            font-weight: bold;
            font-size: 11pt;
        }
        .edu-meta {
            font-size: 9pt;
            color: #4a5568;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>Priya Atul Sawant</h1>
        <p>Data Analyst | Business Intelligence Specialist</p>
    </div>

    <div class="container">
        <div class="sidebar">
            <div class="section">
                <h2>Contact</h2>
                <div class="contact-item">📍 Kalyan, Maharashtra</div>
                <div class="contact-item">💼 LinkedIn: priyasawant</div>
                <div class="contact-item">🌐 Portfolio: priya-dsda.github.io</div>
            </div>

            <div class="section">
                <h2>Technical Skills</h2>
                <ul class="skill-list">
                    <li>Python (Pandas, NumPy)</li>
                    <li>SQL (MySQL)</li>
                    <li>Power BI</li>
                    <li>Tableau</li>
                    <li>Advanced Excel</li>
                    <li>Tally ERP 9</li>
                </ul>
            </div>

            <div class="section">
                <h2>Languages</h2>
                <div class="contact-item">English (Professional)</div>
                <div class="contact-item">Hindi (Fluent)</div>
                <div class="contact-item">Marathi (Native)</div>
            </div>
        </div>

        <div class="content">
            <div class="section">
                <h2>Professional Summary</h2>
                <p style="font-size: 11pt;">
                    Analytical and detail-oriented Data Analyst with a background in Commerce (B.Com) and specialized training in Data Science & Data Analytics. 
                    Proven ability to design complex database schemas, create interactive BI dashboards, and perform exploratory data analysis using Python and SQL. 
                    Passionate about turning data into actionable insights for business growth.
                </p>
            </div>

            <div class="section">
                <h2>Featured Projects</h2>
                <div class="project">
                    <div class="project-title">Cab Booking Service Database Design</div>
                    <p style="font-size: 10pt; margin: 5px 0;">Architected a relational database for a cab application involving customer, driver, and booking entities. Optimized queries for performance and data integrity.</p>
                    <div class="project-tools">Tools: SQL, MySQL Workbench</div>
                </div>
                <div class="project">
                    <div class="project-title">Sales Performance Dashboard</div>
                    <p style="font-size: 10pt; margin: 5px 0;">Developed an end-to-end Power BI dashboard tracking monthly revenue, driver performance, and customer satisfaction metrics using DAX formulas.</p>
                    <div class="project-tools">Tools: Power BI, DAX, Excel</div>
                </div>
            </div>

            <div class="section">
                <h2>Education</h2>
                <div class="edu-item">
                    <div class="edu-title">Post Graduate in DSDA</div>
                    <div class="edu-meta">Current | Kalyan</div>
                </div>
                <div class="edu-item">
                    <div class="edu-title">Bachelor of Commerce (B.Com)</div>
                    <div class="edu-meta">Mumbai University | 2019</div>
                </div>
            </div>

            <div class="section">
                <h2>Certifications</h2>
                <ul style="font-size: 10pt; padding-left: 20px;">
                    <li>MS-CIT (Information Technology)</li>
                    <li>Government Certified Marathi Typing</li>
                    <li>Financial Accounting in Tally</li>
                </ul>
            </div>
        </div>
    </div>
</body>
</html>
