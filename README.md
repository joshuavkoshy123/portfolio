# CS Student at UTD

#### Competencies: Testing, Dependency Injection, API Development, CI/CD
#### Programming Languages: C#, Java, Python, JavaScript (Vue and React), SQL, Selenium
#### Technologies: Microsoft Azure, Terraform, JFrog Artifactory, Git/GitHub, CosmosDB, PostgreSQL, MySQL

## Education
- B.S., Computer Science | The University of Texas at Dallas (_2024-Present_)
- A.S., Computer Science | Dallas College (_2021-Present_)

## Experience
### GM Financial - Software Development Engineer Intern (_May 2025-August 2025_)

Over this 12-week internship with GM Financial, I gained hands-on experience as a software developer in a corporate environment. I had the privelege to work directly with **CI/CD** processes and engage with the dev-ops lifecycle. I also received firsthand exposure to the cloud through the companies heavy use of Microsoft Azure. Through **Azure DevOps**, I was able to contribute to the teams codebase through code repositories and pipelines, which built and packaged our code to **JFrog Artifactory**. Additionally, I'm grateful for the opportunity to work with the powerful IaC tool **Terraform**, which enabled me to provision Azure resources, including an **App Service** and multiple **CosmosDB** containers.

In this internship, I developed a major component of the End-To-End Testing for the Helix (application decisioning) system. Helix is a new loan/lease application processing system for GM Financial dealers, designed to replace an older legacy system that has been around for over 20 years. My work this summer was to start on End-To-End Testing for this system to test various customer scenarios, ensuring that all the paths and application decision possibilities in our eventflow were covered. Specifically, I developed a Customer Test API to create templates for test customers and their reports from Credit Bureaus and other entities. These templates would in turn be used to create a new application for the test customer that would be passed through the Helix eventflow. Finally, the application would be decisioned and functional tests would determine if the application was decisioned correctly.

In order to develop the Customer Test API, I had to program using **C#**. Working with a .NET framework it was essential that I grasped the concepts for **Dependency Injection (DI)**, which allowed me to use external services in my API. These external services included various database contexts which enabled me to interact with our CosmosDB database. I also learned how to develop my API using the **Clean Architecture** to reduce the complexity of my project. Finally, I needed to test the various components within my API. I did this through Unit, Integration, and Functional Tests. For **Unit Tests**, I utilized Moq to test my logic while "mocking" dependencies. For **Integration Tests**, I used dependency injection through fixtures, to test my components. For **Functional Tests**, I utilized the powerful tool **Reqnroll** and the scenario-based language **Gherkin** to test my API endpoints with various customer scenarios. After the API was developed, I hosted it on an Azure App Service. Before my internship ended, I was sure to develop wikis on my work as well as essential knowledge I had gained through the internship, to enable knowledge transfer to the team members who would be taking up the rest of the End-To-End Testing.

To conclude, this internship experience was truly unforgettable. I learned more than I ever imagined and grew both personally and professionally. This experience helped me to reignite my passion for software development and serves as the first step in my career.

### UTD EPICS - Hope Restored Missions (_January 2025-May 2025_)

[EPICS Poster](EPICS_Poster.pdf)

EPICS (Engineering Projects in Community Service) is a semester long course that gives students the opportunity to help a local non-profit solve a challenge they are facing and make a real impact in the community. I had the opportunity to work with a non-profit group called Hope Restored Missions which helps homeless and underprivileged individuals in the DFW area by providing them with shelter, clothing, and other aid. My group was tasked with developing an inventory tracking software system to allow them to keep track of the inflow/outflow of their inventory items. To do this, we created a **PostgreSQL** database and a modern and simple UI with **Vue JS** for staff to easily add, remove, update, and find inventory items. This would in turn help staff to better manage their inventory and improve efficiency of operations.

## Projects
### Analyzed Housing Data to Determine Market Trends in Major Metropolitan Cities
[Data Visualization](https://public.tableau.com/views/HomeAffordability_17234935713680/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

Created a data visualization in **Tableau** analyzing housing data from major U.S metropolitan areas in August 2023. Through this analysis, I was able to determined relationships between various factors including house price, income, and mortgage. This study led to several important conclusions. I determined that housing prices were strongly correlated to geography, with higher house prices in the North East and West Coast, and lower prices in the Midwest and South, much as expected. The seven highest prices came from cities in California, followed by Washington, New York, and Massachusetts. More suprising insights came from studying the increase in the annual income required to afford a median-priced home from the previous year (2022). I found that this data did not correlate to the cities with the highest house prices. In fact, the top ten percentage increases came from all different states, with many from the Midwest and South, including Tenessee, Texas, and Florida. Overall, this data revealed that while the highest house prices come from the historically "expensive" regions in the North East and West Coast, much of the housing price increase comes from the generally "affordable" areas including Texas and Florida.

![Home Affordability](/img/Tableau_Project.png)

### Food Access Across Various Demographics and Counties in Maine
[Paper](/Food_Access_Across_Various_Demographics_and_Counties_in_Maine/Food_Access_Across_Various_Demographics_and_Counties_in_Maine.pdf)

Research paper on low access to grocery stores in Maine, measured across counties and demographics. The data analysis and visualizations were made using **Python** Libraries in **Jupiter Notebook** on the dataset "Food Environment Atlas" from the U.S Department of Agriculture. I was able to find counties in which store access has decreased over time and demographics with low store access.

![Food Access](/img/Low_Access_to_Store_Population_in_Maine.png)

### News Aggregator Web Application
[View my website here!](https://news-aggregator-app-nddm.onrender.com/)

**Flask** web application that aggregates and displays news articles retrieved from the **News API**. Designed an interactive and user-friendly frontend using **HTML**, **CSS (Bootstrap)**, and **JavaScript**, featuring modals, article cards, and a save feature for bookmarking articles. Developed a **Python** backend to fetch and process data from the News API, with sorting and filtering options for enhanced user experience.

![Webpage](/img/News_Aggregator.png)

### MarketPulse
[View the website here!](https://market-pulse-sooty.vercel.app/)

[Code Repository: ](https://github.com/joshuavkoshy123/MarketPulse)

MarketPulse is a financial hub of knowledge to stay on top of stocks and trends in the financial market. I collaborated with a group of 5 students to build a **React** web application that tracks up-to-date financial news and stock information, utilizing NewsAPI for articles and FinnHub's API for stock information. The backend is supported by a **Firebase** database, which enables users to login/sign-up and save articles and stockes to their favorites list.

## Awards and Certifications
- Phi Thetta Kappa Membership
- MTA: Introduction to Programming Using Java, 2021
- Google Analytics Certification, 2024
- Cisco: Python Essentials 1, 2024
- Cisco: Introduction to Data Science, 2024
- Oracle Cloud Infrastructure Generative AI Professional, 2024 
