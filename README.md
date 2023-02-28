# GoogleMaps360PhotoUpload
Google is removing support for the StreetView apps.  Here is my current work-around.


## Problem Statement
Google is killing off the Streetview app for IOS and android.  This was my go-to to send my 360 drone photos to Google maps.  There were drawbacks to the on-phone process though - 1. The image quality was ok but not great.  2. The drone IOS app did not include the GPS coords, so the Streetview app was critical to set the location.  

Now that Google is removing Streetview, they recommend you go to maps.google.com and add photos to the map.  This did not work.  To test this, I took a Pano photo that had correct GPS coords and added it to the "Place."  In my test case, the place was a lake.  The image appeared on Google maps in the usual timelines, but it was off my a mile.  Google maps shows the blue bubble in the middle of the lake rather than on the edge where the GPS coords were.  To verify, I took the same image and uploaded it via my process below with the Android App....the image then showed up exactly where it should be based on the GPS coords.  



## Sources of 360 Pano's
There are a ton of ways to take 360 pano's, here are my personal methods - 
1. Insta360 x3 camera will take decent 360 photos.
2. DJI Mini 2 drone.  There are caveats with processing these, so check out my other project here - https://github.com/RookieITSec/HuginPanoScript

Note - the 360 photo will need to contain the correct GPS coords (x,y,z) for this to work the best.  



## Things I have tried that did NOT work well - 



## Thank you's and sources of information - 
1. UL2GSV - https://www.facebook.com/groups/Insta360Pro/posts/3934550599955390/?comment_id=3974963629247420
2. Google Guides Connect Forums - https://www.localguidesconnect.com/t5/General-Discussion/bd-p/localguide/label-name/How-tos
