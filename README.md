# How to add autoLink in android

<img src ="https://storage.googleapis.com/gweb-uniblog-publish-prod/images/android_ambassador_v1_cmyk_200px.max-2800x2800.png" height="250" width="250">

#### What is autoLink
  **autoLink** is an attribute in android which is used when working with **XML**. It links the texts, such as _urls_ and _email addresses_ which are found in our code and automatically converted to _clickable links_.
  
#### Synatx for autoLink 

 `android:autoLink="VALUE"` </br>
  Where **VALUE** is replaced with the below mentioned attributes
   
   `all` ----> Match all patterns (equivalent to web|email|phone|map).</br>
   `email` ----> Match email addresses.</br>
   `map` ----> Match map addresses.</br>
   `none` ----> Match no patterns (default).</br>
   `phone` ----> Match phone numbers.</br>
   `web` ----> Match Web URLs.</br>
   
   [Read More](https://developer.android.com/reference/android/widget/TextView.html#attr_android:autoLink)
