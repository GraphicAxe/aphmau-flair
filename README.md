# Aphmau Custom Flair Requests (`aphmau-flair`)

A standalone Reddit Devvit application that provides a native, moderator-reviewed custom user flair request workflow with an interactive custom post, subreddit menu actions, sidebar button widget setup, and Discord webhook audit logging.

## Configuration Settings

* **`flairLogWebhook`**: Discord webhook URL used to post and update custom flair request audit cards.
  ```bash
  npx devvit settings set flairLogWebhook "https://discord.com/api/webhooks/..."
  ```
* **`discordWebhook`**: Optional fallback/error alert Discord webhook URL.
  ```bash
  npx devvit settings set discordWebhook "https://discord.com/api/webhooks/..."
  ```

