# Badir Incubator Projects and Requirements

Badir Incubator companies have invited YOU to build their MVP!

### 1. [Canary](badir-projects/canary.md)
### 2. [Caocap](badir-projects/caocap.md)
### 3. [Nala](badir-projects/nala.md)
### 4. [Subol](badir-projects/subol.md)
### 5. [Jamjoom Pharma Academy](badir-projects/jamjoom.md)
### 6. [Take Away SA](badir-projects/easy-print-customers.md)
### 7. [Alsa Printing](badir-projects/alsa-printing.md)
### 8. [My Data](badir-projects/my-data.md)
### 9. [Project Shipment](badir-projects/project-shipment.md)
### 10. [Dr. App](badir-projects/doctor-app.md)
### 11. [Saudi Knowledge](badir-projects/saudi-knowledge.md)
### 12. [Helper Robot](badir-projects/helper-robot.md)

# Other Ideas

## Bucket List

### Pitch

Besides finishing WDI, you surely have one or two things you'd love to do with
your life. Let's get 'em on paper!

### MVP User Stories

- As an unregistered user, I would like to sign up with email and password.
- As a registered user, I would like to sign in with email and password.
- As a signed in user, I would like to change password.
- As a signed in user, I would like to sign out.
- As a signed in user, I would like to create a bucket list item with a title
  and description.
- As a signed in user, I would like to update my bucket list item's title and
  description.
- As a signed in user, I would like to delete my bucket list item.
- As a signed in user, I would like to see all my bucket list items but not
  other users'.
- As a signed in user, I would like to cross off items to complete them.

### Reach Goal(s)

- Integrate with a third-party location-based API to:
  - allow users to search for a location or venue to add to their bucket list
    items.
  - autofill an input field.
  - drop pins on a map.
- Add social features to your site, such as following other users.
- Allow users to make certain list items public, but default to private.
- Allow users to upload an image when they complete an item.

___

## E-Commerce

### Pitch

Create an e-commerce site.

### MVP User Stories

- As an unregistered user, I would like to sign up with email and password.
- As a registered user, I would like to sign in with email and password.
- As a signed in user, I would like to change password.
- As a signed in user, I would like to sign out.
- As an unregistered user, I would like to see all of the products.
- As a signed in user, I would like to add and remove products from a shopping
  cart.
- As a signed in user, I would like to purchase products in a shopping cart
  using [Stripe](https://stripe.com/docs/checkout).
- As a signed in user, I would like to see all my past orders.

### Reach Goal(s)

- Build a search feature so that people can search for specific products by name.

___

## Survey

### Pitch

Make an app that can be used to create custom surveys (for instance, asking
"what should we eat for lunch today?" or "On a scale of 0-5, how well did you
understand what we just learned?") and collect the responses on a dashboard for
that particular survey.

### MVP User Stories

- As an unregistered user, I would like to sign up with email and password.
- As a registered user, I would like to sign in with email and password.
- As a signed in user, I would like to change password.
- As a signed in user, I would like to sign out.
- As a signed in user, I would like to create a survey with a title and possible
  answers.
- As a signed in user, I would like to update my survey's title and possible
  answers of a survey.
- As a signed in user, I would like to delete my survey.
- As a signed in user, I would like to see all surveys and its answers.
- As a signed in user, I would like to take a survey.

### Reach Goal(s)

- Make the dashboard real-time, so you can see answers pour in as they're completed.
- Each live survey should be hosted at a unique, randomly-generated URL.

___

## Image Hosting

### Pitch

Build an app that allows users to upload images onto a
virtual file system. Ordinary users can only read/download an image where as
Owners can do anything to the images they own.

### MVP User Stories

- As an unregistered user, I would like to sign up with email and password.
- As a registered user, I would like to sign in with email and password.
- As a signed in user, I would like to change password.
- As a signed in user, I would like to sign out.
- As a signed in user, I would like to upload an image to AWS.
- As a signed in user, I would like to update the meta-data of my image on AWS.
- As a signed in user, I would like to see the name of all images on AWS.
- As a signed in user, I would like to see the thumbnail of all images on AWS.
- As a signed in user, I would like to delete the reference of my image from the
  database.
- As a signed in user, I would like to see the following meta-data for any image:
  - date created/uploaded
  - date modified
  - owner (user who uploaded the image)
  - tag

### Reach Goal(s)

- "collaborators" can be chosen; they have permission to read from and write to
  images.
- As a signed in user, I would like to download images from AWS.

___

## Blogging Platform

### Pitch

It's 1999, and blogging is the coolest new trend on the world wide web! You've
been hired to create a blogging platform for the 21st century.

### MVP User Stories

- As a unregistered user, I would like to sign up with email and password.
- As a registered user, I would like to sign in with email and password.
- As a signed in user, I would like to change password.
- As a signed in user, I would like to sign out.
- As a unregistered user, I would like to see all users blog posts.
- As a unregistered user, I would like to see comments on those blog posts.
- As a signed in user, I would to create blog posts.
- As a signed in user, I would to comment on other users' blog posts.
- As a signed in user, I would to update my blog posts and comments.
- As a signed in user, I would to delete my blog posts and comments.

### Reach Goal(s)

- Add social features to your site, such as following other users.

___

## Inventory Management System

### Pitch

The main responsibility of the inventory management system is to be able to
track the inventory levels of various items that your business needs in stock.
You must keep track of the quantity of each item in stock, as well its price.

### MVP User Stories

- As an unregistered user, I would like to sign up with email and password.
- As a registered user, I would like to sign in with email and password.
- As a signed in user, I would like to change password.
- As a signed in user, I would like to sign out.
- As a signed in user, I would like to create an item.
- As a signed in user, I would like to update my item.
- As a signed in user, I would like to delete my item.
- As a signed in user, I would like to see all items.
- As a signed in user, I would like to see the quantity and price of each item.

### Reach Goal(s)

- Develop a barcode generator or QR code generator that creates a unique image
  that contains the unique identifier for each item in your inventory
- Automatic refill notifications: when an item gets to a low quantity, alert the
  user via email that they need to order more
- Enhanced authentication: Restrict user signups to emails of a certain domain,
  that of the company that is running the inventory management system. Make sure
  to verify email addresses. Use multi factor authentication during the sign up
  or sign in process.
