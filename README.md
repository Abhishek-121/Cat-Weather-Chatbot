
# Static Website

The goal of this website is to support the learning of the Building Serverless Applications course.

This folder is designed to be downloaded locally and then uplaoded as is to S3, strictly following the instructions in the excercise guide.,


Thought the lab you may need to edit a config file. Simpy replace the `null` with with your content.

For example inside config.json you would replace

```JavaScript
		var G_API_GATEWAY_URL_STR = null;
```

with

```JavaScript

		var G_API_GATEWAY_URL_STR = "https://eois2fhvse.execute-api.us-east-1.amazonaws.com/test"
```
according to the excercise guide.


Then push that back up to the root of the website.

