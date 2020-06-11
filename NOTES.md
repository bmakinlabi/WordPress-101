# Part 7: How to add and create Post Formats
- https://www.youtube.com/watch?v=ut5b0gSpV1w&list=PLriKzYyLb28nUFbe0Y9d-19uVkOnhYxFE&index=7
- We activated post formats. Note that post formats are post types which we can publish on the blog.
- It means that we can publish a video, audio, image and more. There're nine types of post formats.
- The standard is the default. It'll the normal one we publish. We can't remove that one.
- Note that we can't create our own post format.
- `get_post_format()` returns the name of the post format. Note that it returns nothing for the standard because it's the normal.
- We're now dynamically generating the content base on the post format
- If the post format is different, the content will be different
- Wow. It's really cool. 