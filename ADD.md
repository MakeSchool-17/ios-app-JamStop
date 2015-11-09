#App Design Document


##Objective
Charge* lets writers take snapshots of moments of inspiration and write on them. It will be a platform that either is connected with Medium, or wholly relies on Medium overall.


##Audience
The audience is anybody who likes to read or write, as there will indeed be a feed system and a following system. Writers are generally familiar with the concept of "charges", so the idea shouldn't be alien to them. This app is very easy to globalize.


##Experience
The app should open up to a page view controller that brushes past the concepts of the app, with a "login with Facebook" or "login with Medium" bar on the bottom at all times. After logging in, the user is exposed to a tab bar controller similar to Medium's app (though if the app ends up relying on Medium, can remove some views). 

The use case for an app is for those "AH-HA" moments that those who enjoy writing have, whether it be a single tree peeling from the brunt force of San Francisco's winds, or a man sitting on a pier bench alone. You open up Charge*, take a picture, and start writing whenever you're up to it! In addition to posting to Medium, I also want to interact with other social media, preferrably Facebook; and for the shorter stories I want to interact even with Twitter.

The user should not have to describe the length of the story they plan to write; rather, the story's state changes dynamically with user interaction.


##Technical

####External Services
Medium API
Facebook API

####Screens
Page View Controller w/ some form of login
Home/Feed View (Tab Bar)
Picture Taker/Story Writer (Tab Bar and Modal)
Profile (Tab Bar)*
Drafts/Charges (Tab Bar)
Browse (Tab Bar)*


####Views / View Controllers/ Classes
Login Page View Controller
Tab Bar View Controller
Photo Taker View Controller
Post Maker View Controller
Login 1 View
Login 2 View
Login 3 View
Home View
Browse View
Drafts View
Profile View

####Data Models
Draft
User
Post


##MVP Milestones
Week 1 -> Sketch and Design
Week 2 -> App Layout/APIs
Week 3 -> Login + Auth
Week 4 -> Post Making
Week 5 -> Feed and Browsing
Week 6 -> Drafts
Week 7 -> Tidy Up
Week 8 -> Tidy Up + Profile (which should be Medium Anyways)
