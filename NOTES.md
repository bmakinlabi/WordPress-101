# Part 6: How to add Theme Features with add_theme_support
- https://www.youtube.com/watch?v=ghmdq1hEm14&list=PLriKzYyLb28nUFbe0Y9d-19uVkOnhYxFE&index=6
- We added background customizer. It lets us customize the background of our WordPress site. We activated that support.
- Note that this is located under `Appearance > Background`. 
- We activated the header now too. Just go to `Appearance > Header` (there we can customize the header of our app.)
- I also get this code 
```php
<img src="<?php header_image(); ?>" height="<?php echo get_custom_header()->height; ?>" width="<?php echo get_custom_header()->width; ?>" alt="" />
```
- from here: https://codex.wordpress.org/Custom_Headers
- it's made for us to just get our custom image. WordPress has made it already for us. I can use it where I want to place the customer header image. 
- We also activated post thumbnails. (Now if we go to our posts, we can see that the featured image is allowed if we want to upload it.)
- We activated post thumbnails. We can specify the size inside the function. We can use `large`, `thumbnail` and there're others. 