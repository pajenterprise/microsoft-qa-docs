## Spam management

Spam can be caught two ways:

1. **Automatically**. All posts by the community go through Akismet's checking process.
If the post passes the check from Akismet, then it will post to the community. If the post fails the check from Akismet, then it will go to the **Spam** tab, under the Moderation page where a moderator can evaluate it.
1. **Manually**. Users can report content for moderation review.

This article explains the workflow to follow for each of the options enabled in Microsoft Q&A.

> [!TIP]
> This article is targeted to moderators and site admins.

When you are moderator, you can see a Moderation option when you click on your Avatar. Clicking on it, it will take you to the [moderation page](https://review.docs.microsoft.com/en-us/microsoft-qa-docs/user-experience-guides/moderator?branch=master). Where you can see 3 tabs: 

1. Moderation
1. Reported
1. Spam

## Moderation tab

Right now, there is not content coming to this folder, as we have disabled the AnswerHub Shield plug in and we do not have allow people to report something to moderation, as it is confusing with the report functionality.

## Reported tab

When content is in this tab, that means a user has manually sent the thread for a moderator to review. When they do that, users have to send an explanation for it as well:

1. Spam
1. Advertising
1. Offensive, Abusive, or Inappropriate
1. Content violates terms of use
1. Copyright Violation
1. Misleading
1. Someone is not being nice
1. Not relevant/off-topic
1. Other

> [!NOTE]
> The content will be displayed on the site while a moderator reviews it.
> Users do not see a note in the content indicating that the content is under moderation review.

### Steps to follow if the content is spam

*To be documented once bugs are resolved.*

<!--
Bugs:

1. https://dzonedev.atlassian.net/servicedesk/customer/portal/6/MSAH-1012
1. https://dzonedev.atlassian.net/servicedesk/customer/portal/6/MSAH-1011
-->

<!--

1. Click on Delete the content link, so the content is removed from the site.
1. Click on *Reject as spam*.
1. The content is moved to the "Spam" tab.
1. Go back to the moderation page, Spam tab, and ban the user if necessary.
**Sandra to write guidelines to ban a user**
-->

### Steps to follow if the content is not spam

1. Click on *Cancel Report* link. This will remove the content from the report queue.

## Spam tab

This is the tab where all content reported by Akismet is automatically sent. This folder should be mainly managed by Dev Relations team. If you feel like you want to go over spam on this folder, here are the guidelines.

Items in the Spam tab are "invisible" to community members. Items caught by Akismet will only be visible in the Spam tab and will not show in any search results.

### Steps to follow if the content is spam

1. Evaluate the part of the thread that is being reported: question, answer, feedback, comment.
1. Click on the link to go to the content
1. Click on the gear icon next to the content piece that contains the spam (question, answer, feedback, comment).
1. Click on Delete. As a moderator, you will see a label indicating the content is being deleted. Regular users will not see the deleted content though.
1. Go back to the moderation page, Spam tab, and ban the user if necessary.

*Sandra to write guidelines to ban a user*

> [!IMPORTANT]
> In order to allow moderators to go over the reported spam, we have set a *Spam Queue Retention Period* of 3 days. So if the content is spam, you will see the content there for 3 days. Simply ignore it if you already did the steps above.

### Steps to follow if the content is not spam

1. Click on the "Publish" button. This will make the content disappear from this tab.
1. This will also report the post as non-spam to Akismet.

