## Spam management

> [!NOTE]
> This article is targeted to moderators and site admins.
> This article assumes that you are in the moderation area. For dealing with spam when found on the site, please see [Report content for moderation review](report-to-moderation.md).

Spam can be caught two ways:

1. **Automatically**: Via both Akismet and the AnswerHub Shield plugin
1. **Manually**: Users can report content for moderation review.

When you are moderator, you can see a *Moderation* option when you click on your Avatar. Clicking on it, it will take you to the [moderation page](https://review.docs.microsoft.com/en-us/microsoft-qa-docs/user-experience-guides/moderator?branch=master). Where you can see 3 tabs:

1. Moderation
1. Reported
1. Spam

## Automatic spam reports - The Moderation tab

This tab is for content caught by AnswerHub's Shield plugin. Posts will go into this folder if:

1. A user is posting more than one question in less than 5 minutes. The second and Second question and any subsequent questions will go to this folder.
1. A user enters a phrase more than 10 times in their question. Example "phone number".
1. Spammers usually replace standard letters and numbers with characters that mimic the original ones. When the amount of unusual characters exceeds 40%, this is considered spam.

Note that while items show up on the Moderation tab, they are no longer visible in the community.  

When there is content in this folder, you can take the follow actions:

1. Suspend the user if necessary.
1. **Publish**. To publish the content back as it is a false positive.
1. **Reject**. Moderator thinks the post is problematic and deletes it from the site.
1. **Reject as spam** (RECOMMENDED). To move the content to the ["Spam" tab](#automatic-spam-filtering---the-spam-tab) folder and report the post as spam to Akismet to help them improve their spam algorithm.

> [!TIP]
> Sandra to write guidelines to suspend a user

## Manual spam reports - The Reported tab

This tab is for content that a user has manually sent to a moderator for review. When they do that, users have to send an explanation for it as well:

1. Spam
1. Advertising
1. Offensive, Abusive, or Inappropriate
1. Content violates terms of use
1. Copyright Violation
1. Misleading
1. Someone is not being nice
1. Not relevant/off-topic
1. Other

Note that until a moderation has taken action, the content will continue to be displayed on Microsoft Q&A. Users do not see a note in the content indicating that the content is under moderation review.

### Steps to follow if the content is spam

1. Click on *Delete the content* link, so the content is removed from the site.
1. Click on *Reject as spam*.
1. The content is moved to the ["Spam" tab](#automatic-spam-filtering---the-spam-tab) and report the post as spam to Akismet to help them improve their spam algorithm.

Note that you cannot Reject as Spam a content that is deleted.

### Steps to follow if the content is not spam

1. Click on *Cancel Report* link. This will remove the content from the report queue.

## Automatic spam filtering - The Spam tab

This is the tab where all content reported by Akismet is automatically sent or users report as spam from the *Report* folder. Items in the Spam tab are visible to community members with the following disclaimer at the top "This post is currently awaiting moderation. If you believe this to be in error, contact a system administrator.". Items in the Spam folder will not show in any search results.

This folder is mainly managed by Dev Relations team. The current cadence to review this folder is at least once a day. Once the process is outsourced to our Tier 1 support team, it will be every few hours.

If you want to review spam in this folder, please follow the guidelines below.

Note that the Spam folder shows content reported from oldest to newest. So you need to scroll all the way to the end of the page to see the newest content.

### Steps to follow if the content is spam

1. Evaluate which part of the thread has been reported: question, answer, feedback, comment.
1. Click on the link to go to the content.
1. Click on the gear icon next to the content piece that contains the spam (question, answer, feedback, comment).
1. Click on *Delete*. As a moderator, you will see a label indicating the content is being deleted. Regular users will not see the deleted content though.
1. Go back to the moderation page, Spam tab, and Suspend the user if necessary.

> [!TIP]
> Sandra to write guidelines to suspend a user

> [!IMPORTANT]
> In order to allow moderators to go over the reported spam, we have set a *Spam Queue Retention Period* of 3 days. So if the content is spam, you will see the content there for 3 days. Simply ignore it if you already did the steps above.

### Steps to follow if the content is not spam

1. Click on the "Publish" button. This will make the content disappear from this tab.
1. This will also report the post as non-spam to Akismet.

