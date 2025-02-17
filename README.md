### **👩‍💻 My Role in the Project**

I contributed as a **Full-Stack Developer & Data Engineer**, working on **data crawling, processing, backend development, visualization, and frontend implementation**.

#### **Key Contributions:**
- **Developed Web Crawling System** → Used **PySelenium** to collect Instagram data, including followers, following, and liked users.
- **Designed and Optimized Data Processing Pipelines** → Processed and structured data using **Pandas** for efficient analysis.
- **Implemented Backend with Django** → Developed **REST API** and server-side logic to handle data processing and provide analysis results.
- **Built Data Visualization Features** → Created insightful visualizations using **Matplotlib** to represent social network interactions.
- **Developed User Interface** → Designed and implemented **HTML & CSS** frontend to display analysis results in an interactive way.
- **Version Control & Team Collaboration** → Used **Git/GitHub, Notion, Slack, and VSCode** for team coordination, documentation, and project management.

---

# Insta-Lens

## **📌 Project Overview**

### **Background & Introduction**  
Instagram has become an essential platform for both personal users and businesses as a marketing and communication tool. The interactions on this platform play a key role in shaping and strengthening relationships among users. This project aims to provide insights by collecting and analyzing data on followers, following relationships, and user engagement with posts through Instagram crawling.

### **Reason for Selection**  
While Instagram users generate massive amounts of information, there is a lack of tools that effectively analyze this data. Understanding follower and following relationships and analyzing user engagement with posts can provide valuable insights for social network management. This project was selected to help users build better communication strategies based on these insights.

### **Goals & Expected Outcomes**  
The primary goal of this project is to visualize follower and following relationships and analyze user engagement trends. Through this, users can gain a clear understanding of their network and analyze interaction patterns. Ultimately, the project aims to enhance user experience and contribute to improving marketing strategies for individuals and businesses.

---

## **🛠️ Technologies & Frameworks**  

| Category | Technologies & Frameworks | Description |
| --- | --- | --- |
| **Crawling** | PySelenium | Automatically navigates Instagram pages to collect desired data (followers, following, likes). |
| **Data Processing** | Pandas | Structures and organizes collected data for analysis. |
| **Backend** | Django | Implements server-side logic for data processing and provides analysis results through a web application. |
| **Frontend** | HTML, CSS | Creates the user interface to visually display analysis results. |
| **Visualization** | Matplotlib | Visualizes follower, following relationships, and liked user analysis results using graphs. |
| **Collaboration & Communication** | Git/GitHub, Notion, Slack, VSCode | Used for version control, task scheduling, and real-time communication within the team. |

---

## **🖥️ Project Details & Source Code**  

The Insta-Lens project is divided into four main parts:

1. **Crawler:**
    - Uses functions like `get_data()`, `get_followers()`, `get_following()`, and `get_likes()` to collect user account information.
    - Crawls data on users who liked posts, followers, and followings using Selenium.

2. **Data Model:**
    - The Django models `User` and `Friendships` store user account information and social relationships.
    - `User` represents an Instagram account, while `Friendships` stores friend details, including their username, follower/following status, and like counts.

3. **Backend:**
    - The Django views handle input, retrieve Instagram account data (`getInput`), save crawled data, and create a database (`createDatabase`).
    - Displays user interaction insights such as unfollowed users (`find_unfollow_list`) and liked user statistics (`show_liked_stats`).

4. **Frontend:**
    - Django templates (`account_input.html`, `crawled_result.html`, `show_unfollow_list.html`, `show_liked_status.html`, `user_overview.html`) present data and analysis results.



