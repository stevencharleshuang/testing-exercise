# testing-exercise

## Email Verification Feature

### Conditionals & User Stories
* If user email is not a valid format, display error
  * As an admin, I want to verify a user's email so that my database has valid email addresses for each user.
* If user hasn't verified email within 24 hours, send email that verification link has expired
  * As an admin, I want to set a 24 hour expiration period so that the user has 24 hours to verify their email address.
* if user clicks verification link from email, ask to set password
  * As a user I want to clik the verification link in my email so that I can confirm my email address.

## Posts Feature
* If user creates a post without content, display error
  * As an admin, I want to make sure that all posts have content so that there are no empty posts
* If the post description contains more the 2000 characters, display error
* If user does not have permission to comment, hide comment button
