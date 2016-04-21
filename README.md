## Overview

[Live Link](http://rails-eshop.herokuapp.com/)

* This is a shop application made in Ruby using the Rails Framework.
* It supports image uploading utilizing Amazon Web Services.
* This is not a commercial app.

##Contributors:

* [Nicole](http://github.com/themcny)
* [Isaac](https://github.com/isaachlee)
* [Paul](http://github.com/gastongouron)

## Features

* Users and Admins are different types of users

### Users
* Users have profile pages
* Users have timezones
* New users can register
* Existing users can login
* Users can upload an avatar
* Users can see the details of a particular product (quantity, price, name, description, etc.)

### Admins
* Admins can add new products to the site
* Admins can edit an existing product (validations implimented)
* Admins can delete existing products
* Admins can upload a product image

## Tests (Using RSPEC with Capybara)

* Product model tests
* Product controller tests
* User model tests
* User controller tests
* Feature testing for login/logout
* Feature testing for filling out the product forms.
