<!-- PROJECT LOGO -->
<br />
<div align="center">
<a href="https://github.com/Zero2164"><img width="200px" src='https://i.postimg.cc/9ftSxC9h/gitlogo.png' border='0' alt='gitlogo'/></a>
<br>
</div>
<!-- Latest -->




<style>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        font-family: 'Poppins', sans-serif;
    }

    body {
        display: flex;
        justify-content: center;
        align-items: center;
        min-height: 100vh;
        background: #000;
    }

    .container {
        display: flex;
        justify-content: center;
        align-items: center;
        flex-wrap: wrap;
        gap: 30px;
        padding: 50px;
    }

    .card {
        position: relative;
        width: 350px;
        height: 300px;
        transition: 0.5s;
        background: rgba(255, 255, 255, 0.1);
        border-radius: 15px;
        backdrop-filter: blur(10px) saturate(180%);
        box-shadow: 0 35px 80px rgba(0, 0, 0, 0.15);
        overflow: hidden;
    }

    .card:hover {
        height: 400px;
    }

    .img-box {
        position: absolute;
        top: 20px;
        width: 300px;
        position: absolute;
        left: 50%;
        margin-left: -150px;
        height: 220px;
        background: #333;
        border-radius: 12px;
        overflow: hidden;
        transition: 0.5s;
        
    }

    .card:hover .img-box {
        top: -100px;
        transform: scale(0.75);
        box-shadow: 0 15px 45px rgba(0, 0, 0, 0.2);
    }

    .img-box img {
        width: 100%;
        height: 100%;
        object-fit: cover;
    }

    .content {
        position: absolute;
        top: 235px;
        width: 100%;
        padding: 0 30px;
        text-align: center;
        overflow: hidden;
        transition: 0.5s;
        text-decoration:none;
        
    }

    .card:hover .content {
        top: 130px;
        height: 250px;
    }

    .content h3 {
        font-size: 1.5rem;
        font-weight: 700;
        color: var(--clr);
    }

    .content p {
        color: white;
    }

    .content a {
        display: inline-block;
        padding: 12px 25px;
        text-decoration: none;
        background: var(--clr);
        color: white;
        font-weight: 500;
    }

    .content a:hover {
        opacity: 0.8;
    }

    @media (max-width: 480px) {
        .card {
            width: 230px;
            border-radius: 15px;
        }

        .img-box {
            width: 185px;
            border-radius: 10px;
        }

        .content p {
            font-size: 0.8rem;
        }

        .content a {
            font-size: 0.9rem;
        }
    }
</style>
<body>
<div class="container">
    <!-- InsightConnect Experience Card -->
    <div class="card" style="--clr: #FF3E7F">
        <div class="img-box">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ6PdmNFJGjqq3AQJaxb1Fbe7r_UCmv08XA0g&s" alt="InsightConnect Experience">
        </div>
        <div class="content">
            <h3>InsightConnect Experience</h3>
            <p>
                Automated multi-country alert processing, integrating APIs to streamline user account disablement and incident handling.
            </p>
            <a href="#expDetails">Read More</a>
        </div>
    </div>
    <!-- Swimlane Experience Card -->
    <div class="card" style="--clr: #009688">
        <div class="img-box">
            <img src="https://pbs.twimg.com/profile_images/1222923017837318147/L__x9si5_400x400.jpg">
        </div>
        <div class="content">
            <h3>Swimlane Experience</h3>
            <p>
                I built a unified SOC control panel integrating Rapid7, Crowdstrike, and JIRA, automating workflows and saving the company over $300,000/year.
            </p>
            <a href="#expDetails">Read More</a>
        </div>
    </div>
    <!-- Python and Automation Skills Card -->
    <div class="card" style="--clr: #03A9F4">
        <div class="img-box">
            <img src="https://www.graphicdesigndegreehub.com/wp-content/uploads/2020/09/If-I-Do-Not-Like-Coding-is-a-Graphic-Design-Degree-Right-for-Me.jpg" alt="Python Automation">
        </div>
        <div class="content">
            <h3>Python & Dev Tool Skills</h3>
            <p>
                Developed custom Python & Frontend plugins for JIRA, Crowdstrike and internal tools, automating workflows and enhancing cloud infrastructure management.
            </p>
            <a href="#expDetails">Read More</a>
        </div>
    </div>
</div>
</body>












<h2 id="expDetails">Professional Portfolio: SecOps Automation and Custom Python Development</h2>

Throughout my career, I have consistently focused on streamlining SecOps processes through automation and custom development. My expertise in building scalable security platforms, integrating multiple security tools, and automating manual workflows has enhanced operational efficiency and delivered measurable financial savings. Whether working with **Swimlane**, **InsightConnect**, or **custom Python scripts**, my goal is to provide solutions that drive value for security teams while simplifying their operations.


<details>
<summary style="font-size:18px; color:#009688;"><strong>Rapid7 InsightConnect Automation Experience</strong></summary>
<p>

#### **Overview**

Prior to my work with Swimlane, I gained valuable experience in automating processes using Rapid7 InsightConnect. This experience laid the groundwork for my later automation efforts, with a focus on simplifying and improving alerting processes for a Managed Security Service Provider (MSSP).
#### **Key Contributions**

#### Alerting Stack Simplification 
Streamlined multi-country/suspicious authentication alerting by integrating various threat intelligence sources (e.g., whois lookups, threat feeds) and security tools such as Secure Web Gateway (SWG). Built automation workflows that compared incoming alerts against these sources, automatically disabling suspicious user accounts when necessary.

#### Automation and Integration
Leveraged APIs to automate workflows across multiple customers, deploying custom solutions for each. This required extensive testing, deployment, and administration of InsightConnect tooling.

#### User Interaction Automation
Developed automated user interaction workflows to handle customer outreach in the event of suspicious activity, ensuring prompt responses and reducing the manual workload on SOC teams.

#### **Challenges and Solutions**
A significant challenge was the need for customer-specific deployments of InsightConnect workflows. To address this, I developed scalable processes for API integration and automation that could be replicated across multiple environments.
</details>
<br>

<details>
<summary style="font-size:18px; color:#FF3E7F"><strong>Swimlane Automation Experience</strong></summary>

#### **Overview**
During my time as a Security Engineer, I played a key role in developing and optimising a custom Swimlane platform that streamlined SOC operations. My work on this project involved creating a unified control panel for analysts, integrating various security tools, and leveraging automation to enhance incident response and operational efficiency. The result was an advanced solution that not only reduced manual workloads but also delivered significant cost savings.

#### **Key Contributions**
- **Unified SOC Control Panel**  
   Developed a comprehensive SOC operations dashboard using **custom Python plugins** and **JavaScript widgets**. This interface enabled analysts to conduct investigative analysis from a single, streamlined platform, integrating data from multiple sources.
  
- **Integration of Multiple Security Platforms**  
   Integrated investigations from **Rapid7** and detections/incidents from **Crowdstrike**, managing multi-customer tenants with customer-specific indicators and automating event handling.
  
- **Automation Playbooks**  
   Designed and implemented automation playbooks that assessed incoming events and executed auto-closures based on customer-specific global artefacts. These playbooks reduced noise and flagged events requiring attention, creating workflows for recurring incidents.
  
- **Custom API Integrations**  
   Built custom Python API plugins to integrate with **JIRA** (primary customer ticketing system), **Crowdstrike**, and **Rapid7**. Automated updates across these systems to ensure consistent communication between sources, with synchronised comments across all platforms.

- **Threat Intelligence Integration**  
   Automated threat intelligence lookups by integrating sources such as **Crowdstrike**, **Rapid7**, and community intelligence feeds. This provided real-time context and confidence ratings, simplifying decision-making for analysts.
  
- **Action Buttons and Pre-Built Templates**  
   Created custom action buttons for **disabling users** and **network containment**, enabling analysts to take immediate action. Developed email templates that auto-populated from customer-specific global artefacts, streamlining communication.

#### **Results**
- **Dashboard and Reporting**  
   Built custom dashboard views for **Analysts**, **Managers**, and **POC customers**. These dashboards provided clear metrics on incident response efficiency and demonstrated the financial benefits of automation.
  
- **Cost and Time Savings**  
   Over a 12-month period, the Swimlane solution saved over **$300,000 USD** in manual labour by reducing the time required for incident management. This resulted in greater efficiency, allowing analysts to focus on real investigations and high-priority tasks.
  
- **Onboarding Efficiency**  
   Simplified onboarding for new analysts by centralising workflows into a single interface, reducing the need for in-depth knowledge of underlying platforms like Crowdstrike and Rapid7.
</details>
<br>

<details>
<summary style="font-size:18px; color:#03A9F4"><strong>Relevant Python and Development Skills</strong></summary>

#### **Python Development**  
- **Custom Python API Plugins**  
   Developed plugins for Swimlane that integrated with external tools such as **JIRA**, **Crowdstrike**, and **Rapid7**, facilitating automation of investigation workflows, record updates, and synchronisation across platforms.
  
- **Automation Scripts**  
   Wrote Python scripts for various security tasks, including **automated lookups**, **event triaging**, and **workflow management**, which streamlined manual tasks and improved response times.
  
- **Infrastructure as Code (IaC)**  
   Experience in leveraging Python within **Infrastructure as Code** (IaC) environments to automate the deployment of cloud infrastructure and security policies, contributing to overall system reliability and efficiency.

#### **Other Programming and Technical Skills**  
- **JavaScript/Frontend Development**  
   Utilised **JavaScript** and **HTML** and **CSS** practices to create custom widgets for Swimlane’s frontend, as well as other projects like SOCAPPS, an internal developed offering for customers attack surface management where I utilised tools like **Flask** The focus being to ensure seamless integration between the user interface and backend automation scripts.
  
- **CI/CD Pipeline Management**  
   Managed **CI/CD pipelines** to support automated code deployments using a company managed Gitlab instance, ensuring consistent updates across cloud environments and the Swimlane platform.
  
- **Cloud Technologies**  
   Experience with cloud platforms and various plugins, including **AWS** and **Azure**, in conjunction with security automation and incident response workflows.
</details>

<br>
<br>

<div align="center">
<h2>Latest Hobby Projects</h2>

[![Count Down Timer](https://img.shields.io/badge/Latest-Count_Down_Timer-orange?style=for-the-badge&logo=firebase&logoColor=white&color=orange)](https://github.com/Zero2164/HTML-CSS-JS-Projects/tree/main/countdown_timer) 



<!-- Repos -->
 <h2>Repositories</h2>


### Projects

##### Keeping track of my projects large and small

[![repo - HTML-CSS-JS-Projects](https://img.shields.io/badge/Repo-HTML_CSS_JS_Projects-100000?style=for-the-badge&logo=HTML5&logoColor=white&color=00C878)](https://github.com/Zero2164/HTML-CSS-JS-Projects)
[![repo - Svelte-Projects](https://img.shields.io/badge/Repo-Svelte_Projects-100000?style=for-the-badge&logo=Svelte&logoColor=white&color=00C878)](https://github.com/Zero2164/Svelte-Projects)
[![repo - Python-Projects](https://img.shields.io/badge/Repo-Python_Projects-100000?style=for-the-badge&logo=Python&logoColor=white&color=00C878)](https://github.com/Zero2164/Python-Projects) 
[![repo - Powershell-Projects](https://img.shields.io/badge/Repo-Powershell_Projects-100000?style=for-the-badge&logo=Powershell&logoColor=white&color=00C878)](https://github.com/Zero2164/Powershell-Projects)





### Code Challenges

##### Challenges I've mucked in on

[![repo - Frontend-Challenges](https://img.shields.io/badge/Repo-Frontend--Challenges-100000?style=for-the-badge&logo=Codepen&logoColor=white&color=Eedf51)](https://github.com/Zero2164/Frontend-Challenges)


### Learning

##### Coding courses / tutorials I've taken part in
  
[![repo - Coursera-Courses](https://img.shields.io/badge/Repo-Coursera_Courses-100000?style=for-the-badge&logo=Coursera&logoColor=white&color=268694)](https://github.com/Zero2164/Coursera-Learning) 
[![repo - Udemy-Courses](https://img.shields.io/badge/Repo-Udemy_Courses-100000?style=for-the-badge&logo=Udemy&logoColor=white&color=268694)](https://github.com/Zero2164/Udemy-Learning)
[![repo - Youtube-Courses](https://img.shields.io/badge/Repo-Youtube_Courses-100000?style=for-the-badge&logo=Youtube&logoColor=white&color=268694)](https://github.com/Zero2164/Youtube-Learning)
[![repo - CodeWars](https://img.shields.io/badge/Repo-CodeWars_Challenges-100000?style=for-the-badge&logo=codewars&logoColor=white&color=268694)](https://github.com/Zero2164/codewars)
<br>

<!-- CONTACT ME -->

 <h2>Connect with me</h2>
 
 
[<img width="60px" src='https://cdn-icons-png.flaticon.com/512/1383/1383262.png' alt='k_linkedin'/>](https://www.linkedin.com/in/kyle-lamont-a72326152)///////
[<img width="60px" src='https://cdn-icons-png.flaticon.com/512/3447/3447695.png' alt='k_email'/>](mailto:kylejlamont@hotmail.com)///////

</div>

<!-- Icon Images provided by: https://www.flaticon.com/ -->
