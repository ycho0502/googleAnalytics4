2023-03-29

#### Understand the Analytics account structure  
  
You can use Analytics exclusively for web data, exclusively for app data, or for both app and web data together. You can also create one property per account, or you can nest multiple properties under the same account. It's important to understand your options so you set up your Analytics account in a way that matches your business needs.

**Analytics account**
	An Analytics account is your gateway to Analytics. An account can include multiple properties and property types, but a property can belong to only one Analytics account.
**Property**
	A property lives within an account. Properties are the containers for your reports based on the data you collect from your apps and sites. It's the level at which Analytics processes data and where Analytics can connect with other Google products, like Google Ads.
**Data stream**
	A data stream lives within a property and is the source of data from your app or website. A property can have one or many data streams.


## Identity spaces in Analytics

When trying to understand user journeys, your Analytics property can use several different user identifiers, such as the IDs you assign users logged into your website, Google signals, and device ID. These groups of identifiers are called identity spaces.

**User-ID**
	If you create your own persistent IDs for signed-in users, you can use this data to accurately measure user journeys across devices. To enable the User-ID feature, you must consistently assign IDs to your users and include the IDs along with the data you send to Analytics. To learn more about the User-ID feature, visit this [Help Center article](https://support.google.com/analytics/answer/9213390).

**Google signals**
	Google signals uses data from users who are signed in to Google. With Google signals enabled, Analytics associates event data it collects from users on your site with the Google accounts of signed-in users who have consented to sharing this information.
	Enabling Google signals is very simple. You don’t have to make modifications to your website or app to get started with this feature — just follow the instructions in this [Help Center article](https://support.google.com/analytics/answer/9445345#zippy=%2Cin-this-article) to enable this in your property settings.

**Device ID**
	Analytics also automatically uses device ID as an identity space. On websites, the device ID comes from the user’s browser. On apps, the device ID comes from app-instance ID. You don't need any further setup in Analytics to use device ID.


#### Joining forces

In Analytics, data is processed using all available identity spaces. First, Analytics looks for User-ID because this feature uses the data you collect. Next, it tries Google signals, and finally, if there isn't a match for either, it relies on the device ID. From there, Analytics creates a single user journey from all the data associated with the same identity. 

Because these identity spaces are used in all reports, they allow you to de-duplicate users and tell a more unified, holistic story about their relationships with your business.