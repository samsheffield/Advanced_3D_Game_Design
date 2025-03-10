# W E L C O M E &nbsp; B A C K ! !
So excited to welcome you all back. Today, we'll meet as a group to...
- Check out your homework.
- Intro to VR (Workshop 1/2)

## Character Animation Homework
- Review in  small groups, dependent on class size. __Find two new partners!__

### Demo Materials
- Setting up the VR/XR toolchain for Meta Quest development on lab PCs (link)
- Useful videos ([Unity]())

### Meta Quest VR/XR Workshop (Part 1 of 2)
- Today: Focus on setting things up and some basic experiments on small teams with basic locomotion (teleportation) and interaction (grabbing).
- _We have limited equipment, so you will need to work on small teams of 3 to 4 people._
- This will be in-class work. We'll review work within the last hour of class as a group today.

### Setup Meta Quest Link Software
VR has some pretty specific high-end specs to work properly, so we're going to focus on using the newer lab computers for our work over the next week and a half.

__The first portion of this video is a good Meta Quest setup resource ([link](https://youtu.be/23WUfV1U6mQ?si=8k-S-fkSGgaHjNTV))__
- Install Meta Quest Link software ([link](https://www.meta.com/help/quest/1517439565442928/?srsltid=AfmBOoo8CKmsijNNN0rC31y7X2uOEQks7KH4PLIBjGf0KpIEFyFxO2Od))
- Log in using the MICA Gamelab credentials I provide in-class (If you get stuck in a loop trying to log in, restart the Meta Quest Link application)
- Settings > Beta > Developer Runtime Features: Check both Passthrough over Meta Quest Link and Spatial Data over Meta Quest Link
- __Make sure the headset is plugged into a USB 3 port on the computer__


### Unity Setup
- From Unity Hub, choose Installs in the sidebar.
- Next to the Unity 6 installation, click on the small gear icon and Add Modules.
- Check Android Build Support (this will install teo things)
- Check Windows Build Support (IL2CPP)
- Click Install and agree to terms in the popup windows
- If Visual Studio is not installed, you will be prompted to install that as well. Please choose the Game Development with Unity under the Gaming category.

#### Unity Project Setup
__The second part of this video is a great overview of the process ([link](https://youtu.be/23WUfV1U6mQ?si=oUnbwF67tw9ix9N4&t=238))__
- Add the Meta XR All-In-One Asset from the Unity Asset Store (requires log in)([link](https://assetstore.unity.com/packages/tools/integration/meta-xr-all-in-one-sdk-269657)).
- Use the Universal 3D template
- Add the Meta XR package from the Package Manager (Window > My Assets)
- The installation will require Unity to restart and at some point you will see a popup window prompting you to choose the OpenXR Hand.
- Set build profiles for the Meta Quest (File > Build Profiles)
- Change Platform by selecting Android in the Platform sidebar and pressing the Switch Platform button
- Set Player Settings (Player Settings tab > XR Plugin Management > Install XR Plugin Management)
- Set Plugin Provider to Oculus in both Windows and Android tabs (note the icons for each platform!)
- Select Meta XR in the sidebar and then click the Fix All and Apply All buttons for both Windows and Android tabs
- Select Player in the sidebar and chance the Company Name from DefaultCompany to something else
- Under Player > Other Settings > Identification: Uncheck Override Default Package Name and then check it again
- Done!

#### Meta XR Building Blocks
The Meta XR SDK includes its own interface to add commonly used XR behaviors to your project.
- Open the Meta XR Building Blocks window (Meta XR Tools in the toolbar > Building Blocks)
- Add Camera Rig (this is your player)
- Add Controller Tracking (this is so you can get controller input)
- Add Teleport and choose the Type (Hotspot or Navmesh)
- Add Grab Interaction (you can change this mesh in the inspector)
- Experiment!


### Unreal Setup
- Surprise! It's already included.
- You will just need to select the VR Game Template from the Unreal Project Launcher
- __The second part of this video is a nice basic introduction to the VR template ([link](https://youtu.be/i3xNb5R_xos?si=8v6MhqdnoZTTDrA8&t=407))__
- Test the template. To play in the headset, select the 3 dots next to th Play button and switch the type to the VR headset option
- I will demo some of the key parts needed to work with the VR template's assets. _Let me know when you have everything set up!_
- Experiment with Teleport locomotion (you will need a NavMesh Bounds Volume) and the Grab Component!

## Open Studio
Please work on your prototype with whatever remaining time we have in class anywhere on the 2nd floor. _Don't leave early without getting permission._

__Share out in the last hour of class.__ Be prepared to share your team's experiments with the class.


# Homework

### Spring Break

I hope you can take a break! No homework in this class except to think of some ideas that you might be interested in pitching as a final project in class after the break. 
- Everyone will work on a team of 3-4 people that we will form in the second half of class based on interests, not individuals. Everyone will pitch ideas and you'll gravitate towards things that you are interested in. __No pre-formed teams.__
- __Please do not miss our next class unless it is completely unavoidable.__ Doing so will probably result in being placed on a team that has already decided what it wants to work on without you.

