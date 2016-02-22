# Login Page
- sends POST request with username and password
- server returns Main Page with post/feeds

# Main Page
1.  Clicking on a Facebook picture (in the post) sends a GET with the profile ID and brings you to the profile page

# Profile Page (shows a lists of posts)
1.  Click on a profile picture, sends a GET with profile ID and returns a page with the picture

  <b>OR</b>

1. Clicking on like of a Facebook post, sends a POST request(with the current user ID, profile ID, and Facebook ID) to like a Facebook post
2. Clicking on comment, sends a POST request(with the current user ID,profile ID, and comment text) and posts a comment

# Profile Picture Page
1. Clicking on like, sends a POST request (with the current user ID and profile ID) to like the picture
2. Clicking on comment, sends a POST request (with the current user ID, profile ID, and comment text) and posts a comment
