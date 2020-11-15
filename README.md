# Spring-boot
Stack: springboot, spring jpa, java 11, h2

This should be RESTful app. We are not interesting in the UI

The goal of this task is to analyze and transform the > 500.000 reviews from Amazon. 

We are interested in:

1) Finding 1000 most active users (profile names)

2) Finding 1000 most commented food items (item ids).

3) Finding 1000 most used words in the reviews

Any errors will be reported by the HTTP codes.

Implement Spring Security and JWT authentication. Expected to have two roles: ADMIN and USER. 
User is able to create and edit his own comments (not the other user’s comments). 
Admin is able to delete any comment, but is not able to edit any comment.