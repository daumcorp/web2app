# Web2App Library

Launch an mobile app. from a webpage


```javascript
daumtools.web2app({
	urlScheme : '',									// iphone : custom scheme
	intentURI : '',									// android : intent URI
	appName   : '', 								// application Name (ex. facebook, twitter, daum)
	storeURL  : '',									// app store URL
	willInvokeApp : function() {},					// function for logging
	afterInvokeApp : function() {},					// function invoked after logic
	onAppMissing  : function() {},					// fallback function (default. move to appstore)
	onUnsupportedEnvironment : function() {}		// fallback function
});
```

Dependency : [ua_parser](https://github.com/daumcorp/ua_parser)
