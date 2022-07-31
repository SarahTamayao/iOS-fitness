# SimpleFav

## Table of Contents
1. [Overview](#Overview) 
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description


### App Evaluation
[Evaluation of your app across the following attributes]
- **Category:** Lifestyle/ Fitness 
- **Mobile:** iOS App
- **Story:** User can save videos to be referenced later, and be able to plan a routine with free 
                videos available online. 
- **Market:** Influencers, users looking to organize their workout videos 
- **Habit:** This app could be used everyday or as often as the users exercise habits are. 
- **Scope:** First we would start with the user being able to search and save the videos available  
                this app. Then, the user could organize specific videos to a playlist. Then, a 
                scrolling timeline. If we had time, the ability to share with other people and 
                integrated with the user's calendar. 

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**
- [x] Login to an account they have and log out 
- [x] A feed scroll screen 
- [ ] A weekly scroll screen

**Optional Nice-to-have Stories**

- [x] Scrolling timeline 
- [ ] Sharing between users 
- [ ] Integration with calendars 

### 2. Screen Archetypes

* Login screen 
Ability to login 
Ability to logout 
Timeline view 
Scroll through the videos 
Get videos from other sources 
* Weekly view 
Saved a video to a specific day  

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Default playlist 
* Homescreen 
* Possible - User profile 

**Flow Navigation** (Screen to Screen)

* Forced Log-in -> Account creation if no log in is available
* Video selection -> Add to playlist 
* Select video -> Add to day 

## Wireframes
<img src="https://user-images.githubusercontent.com/98985433/158521938-d6ebe3a5-ef27-43f0-83f6-17e9db309787.jpg" width=600>

### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype

## Schema 
### Models
| Property     | Type           | Description   |
| :---         |     :---:      |          :--- |
| Username     | String         | Users Username|
| Password     | String         | Users Password|
| Image        | File           | Users defined playlist thumbnail|
| Search | String | Search to find workout videos |
| Video Title | String | The user defined title given to a saved video |
| Video Decsription | String | User defined Description given to a video |
| Day | String | Holds the value of the days of the week |
| User | File | User profile pic |
| Personal Info | String | Personal information of the user such as age and height |
| About Me | String | Holds the description of the user |

[This section will be completed in Unit 9]
### Networking
#### List of network requests by screen
   - Home Screen
      - (Read/GET) Query all weekly view posts 
      - (Create) Create new post for weekly view
      - (Delete) Delete post for weekly view
   - Scrolling Feed Screen
      - (Create/POST) Create a new like on a post
      - (Delete) Delete existing like
      - (Create/POST) Create a new comment on a post
      - (Delete) Delete existing comment
   - Profile Screen
      - (Update/PUT) Update user profile image
      - (Update/Info) Update user profile info

- [Add list of network requests by screen ]
- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Yelp]


# SimpleFav_Sprint1
<img src="https://user-images.githubusercontent.com/30871002/161178944-6661e407-07fa-453e-bcc4-c18bbee3c75c.gif" width="300" height="650"/>

# SimpleFav_Sprint2
![ezgif com-gif-maker-11](https://user-images.githubusercontent.com/98985433/162364022-9289ab54-663c-4189-a14a-59ac7e6ca344.gif)



