# Release frequency, process, and notifications

We have two engineering streams for Microsoft Q&A:

1. Dev Relations team to include updates on UI and integration with our services, such as Tech Profile.
2. Devada team delivers AnswerHub builds with bug fixes and new features.

## Dev Relations team

As part of the full Docs ecosystem, Dev Relations team deploys fixes and new features in daily basis. So when we need to ship fixes and new features for Q&A, we will release as part of this daily deployment.

## Devada team

Devada sends AnswerHub builds Dev Relations builds every other week that includes both bug fixes and new features. This happens on Fridays. **The first build in 2020 will be on January 17, and from then, every two weeks**.

Dev Relations will deploy the build to [Microsoft Q&A PPE](https://ppe.docs.microsoft.com/answers/index.html), where our team will do both automatic and manual testing to ensure the build has the quality needed to be deployed to production.

> [!NOTE]
> Partners are welcome to do testing on this build in PPE as they see it fit and log issues as per [Report issues instructions](report-issues.md). However, we do not require partner sign off to deploy the builds to production.

If the build passes our quality gates, the build will be **deployed to production on the following Monday** (so if a build is deployed on Jan 17 to PPE, the build will be deployed to production on Jan 20).

> [!IMPORTANT]
> Right now we do not provide release notes to our customers. Once we have a good process in place, we will provide release notes to customers too.

## How can I stay informed on build deployments, bug fixes, and new features?

1. **PPE**
    - We will have a sticky post indicating that the build is deployed and a link to Devada's release notes.
    - You can subscribe to the "*qna-ppe*" tag and get a mail notification when there is a new post about it. 
2. **Production**
    - We will update the [Release notes](platform-improvements.md) page. Release notes will include fixes/features both from Dev Relations and Devada.
    - We will send a monthly notification with all the improvements made to [Technical Q&A Partner Announcements](devrelannouncetechqa@microsoft.com). Make sure you subscribe to that DL if you want to get these notifications. 