# News Website by DevArea

Project Overview

This project is a responsive news website developed using HTML, CSS, and JavaScript. It fetches and displays news articles from various categories and allows users to search for specific topics using the NewsAPI. The website is designed to be user-friendly and responsive, providing a seamless experience across different devices.

Creator

# Name: Ekansh Pratap Singh
# YouTube / Instagram : DevArea
Features
Category-Based News: Users can select news categories like IPL, Coding, Finance, and Politics.
Search Functionality: Users can search for news articles based on specific keywords.
Responsive Design: The website adapts to different screen sizes for a smooth user experience.
Real-Time Updates: News articles are fetched in real-time using the NewsAPI.
Setup Instructions
Download the Files:

Ensure you have the following files downloaded to a directory:
index.html
style.css
script.js
Open the HTML File:

Double-click the index.html file to open it in your default web browser. This will display the news website.
API Key Setup:

The website uses the NewsAPI to fetch news articles. Ensure you have an API key from NewsAPI.
Replace the placeholder API key in the script.js file with your actual API key:
javascript
Copy code
const API_KEY = "YOUR_ACTUAL_API_KEY_HERE";
File Structure
index.html: The main HTML file that structures the website.
style.css: The CSS file for styling the website.
script.js: The JavaScript file that handles fetching and displaying news articles.
Detailed Steps
HTML (index.html)
Structure:
Sets up the basic structure of the website, including a navigation bar, search bar, and a container for displaying news articles.
Template:
A <template> element is used to define the structure of a news card, which is cloned and populated with data dynamically.
CSS (style.css)
Styling:
Provides styles for various elements, including the navigation bar, search bar, news cards, and general layout.
Responsive Design:
Uses Flexbox to ensure the layout is responsive and adapts to different screen sizes.
JavaScript (script.js)
API Integration:
Fetches news articles from the NewsAPI based on the user's input or selected category.
Dynamic Content:
Functions dynamically create and display news cards based on the fetched data.
Event Handling:
Event listeners handle user interactions, such as searching for news articles or selecting a category.
ER Diagram
Since this project is a frontend application fetching data from an external API, there isn't a traditional database involved. However, an ER diagram for an expanded version of this project (including a backend) might include entities such as Users, Articles, Categories, and Searches.

lua
Copy code
Users -----< Searches >----- Articles -----< Categories
Data Flow Diagram (DFD)
Level 0 (Context Diagram)

scss
Copy code
[User] ---> (News Website) ---> [NewsAPI]
Level 1 (Decomposition)

User Interactions

User inputs a search query or selects a category.
User clicks on a news article to read more.
System Processes

Fetching news articles based on category or search query.
Displaying the fetched articles.
scss
Copy code
[User] ---> (Enter Search Query / Select Category) ---> (Fetch News Articles) ---> [NewsAPI]
          <--- (Display News Articles) <---
Conclusion
This project showcases the creation of a dynamic, responsive news website using HTML, CSS, and JavaScript. By integrating with the NewsAPI, it provides real-time news articles to users based on their preferences and search queries. The detailed documentation, ER diagram, and DFD provide a comprehensive understanding of the system's functionality and data flow.

Feel free to reach out if you have any questions or need further assistance.

Contact Information:

Email: Ekanshprataps@gmail.com
Youtube: www.youtube.com/@DevArea/

Thank you for checking out my project!

Ekansh Pratap Singh (DevArea)