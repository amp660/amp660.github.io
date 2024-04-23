<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Portfolio</title>
    <!-- Link to your CSS file for styling -->
    <link rel="stylesheet" href="styles.css">
    <style>
        /* Add custom CSS styles here */
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
        }
        main {
            padding: 20px;
            max-width: 800px;
            margin: 0 auto;
        }
        h2 {
            color: #333;
        }
        .project {
            margin-bottom: 20px;
        }
        .experience {
            margin-bottom: 30px;
        }
        .company-logo {
            text-align: center;
        }
        .company-logo img {
            width: 150px; /* Adjust the logo size */
            height: auto;
            border-radius: 50%; /* Optional: Add rounded corners */
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1); /* Optional: Add shadow */
        }
        ul {
            list-style-type: none;
            padding: 0;
        }
        li {
            margin-bottom: 5px;
        }
        a {
            color: #007bff; /* Link color */
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

<main>
    <section id="projects">
        <h2>Projects</h2>
        <!-- Project sections -->
    </section>

    <section id="work-experience">
        <h2>Work Experience</h2>
        <div class="experience">
            <h3>Data Analyst</h3>
            <div class="company-logo">
                <img src="https://logos-world.net/wp-content/uploads/2020/06/Accenture-Emblem.png" alt="Accenture Logo">
            </div>
            <h4>Accenture</h4>
            <p>10/2019 - 08/2023</p>
            <ul>
                <li>Designed and implemented 5 complex data pipelines to facilitate efficient information exchange between banks and stakeholders, utilizing ETL tools such as Rundeck, Syncsort, Spark, Hadoop, Hive, and GCP Airflow</li>
                <li>Collaborated with a vendor to improve the efficiency of credit card adjudication processes by implementing AI/ML solutions, resulting in a 10% enhancement in accuracy and speed</li>
                <li>Developed 10 Key Performance Indicator (KPI) dashboards using Tableau, Grafana, and Kibana, achieving a 30% reduction in SLA breaches within 3 months</li>
                <li>Implemented over 10 data patches using Artifactory, leading to a 20% decrease in customer issues and an improvement in product quality</li>
                <li>Enhanced the performance of more than 15 database queries by 40% through strategic optimization techniques such as indexing and query restructuring, thereby improving overall system efficiency and responsiveness</li>
            </ul>
        </div>
        <!-- Add more work experience sections as needed -->
    </section>

    <section id="education">
        <h2>Education</h2>
        <!-- Education sections -->
    </section>

    <section id="certifications">
        <h2>Certifications</h2>
        <!-- Certification sections -->
    </section>

    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>Skill 1</li>
            <li>Skill 2</li>
            <!-- Add more skills as needed -->
        </ul>
    </section>

    <section id="other-links">
        <h2>Other Links</h2>
        <ul>
            <li><a href="https://github.com/amp660">GitHub</a></li>
            <li><a href="https://www.linkedin.com/in/aphans/">LinkedIn</a></li>
            <!-- Add more links to your social media profiles, personal blog, etc. -->
        </ul>
    </section>
</main>

</body>
</html>
