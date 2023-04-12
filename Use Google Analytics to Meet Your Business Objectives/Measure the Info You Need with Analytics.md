2023-03-29

### Analytics collects data as events

Analytics collects and stores user interactions with your website or your app as events. Events provide insight into what's happening on your website or app, such as page views, button clicks, user actions, or system events.

If you have a website and an app, it’s important to measure a diverse range of user interactions to better understand how people engage with your business across these platforms. For example, you could measure:
-   Clicks and pageviews on your website
-   Installs and opens on your app
-   User engagement and conversions on either platform
By collecting data as events, Analytics combines app and web data in a common language in your reports.


### Key concepts: data collection fundamentals

Events are the backbone of how Analytics collects and processes data. However, Analytics collects and measures a few other pieces of info along with events to give you the full picture of how your customers interact with your business.

- **User properties** are attributes about who's using your app or website that can help you better understand segments of your user base, like geographic location or device used.
- **Events** are user interactions with a website or app that can be measured, like a video view.
- **Event parameters** are additional pieces of information, sent with events, that can further specify the action the user took, or add further context to the event, like the name of the video or how long the user watched it.
- A **conversion** is a type of event: Conversions are events that you've assigned a specific value, like a purchase or a download. You can measure many events, just be sure to mark the most important ones as conversions.


## Creating events

Many basic interactions with your website or app are automatically collected as events in Google Analytics. But to be sure you're measuring the things that matter to your business, you'll likely need to create some more events as well.
https://youtu.be/WVqJjLbd8mc


## Understanding dimensions and metrics

First, Analytics collects these user interactions as events, event parameters, and user properties. Then, it compiles all this data into reports. To represent this data in these reports, Analytics uses dimensions and metrics. That means for every automatically collected event parameter and user property, Analytics automatically creates a dimension or metric.

So, what are dimensions and metrics?

Dimensions answer the question “who, what, or where?” while metrics answer the question “how many?” For example, dimensions answer the question, “what device is most commonly used?” while metrics answer the question, “how many users visited my site yesterday?”


## What about sessions?

In Universal Analytics properties, Analytics groups data into sessions — these sessions are the foundation of all reporting in UA. A session is a group of user interactions with your website that take place within a given time frame. 

In GA4 properties, events — not sessions — are the basis of reporting, but you can still report on sessions in GA4. However, they are calculated differently from sessions in UA. To learn more about how sessions are calculated in GA4, visit this [Help Center article](https://support.google.com/analytics/answer/9191807).

Because sessions are the basis of reporting in UA, you can create session-scoped dimensions and metrics in UA. But because sessions aren't the basis of reporting in GA4, you can't create session-scoped dimensions and metrics in GA4. To learn more about how data is collected in GA4 and UA, visit this [Help Center article](https://support.google.com/analytics/answer/9964640#zippy=%2Cin-this-article).