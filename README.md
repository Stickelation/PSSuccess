# PSSuccess
A university-finder application made for AndriodOS


3P97 ‘PSSuccess’ App Walkthrough
When the app is launched, note the ‘Splash Screen’ displaying the app logo + theme.
*The associated code is under ‘MainActivity.java’ and
‘activity_main.xml’
After the five seconds, the user is redirected to the app’s home screen
(‘HomeActivity.java’/’activity_home.xml’), where they are prompted to enter a location:
*Note that with the google maps/geocode api, the input
can be in the form of any standard location, such as a
street address.
After entering an address and clicking ‘search’, the app then displays information about the nearest
university:
From here, the user can click ‘next’ to view information about the
next-closest university to their location, or click ‘view on map’ to be
redirected to a maps-view of the displayed university:
From here, users can interact with the map by inspecting the nearby
area, and can additionally press the back arrow at the bottom left
of the screen to return to the home page, where they can once
again enter a new address.

Purpose:
The actual intended purpose of the app is for future university students (such as those still in highschool) to have a resource to see their options. 
By being able to enter their address and view the
university on a google map, they are also able to see surrounding locations of interest via moving the map around, thus giving them some perception of the area. 
Additionally, by being able to view the nextcloses location, they can systematically see which universities are closest to them and periodically view
the associated maps as well.
