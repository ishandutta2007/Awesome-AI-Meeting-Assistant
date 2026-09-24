# Awesome-AI-Meeting-Assistant

## Top AI Meeting Assistant Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Meeting Transcription, AI Notes, Action Items, Speaker Diarization, Call Summaries & Meeting Intelligence*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Meeting Assistants**. These tools record or capture meetings, transcribe speech, identify speakers, generate summaries and action items, and make conversations searchable—often integrating with Zoom, Google Meet, Teams, and calendars.



**Examples** include Otter.ai, Fireflies.ai, Fathom, Read AI, Sembly AI, Avoma, Jamie AI, Supernormal, MeetGeek, and tl;dv (the category leaders).



**Open-source emphasis**: Commercial meeting assistants dominate team workflows, but strong local-first alternatives exist—**Meetily**, **Meet2Notes**, **MeetingScribe**, and related projects—built on Whisper-class transcription and local or private LLMs. This section lists every significant relevant project found.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Otter.ai](https://otter.ai/)**  

  Widely used AI meeting transcription and note-taking platform with real-time captions, summaries, and collaboration features.



- **[Fireflies.ai](https://fireflies.ai/)**  

  Meeting assistant that joins calls, transcribes, summarizes, and integrates with CRM and productivity tools for teams.



- **[Fathom, Read AI, Sembly AI](https://fathom.video/)**  

  AI notetakers focused on automatic summaries, action items, and post-meeting insights with strong UX for sales and general meetings.



- **[Avoma](https://www.avoma.com/)**  

  Conversation intelligence and meeting assistant oriented toward sales and customer conversations, with coaching and CRM updates.



- **[Jamie AI, Supernormal, MeetGeek, tl;dv](https://www.meetjamie.ai/)**  

  Modern AI meeting tools offering transcription, clips, searchable libraries, and workflow integrations.



- **[Other commercial AI meeting platforms](https://otter.ai/)**  

  Additional solutions for enterprise meeting intelligence, compliance recording, and multi-language support.



## Open-Source GitHub Projects



- **[Meetily](https://github.com/Zackriya-Solutions/meetily)**  

  Popular open-source, self-hosted AI meeting notetaker (MIT)—captures system audio (no bot required), local Whisper/Parakeet transcription, and local LLM (e.g. Ollama) summaries; privacy-first alternative to Otter/Fireflies.



- **[Meet2Notes](https://github.com/estebanstifli/Meet2Notes)**  

  Local-first, self-hosted AI meeting assistant for transcription, speaker diarization, and structured notes on Windows, macOS, and Linux—explicit open alternative to Fireflies, Fathom, and Otter.



- **[MeetingScribe](https://github.com/elmoghany/meeting-scribe)**  

  Local, key-free MIT meeting-notes agent for Google Meet and Zoom—live transcription, diarization, AI summaries, action items, and “ask your meeting” chat without cloud APIs.



- **[Memoir-Ai](https://github.com/TARIFUDDIN/Memoir-Ai)**  

  Open-source enterprise-style meeting intelligence platform aiming at autonomous recording, diarization, global RAG across meetings, and integrations (e.g. Jira/Slack)—self-hosted alternative framing to Fireflies/Otter.



- **[Char & similar local notepads](https://github.com/search?q=meeting+transcription+Whisper+open+source)**  

  Local-first AI notepads that combine manual notes with real-time Whisper transcription for private meeting capture.



- **[Whisper & faster-whisper ecosystems](https://github.com/openai/whisper)**  

  Foundational open speech-to-text models and optimized runtimes used by nearly all open meeting assistants.



- **[Speaker diarization open tools](https://github.com/pyannote/pyannote-audio)**  

  Open diarization pipelines (e.g. pyannote) for separating speakers in meeting audio.



- **[Meeting bot / recorder open projects](https://github.com/search?q=Zoom+bot+transcription+OR+meeting+bot+open+source)**  

  Community bots and recorders that join Zoom/Meet/Teams for automated capture (use with care regarding consent and platform ToS).



### Additional Strong Open-Source Options



- **Desktop local-first**: Meetily, Meet2Notes, and MeetingScribe for private, no-bot capture and notes.

- **Team / self-hosted platforms**: Memoir-Ai–style stacks for searchable meeting libraries and integrations.

- **Building blocks**: Whisper + diarization + local LLM summary as a minimal custom pipeline.

- **Composable stacks**: Audio capture → transcription → diarization → summary/action items → search/RAG.

- Commercial platforms still lead in calendar bots, CRM sync, multi-language polish, and team admin.



**Frameworks for building custom systems**:  

**Meetily**, **Meet2Notes**, and **MeetingScribe** are the strongest ready-to-run open alternatives.  

Under the hood, **Whisper** (or faster-whisper/Parakeet) + **pyannote** (or similar) + a local or private LLM cover the core pipeline.  

Commercial tools (Otter, Fireflies, Fathom, Read AI, Avoma, etc.) excel at seamless bot join, team libraries, and integrations.  

Privacy-conscious individuals and regulated teams often prefer local open tools; large sales or CS orgs often standardize on commercial assistants. Hybrid use (local for sensitive calls, commercial for routine meetings) is common.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Recording meetings may require consent under local law and company policy. Meeting bots and system-audio capture can raise privacy and platform terms-of-service issues. Inform participants and follow applicable rules.

- Open-source tools keep data local but require you to manage models, storage, and security. Commercial platforms handle infrastructure and support. Choose based on privacy needs, accuracy requirements, and team workflows.



---



**Made for knowledge workers, sales teams, founders, and anyone who wants better meeting notes without losing control of their data.**  

Let's expand open, private AI meeting assistants while recognizing the convenience and scale that leading commercial platforms deliver.
