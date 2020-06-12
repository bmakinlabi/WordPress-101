# Part 9: Edit the query_posts with WP_Query
- https://www.youtube.com/watch?v=GA--ROatgYM&list=PLriKzYyLb28nUFbe0Y9d-19uVkOnhYxFE&index=9
- A reference: https://developer.wordpress.org/reference/functions/query_posts/
- We included the last blog post on the home page. Wow. We're now creating a home and how it should look. What it should display. 
- Always use `wp_reset_postdata();` to reset everything you've done above. Whenever you use the query post. 
- To print posts only from a certain category you need to get the category id. Go to the browser and go to categories in your backend and find the category and then click on it. Go to the browser box and you'll see `tag_ID=6` - In my case here, that particular category id is 6 and that's why it's there.
- We use `cat` for the id and then `category_name` for the name
- We're formulating the real home page and how we want it to look here. And I can already start to understand how I can build a great home page and put everything organized.