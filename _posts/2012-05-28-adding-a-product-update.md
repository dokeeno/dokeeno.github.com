---
layout: post
title: Adding a product update
---

Just click on an **Add New** button on our Product Update tab in the Dashboard (as shown below).

![Add Product Updates](/images/getting-started/product-updates.png)

Then you'll see a screen like this

![Product Update Page](/images/adding-a-update/add-update.png)

Fields in the above form are described below.

##1.Title
The title of the Update. This will be shown in the Dashboard as well as the title of the Documentaton.

##2. Notify Text
Every Update will be delivered to the customer using a notification. This will be the text apear on there.

##3. Feature URL
This is the URL customer will be redirected when he click on the notification. URL can be either internal or external.

###Internal
URL exists within your application domain. Example internal URL is shown below.
	
	/user/newFeature.html

###External
URL exists outside of your domain. Example external URL is shown below
	
	http://blog.myapp.come/new-annoucement.html

Leave it blank if you do-not need to redirect your customer

##4. Feature Element
**This only apply if your feature URL is an internal one**

Once redirected dokeeno [can focus](/images/product-tour/navigated.png) the HTML DOM element where the feature exists. Specify the element using CSS selectors here. Leave it blank if you do not need to focus. E.g. :-

	.content #feature

##5. Documentation
This is the documentation where customer can learn about the feature or the announcement. You can enter the documentation using [markdown](http://daringfireball.net/projects/markdown/syntax) syntax.