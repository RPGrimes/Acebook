# AceBook

This task was completed in Weeks 8 and 9 of the Makers Academy course. The general objective of the task was to build a social media site that clones many of the elements present in other social media sites, such as Facebook.

Unfortunately, our original project repo is a private repository that cannot be made public. Therefore, this repository contains the files copied across upon completion of the project.

#### The Team
- [Ryan Grimes](https://github.com/RPGrimes)
- [Myoung Bae](https://github.com/mhbae-dev)
- [Dean Lewis](https://github.com/doinyne)
- [Mo Salah](https://github.com/mo-codes1)
- [Will Birdseye](https://github.com/Will-Birdseye)
- [Madihah](https://github.com/DoodleDeBug)
- [Ben Dowsett](https://github.com/bdowsett)

## Acebook App
To run on your machine please clone and run:
```
bundle install
bin/rails db:create
bin/rails db:migrate
bin/rails server
```
You can then visit and use the app at http://localhost:3000

To see test coverage run:
```
bundle exec rspec
```

![Testing coverage screenshot](https://user-images.githubusercontent.com/75947453/149622547-41f40808-248f-451f-8ec5-374638a7a66a.png)

##### Troubleshooting

If you don't have Node.js installed yet, you might run into this error when running rspec:

```
ExecJS::RuntimeUnavailable:
  Could not find a JavaScript runtime. See https://github.com/rails/execjs for a list of available runtimes.
 ```

Rails requires a Javascript runtime to work. The easiest way is to install Node by running `brew install node` - and then run `bundle exec rspec` again

### Functionality

- Sign up:  A user can create a new account with the option of uploading a profile image. If one isn't uploaded a default one will be assigned.
- Log in: A signed up user can log in to the site.
- Log out: A logged in user can log out of the site.
- Create post: A logged in user can post to the communal wall with a text based comment, post an image or create a post with text and an image.
- Managing posts: A logged in user can edit or delete posts they have previously posted on the wall.
- Liking/unliking a post: A logged in user can like/unlike posts present on the communal wall.
- Commenting on a post: A logged in user can comment on posts present on the communal wall.
- Managing comments: A logged in user can delete comments they have previously made on posts.
- Chat rooms: Users can create a new chat room and send live messages to other logged in users.

### Team Approach

We started the project mob planning until we had enough functional design. This meant that every team member had a common goal in mind in terms of what we were aiming to achieve over the course of the project and how all agreed on roughly how it was going to look (as shown in our MVP mockup below).

We began each day with a technical stand up to discuss what tasks we were working on and how we were progressing, to keep the rest of the team in the loop. We ended each day with an emotional check in retro, as team wellbeing was highlighted as important from the outset of the project.

##### MVP Mockup 

![image](https://user-images.githubusercontent.com/75613073/145019013-674c2d06-2cb6-4165-9039-8a9b5a9912d5.png)

##### Links

- Link to our [Trello Board](https://trello.com/b/L3P4vDYK/acebook-team-name)

##### Completed User Stories

```
As a user 
So I can access content 
I would like to sign up for an account on Acebook

As a user 
So I sign up 
I would like to see a form on the page that takes email and password

As user 
So I can log in with my new account 
I would like to be redirected to login page

As a user 
So that I can use Acebook 
I would like to be able log in 

As a user 
So that I can login
I want a form that takes my email and password

As a user 
So that its easy to login 
I want the login form to be on the homepage

As a user
So that other people cant log in to my account 
I want my password to be checked against my email 

As a user 
So I can receive some personalistion
I want to see receive a welcome message with my details

As a user 
So that I can use Acebook 
I want to be taken to my dashboard once logged in 

As a User
I want to logout of Acebook
So that nobody can post using my login credentials

As a User
I want to access the logout button on the posts page
So that I can logout from Acebook after posting

As a User
I want to be redirected to the Homepage upon logging out
So that I can Login again If I wish to continue browsing and posting

As a user 
I should only be able to access root when I am logged out 
So that the site is secure 

As a user
I want to be able to make a post to Acebook
So that my post can be displayed

As a User
I want to be able to like/unlike a post 
So I can see how popular posts are

As a User 
So I can see how popular a post is
I want to be able to see how many likes a post has

As a user
So theres a true reflection of likes 
I want to only be able to like a post once

As a user
I want to be able to post a photo
So that my photo can be displayed

As a user
I want to add a post to the feed
So that my newest post is displayed at the top of the feed

As a user
I want to be able to comment on a post
So that my comment can be displayed

As a user
I want to see the time a post was uploaded comment was made
So that I see when a post and its comments were posted

As a user
I want to see the number of comments made on a Image posted
So that I see how interested people are in the image

As a user
I want to be able to see a users name and photo on a post
So that I can see who made a post

As a user
I want to be the only person able to delete and update my own post
So that I can control edits and deletes it

As a user
I want to be able to be the only person able to delete my comment
So that I can prevent others from deleting my comment

As a user
I want to be able to live message in a chatroom
So that I can tell my friends how cool Acebook is!
```


