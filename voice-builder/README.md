# Voice Builder

Version 0.1.0

Build a reusable Writer skill from an existing writing voice. Voice Builder reads authorized samples, asks targeted questions in a quiz-like conversation, tries real writing, and exports the approved guidance as a separate skill.

It supports learning from your own writing or a clearly labeled reference voice. Creating an invented persona is outside this version's core workflow.

For Romanian instructions, see [GHID-RO.md](GHID-RO.md).

## Use terms

Free use and private modification are permitted, including business and paid client work. Redistribution or resale of the Builder, including modified versions, requires separate written permission. You may share the original distribution link instead. Customized Writer skills and writing outputs are excluded from this redistribution restriction, subject to the rights and permissions otherwise applicable to them.

The full [Voice Builder Free Use License](LICENSE.txt) governs the package. This is a custom license, not an open-source license.

## What is included

- `SKILL.md`: the workflow.
- `references/samples-and-privacy.md`: handling writing samples and export permissions.
- `references/learning-and-calibration.md`: learning expression, development, and recurring signatures; improving drafts from feedback.
- `references/writer-export.md`: creating and checking an independent Writer.
- `agents/openai.yaml`: optional interface metadata for compatible hosts.
- This guide and its Romanian counterpart.
- `LICENSE.txt`: the Builder's use and distribution terms.

The package contains generic instructions. It includes no personal samples, completed Writer, transcripts, personal profile, test output, credentials, executable scripts, external service configuration, or tracking code. It does not require an account beyond the AI environment you choose to use.

## Start in a chat

1. Open a new conversation in an AI environment that can read Markdown files and attachments or local folders.
2. Attach this package, or make the extracted `voice-builder` folder available to that environment. Keep `SKILL.md` together with its `references` folder. A host may require extraction or its own supported skill-installation process; uploading a ZIP alone does not establish installation.
3. Send this request:

   > Read Voice Builder's SKILL.md and follow its linked resources as needed. Help me create a reusable Writer from an existing voice. Guide me from the beginning through export. Do not install or publish anything.

4. The assistant should establish the intended writing task, language, and voice source using information you have already provided, then invite suitable samples.
5. Approve or adjust the proposed voice, review a useful draft, and confirm the guidance and destination for the Writer export.

If the assistant cannot read the package or a referenced file, it should say so. Keep the resources together or use a compatible environment; a claim that the skill was applied is not a substitute for file access.

For hosts with skill discovery, use their documented installation method for a folder containing `SKILL.md`. The Builder and its generated Writer are separate skills and separate installation decisions. This package does not install either automatically.

## The quiz and the result

Where the host supports selectable choices with free text, the assistant can use them. Elsewhere, it should offer numbered options and accept a number or another answer. The skill itself does not add buttons to a host.

The exported Writer should contain concrete approved voice guidance, any explicitly chosen recurring wording, and writing or review instructions. It should not need the Builder or the original interview to work. You can test it in a new chat with a new topic before relying on it.

If the host can create files, the assistant should deliver the actual Writer artifact. If it cannot, it should provide the complete content and clearly say it has not saved or installed it.

## Privacy and your material

Reading a local file through a cloud AI assistant is still processing by that AI service. Remove confidential information before sharing samples, and check your chosen service's data settings and policies. This instruction package cannot control provider retention, training settings, account access, backups, or external storage.

The workflow asks the assistant to use only authorized material, avoid saving a raw corpus by default, and obtain approval before storing or exporting exact excerpts. A voice profile or distinctive phrase can itself be identifying. Check the generated Writer before sharing it, even when the original samples are excluded.

Use material you are entitled to provide. Analysis permission does not automatically authorize publishing someone else's writing or passing private material to another service. The Builder's distribution terms do not grant rights over your samples or the Writer you create; those materials remain subject to their own rights and any applicable AI-provider terms.

## Limits

This is a conversational instruction package, not a local model, fine-tuning system, autonomous publishing service, or guarantee of identical behavior across AI hosts. Available browsing, file creation, choice controls, and skill discovery depend on the host.

There is no claim that every language, medium, model, or edge case has been validated. Judge actual writing for fluency, voice resemblance, factual accuracy, and the requested editorial angle. Structural validity alone does not establish writing quality. Voice Builder does not promise undetectable AI text or exact reproduction of an author.

The package requires no compiler, Python environment, mailbox access, or social-media integration. Fact research is optional and requires suitable tools. Publishing, installing skills, and sharing private material require their own authorization.
