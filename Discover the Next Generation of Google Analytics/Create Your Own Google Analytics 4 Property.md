2023-03-23

##  Analytics property structure

![[Pasted image 20230323155636.png|500]]

### Data Streams

- Data streams are a feature of GA4 properties that allow you to connect a single Analytics property to the various places where your users interact with your business. For example, a company that has both a website and an app would need a separate data stream for each platform to combine their reporting and insights into a single Analytics property.
- As you set up your Analytics account, consider how to map it to your existing business structure so you can collect and analyze data in the way that makes the most sense for your business.

	EX) Aria only has one website, she only needs one data stream. 
	Her Analytics account should look like this:
	- One Analytics account
		- One GA4 property
			- One data stream for her website`

	EX) Jasmeet created a mobile racing game for both Android and iOS. He needs two data streams — one for Android and one for iOS. His Analytics account should look like this:
	- One Analytics account
		- One GA4 property
			- One app data stream for his Android game
			- One app data stream for his iOS game

	EX) Claire is the CEO of a soap-making business that has a website and an Android app. Claire's business has both a website and a mobile app, she'll need a data stream for each. Her Analytics account should look like this:
	- One Analytics account
		- One GA4 property
			- One web data stream for her website
			- One app data stream for her app

EX) Roberto owns a restaurant chain. To make it easy for his customers to order food online, he has a website, an Android app, and an iOS app. When setting up his new property, Roberto should create:
	- One Analytics account
		- One GA4 property
			-   One web data stream for his website
			-   Two app data streams, one for each of his apps


### How to set up a Google Analytics 4 property

**Step 1 — Open your Google Analytics account**
	`Go to google.com/analytics to create a new Analytics account, or sign in to your existing account and go to your account settings.`

**Step 2 — Create a GA4 property**
	`Enter your business’s information for your new property. New properties created in Analytics are GA4 properties by default.`

**Step 3 — Create a data stream**
	`Choose the platform for your data stream — iOS, Android, or web — and enter the information for your app or website.`
	`If you’re creating a web data stream, you’ll see an option called "enhanced measurement." Keep this on to automatically collect pageviews, scrolling, outbound link clicks, site searches, and other common user events. You can disable or re-enable enhanced measurement at any time.`

**Step 4 — Enable data collection
	`Web: Follow the steps in the following guides to make sure your website contains the appropriate tags.`
		- Gtag.js users: To manually deploy your Analytics code to your website with gtag.js, follow this [developer guide](https://developers.google.com/analytics/devguides/collection/app-web).`
		- Google Tag Manager users: To deploy your Analytics code to your website using Google Tag Manager, follow this [Help Center guide](https://support.google.com/tagmanager/answer/9442095).
	App: Follow the steps outlined in this [Help Center guide](https://support.google.com/analytics/answer/9304153) to create an app data stream.