[<img src="https://about.mappls.com/about/images/MAPPLS-MapmyIndia-logo.png" height="40"/> </p>](https://about.mappls.com/api/)
# Mappls Realview Widget

## Introduction
RealView is a way for you to view the world, right from the comfort of where you are. Now, get a full panoramic view of your assets and even geo-tag, measure and analyse them with photo-realistic quality.
Visualise streets, roads, motorways, railway tracks, as well as residential and commercial zones from the comfort of your own desk.

The Realview widget provides an easy mechanism to consume our Realview services within your applications.

Power your business with RealView to increase operational efficiency. Avoid in-person surveys, countless man-hours on the field, and wasted time. Sit from the comfort of your desk and see all your assets, across locations, in one go. Monitor and geo-tag your assets and control your own data collection with the Mappls RealView Widget.

#### Note
This wdiget is access controlled and a paid service.

### Getting Access

Before using our SDKs or APIs in your solution, please ensure that the related access is enabled in the [Mappls API Console](https://apis.mappls.com/console). 

Mappls SDKs & APIs follow OAuth2 based security.
Access Tokens can be generated using Token Generation API.
To know more on how to create your access tokens, please use our authorization API URL. More details available [here](https://developer.mappls.com/mapping/tokenGeneration).<br>
The access token is valid by default for 24 hours from the time of generation. This can be configured by you in the API console.

![](/assets/realview-widget.png)


### Embed Mappls Realview on your app by following the below steps.

To use the Mappls Realview Widget, you need to specify the following URL format:
```html
<iframe src="https://embed.mappls.com/place/<MAPPLS_PIN>?token=<TOKEN>&fullscreen=true&position=top-left&zoom=16&pitch=45" style="width: 100%; height: 80vh;" allowfullscreen="">
```

### Configurable Parameters

1. `<MAPPLS_PIN> OR <latitude,longitude>` (Required): Replace this with the unique identifier of the Mappls Pin or the coordinates for which you want to display details for.
2. `access_token` (required): An access_token token for access control.
3. `minDistance` (Optional): An integer value in meters to configure the minimum distance around the referred place against which a Realview will be returned for . (Default: 20 meters)
4. `maxDistance` (Optional): An integer value in meters to configure the maximum distance around the referred place against which a Realview will be returned for . (Default: 1000 meters)
5. `arrow` (Optional): A boolean value which configures the Realview to display navigation control arrow or not. (Default: true)
6. `map` (Optional): A boolean value which configures the Realview to display map or not. (Default: true)
7. `zoomControls` (Optional): A boolean value which configures the Realview to display zoom controls over the panoramic images or not. (Default: false)
8. `controls` (Optional): A boolean value which configures the Realview to display bottom toggle controls or not. (Default: true)
9. `mapWidth` (Optional): An integer value in pixels to configure the map width. 
10. `mapHeight` (Optional):An integer value in pixels to configure the map height.
 
### Demo Link
[https://realview.mappls.com/realview_widget/sample/index.php?token=6xxxxxx4-9xxx-xxx7-xxxb-8dxxa7xxxdc](https://realview.mappls.com/realview_widget/sample/index.php?token=6xxxxxx4-9xxx-xxx7-xxxb-8dxxa7xxxdc)

To learn more on how to create your authorization tokens, please use our authorization token URL. More details available [here](https://developer.mappls.com/mapping/tokenGeneration/).

### Sample code for Mappls pin
```html
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mappls Realview Widget</title>
    <style>
        body {
            margin: 0;
            padding: 0;
        }
    </style>
</head>

<body>
    <iframe
        src="https://realview.mappls.com/realview_widget/jq5qn8?access_token=<Token>&minDistance=1&maxDistance=500&arrow=true&map=true&zoomControls=true&controls=true&mapWidth=200&mapHeight=200"
        style="width: 100%; height: 80vh;" title="embed Example" allowfullscreen="">
    </iframe>
</body>

</html>
```

### Sample code for Coordinate Pair
```html
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mappls Realview Widget</title>
    <style>
        body {
            margin: 0;
            padding: 0;
        }
    </style>
</head>

<body>
    <iframe
        src="https://realview.mappls.com/realview_widget/28.553302,77.258677?access_token=<Token>&minDistance=1&maxDistance=500&arrow=true&map=true&zoomControls=true&controls=true&mapWidth=200&mapHeight=200"
        style="width: 100%; height: 80vh;" title="embed Example" allowfullscreen="">
    </iframe>
</body>

</html>
```

#### Sample Output
![](/assets/realview-widget.gif)



<br>

For any queries and support, please contact: 

[<img src="https://about.mappls.com/images/mappls-logo.svg" height="40"/> </p>](https://about.mappls.com/api/)
Email us at [apisupport@mappls.com](mailto:apisupport@mappls.com)


![](https://www.mapmyindia.com/api/img/icons/support.png)
[Support](https://about.mappls.com/contact/)
Need support? contact us!

<br></br>
<br></br>

[<p align="center"> <img src="https://forum.mappls.com/uploads/default/original/1X/06259be1fb3006347ade2ee843cf16e9f16ce997.png"/> ](https://forum.mappls.com/)[![](https://www.mapmyindia.com/api/img/icons/blog.png)](https://about.mappls.com/blog/)[![](https://www.mapmyindia.com/api/img/icons/gethub.png)](https://github.com/mappls-api)[<img src="https://mmi-api-team.s3.ap-south-1.amazonaws.com/API-Team/npm-logo.one-third%5B1%5D.png" height="40"/> </p>](https://www.npmjs.com/org/mapmyindia) 



[<p align="center"> <img src="https://www.mapmyindia.com/june-newsletter/icon4.png"/> ](https://www.facebook.com/Mapplsofficial)[![](https://www.mapmyindia.com/june-newsletter/icon2.png)](https://twitter.com/mappls)[![](https://www.mapmyindia.com/newsletter/2017/aug/llinkedin.png)](https://www.linkedin.com/company/mappls/)[![](https://www.mapmyindia.com/june-newsletter/icon3.png)](https://www.youtube.com/channel/UCAWvWsh-dZLLeUU7_J9HiOA)




<div align="center">@ Copyright 2024 CE Info Systems Ltd. All Rights Reserved.</div>

<div align="center"> <a href="https://about.mappls.com/api/terms-&-conditions">Terms & Conditions</a> | <a href="https://about.mappls.com/about/privacy-policy">Privacy Policy</a> | <a href="https://about.mappls.com/pdf/mapmyIndia-sustainability-policy-healt-labour-rules-supplir-sustainability.pdf">Supplier Sustainability Policy</a> | <a href="https://about.mappls.com/pdf/Health-Safety-Management.pdf">Health & Safety Policy</a> | <a href="https://about.mappls.com/pdf/Environment-Sustainability-Policy-CSR-Report.pdf">Environmental Policy & CSR Report</a>

<div align="center">Customer Care: +91-9999333223</div>