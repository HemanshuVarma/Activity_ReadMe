# How to add autoLink in android
<img src ="https://storage.googleapis.com/gweb-uniblog-publish-prod/images/android_ambassador_v1_cmyk_200px.max-2800x2800.png" height="250" width="250">

### What is autoLink
  **autoLink** is an attribute in android which is used when working with **XML**. It links the texts, such as _urls_ and _email addresses_ which are found in our code and automatically converted to _clickable links_.
  
### Synatx for autoLink 

 `android:autoLink="VALUE"`
  Where **VALUE** is replaced with the below mentioned attributes  
  * `all` ----> Match all patterns -- equivalent to web, email, phone, map.
  * `email` ----> Match email addresses.
  * `map` ----> Match map addresses.
  * `none` ----> Match no patterns (default).
  * `phone` ----> Match phone numbers.
  * `web` ----> Match Web URLs.
   
### Example for autoLink attribute

* android:autoLink=”email”

```
<TextView
	android:layout_width="wrap_content" 
	android:layout_height="wrap_content"
	android:text="support@udacity.com"
	android:autoLink="email"
	android:textSize="16sp"
	android:layout_margin="5dp">
</TextView>
```

* android:autoLink=”phone”

```
<TextView
	android:layout_width="wrap_content"
	android:layout_height="wrap_content"
	android:text="0987654321"
	android:autoLink="phone"
	android:textSize="16sp"
	android:layout_margin="5dp">
</TextView>
```

* android:autoLink=”web”

```
<TextView
	android:layout_width="wrap_content"
	android:layout_height="wrap_content"
	android:text="www.udacity.com"
	android:autoLink="web"
	android:textSize="16sp"
	android:layout_margin="5dp">
</TextView>
```

* android:autoLink=”map”

```
<TextView
	android:layout_width="wrap_content"
	android:layout_height="wrap_content"
	android:text="381 Park Avenue South, New York"
	android:autoLink="map"
	android:textSize="16sp"
	android:layout_margin="5dp">
</TextView>
```

   [Learn More](https://developer.android.com/reference/android/widget/TextView.html#attr_android:autoLink)
