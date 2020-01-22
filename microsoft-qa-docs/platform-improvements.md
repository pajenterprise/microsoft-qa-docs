# Microsoft Q&A release notes

This document shows a list of bugs/improvements done in Microsoft Q&A. Those are a combination of internal feedback, customer feedback, and our own testing.

<!--
## Jan 1-31, 2020

### AnswerHub fixes

2.5.10 build (Jan 17)

-fixed: ANSUP-11444: Sign-in broken with SSO for contextual URL
-fixed: ANSUP-11782: New permission:
    - Access API anonymously
    - Publish others idea                      
    - Publish others idea comment                  
    - Publish others kbentry
-fixed: ANSUP-11534: Revoke publish question permissions still allow user to post their own posts from in moderation
-fixed: ANSUP-11490: Search result count includes deleted items
-fixed: ANSUP-11504: Tags field: Autosuggest doesn't work for compound tags
-fixed: ANSUP-11513: Favicon does not show due to contextual URL
-fixed: ANSUP-11530: When there is not a favicon link, there should not be a link for it
-fixed: ANSUP-11555: Search using the "authored by" returns blank results on prod/stage
Admin dashboard: Make Site - Layout - Sitemaps - "Questions Sort" a drop-down control
-fixed: ANSUP-11635: Reported Number is not correct in moderation list
-fixed: ANSUP-11360: A user can vote on their own ideas and answers
-fixed: ANSUP-11693: [MD Editor] When attaching a file, the link text for the file should be the file name (image ame is the file name with the Unique ID)
-fixed: ANSUP-11743: Heading tag (H1) are missing or duplicates across different pages
-fixed: ANSUP-11724: Äú/page-view/track.json" throwing 500 errors on docs.microsoft.com/answers
-fixed: ANSUP-11803: Submit to Akismet edited posts with the – recheck_reason flag instead to avoid spam false positives
-fixed: ANSUP-11807: “Follow/UnFollow” a tag - the Follower count will not get updated/incremented
- Accessibility bugs

### Dev Rel fixes/features

Shipped via continuous development: 

- Updating Tech Profile user details get reflected automatically in Q&A
- Q&A activity shows in Tech Profile for all users
-->

## November 25-December 31 2019

### AnswerHub fixes

2.5.8 build (Dec 13)

- Award Plugins get activated with each build deployment

2.5.7 build (Dec 6)

- Azure Search Broken if custom schema is defined
- Character limitation is different when editing a topic description from the site than from the admin console

- Search results include items for topics that have been deleted
- Sign-In broken with SSO under certain conditions
- When following a question/idea/article, I need to refresh the page to see the Following # increase and my name as a follower (permanent fix)
- Despite making the site in English, some strings show localized in localized Operating Systems
- Tag car renders offscreen
- Favicon does not show due to contextual URL

### Dev Rel fixes/features

Shipped via continuous development: 

* Support for Usabilla to measure CSAT 
* Following Users image is no longer broken if user is not logged into Q&A
* Breadcrumbs respect casing
* When hovering a tag, the description is now fully visible

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
