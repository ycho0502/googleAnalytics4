2023-03-29

#### Set up an Analytics property with data streams

**Step 1 — Open your Analytics account** 
	Go to [analytics.google.com](http://analytics.google.com/) to create a new Analytics account, or sign in to your existing account and go to your account settings.

Step 2 — Create a GA4 property
	Enter your business’s information for your new property. New properties created in Analytics are GA4 properties by default.

Step 3 — Create a data stream
	Choose the platform for your data stream — iOS, Android, or web — and enter the information for your app or website.
	If you’re creating a web data stream, you’ll see an option called "enhanced measurement." Keep this on to automatically collect pageviews, scrolling, outbound link clicks, site searches, and other common user events. You can disable or re-enable enhanced measurement at any time.

Step 4 — Enable data collection
	**Web****:** You'll need to add the Analytics tag to your web pages to begin seeing data in your new GA4 property. Use the guide in this [Help Center article](https://support.google.com/analytics/answer/9304153?#add-tag) to make sure your website contains the appropriate tags. Note that there are different instructions depending on whether you use a CMS, the global site tag, or Google Tag Manager.  
	**App:** After you integrate the Firebase SDK with your app, basic app-usage data is collected automatically. Learn more about Analytics and Firebase integration in this [Help Center article](https://support.google.com/analytics/answer/9289234).