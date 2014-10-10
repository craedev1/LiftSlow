
Lift Slow for Pebble
====================

An app for those that are interested in experimenting with slow and deliberate weight lifting. The app features separate timing for the up and down lift stroke, the rest intervals at the bottom or top of each lift stroke, variable warmup and cooldown intervals between sets, and an adjustable vibe strength. The vibe, not the watch display, is the primary mode for indicating the timed intervals

Instructions
============

Pressing the DOWN button (the lower button on the right side of the watch) moves the cursor to highlight one of three icons: the Start icon, the Timer icon, and the Settings icon. Pressing the SELECT button (the middle button on the right side of the watch) activates that particular function.

THE START ICON:

+ A short press of the SELECT button while the Start icon is highlighted starts the weight lifting cycle timer. After activating this icon you should feel vibes that indicate the timing of the weight lifting cycle has begun. 

+ A short press of the SELECT button while the timer is running toggles between Start and Pause modes of the timer. This way you can pause the timer to get a drink, talk to a friend, etc and then restart the timer.

+ A long press of the SELECT button (a HOLD) while the Start/Pause icon is highlighted will reset the timer and stop all vibes.

For example, imagine a shoulder press with the default 10 second prep time, 5 second warning time with a 5-second up-lift, 1 second rest, 5-second down-lift, and 1 second rest. 

After pressing SELECT with the Start icon highlighted the following will happen:

1) Ready !!
A series of short vibes are the sign for "Ready" and will go off every other second for 10 seconds. Good uses of this time are to add or subtract weights or adjust the bench height.

2) Set !!
Next, a series of short double vibes will signal the "Set" and will go off once every second for 5 seconds.  Good uses of this time would be to set your grip on the weight bar and adjust your mental focus.

3) Lift !!
A long vibe indicates that beginning of a lift. After the long vibe, a series of short vibes count out the seconds of the beginning/positive stroke of the lift. Another long vibe indicates the end of the beginning/positive stroke.  

Next, there is a pause for the rest interval at the top of the positive stroke. Beware, a one second rest is not a very long time !!

Then another long vibe to indicate the start of the finish/negative stroke of the lift.  A series of short vibes then count out the seconds of the stroke and another long vibe ends the finish/negative stroke.

Next there is a pause for the rest interval at the bottom of the finish/negative stroke.

This cycle of lift,rest,lift,rest repeats for each repetition

4) Cooldown !!
After all the reps are completed, the final part of the lift cycle is a longer pause for the cooldown duration. Once the cooldown duration is completed, the watch returns to step 1) and the operation repeats.

THE TIMER ICON:

A short press of the SELECT button while the Timer icon is highlighted brings up the timer settings menu.

The timer follows a "ready...get set...go" idea.  The lifter uses a prep time ("ready") to get equipment ready, uses the warning time ("get set") to settle down on the equipment, adjust grips, etc.  Then the reps are performed  ("go").  After the reps are completed a cooldown period is used to recover before the next activity. 

+ Reps: the number of repetitions to perform. 
+ Prep time: the number of seconds to get any equipment ready before the repetitions start. This is the "ready" part and the watch will produce a vibe every other second to indicate the prep time interval.
+ Warning time: the number of seconds to mentally prepare for the repititions to start. This is the "set" part and the watch will produce a double vibe every second to indicate to get ready to lift.
+ Lift time (+), Rest time (+), Lift time (-), and Rest time (-): the times for the beginning/positive lift stroke, the rest at the top of the lift stroke, the finish/negative lift stroke, and the rest at the bottom of the lift stroke, respectively.
+ Cooldown: the number of second to cooldown before beginning the next Prep time. 
+ Vibe Volume - the intensity of the vibe for marking the intervals between the lifts

The Cycle display shows the lift cycle in the format of, for example 10:2:5:1 where:

 10 = 10 seconds for the beginning/positive stroke of the rep
 
  2 = 2 second rest at the top of the lift
  
  5 = 5 seconds for the finish/negative stroke of the rep
  
  1 = 1 second rest before beginning the next rep

NOTE: a long press of the SELECT button (a HOLD) while the Timer icon is highlighted swaps the positive and negative lifting times.  This is helpful when you are doing rapid positive lifts and slow negative lifts. In the shoulder press, the weights typically start in a down position so you want an explosive positive lift followed by a slow negative lift. In contrast, with a bench press the weights typically start in an up position so you want to begin with a slow negative lift followed by a explosive positive lift.  Swapping the lift cycle with a (HOLD) can assist in moving between these types of exercises more rapidly.

THE SETTINGS ICON :

+ Splash Screen: Add or remove the software version and logo screen when the application first starts.

+ Mark Last Reps: Add or remove the presence of a slightly different long vibe for the last two reps in each set. The long vibes that mark the start of the lift cycle and the rest intervals become more intense during the final two reps.  This option has no effect when the vibe volume is set at 10.


## Buglist

## Wishlist
+ Start and stop the timer using wrist shake. However, trials indicate that it is not trivial to distinquish a start/stop signal from some lifting actions.

## Changelog
+ 1.0 - Inital version

## Thanks to:
+ Icons created by Elzor, RichardG, dotar -- http://forums.getpebble.com/discussion/5266/set-of-icons-for-apps-and-future-development
+ PebbleLocalSim simulator created by Helco and others that eased the development process. Added thanks to epatel for mac support -- https://github.com/Helco/PebbleLocalSim
+ The pwm_vibrate library created by Jeffrey R. Blum -- https://github.com/jeffbl/pebble.git
 

## License
+ The icons are under a Creative Commons Atribution-ShareAlike 3.0 Unported License
+ The pwm_vibrate library is under the MIT License 
