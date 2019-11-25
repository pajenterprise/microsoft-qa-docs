# Microsoft Q&A platform improvements

This document shows a list of bugs/improvements done in Microsoft Q&A. Those are a combination of internal feedback, customer feedback, and our own testing.

## November 2019

2.5.4 build (Nov 7)

* When looking for an non-existing tag, AnswerHub returned random results
* When following a question/idea/article, I need to refresh the page to see the Following # increase and my name as a follower
* MD Preview shows HTML format, even though no HTML tags are white listed
* Sitemap for tags and articles misses a backslash due to site URL context
* Azure Search errors for content with more than 100 characters
* Azure Search errors with 'skip' parameter and auto complete
* When clicking on Bookmark question, the "More" contextual menu appears
* Removed permission from admin for "move own comment"
* A bunch of accessibility issues towards getting Grade C

2.5.5 build (Nov 18)

* Tomcat fix upgrade to address security issues

2.5.6 build (Nov 22)

* Page Not found results after canceling edit of topics on an existing piece of content
* Robots.txt requires authentication and some levels of permissions
* Idea status additional comments do not show anywhere in the UI
* Admin dashboard: Some controls are not dropdowns with available options
* A bunch of accessibility issues towards getting Grade C
For the following issues, we had workarounds, so users were not impacted, and now we have permanent fixes.
* Site map does not generated for questions
* Analytics json does not honor site context path
* Site context not honoring image pics in tags on Search suggestions

In addition, our team has fixed the following issues since we shipped via continuous development: 

* Search returned 500 errors due to dual index
* Removed generic tags 
* Q&A Robots.txt is now part of Docs robots.txt
* Signing in and out of Q&A keeps the user when they signed in/out
* Bookmark icon now has a tooltip
* Breadcrumbs respect casing
* Supported products panel wraps and collides in some window sizes
* Moderators were able to Unanswer questions. We removed that capability.
