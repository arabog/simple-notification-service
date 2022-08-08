# Introduction
Things to do:  
send alerts via SNS by creating a topic,     
subscribing to a topic,   
and publishing an alert message to a topic  


## Step 1. Create a Topic
From the AWS Management Console page, select the SNS service.  
On the left-hand navigation pane, click on the Topics service, 
and start the Create topic wizard.  
In the Details section, enter a topic name of your choice  
In the Access policy – optional section, use the following 
configuration to create the topic:  

![topic](topic.png?raw=true "topic")

![policy](policy.png?raw=true "policy")


## Step 2. Subscribe to a Topic
While you are viewing the details of the newly created topic, start the Create subscription wizard, and use the following details:

![sub](sub.png?raw=true "sub")

The subscription page will display, and the status will be Pending confirmation. You will receive an email from Amazon SNS to confirm the subscription. Confirm the subscription.
In your web browser, a subscription confirmation screen appears.  

![pending](pending.png?raw=true "pending")

![confirm](confirm.png?raw=true "confirm")

## Step 3. Publish Message to a Topic
Go back to the Topics service.  
Select the topic you created earlier and Publish a message with the following details:  

![msg](msg.png?raw=true "msg")

![attr](attr.png?raw=true "attr")

In your email client, you will receive an email from AWS Notifications (no-reply@sns.amazonaws.com)

![email](email.png?raw=true "email")