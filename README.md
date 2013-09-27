# Info
This is for Pencil Project (Similar to Visio and Dia)

You'll need to install Pencil and install the collections in the collections folder.
The diagrams are in their own folders with PNGs as well. The PNGs may not be up to date.

#GPGS = Google Play Game Services

These diagrams are derived from my [IsometricWorldExample][0]

# AndEngineLifcycleOneActivity

_This is out dated as I'm not combining both activities into one anymor_

The premise is understand the execution flow of things, this helps managing things like resuming and where certain code should go.
The activity uses fragments for the menus, so it is having to deal with swapping fragments in and out while also pressing the home and back button.

I've tried at the start of flows to put some meaningful text to describe the action.  

These diagrams are based on having an activity which extends 
>org.andengine.ui.activity.fragments.compatibility.LayoutGameFragment

While also mimicking the GPGS examples of creating a multiplayer game. To see this you will need the basegameutils class. [view on github][1]

>com.google.example.games.basegameutils.BaseGameActivity


What these diagrams show is the flow of methods in order of execution. The standard Activity, Fragments and AndEngine Lifecycles I'm pretty sure about, you can see the Fragment life cycles in the android documentation. [Fragment lifecylce][2] [Activity lifecyle][3]. As for AndEngine there is no docs for it, but I'm sure the diagram is right.

However, the only thing which isn't always executed in the same order as the diagram is the GPGS stuff, more specifically the listeners, this can be seen in the following pencil pages

* gpgs_3_players
* with_gpgs


[0]:https://github.com/Niffy/IsometricWorldExample
[1]:https://github.com/playgameservices/android-samples
[2]:http://developer.android.com/guide/components/fragments.html#Lifecycle
[3]:http://developer.android.com/reference/android/app/Activity.html#ActivityLifecycle