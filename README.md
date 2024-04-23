# BAO FAQ BOT

This discord bot was created by SmokeyStack for the purpose of making a FAQ bot for the Bedrock Add-Ons Discord Server.

## Managing Entries

Please make a PR to add or delete entries.

**Adding entries**

-   Create a `yaml` file with the following structure:

```yaml
name: entry-name
aliases: [ other-entry-name ]
title: Title Of FAQ Entry
body: |
    Multi
    Line
    String
```

Please note the indents are using 4 spaces, not tabs

For `name`, please use snake-case
For `title`, please capitalize the letter of each word
