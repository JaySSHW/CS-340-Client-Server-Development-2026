# CS 340 – Client/Server Development

## Project Overview

Throughout CS 340, I developed my understanding of client/server development by working with MongoDB, Python, and interactive data visualization tools. For Project One, I created a Python CRUD (Create, Read, Update, Delete) module to interact with a MongoDB database containing animal shelter records. In Project Two, I applied this module to develop an interactive dashboard for Grazioso Salvare, an organization that identifies shelter dogs suitable for search-and-rescue training.

The dashboard incorporated database connectivity, interactive filtering, a data table, and a geolocation map to help users identify animals based on specific rescue-training criteria. These projects strengthened my ability to develop database-driven applications, organize reusable code, and translate client requirements into functional software solutions.

## How Do You Write Programs That Are Maintainable, Readable, and Adaptable?

I believe writing maintainable, readable, and adaptable programs begins with organizing code into smaller, reusable components that each serve a specific purpose. Throughout CS 340, I learned the importance of separating database operations from the application's user interface. In Project One, I developed a Python CRUD module that handled communication with MongoDB. Rather than writing database queries directly into every dashboard component, I could reuse the module in Project Two to retrieve and manage animal shelter records.

One of the greatest advantages of this approach was that it made the dashboard easier to develop, troubleshoot, and maintain. For example, when working on the interactive data table and geolocation map, I could focus on filtering records, handling callbacks, and displaying information without having to rebuild the database connection. This separation also made identifying errors easier because I could examine the database operations and dashboard functionality independently.

In the future, I could adapt this CRUD module for other database-driven applications, including inventory management systems, customer databases, and business reporting dashboards. By modifying the database configuration and adapting the queries to different collections, I could reuse the same general structure. This experience reinforced the importance of modular programming, clear naming conventions, documentation, and designing software with future changes in mind.

## How Do You Approach a Problem as a Computer Scientist?

My approach to solving problems as a computer scientist involves understanding the requirements, breaking complex problems into manageable tasks, implementing solutions, and testing the results. When developing the Grazioso Salvare dashboard, I began by considering how the organization needed to search and analyze animal shelter records to identify potential candidates for rescue training. This required more than simply retrieving information from a database. I needed to determine how the information could be filtered, organized, and presented in a way that supported the client's goals.

I approached the project in stages, beginning with importing and verifying the animal shelter data in MongoDB. I then developed the CRUD module, established the database connection, and integrated the data into the dashboard. After implementing the interactive table, I worked on the filtering functionality and geolocation visualization. During development, I encountered challenges involving callback functions, selected table rows, and map behavior. I addressed these issues by reviewing the code, examining the relationships between components, making targeted corrections, and testing the application again.

This project differed from some of my previous programming assignments because it required several technologies to work together as one application. Rather than focusing primarily on individual programming concepts, I had to consider database design, application architecture, user interaction, and the client's operational needs simultaneously.

For future projects, I would continue using an incremental development approach while placing additional emphasis on planning database structures, validating data, documenting requirements, and testing individual components before integrating them. I would also consider performance, security, and scalability early in development to ensure the application can continue meeting client needs as those requirements evolve.

## What Do Computer Scientists Do, and Why Does It Matter?

Computer scientists use technology, algorithms, data, and logical problem-solving to develop solutions that improve how people and organizations work. Their responsibilities extend beyond writing code. They analyze problems, design systems, evaluate alternatives, test solutions, and continually improve applications to ensure they are reliable, efficient, and useful.

The Grazioso Salvare project demonstrated how computer science can transform large amounts of raw data into meaningful information. By developing an interactive dashboard connected to a MongoDB database, I helped create a system that allows users to explore animal shelter records, apply search-and-rescue criteria, and view geographic information about selected animals. Instead of manually reviewing large datasets, an organization could use this type of application to narrow its search and make more informed decisions.

For an organization like Grazioso Salvare, this technology could reduce the time required to identify potential rescue-training candidates, improve consistency in evaluating records, and support more efficient use of organizational resources. Although the dashboard cannot independently determine whether an animal is suitable for rescue work, it can provide valuable information to assist the people making those decisions.

This course helped me recognize that successful software development is not simply about making a program function correctly. It is also about understanding who will use the application, why they need it, and how the solution can create meaningful value. As I continue working toward my career in software engineering, I want to apply these principles to develop applications that are maintainable, practical, and capable of solving real-world problems.
