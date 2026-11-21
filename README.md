# Pi Ask User Question

A Pi extension providing `ask_user_question`: free-text, single-select, and multi-select prompts. Choice prompts include an Other option for custom answers. Requires Pi's interactive UI.

## Install

```sh
pi install npm:@npm-ken/pi-ask-user-question
```

## Use

Ask Pi to clarify requirements or present choices. The model can call `ask_user_question` with `question`, optional `details`, optional `options` (`label`, optional `value` and `description`), and optional `multiSelect`.

Use arrow keys to navigate, Enter to select, and Escape to cancel. For multiple choices, toggle with Space or Enter, then select Submit.

