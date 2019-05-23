# Advanced & Practical MotionLayout

Talk given by Jason Pearson on May 22nd, 2019

[Original Keynote Presentation](https://github.com/kaeawc/advanced-motionlayout-talk/releases/tag/2019.05.22)

Speaker Deck TBD

## Demos I created for this talk

[Derived ConstraintSets](https://github.com/kaeawc/motion-derived-constraintsets)

<img src="https://user-images.githubusercontent.com/1414364/58134839-06564880-7bf6-11e9-8ef4-2d9ec41828cc.gif" height="360" width="180" >

[Path Motion Arc](https://github.com/kaeawc/motion-path-arc)

[Wrap Content Header](https://github.com/kaeawc/motion-layout-wrap-content-header)

<img src="https://user-images.githubusercontent.com/1414364/58145632-d7090100-7c20-11e9-8b70-52439bd930ef.gif" height="360" width="180" >

[Dynamic Photo Grid](https://github.com/kaeawc/motion-photo-grid)

<img src="https://user-images.githubusercontent.com/1414364/58134945-8b416200-7bf6-11e9-9286-5b6fba986c49.gif" height="360" width="360" >

[Sliding Tile Puzzle](https://github.com/kaeawc/motion-puzzle)

<img src="https://user-images.githubusercontent.com/1414364/58064696-25e76580-7b51-11e9-9967-058dc343f295.gif" height="360" width="180" >

[Hourglass](https://github.com/kaeawc/motion-photo-grid)

* Each ConstraintSet denotes the various states of the hourglass while keeping the vertical or horizontal chain packed.
* Some Constraints are specifying a pathMotionArc to get the curved path of motion.
* ImageFilterView is used with a CustomAttribute property transition on `crossfade` to change how the sand appears.
* A simple rotation transformation keeps both the glass and sand rotating along their respective paths.
* The sand is constrained by the glass
* KeyFrameSets adjust for alpha and rotation quirks to keep the ends of the animation from glitching
* autoTransition starts the animation and keeps it going forever

<img src="https://user-images.githubusercontent.com/1414364/58067733-6f897d80-7b5c-11e9-8468-fdff38c4d74e.gif" height="360" width="180" >

[RecyclerView + MotionLayout](https://github.com/kaeawc/motion-recycler)

<img src="https://user-images.githubusercontent.com/1414364/58263912-e8e6c300-7d4a-11e9-9d17-2a72bc4967de.gif" height="360" width="180" >


## ConstraintLayout 2.0 Release Notes

[alpha 3](https://androidstudio.googleblog.com/2018/12/constraintlayout-200-alpha-3.html)

* KeyTimeCycle
* KeyTrigger
* Gesture interactions can now drive seamless transitions
* Sub Elements in Constraints

[alpha 5](https://androidstudio.googleblog.com/2019/04/constraintlayout-200-alpha-5.html)

* Derived Constraints
* onSwipe Regions
* AutoTransition

[beta 1](https://androidstudio.googleblog.com/2019/05/constraintlayout-200-beta-1.html)

* Flow virtual Layout
* onSwipe onTouchUp modes
* visibilityMode

## Relevant Google I/O 2019 Talks

[Google I/O 2019 - What's new in ConstraintLayout ](https://www.youtube.com/watch?v=29gLA90m6Gk)

Nicholas Roard & John Hoford talk about what they've been working on in ConstraintLayout 2.0 and the features of the latest beta release.

[Nick Butcher - Motional Intelligence](https://www.youtube.com/watch?v=f3Lm8iOr4mE)

What makes animations great, the concepts of reentrant, continuous, and smooth.

## Other sources that inspired or were mentioned in this talk

[Beautiful animations using Android ConstraintLayout](https://robinhood.engineering/beautiful-animations-using-android-constraintlayout-eee5b72ecae3)

<img src="https://cdn-images-1.medium.com/max/1600/1*ljG9dtnDj4GJ79Zq-XiktQ.gif" height="360" width="180" >

[Creating awesome animations using ConstraintLayout and ConstraintSet ](https://proandroiddev.com/creating-awesome-animations-using-constraintlayout-and-constraintset-part-i-390cc72c5f75)

[Build a Responsive UI with ConstraintLayout](https://developer.android.com/training/constraint-layout)

[onTouchUp with Mike Camell](https://mikescamell.com/motionlayoutquickie-ontouchup/)

<img src="https://mikescamell.com/content/images/2019/05/stop-1.gif" height="360" width="180" >

[Exploring MotionLayout: Touch Regions](https://medium.com/snapp-mobile/exploring-motionlayout-touch-regions-c0747e65cca0)
