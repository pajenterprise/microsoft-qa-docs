# Microsoft Q&A platform improvements

This document shows a list of bugs/improvements done in Microsoft Q&A. Those are a combination of internal feedback, customer feedback, and our own testing.

## November 25-December 18

### AnswerHub fixes

2.5.7 build (Dec 6)

- Azure Search Broken if custom schema is defined
- Character limitation is different when editing a topic description from the site than from the admin console
- Despite making the site in English, some strings show localized in localized Operating Systems
- Search results include items for topics that have been deleted
- Sign-In broken with SSO under certain conditions
- Tags field: Autosuggest doesn't work for compound tags
- When following a question/idea/article, I need to refresh the page to see the Following # increase and my name as a follower (permanent fix)

### Dev Rel fixes/features

Shipped via continuous development: 

* Following Users image is broken if user is not logged into Q&A

<!--
* Support for Usabilla to measure CSAT and compare with MSDN Forums.

-->

## October 30-November 25, 2019

### AnswerHub fixes

2.5.6 build (Nov 22)

* Page Not found results after canceling edit of topics on an existing piece of content
* Robots.txt requires authentication and some levels of permissions
* Idea status additional comments do not show anywhere in the UI
* Admin dashboard: Some controls are not dropdowns with available options
* Fixed security vulnerabilities
* A bunch of accessibility issues towards getting Grade C

For the following issues, we had workarounds, so users were not impacted, and now we have permanent fixes.
* Site map does not generated for questions
* Analytics json does not honor site context path
* Site context not honoring image pics in tags on Search suggestions

2.5.5 build (Nov 18)

* Tomcat fix upgrade to address security issues

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

### Dev Rel fixes

Shipped via continuous development: 

* Search returned 500 errors due to dual index
* Removed generic tags 
* Q&A Robots.txt is now part of Docs robots.txt
* Signing in and out of Q&A keeps the user when they signed in/out
* Bookmark icon now has a tooltip
* Breadcrumbs respect casing
* Supported products panel wraps and collides in some window sizes
* Moderators were able to Unanswer questions. We removed that capability.
