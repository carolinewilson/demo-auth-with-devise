# Auth with Devise

Practice app for setting up authentication using devise. 

###Notes
Modified ```def new``` & ```def create``` in Posts controller to use ```current_user.posts.build``` in place of ```Post.new```. 

Includes ```authentication_before_action``` for posts, with exceptions for ```index``` and ```show```.


* Rails 5.0.1
* Devise 4.2
* sqlite3