# Prepare the phone

I'm assuming that you have a near-factory-reset state here.

Let's start by turning on developer mode.

Drag down the notification bar at the top of the screen.

Hit the settings sliders.

Scroll down to "About Phone"

If you don't see a "Developer Options" menu above "About Phone":

   Hit "About Phone"
   Scroll down to "Build Number"
   Tap "Build Number" repeatedly until it unlocks Developer Mode
   Hit Back

Select "Developer Options"

Turn on "Developer Options" at the top

Enable "USB Debugging"


# Prepare your computer.

You need the Android Platform Tools to do USB debugging stuff.
Specifically you want the `adb` and `fastboot` commands to be in your
path.  You'll probably need a root shell to do this stuff.


# Run the magic script.

*Whatever the hell you do, don't run the root_phone.sh script yet.  You'll
brick your phone.  Once I get it updated, it'll be better.*