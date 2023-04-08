# README

* Ruby -v 3.2.1


This app is just a tutorial in how to create categories in Rails.
:category | :title | :description
** Does not come with full content text **

_________________________________________

To | CREATE | a new blog:
http://localhost:3000/blogs/new
OR
http://localhost:3000/blogs
--> New blog <--

To | SHOW | PATCH | DESTROY | a blog
navigate in browser to:
http://localhost:3000/blogs/1 <-- SHOWS a single blog id
OR
http://localhost:3000/blogs/
--> Show this blog <-- you can EDIT or DESTROY here. You can also change the category in 'edit this blog'
OR
http://localhost:3000/blogs/1/edit <-- to EDIT/PATCH that specific id

----------------------------------------

To | CREATE | a new category:
http://localhost:3000/categories
--> New category <--
OR
http://localhost:3000/categories/new

TO | SHOW | a list of categories and blogs
http://localhost:3000/categories <-- you can also create a new category here

To | PATCH | DESTROY | a category
http://localhost:3000/categories/1 <--
--> New category <-- you can EDIT or DESTROY here
