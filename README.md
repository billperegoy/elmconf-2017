# Fully Functional: Cat-egorization with Elm and Phoenix

## Abstract
In this talk, I'll teach the audience to create a real-time, multi-user, interactive web application using Elm and Phoenix. 
I'll use the example of a platform that allows for crowd-sourced work on a large task, in this case, the categorization of images... of cats! As a bonus, the application will also entertain users by providing live updates on the growing cat categories being built while they work.

This talk will provide a fun way to learn how to integrate an Elm frontend with a Phoenix REST API and Phoenix channels. The talk will culminate in a live demo where the audience will use the application to collaboratively categorize as many cats as possible in a timed mad dash.


## Talk Details 
I plan to start this talk with a tongue-in-cheek history of the internet based on the premise that for years we didn't have enough cat GIFs, and now that we do, we have a major problem keeping them sorted into suitable taxonomies — thus the need for better tools to categorize cats.

I'll next outline the steps for building the application to fix this problem and describe its architecture — which uses Elm on the frontend, Phoenix and Elixir on the backend and makes extensive use of Phoenix channels to provide real-time updates. 

I'll use pre-prepared code to put the pieces together while explaining the theory and function of each step.

Finally, I'll run a demo where all audience members may use this application as a group to see how many cat GIFs a room full of Elmconf attendees can categorize in a short demo period. I'll be projecting a dashboard of overall stats from my computer while individual users are receiving more personalized updates in their own browsers.

The audience members will leave with a clearer idea of how to make Elm and Phoenix play together. In addition, they will learn how Phoenix channels can work in conjunction with Elm to provide real-time, asynchronous communication
with a backend server. Hopefully, the audience will also have a lot of fun with the live demo as they get a chance to interact with the technology.


## Pitch
After being exposed to Elm, I think many of us have been looking for ways to build complete applications in a more functional style. Using Elm along with a Phoenix backend gives us a full-stack application totally built with functional languages that leverages the real-time capabilities of both environments.

I've been a huge fan of Elm since seeing Richard Feldman speak at Strange Loop 2015. Since then I have been using Elm for small work projects as well as numerous side projects. Most recently, I've been focusing on developing a full-stack environment that uses only functional programming tactics and on making use of persistent web connections to enable highly interactive web applications. I participate as a speaker at my local Elm meetups and blog regularly on Elm and other functional programming topics.
