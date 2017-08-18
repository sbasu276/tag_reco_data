# Tag recommendation data #
This repository contains the extracted data for software information sites in following JSON format.
```
{
	"body": "<text>",  
	"tags": ["<text>"],
	"title": "<text>"
}
```
For example,
```
{
	"body": "Every time I turn on my computer, I see a message saying something like: Your battery may be old or broken. I am already aware that my battery is bad. How do I suppress this message?",
	"tags": [
	    "power-management",
	    "notification"
	], 
	"title": "How to get the Your battery is broken message to go away?"
}
```
