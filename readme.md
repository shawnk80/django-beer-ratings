# Using nested resources: Beer Ratings

Today, we are going to be creating an app that allows users to review their favorite beers. Just about everyone likes beer, and life is too short to drink Keystone Light and/or Milwaukee's Best.

In our app, we're going to use `django's` built in user sign-up and authorization. A user can sign up, find a list of beers, and leave a review for a beer. A beer can have many reviews and when all the beers are listed, you can click on an individual beer and see all the relevant reviews. When you sign in, you can see all the reviews you've left on different beers.

For the purposes of our basic CRUD app today, anyone can create a beer. 


Release 0: Users 
----------------
Set up the user sign-in/sign-up using the `django` built in functionality. 

Release 1: Generate Models/Migrations
-------------------------------------
In `beer-rating/ratings/models.py`, create models for `Beer` and `Review`. A Beer can have many reviews and a review belongs to a beer. Then, create a few beers to use as test data. 

Release 2: CRUD Beers/Reviews (Nested)
--------------------------------------
Now add your routes so that users can add, update, and delete reviews for a beer. Users should be able to see all reviews for a beer, but should only be able to update and delete reviews that they created. 

