
# Table of Contents

* [About Hale Manoa](#about-hale-manoa)
  * [Key Features](#key-features)
  * [Sample Mockup Pages](#sample-mockup-pages)
  * [Guided Tour](#guided-tour)
* [Installation](#installation)
* [Developer's Guide](#developers-guide)
* [Development History](#development-history)


# About Hale Manoa
[Hale Manoa]() is a tool for University of Hawaii at Manoa students to browse available and affordable housing options in the area. With Hale Manoa, users are able to directly compare prices and find housing adequate for their needs. Furthermore, local individuals and businesses are able to advertise their housing options while gaining community recognition through reviews given by other users.

Hale Manoa allows students to find a roommate with similar interests. Students will create their own personal profile with important information such as hobbies, habits, cleanliness, pets, etc. Students can get notified when they have a match. Admins can monitor for inappropriate content and other information.



## Key Features
* Create personalized profiles
* Discover housing options based on specific characteristics
* Compare prices and locations
* Advertise housing options
* Add reviews / community feedback
* Secure login via the UH authentication system


# Guided Tour

Hale Manoa Web Potral is deployed here: [https://halemanoa.meteorapp.com](https://halemanoa.meteorapp.com/)

When you first get to the page, you will be greeted with the landing page. This is shown below.

<img width="500px" src="images/Landing2.png">

You will then need to create an account. You can do this by clicking on login at the top right corner and then clicking sign up.

<img width="500px" src="images/Signup.png">

Please enter a valid email and password.

Once logged in you will be greeted with the landing page again, but with more options in the top menu.

The first thing you should do is add your user profile. You can do so by clicking the dropdown on your email in the top right corner then clicking on "my profile". You will be greeted with the following page:

<img width="500px" src="images/Addprofile.png">

After adding your profile, if you click on "connect" at the top, you will be able to view all of the user profiles that exist in the system. Currently, you are only able to filter if they are lenders or seekers, but you will eventually be able to filter by preferences to find your preferred roommate.

<img width="500px" src="images/Userbios-2.png">

Clicking on the full profile will expand a user's profile for more details. The profile also includes a rating system to rate other users (maybe if they were prior roommates, etc.).

Next, you can list a location to rent out. You can do so by clicking the housing drop down at the top. Currently, every user can use it, but eventually only the users registered as a lender can use it. Additionally, the dropdown also includes a list housing to see all the housing options clicking on the button expands it into a more detailed view. Additionally, if you created a listing you would also see an option to edit your listing.

<img width="500px" src="images/Housing-2.png">

The search bar on the landing page does work. You can search for other users or you can search for a listing. Clicking on the search result will either bring you to the listing's page or the user's profile page, depending on what your search result was.

<img width="500px" src="images/Searchbar.png">

## Developer Guide (Installation)

First, [install Meteor]( https://www.meteor.com/install).

Second, [download a copy of Hale Manoa](https://github.com/hale-manoa/hale-manoa). Note: Hale Manoa is a private repo so permission needs to be granted from the author to gain access.

Third, cd into the app directory and install the required libraries with:

```
$ meteor npm install
```

Once the libraries are installed, you can run the application by invoking:

```
$ meteor npm run start
```

# Initial User Study

##Description of Reviewers of the Website

##Method of Study

##Summary of feedback

# Development History

##  Milestone 1: Mockup Development

This milestone started on April 3, 2018 and ended on April 12, 2018

The goal of Milestone 1 was to create a set of HTML pages to provide a mockup for the pages that will be in our application. This mockup was developed as a Meteor app.

Mockups for the following pages were implemented during M1:

Landing:

<img width="500px" src="images/Landing-2.png">

Housing:

<img width="500px" src="images/Housing.png">

User Bios:

<img width="500px" src="images/Userbios.png">

Profiles:

<img width="500px" src="images/Profile.png">

Milestone 1 was implemented as [Hale Manoa Github Milestone M1](https://github.com/hale-manoa/hale-manoa/projects/1)

## Milestone 2

This milestone started on April 12, 2018 and ended on April 24, 2018.

The goal for Milestone 2 is to create an MVP (minimum viable project) of our project. We want to finalize our pages and implement basic functionality to be able to utilize most of the aspects of our app.

Updated Housing:

<img width="500px" src="images/Housing-2.png">

Individual Housing:

<img width="500px" src="images/Individual-Housing.png">

Edit Housing:

<img width="500px" src="images/Edit_Housing.png">

User Bios Search Bar:

<img width="500px" src="images/Userbios-2.png">

User Bios Search Preferences:

<img width="500px" src="images/Userbios-3.png">

Milestone 2 was implemented as [Hale Manoa Github Milestone M2](https://github.com/hale-manoa/hale-manoa/projects/2)

## Milestone 3

This milestone started on April 25, 2018 and ended on May 4, 2018.

The goal for Milestone 3 is to create an MVP (minimum viable project) of our project. We want to finalize our pages and implement basic functionality to be able to utilize most of the aspects of our app.

Updated Housing:

<img width="500px" src="images/Housing-2.png">

Individual Housing:

<img width="500px" src="images/Individual-Housing.png">

Edit Housing:

<img width="500px" src="images/Edit_Housing.png">

User Bios Search Bar:

<img width="500px" src="images/Userbios-2.png">

User Bios Search Preferences:

<img width="500px" src="images/Userbios-3.png">

Milestone 3 was implemented as [Hale Manoa Github Milestone M3](https://github.com/hale-manoa/hale-manoa/projects/3)

# Contributors
  * [Akira Vernon](https://akirav.github.io/)
  * [Kyle Chan](https://kyle-chan.github.io/)
  * [Arnold Shek](https://arnoldshek.github.io/)
  * [Jonathan Lau](https://jon-lau.github.io/)
