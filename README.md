# PlanBook

The Basic Architecture of the PlanBook App was developed during Spring Term 2023. You can find some more detailed documentation of that work in the documentation folder. The overview is as follows: 

## The Mobile App

The Mobile App is an app meant to be used primarily on a mobile device, but could potentially be used on multiple devices depending on how it was developed. For instance, if React Native was the development tool, a web version could easily be produced as well. The preliminary requirements for this app are:

1. The App is _skeuomorphic_ in that it looks like the paper version of the Plan Book in terms of layout and design while allowing for fluid interaction with entries.
2. The App is accurate in terms of dates, rotations, and schedule exceptions _at least as far as it would be at the normal time of publication_.
3. The App allows for custom entries by the user.
4. The App allows for the user to input their class schedule and have that be reflected in the app.
5. The App persists entries to an account. 

Things that would be nice but are perhaps a little further down the line in terms of priority (like the 2.0 version...)

1. Entries associated with a time show up in Outlook
2. Outlook entries show up in the App

## The Outlook Plugin

This Outlook Plugin is meant to allow users of Outlook to easily schedule things against our schedule. For instance, being able to schedule a repeating event during A1. The preliminary requirements for this tool are: 

1. Compatibility with the Outlook program on Surface Pros, any Moble App, and the web versions.
2. 
