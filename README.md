# Examples for use with Advanced VR Framework
A collection of examples from SSZ Canada for use with the Advanced VR Framework made by Human Codeable.


All examples require you to own the asset Advanced VR Framework for Unreal Engine which can be found at
https://www.unrealengine.com/marketplace/en-US/product/advanced-vr-framework

# SPECIAL NOTE

**No files from Advanced VR Framework have been included with this repo.**

**We have not modified any of the AVRF files to make these examples work so a fresh launcher version of AVRF will work to load these examples without any changes needing to be made to AVRF**





# How To Use
Download a copy of Advanced VR Framework from the Unreal Marketplace

Add the Content folder in this repo to your newly installed project directory.

Enjoy your examples :)



# Allowed Usage 
The examples are provided free to you without limitation. You may use any of these examples in any way allowed by licensing terms from Unreal Engine.


# Get Help
We can often be found in the #Off-Topic channel of the Human Codeable Discord server if you have any questions. You can also open an issue here on GitHub and we will respond as soon as we can. 


# Special Requests
We would be happy to take some requests. Please keep in mind that this is done in our spare time to help out the community. We are not involved with the AVRF project so it might be a bit before we can get to your request. We will consider making as many examples as we can with the time we can spare away from our project :)
<br>
<br>
If you would like us to create an example of something for you please send us an @ message on the Human Codeable Discord server in the #Off-Topic channel. Even if we are not able to create an example for you someone in the Human Codeable Discord server is bound to offer you advice that will help you create it yourself :)


# What's Inside

**BP_FishingPole**
<br>
  A basic fishing pole which has a physics connection holding the physics enabled lure at the end of the line.
<br>
<br>
**BP_Lure**
<br>
  Basic lure with physics enable to connect to the end of the fishing poles line.
<br>
<br>
**BP_MultiGrabFirstMesh + BP_MuiltiGrabSecondMesh**
<br>
An example of connecting 2 actors together when both have grab components.
<br>
<br> 
**BP_Vehcile**
<br>
  Built using the dual wishbone example project. We retrofitted a Lever and Valve from the AVRF project then linked those values to the throttle and steering.
<br>
**Note For some reason pointers are the only controller type that seem to work well at higher speeds**
<br>
<br>
**TrackGenerator**
<br>
Based on the Live Training session from Unreal it easily allows you to create roads to drive on using a spline mesh system.
<br>
<br>
**BP_MapControl**
<br>
An example of loading and unloading maps from anywhere in your project folder without using the level streaming system.
<br>
<br>
**BP_UnifiedLevelSettings**
<br>
Add to you level to easily configure all of the required AVRF files in your level. Also includes examples of changing your controllers during runtime.
<br>
**Note BP_Helper_Debug is now inside of that blueprint and you do not require a second copy only the Unified Level Settings Blueprint**