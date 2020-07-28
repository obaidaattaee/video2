![Image of Yaktocat](https://i.ibb.co/c1wy4dG/Screen-Shot-2019-05-11-at-8-38-51-PM.png)
![Image of Yaktocat](https://i.ibb.co/bdhFRsQ/Screen-Shot-2019-05-11-at-8-39-04-PM.png)
![Image of Yaktocat](https://i.ibb.co/JyggXGY/Screen-Shot-2019-05-11-at-8-39-16-PM.png)

# video-website
Video , category , skills , tags  , comments ,search , pages , contact us (dashboard , website)

# Install

 go to this path

```
app/Providers/AppServiceProvider.php
```

then comment this lines

```
view()->share('categories' , Category::get());
view()->share('skills' , Skill::get());
view()->share('pages' , Page::get());
```

then

```
   composer install
   php artisan migrate
   php artisan db:seed
```

now remove comment the lines on `AppServiceProvider.php` file

then login with

```
   email : admin@website.com
   password : 123456
```

# Admin 
-	Add / edit /delete category
-	Add/edit/delete skills
-	Add/edit/delete tags
-	Add/edit/delete users
-	Add/edit/delete videos
-	Add/edit/delete comments
-	Add/edit/delete pages
-	Delete/Reply Contact us
-	Statistics videos/comments/category/skills/tags

# Website
Visitors
   -	Can view video
   -	Can view category
   -	Can view pages
   -	Can view comments
   -	Can search by name 
   -	Can search by tags
   -	Can view skills
   -	Can view user profile
   -	Can send message in Contact us
   
Users
   -	Can add comments
   -	Can edit profile

# Technologies
  -	Laravel 5.8
  -	Bootstrap 4
  -	Jquery


# video2
