2023-03-23

### Google Analytics Property

- **Universal Analytics properties:** Also known as UA properties, this is the term for the existing web-only Analytics property type.
- **Google Analytics 4 properties:** Also known as GA4 properties, this Analytics property type can process data from both websites and apps. Plus it has many new features for all Analytics users.
- Note that in the past, there was a separate property type, called Google Analytics for Firebase, which was only for apps, but now these properties have been upgraded to GA4 properties.

![[Pasted image 20230323133037.png]]



### Advanced features available to all Analytics accounts

Several powerful features are available to everyone using the latest Google Analytics experience. These include:
-   **Explorations:** Interpret your data with greater freedom using the Explorations tool. Use a variety of techniques, like funnel exploration, path exploration, and free form exploration to uncover insights.
-   **BigQuery Export:** Export your Analytics data to BigQuery so you can securely store your data in the cloud, combine it with data from other sources, and run queries across all your data sets. Or move your data to any other system where you want to use it.

### Data collection process

###### **The session-based model**
 - In UA properties, Analytics groups data into _sessions_, and these sessions are the foundation of all reporting. A session is a group of user interactions with your website that take place within a given time frame. 
 - During a session, Analytics collects and stores user interactions, such as pageviews, events, and eCommerce transactions, as hits. A single session can contain multiple hits, depending on how a user interacts with your website.
###### **The event-based model**
 - In GA4 properties, you can still see session data, but Analytics collects and stores user interactions with your website or app as _events_. Events provide insight on what's happening in your website or app, such as pageviews, button clicks, user actions, or system events.  
 - Events can collect and send pieces of information that more fully specify the action the user took or add further context to the event or user. This information could include things like the value of purchase, the title of the page a user visited, or the geographic location of the user.+

### Types of Identities
 - User-ID
	 - If you create your own persistent IDs for signed-in users, you can use this data to accurately measure user journeys across devices. To enable the User-ID feature, you must consistently assign IDs to your users and include the IDs along with the data you send to Analytics.
- Google signals
	- Google signals uses data from users who are signed in to Google. With Google signals enabled, Analytics associates event data it collects from users on your site with the Google accounts of signed-in users who have consented to sharing this information. Enabling Google signals is very simple. You don’t have to make modifications to your website or app to get started with this feature — just turn it on!
- Device ID
	- Analytics can also use device ID as an identity space. On websites, the device ID comes from the user’s browser. On apps, the device ID comes from app-instance ID. You don't need any further setup in Google Analytics to use device ID.

### Key takeaways

-   The GA4 property type is the next generation of Google Analytics and is designed to scale with your business and measure across devices and platforms.
-   GA4 properties are built to handle data from both websites and apps.
-   The latest Analytics experience is fully operational today, but new features and innovations are still being added.
- With GA4 properties, it’s easy to create new audiences, and you have more options when defining and segmenting these audiences.
-   GA4 properties collect and store user interactions with your business as events instead of sessions. This allows Analytics to be more flexible and scalable, and to perform more custom calculations, faster. 
-   GA4 properties combine the use of several different user identity spaces. This gives better insight into user journeys, with more robust cross-device and cross-platform data and reporting that reflects de-duplicated users.

### Resources
To learn more about the newest innovations in Google Analytics, select the links below.

[Google Analytics products | Official Blog ↗](https://blog.google/products/marketingplatform/analytics/)

[What’s new in Google Analytics | Help Center ↗](https://support.google.com/analytics/answer/9164320)

![](https://skillshop.exceedlms.com/uploads/resource_courses/targets/928605/original/course/en/assets/5e18a7099b6c897d96ca0330/original.gif)


GPT QS

## What is the difference between bigquery vs sql database?
- BigQuery and SQL databases are both used to store and manage large amounts of data, but there are some key differences between the two.

1.  Architecture: BigQuery is a cloud-based data warehouse that is designed to store and analyze large amounts of data using a distributed architecture. SQL databases, on the other hand, can be deployed on-premises or in the cloud, and are designed to be used with a single server.
    
2.  Scalability: BigQuery is highly scalable and can handle petabyte-scale datasets with ease. SQL databases can also scale, but usually require additional hardware and infrastructure to handle large datasets.
    
3.  Querying: BigQuery uses a SQL-like syntax called BigQuery SQL, which is optimized for large datasets and can run complex queries quickly. SQL databases use standard SQL, but may not be optimized for large datasets.
    
4.  Pricing: BigQuery is a pay-per-use service, meaning that you only pay for the queries you run and the amount of data stored. SQL databases usually require an upfront investment for hardware and infrastructure, as well as ongoing maintenance and support costs.
    

Overall, BigQuery is ideal for organizations that need to store and analyze large amounts of data quickly and efficiently, while SQL databases are better suited for smaller datasets or applications that require a traditional database architecture.


## Difference between developer's role and marketer's role in GA4?
- In Google Analytics 4 (GA4), the developer's role and marketer's role are quite different. Here are some key differences:

1.  Implementation: The developer's role in GA4 is to ensure that the tracking code is properly implemented on the website or app. This involves setting up event tracking, custom dimensions, and other advanced features. Marketers may not have the technical expertise to handle these tasks and would rely on the developer to ensure accurate tracking.
    
2.  Data quality: Developers play a critical role in ensuring that the data collected in GA4 is accurate and reliable. They must test the tracking code thoroughly and ensure that it is working as intended. Marketers, on the other hand, use the data collected by GA4 to make informed decisions about their marketing campaigns.
    
3.  Analysis: Marketers use GA4 to analyze data and gain insights into user behavior, engagement, and conversions. They use this data to optimize their marketing campaigns and improve the user experience. Developers, however, may not be involved in the analysis process, as their role is focused on ensuring that the tracking code is working properly.
    
4.  Customization: Marketers can use the GA4 interface to customize reports, create audiences, and set up conversion tracking. Developers, on the other hand, may need to create custom code or use the GA4 API to build custom integrations with other tools or platforms.
    

Overall, the developer's role in GA4 is focused on ensuring accurate tracking and data quality, while the marketer's role is focused on using that data to drive business outcomes through analysis and optimization.