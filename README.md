QueryStringCondition.cs - class that implements logic for personalization in Sitecore based URL Query string parameters.

Instructions:

1. Create an item under/sitecore/system/Settings/Rules/Conditional Renderings/Conditions folder in Sitecore
2. Enter your class and assembly into Type field and the following value into text field:
	Where the QueryString Parameter [QueryStringName,,,QueryString Name] has a value that [operatorid,StringOperator,,compares to] [QueryStringValue,,,QueryString Value]

3. Compile your project and publish condition definiion item to your targets (if required)

Now, you may personalize Sitecore based on URL query stribng parameters!

Please read a blog post with more details on how it works:
	http://blog.martinmiles.net/post/rules-engine-and-sitecore-personalization-based-on-url-query-string-parameters


Hope this helps!