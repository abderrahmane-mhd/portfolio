---
title: Kairos Club App
date: 2020-05-13T12:49:27.000+06:00
thumbnail: images/portfolio/portfolio-1.png
service: Development
client: Kairos Club
shortDescription: Kairos Club App is the first step of an evolving application for Kairos Club  retailers. It offers inventory management, sales analysis, financial statements, and will eventually allow predictive actions based on statistics collected in the application.
challenge: The App is based on different APIs, because the products sold has two formats  Digital via Spotify, Apple Music... and Physical products through e-commerce websites. The problem was linking the two channels and collecting data from different APIs (Shopify,...).
solution: Created Python CronJobs which runs periodically in order to fetch data from several APIs and stores them in the KairosClubApp database.

---
The App is a great tool for the clients of Kairos Club to get specific and accurate analytics about their sales, best products, informations about the current state of their inventory and Customers listing. The App generates also financial statements every month.
### Presentation of the different sections of the app :
- **Statistics** has 14 different types of charts which includes Maps, Timeseries and DoghnutCharts...
- **Inventory** displays a listing of all the digital and physical products of the supplier with the current state of inventory in each warehouse and the gross income.
- **Customers** displays a listing of all the customers with some statistics such as the number of passed orders, and the total amount spent.
- **Statements** displays the financial statements of each month with the payment status.

### The technologies used : 
Laravel a PHP framework, Vue.js, TailwindCss, Python for cronJobs, mysql database with Redis for caching and queues and AWS (S3 and EC2).