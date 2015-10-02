# Device Type Detection

JavaScript Snippet to detect the device type a user is browsing with.
The Script is inspired by [detectmobilebrowsers.com].

### Installation

**1. Import file** 

Copy the
``` deviceTypeDetection.js ```
file into your website project. 

**2. Embed file**

Place the script tag in the ``` <head> ``` section of your site like this:
``` <script type="text/javascript" src="path/to/deviceTypeDetection.js"></script> ```
> **NOTE:** To use the script you have to place this script tag
> **before your custom javascript**.
> Example:
> ``` <head>
> ```   <title>My Website</title>
> ```   <link rel="stylesheet" type="text/css" />
> ```   <script type="text/javascript" src="path/to/deviceTypeDetection.js"></script>
> ```   <script type="text/javascript">
> ```     YOUR JAVASCRIPT GOES HERE
> ```   </script>
> ``` </head>

### Usage

In your custom JavaScript run
``` getDeviceType(); ```

#### Returns

The function returns one of the following strings:

```
"mobile"
"tablet"
"desktop"
```

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does it's job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)


[detectmobilebrowsers.com]: <http://detectmobilebrowsers.com/>