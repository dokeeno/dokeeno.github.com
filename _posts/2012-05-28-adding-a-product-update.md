---
layout: post
title: Adding a product update
---

Just click on an **Add New** button on our Product Update tab in the Dashboard (as shown below).

![Add Product Updates](/images/getting-started/product-updates.png)

Then you'll see a screen like this

![Product Update Page](/images/adding-a-update/add-update.png)

Field in the above form is described below.

##1.Title
The title of the Update. This will be shown in the Dashboard as well as the title of the Documentaton.

##2. Notify Text
Every Update will be delivered to the customer using a notification. This will be the text apear on there.
Try to add some text interesting.

##3. Feature URL
This is the URL customer will be redirected when he click on the notification. Leave it blank if you do-not need to redirect.
And also URL should be exits on your domain as the app exists. E.g. :-

	/user/newFeature.html

##4. Feature Element
Once redirected dokeeno can focus the element where the feature exists. Specify the element using CSS selectors here. Leave it blank if you do not need to focus. E.g. :-

	.content #feature

##5. Documentation
This is the documentation where customer can learn about the feature or the announcement. You can enter the documentation using popular [markdown](http://daringfireball.net/projects/markdown/syntax) syntax.