# Kotlin-JetPack Navigation Components

The Navigation Architecture Component simplifies implementing navigation, while also helping you visualize your app's navigation flow. 

The library provides a number of benefits, including:

a) Automatic handling of fragment transactions

b) Correctly handling up and back by default

c) Default behaviors for animations and transitions

d) Deep linking as a first class operation

e) Implementing navigation UI patterns (like navigation drawers and bottom nav) with little additional work

f) Type safety when passing information while navigating

g) Android Studio tooling for visualizing and editing the navigation flow of an app.

# Overview of Navigation

The Navigation Component consists of three key parts, working together in harmony. They are:

a) Navigation Graph (New XML resource) 

This is a resource that contains all navigation-related information in one centralized location. This includes all the places in your app, known as destinations, and possible paths a user could take through your app.

b) NavHostFragment (Layout XML view) 

This is a special widget you add to your layout. It displays different destinations from your Navigation Graph.

c) NavController (Kotlin/Java object) 

This is an object that keeps track of the current position within the navigation graph. It orchestrates swapping destination content in the NavHostFragment as you move through a navigation graph.

When you navigate, you'll use the NavController object, telling it where you want to go or what path you want to take in your Navigation Graph. The NavController will then show the appropriate destination in the NavHostFragment.
