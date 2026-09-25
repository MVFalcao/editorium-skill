# Editorium

Editorium is a Codex skill that completes a message template using an **edital** and any supplied annexes or *retificações*. It preserves the template's language and structure, checks official updates for time-sensitive details, and flags information that the documents do not confirm.

## Install in Codex

Paste this command into a Codex chat:

```text
$skill-installer Install Editorium from https://github.com/MVFalcao/editorium-skill/tree/main/skills/editorium
```

Then send your edital and template and ask: `$editorium Complete this message from the attached edital.` If the skill does not appear immediately, restart Codex.

## Use in an existing custom GPT

An existing custom GPT cannot run the Codex skill installer. Open [GPT_INSTRUCTIONS.md](GPT_INSTRUCTIONS.md), copy its contents into your GPT's **Instructions**, and enable web search if you want it to check official updates. This file contains the same workflow as the skill, without the skill metadata. A GitHub link or file in the GPT's Knowledge does not install the skill.

## Use

Send the edital (a PDF, file, or link) and your message template. Then ask: “Use Editorium to complete this message from the edital.”

Editorium returns a ready-to-review draft followed by brief source notes. It does not send the message to recipients. No MCP server or API key is needed.
