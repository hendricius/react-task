# React test task

The goal is to do a little bit of react work and show that you can build an UI and work with a rest API. Please make sure to check the general notes at the end.

## Task

Pick any subreddit you like. For instance you could pick https://www.reddit.com/r/aww.json as it contains super cute puppy pictures. Setup a basic react app that allows the user to interact with the subreddit as outlined in the user flow below:

## User flow

### Login view

* User opens the app and is presented a login form
* He can log in with an arbitrary username (for sake of simplicity) and the password "password"
* If credentials are correct, he gets redirected to the second view. Else he gets some notification to check credentials for correctness.

### Reddit overview

* User sees a view where on top the name of the reddit is displayed.
* The view shows the username he used to log in. Could be in a menu.
* Below there is a list of the posts of the subreddits.
* The user can approve/disapprove the individual images by swiping either left or right like one can do in the tinder app.

### Users approve/disapprove list

* User can switch to this view (and back to the previous view by some kind of menu).
* He will see a list with small preview images of the puppets and some nice indication of he approved or this approved the post.

## General notes

* No need to reinvent the wheel: If you know a library that does what you need, use it. Good coders write less code, not more.
* If you use a react project template to start off please seperate this into an extra commit, so that we can see what you personally did.
