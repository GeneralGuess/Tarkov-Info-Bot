# Tarkov Info Bot - Troubleshooting

If Tarkov Info Bot is not returning the expected result, use the steps below to help identify the problem.

## 1. Check the Command

Make sure you are using one of the supported commands:

| Command | Search |
|---------|--------|
| `!info` | Quests |
| `!item` | Items |
| `!key` | Keys and keycards |
| `!ammo` | Ammunition |
| `!map` | Maps |

The basic command format is:

`!command name`

Partial searches should contain **at least 4 characters** for proper results.

---

## 2. Check Streamer.bot

Verify that:

- Streamer.bot is running.
- Tarkov Info Bot was successfully imported.
- The Tarkov Info Bot commands and actions are enabled.
- Your streaming/chat platform is connected to Streamer.bot.
- Streamer.bot has internet access.

---

## 3. Try a Known Search

Test:

`!item bitcoin`

Expected result:

`Physical Bitcoin`

`https://escapefromtarkov.fandom.com/wiki/Physical_Bitcoin`

If this works but another search does not, the problem may be related to that specific search rather than the plugin itself.

---

## 4. Check the Escape From Tarkov Wiki

Tarkov Info Bot retrieves information from the Escape From Tarkov Wiki.

If the Wiki is unavailable, has changed its information or categories, or has changed how a page is named, a search may fail or return an unexpected result.

---

## 5. Check the Streamer.bot Logs

Tarkov Info Bot includes logging to help troubleshoot searches and API responses.

In Streamer.bot, check the logs after running the command that is causing the problem.

The logs can help determine whether:

- The command was triggered.
- A Wiki response was received.
- Search results were found.
- Results were rejected during filtering.
- An error occurred while processing the Wiki response.

When troubleshooting, run the problem command again and review the log entries generated immediately after it.

---

## Reporting a Problem

If you report an issue with Tarkov Info Bot, please provide:

- The command you entered.
- What you expected it to return.
- What it actually returned.
- Any relevant Streamer.bot log entries.

Providing the command and logs will make it much easier to reproduce and identify the problem.

---

## Support & Maintenance

Tarkov Info Bot is an open-source project created by **General Guess**, a beginner/hobbyist developer.

The source code is available for anyone who wants to review, modify, troubleshoot, or expand the project in accordance with its license.

**General Guess is not obligated to provide technical support, troubleshooting, updates, maintenance, or compatibility fixes.** Support and development may be provided at the discretion of General Guess and may be reduced or discontinued at any time.

If development of Tarkov Info Bot is discontinued, the source code will remain available so the community can continue to use, modify, or develop the project in accordance with its license.
