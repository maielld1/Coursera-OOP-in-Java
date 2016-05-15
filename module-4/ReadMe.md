#Introduction

In the part of the project you completed in module 3, you wrote all of your styling code for the earthquake markers in the setup method (or a helper method, which you then called from the setup method). Now that you’ve learned about inheritance, you will use the power of class hierarchies to organize and improve your code while also adding new features.

The impact of an earthquake depends on many factors, including whether the epicenter is over land or in the ocean. Your class hierarchy will allow you to customize the earthquake marker for these different kinds of earthquakes. You will write code in four different new classes: an abstract class named EarthquakeMarker and two classes extending it: LandQuakeMarker and OceanQuakeMarker, as well as another class CityMarker.

In each of these classes, you will override the draw() method. This method is executed automatically by the Processing PApplet in a loop for each of the markers you create.
