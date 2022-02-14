# Guest-Post
Guest Post/Page Submission Plugin 
## Description

Using this plug-in user can create guest post submit form. 

This exercise is about creating an interface in Front-end site of website, so that guest authors
can submit posts from front-side. Using this interface, the guest author should be able to create
a post from front side. You will also need to create another page where all the posts created by
this author will be listed.

To achieve this, you should create a new user from wpadmin dashboard with Author role, which
you can use in this exercise.

Also, you should create a custom post type as “guest posts” and develop a Post creation form
UI on frontend through a shortcode or a Gutenberg block. The form should be visible only to
logged in authors.

## Shortcode

1. Add Guest post form shortcode `[add_guest_post]` 
2. Show the list of posts which are in pending status for admin approval shortcode `[list_guest_posts]` 