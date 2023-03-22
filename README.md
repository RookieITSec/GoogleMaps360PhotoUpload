# GoogleMaps360PhotoUpload
Google is removing support for the StreetView apps.  Here is my current work-around.

NOTE - This was written prior to Google Officially killing off GSV app support.  This may not work after 21 MAR 2023.  


## Problem Statement
Google is killing off the Streetview app for IOS and android.  This was my go-to to send my 360 drone photos to Google maps.  There were drawbacks to the on-phone process though - 1. The image quality was ok but not great.  2. The drone IOS app did not include the GPS coords, so the Streetview app was critical to set the location.  

Now that Google is removing Streetview, they recommend you go to maps.google.com and add photos to the map.  This did not work.  To test this, I took a Pano photo that had correct GPS coords and added it to the "Place."  In my test case, the place was a lake.  The image appeared on Google maps in the usual timelines, but it was off my a mile.  Google maps shows the blue bubble in the middle of the lake rather than on the edge where the GPS coords were.  To verify, I took the same image and uploaded it via my process below with the Android App....the image then showed up exactly where it should be based on the GPS coords.  



## Sources of 360 Pano's
There are a ton of ways to take 360 pano's, here are my personal methods - 
1. Insta360 x3 camera will take decent 360 photos.
2. DJI Mini 2 drone.  There are caveats with processing these, so check out my other project here - https://github.com/RookieITSec/HuginPanoScript

Note - the 360 photo will need to contain the correct GPS coords (x,y,z) for this to work the best.  


## Software Used -
1. Bluestacks - Latest version.  So far the specific version does not matter.  I was using 5.10.150.1016 P64 for reference.  
2. Old version of Streetview App - (https://apkpure.com/google-street-view/com.google.android.street/versions) Example Version - 2.0.0.268460236 (40449)
Note - the website is a pain to use.  Make sure you enable a good ad blocker (ublock origin) and only click on the correct APK download link.
3. Win 10 PC.  


## Prep Work - 
1. Install Bluestacks.
2. Spin up an emulated android instance in Bluestacks.
2. Install the APK for the old version of StreetView.


## What to do - 
1. Prep the 360 photo using whatever tool(s) you need to.  Files should be 2:1 aspect ration and contain the corret GPS metadata.  See Sources of 360 Panos' above for how I do this.  
2. Import the 360 photos into Blue stacks - Use the File explorer tool in the android instance and "import from windows"
3. Open Streetview App - Login if needed.  
4. Click Create icon on bottom.
5. Click Import 360 photos.
6. Select the photos from the recently imported directory (or wherever you placed them when you imported).
7. Allow it to import the photos, if you have a slow pc and/or large file sizes, this may take a bit and there is not a good progress indicator.  This is likely caused by the software being old. 
8. Go to the profile section of the app on the bottom row.  
Click publish on the images you added.  I have been clicking one at a time to publish, because the app died when I used the publish button on the entire group.  



## Things I have tried that did NOT work well - 
1. the IOS App - it started to get buggy as soon as it was announced they were killing it.  At this point, it just dies when opening.  
2. Google Maps app/web.  This does not place the blue dot in the location of the GPS metadata...This would be a good solution to avoid all of this mess if they just fixed the GPS location of the photo when adding it to a "place."



## Thank you's and sources of information - 
1. UL2GSV - https://www.facebook.com/groups/Insta360Pro/posts/3934550599955390/?comment_id=3974963629247420
2. Google Guides Connect Forums - https://www.localguidesconnect.com/t5/General-Discussion/bd-p/localguide/label-name/How-tos
3. @jhg34 on Local Guides Connect - https://apkpure.com/google-street-view/com.google.android.street/versions
