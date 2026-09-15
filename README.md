# prompts

A personal library of prompts I use with frontier models. These are the ones that have earned a permanent spot, so I figured they were worth sharing.

## Two kinds of prompt here

**`chat-prompts/`** - sent as a message inside a conversation. Paste into the chat box.

**`platform-instructions/`** - pasted into a platform's customization field (ChatGPT custom instructions, Claude user preferences, Grok custom instructions). These persist across conversations and behave differently from the same text sent as a message. Each file's front matter names the specific field it belongs in.

## Using these

Every file has front matter recording the model and date it was last verified on. Prompts decay - a prompt tuned on one model version can behave differently on the next. If the `last_verified` date is old, treat the prompt as a starting point rather than something that works as-is.

The prompt body is in a fenced block in each file. Copy that, not the surrounding commentary.

## Notes

No guarantees. Some of these push models in directions their defaults resist, and results vary by model, version, and mode.

## License

MIT
