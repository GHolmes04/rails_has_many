![General Assembly Logo](http://i.imgur.com/ke8USTq.png)

Rails: `has_many` \& `belongs_to`
=================================

So far you've seen how to associate records with on another using foreign keys in a database. Just as we can use ActiveRecord to read, change, update, and delete data from our database, we can use ActiveRecord relationship methods to associate records with one another using Ruby code.

Objectives
----------

* Digram the database tables and Entity Relationship Diagram that describe a parent-child relationship.
* Associate plain Ruby objects with one another.
* Write a migration for a parent-child relationship.
* Compare `has_many` and `belongs_to` to other macros, like `attr_accessor`.
* Configure ActiveRecord to manage parent-child relationships using `has_many` and `belongs_to`.
* Create associated records using the rails console.

Instructions
------------

Fork and clone this repo. Change into the appropriate directory and update dependencies.

Next, create your database, migrate, and seed. Start your web server.

Follow along with your instructor, closing your laptop if requested.

Entity Relationship Diagrams (ERDs)
-----------------------------------

Exercise: ERDs
--------------

* Determine parent-child relationships between entities.
* Draw an analogy between collections and containers.

Resources
---------

* [Rails Association Basics](http://guides.rubyonrails.org/association_basics.html) Read the sections on belongs_to and has_many.
* [ActiveRecord Basics](http://guides.rubyonrails.org/active_record_basics.html)
* [Rails Documentation](http://api.rubyonrails.org/)
* [Debugging Rails with the byebug Gem](http://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-byebug-gem)
* [With So Much Rails to Learn, Where Do You Start?](http://www.justinweiss.com/blog/2015/05/25/with-so-much-rails-to-learn/)
