FragmentBasics
==============

This is an extension from sample project of FragmentBasics from Android developer website

The base project files were taken from: http://developer.android.com/training/basics/fragments/creating.html

What I added:
* Sliding transition between fragments
* Change action bar title on fragment change

Where it changed:
* Animation: https://github.com/ardok/FragmentBasics/blob/master/src/com/example/android/fragments/MainActivity.java#L90-L93
  * View the animation file inside `res/anim` directory 
* Title change for main activity: https://github.com/ardok/FragmentBasics/blob/master/src/com/example/android/fragments/MainActivity.java#L113
* Title change for article fragment:
  * https://github.com/ardok/FragmentBasics/blob/master/src/com/example/android/fragments/ArticleFragment.java#L65
  * https://github.com/ardok/FragmentBasics/blob/master/src/com/example/android/fragments/ArticleFragment.java#L69
  * Method to change that article fragment's title: https://github.com/ardok/FragmentBasics/blob/master/src/com/example/android/fragments/ArticleFragment.java#L48-L50
