2023-03-30

#### Get to know conversions and events in Google Analytics

Conversions are user activities that contribute to the success of a business. In Google Analytics, measure those activities using conversion events. Remember, the backbone of Google Analytics data is events, which Analytics collects and stores as users interact with a website or app. Conversions are a subset of those events and should be events that are most valuable to your business.


#### How to create and mark events as conversions

You need [Edit permission](https://support.google.com/analytics/answer/9305587) to mark an event as a conversion. Mark an existing event as a conversion, or create or modify an event and mark that as a conversion.
To mark any of your existing events as a conversion:
1.  Sign in to Google Analytics
    
2.  Select your property
    
3.  In the left pane, select **Configure** which will by default show you the Events page
    
4.  Locate the event in the table and turn on **Mark as conversion**
Once you mark an event as a conversion, it appears in the Conversions page. New conversions may take up to 24 hours to appear in reports. If you don't see conversion data within this time frame, [confirm that your data is being collected](https://support.google.com/analytics/answer/9333790).

Marking an event as a conversion doesn't affect data you've already collected, it only applies to new data.


#### Modeled conversions

Google uses modeling to predict online conversions that can’t be observed directly. Modeling allows for accurate conversion attribution without identifying users (for example, due to user privacy, technical limitations, or when users move between devices). Including modeled conversions lets Google offer more accurate reporting, optimize advertising campaigns, and improve automated bidding.


#### How modeled conversions work

Google’s models look for trends between conversions that were directly observed and those that weren’t. For example, if conversions attributed on one browser are similar to unattributed conversions from another browser, the machine learning model will predict overall attribution. Based on this prediction, conversions are aggregated to include both modeled and observed conversions.

## What's conversion modeling?

**Conversion modeling** is the use of machine learning to measure the impact of marketing efforts when a subset of conversions can’t connect to ad interactions.

-   A conversion is a type of event: Conversions are events that you've assigned a specific value, like a purchase or a download.
-   Conversion modeling is used when conversions can not be directly observed.
-   Google doesn’t allow fingerprint IDs or other attempts to identify individual users. Google uses modeled conversions only when there's enough data to confidently make a prediction.