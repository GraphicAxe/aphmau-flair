# Privacy Policy for aphmau-flair

This Privacy Policy explains how the **aphmau-flair** Devvit application ("the Application") handles information.

## 1. Information We Collect
* **Custom Flair Request Data:** When a user voluntarily submits a custom flair request, the Application temporarily stores the requesting Reddit username, requested flair text, selected template, public account age/karma, and moderation status in Reddit's built-in Redis store and logs the request status to the moderation team's private Discord audit webhook.
* **Configuration Settings:** The Application accesses Discord webhook URLs configured by the app owner inside Reddit's encrypted developer settings store.

## 2. Third-Party Services
* **Discord API:** The Application posts moderation audit logs for custom flair requests to the subreddit moderators' Discord server.
* **Reddit API:** The Application publishes the interactive flair request post, manages the subreddit sidebar widget, and updates user flairs on Reddit via the Devvit SDK.
