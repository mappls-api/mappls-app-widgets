[<img src="https://about.mappls.com/about/images/MAPPLS-MapmyIndia-logo.png" height="40"/> </p>](https://about.mappls.com/api/)

# Post on Map Widget          <img src="https://cdn-icons-png.flaticon.com/256/9933/9933548.png" height="40" alt="Free"/>

The **Post On Map Widget** by **Mappls** is free to use, offering seamless functionality for all users. It allows flexibility to post updates either as a logged-in user or anonymously, depending on the type of post. If posting **with an image**, users need to log in via **SSO (Single Sign-On)** to upload images, ensuring accountability and security. If posting **without an image**, users can post updates anonymously, enabling quick and hassle-free sharing of information. This approach balances accessibility and user accountability, making it ideal for diverse scenarios while maintaining ease of use.

| **Category**     | **Subcategories**                                      |
|------------------|--------------------------------------------------------|
| **Traffic**      | Jam (Light, Heavy), Accident (Major, Minor), Road Closed (Construction, Accident, Local Event), Traffic Monitoring (Red Light/Speed Cameras), Other (Road Work, Breakdown, Interruptions) |
| **Safety**       | Police Checkpoint, Hazards (Waterlogging, Unsafe Areas, Landslide Zones), Bad Weather (Fog, Rain, Hailstorm), Street Issues (Broken Lights, Fallen Trees, Potholes), Other (Flood Alert, Wrong-Side Driving, Blackspots) |
| **Road Conditions** | Road Type (Speed Breakers, Sharp Curves, Unpaved Roads), Crossings (Blind Spots, Culverts, Railway, Pedestrian), Other (Traffic Merging, Accident Zones) |
| **Map Issues**   | Missing/Incorrect (Roads, Places, House Numbers), Other (Invalid Turns, Place Closed, Other Issues) |


## Demo Link: 
> [https://embed.mappls.com/postOnMap](https://embed.mappls.com/postOnMap) <br>
To learn more on how to create your authorization tokens, please use our authorization token URL. More details available [here](https://developer.mappls.com/mapping/tokenGeneration/).

## Embed Mappls PostOnMap on your website by following the below.

To use the Mappls Places Widget, you need to specify the following URL format:
```html
<iframe 
   src="https://embed.mappls.com/postOnMap?fullscreen=true&position=top-left&zoom=16&pitch=45" style="width: 100%; height: 80vh;" allowfullscreen="">
</iframe>
```

## Sample Code

Embed the **Post On Map Widget** on your website using the following HTML code:

```html
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Post On Map Widget</title>
</head>
<body>
  <iframe src="https://embed.mappls.com/postOnMap" 
          style="width: 100%; height: 80vh;" 
          title="Post On Map Widget" allowfullscreen="">
  </iframe>
</body>
</html>
```

![postonmap](https://github.com/mappls-api/mappls-app-widgets/blob/main/mappls-post-on-map/postonmapdoc/1.PNG) 


## How to Submit a Post

**Step 1.** **Locate Your Desired Position**
   - Drag the map to the area you want to post about, or use the search bar to find a specific location.
   - Fine-tune the pinpointed position by adjusting the map.

   ![Map with Search Bar](https://github.com/mappls-api/mappls-app-widgets/blob/main/mappls-post-on-map/postonmapdoc/2.PNG)

**Step 2.** **Select a Primary Category**
   - Choose the category that best fits your post:
     - **Traffic:** Updates on traffic conditions, congestion, or incidents.
     - **Safety:** Alerts about safety concerns.
     - **Road Condition:** Information about road quality, closures, or maintenance.
     - **Map (Routing):** Suggestions for better navigation or route adjustments.

   ![Category Selection Menu](https://github.com/mappls-api/mappls-app-widgets/blob/main/mappls-post-on-map/postonmapdoc/2.PNG)

**Step 3.** **Select a Sub-Category**
   - Choose a relevant sub-category to provide more specific details for your post.

   ![Sub-category Selection](https://github.com/mappls-api/mappls-app-widgets/blob/main/mappls-post-on-map/postonmapdoc/3.PNG)

**Step 4.** **Enter Post Details**
   - Provide a description of the issue or update.
   - Optionally, attach an image for context (preview available).
   - Click 'Post' to submit:
     - If logged in, the post will be published immediately.
     - If not logged in, you'll be prompted to log in or post anonymously.

   ![Post Details Form](https://github.com/mappls-api/mappls-app-widgets/blob/main/mappls-post-on-map/postonmapdoc/4.PNG)

**Step 5.** **Review and Submit**
   - After reviewing your information, click 'Post' to submit the post. 
   - Once submitted, your post will be visible to others in the area.
   ![Post Details Form](https://github.com/mappls-api/mappls-app-widgets/blob/main/mappls-post-on-map/postonmapdoc/5.PNG)

<!-- ## Access Required

To use the Post On Map Widget, you need the following access:

1. **Map Access** – View and interact with the map.
2. **Place Search** – Search for places and locations.
3. **Text Search** – Search locations by keywords.
4. **SSO Login** – Optional, for authenticated users (not required for anonymous posting).
5. **Add Post API** – Endpoint for submitting posts.
6. **Add Asset API** – Upload images for posts.
7. **POI Access** – Access Point of Interest (POI) data when dragging the map marker. -->

<!-- ![API Integration Diagram](#) -->




## Use Cases

1. **Traffic Jam Reporting**: Users report light or heavy traffic jams to help other drivers adjust routes.
2. **Accident Reporting**: Users share details about major or minor accidents to warn others.
3. **Road Closure Alert**: Users report road closures due to construction, accidents, or local events.
4. **Traffic Monitoring**: Users report red light or speed camera locations to alert fellow drivers.
5. **Road Work Updates**: Users report ongoing road work, breakdowns, or other traffic interruptions.
6. **Police Checkpoint Reporting**: Users share the presence of police checkpoints to inform drivers.
7. **Hazard Alerts**: Users report hazards like waterlogging, unsafe areas, or landslide zones.
8. **Bad Weather Alerts**: Users report fog, rain, or hailstorms affecting driving conditions.
9. **Street Issue Reporting**: Users report broken lights, fallen trees, or potholes on the road.
10. **Flood Alert**: Users post updates about flooding or wrong-side driving to keep others informed.
11. **Road Condition Alerts**: Users report speed breakers, sharp curves, or unpaved roads.
12. **Map Issue Reporting**: Users notify about missing or incorrect roads, places, or house numbers.

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
