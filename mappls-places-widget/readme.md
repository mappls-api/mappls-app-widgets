[<img src="https://about.mappls.com/about/images/MAPPLS-MapmyIndia-logo.png" height="40"/> </p>](https://about.mappls.com/api/)
## Mappls Places Widget

### Introduction
The Mappls Places Widget simplifies the process of embedding a Mappls map with specific Mappls pin details into your website or web application. With just a single line of code, you can enhance your web presence and offer valuable features to your users. This versatile widget not only allows you to showcase your place's location on Mappls but also offers powerful customization options.

You can provide directions to your place, enable users to view their location on Mappls, offer easy access to Mappls pin QR codes, and effortlessly adjust the size to seamlessly integrate with your website's design.

Add the Mappls Place widget to the website to elevate user experience and make your website more intuitive and interactive with the Mappls Places Widget.

![image](https://github.com/mappls-api/mapmyindia-api-addendums/assets/59359484/2deb988b-af33-45b9-a950-980e6024dddf)


### Embed Mappls Place on your website by following the below steps.

To use the Mappls Places Widget, you need to specify the following URL format:
```html
<iframe src="https://embed.mappls.com/place/<MAPPLS_PIN>?token=<TOKEN>&fullscreen=true&position=top-left&zoom=16&pitch=45" style="width: 100%; height: 80vh;" allowfullscreen="">
```

### Configurable Parameters

1. ***<MAPPLS_PIN> (Required):*** Replace this with the unique identifier of the Mappls Pin you want to display details for.
2. ***Token (Optional):*** An optional user token for access control.
3. ***fullscreen (Optional):*** A boolean value (true/false) to enable or disable fullscreen mode. (Default: true)
4. **position (Optional):** Specifies the position of the widget on the screen. Options include 'top-left,' 'top-right,' 'bottom-left,' and 'bottom-right.' (Default: top-left)
5. ***zoom (Optional):*** Sets the initial zoom level for the map. (Default: 16)
6. ***pitch (Optional):*** Sets the initial pitch angle of the map. (Default: 0)
7. ***width:*** 100% (Optional): This sets the width of the  iframe to be 100% of its parent container's width.
8. ***height:*** 80vh (Optional): This sets the height of the iframe to be 80% of the viewport height (vh)
 
**Demo Link**: [https://embed.mappls.com/demo.html](https://embed.mappls.com/demo.html)

To learn more on how to create your authorization tokens, please use our authorization token URL. More details available [here](https://developer.mappls.com/mapping/tokenGeneration/).

### Sample code
```html
<html lang="en">
<head>
<meta charset="UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mappls Place Widget</title>
</head>
<body>
<iframe src="https://embed.mappls.com/place/mmi000?token=<TOKEN>&fullscreen=true&position=top-left&zoom=16&pitch=45" style="width: 100%; height: 80vh;" title="embed Example" allowfullscreen="">
</iframe>
</body>
</html>
```
#### Sample Output
![image](https://github.com/mappls-api/mapmyindia-api-addendums/assets/59359484/45e9d6e2-6922-4e38-9aa7-8257483f2e2c)

#### Customize the size according to the required size (The below image is for 300 *300). 
![image](https://github.com/mappls-api/mapmyindia-api-addendums/assets/59359484/f1843f98-073c-4d79-b749-44e389391fe9)

### Use Cases of Mappls Places :

The Mappls Places Widget can be a valuable addition to various types of websites and web applications, enhancing user experience and providing useful location-based information.

Here are some ideal places and scenarios where you can effectively use this:

**1. Business Websites**: Any business with a physical location can benefit from embedding the Mappls Places on their website. It allows customers to find directions, view the location on a map, and get a sense of the surroundings.

**2. Event Websites**: Websites promoting events, conferences, or festivals can use the widget to display the event's venue location. Attendees can easily access directions and explore nearby points of interest.

**3. Tourism and Travel Websites**: Travel agencies, hotels, and tourism-related websites can use the widget to showcase the locations of accommodations, tourist attractions, and points of interest. It helps travelers plan their trips more effectively.

**4. Real Estate Listings**: Real estate websites can use the widget to display the location of properties. This provides potential buyers or renters with a clear understanding of the property's surroundings.

**5. Local Directories**: Websites that serve as local directories or business listings can enhance their listings by including interactive maps with pins for each business.

**6. Restaurants and Food Services:** Restaurants, cafes, and food delivery services can use the widget to show their location and allow customers to get directions or check out the restaurant's surroundings.

**7. Community and Event Spaces:** Websites for community centers, event spaces, and public venues can use the widget to help users locate the facility and explore nearby amenities.

**8. Education and Campus Maps:** Educational institutions can embed the widget to display campus maps, making it easy for students, staff, and visitors to find specific buildings or departments.

**9. Healthcare Providers:** Medical facilities, clinics, and hospitals can use the widget to display their locations, making it convenient for patients to locate their services.

**10. E-commerce Websites:** Online retailers with physical stores can use the widget to display store locations and help customers find the nearest retail location.

**11. Non-profit Organizations:** Nonprofits organizing events or fundraisers can use the widget to show event locations and help participants navigate to the venue.

**12. City and Government Websites:** Municipalities can provide interactive maps on their websites for citizens to access important locations such as government offices, parks, and public services.

**13. Transportation Services:** Websites related to transportation services, such as taxi or ride-sharing companies, can use the widget to display vehicle locations or pickup points.

**14. Adventure and Outdoor Activities:** Websites promoting outdoor activities like hiking, biking, or adventure sports can use the widget to showcase trailheads and adventure locations.

**15. Blog Posts and Articles:** Individual bloggers and content creators can embed the widget in articles or blog posts to provide context for specific locations mentioned in their content.

The Mappls Places Widget's versatility makes it a valuable tool for any website or application that aims to provide location-related information, improve user engagement, and enhance the overall user experience. Its ease of integration and customization options make it suitable for a wide range of industries and purposes.


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