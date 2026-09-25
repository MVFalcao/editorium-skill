# Editorium

Editorium completes a message template using an **edital** and any supplied annexes or *retificações*. It preserves the template's language and structure, checks official updates for time-sensitive details, and flags information that the documents do not confirm.

**Share this repository link for both Codex and custom GPTs.** The workflow is the same; each product has its own setup step below. There is no single install command that works in both.

## If you use Codex

Paste this command into a Codex chat:

```text
$skill-installer Install Editorium from https://github.com/MVFalcao/editorium-skill/tree/main/skills/editorium
```

Then send your edital and template and ask: `$editorium Complete this message from the attached edital.` If the skill does not appear immediately, restart Codex.

## If you edit your own custom GPT

Open [GPT_INSTRUCTIONS.md](GPT_INSTRUCTIONS.md), copy its contents into your GPT's **Instructions**, and save the GPT. Enable web search if you want it to check official updates. This file mirrors the [Codex skill](skills/editorium/SKILL.md) without skill metadata. The Codex install command does not work in a custom GPT's chat or editor.

## Use

Send the edital (a PDF, file, or link) and your message template. Then ask: “Use Editorium to complete this message from the edital.”

Editorium returns a ready-to-review draft followed by brief source notes. It does not send the message to recipients. No MCP server or API key is needed.
