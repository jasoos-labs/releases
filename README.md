# JasoosLabs Releases

**Of the AI, By the AI and For the AI.**

![JasoosLabs software releases](media/NovaInsert-GitHub-Hero-1280x640.png)

Practical software from JasoosLabs.

---

## Our Released Products

1. [TTS Voice Showdown](#tts-voice-showdown)
2. [Windows Dev Starter Kit — PowerShell Edition](#windows-dev-starter-kit--powershell-edition)
3. [NovaInsert](#novainsert)

---

## TTS Voice Showdown

### Hear the difference before choosing a narration voice

Choosing a voice from a name or sample clip can be misleading. TTS Voice Showdown lets you hear AI voices, cloned voices, and the author’s recorded voice read the **same passage**, so you can compare how they actually sound for video narration.

Choose one of three passages, select up to three voices, and play them individually or together. Compare the voices side by side and decide which fits your video.

**What’s included:** 17 recordings from 10 sources: commercial and Windows voices, open models, voice clones, and the author’s recording. Links identify the source or model behind each recording group.

**TTS Voice Showdown helps you choose by listening and comparing—not by guessing from a voice label.**

- [Open the live PWA](https://jasoos-labs.github.io/tts-voice-showdown/)
- [View the source repository](https://github.com/jasoos-labs/tts-voice-showdown)

---

## Windows Dev Starter Kit — PowerShell Edition

### Spend less effort remembering the chores around your project

Every project comes with a familiar set of small jobs: find a file, inspect changes, package source, apply an update, build, test, and run. Remembering which command does what—and how to do it consistently—can become its own task.

**Windows Dev Starter Kit gives those chores a simple, repeatable command set.** Short commands help you inspect a project, search files and text, check Git status, and follow a build-test-run cycle from PowerShell.

**`bld` → `tst` → `run`**  
Or use **`go`** to build, test, and run in sequence, stopping when a step fails.

It’s a beginner-friendly personal toolkit for working with projects under Windows development folders. It complements the tools you already use; it isn’t meant to replace experienced developers’ established workflows.

### Quick start

Place the kit under your development folder, such as `D:\dev\windows-dev-starter-kit-powershell`, then load it in PowerShell:

```powershell
. .\dev.ps1
```

Go to a project folder and enter `dev` to see the command guide. Add a dot-source line to your PowerShell profile to load the commands automatically in later sessions.

### Main commands

`dev` help · `cdd` choose project · `sht` browse files · `fff` find files · `fft` search text · `pjs` Git status · `src` package source · `upd` apply update · `bld` build · `tst` test · `run` launch · `go` build, test, run

- [View the public repository](https://github.com/jasoos-labs/windows-dev-starter-kit-powershell)

---

## NovaInsert

### Put augmented and agentic AI to work—with structure

AI can help explore ideas, build solutions, and handle work in the background. But every task still needs clear direction, useful context, and a way to check the result.

**NovaInsert gives you a repeatable way to manage that work.** Use the **4E Value Chain** to move from exploring a possibility to realizing value. Use the **5E Solution Chain** to take each task from understanding the need through evidence, engineering, evaluation, and delivery.

Prepare the instructions and tools for a project, give the task to AI, step away while it works, then return to verify the result. Reuse what works instead of reconstructing your workflow each time. NovaInsert also helps with the commands and repetitive computer tasks around your AI work.

### How it works

**Prepare → Delegate → Leave → Return → Verify**

You direct the work and remain accountable for the result. NovaInsert helps make the process organized and repeatable.

### What NovaInsert provides

**Library Insert Sets (LIS)** organize reusable prompts, instructions, procedures, commands, checks, and keyboard actions by project, ready to send to the application where the work happens.

**Hideout** keeps selected protected information separate from ordinary workflow material.

NovaInsert is a Windows tool for human-directed AI workflows and everyday computer tasks. It facilitates agentic work; it is not an autonomous AI agent.

### Download NovaInsert v1.0.2

- [Small — requires .NET 8 Desktop Runtime](releases/NovaInsert/v1.0.2/NovaInsert-v1.0.2-win-x64-small.zip)
- [Full — includes the .NET runtime](releases/NovaInsert/v1.0.2/NovaInsert-v1.0.2-win-x64-full.zip)
- [v1.0.2 release notes](releases/NovaInsert/v1.0.2/RELEASE-v1.0.2.md)

**What’s new in v1.0.2:** improved Windows Terminal tab discovery and reuse, stronger destination verification, and dragon flight timed immediately before command dispatch. This release also adds a 22-command Windows Dev Starter Kit LIS. **320 automated tests passed.**

Earlier NovaInsert packages and release notes are in [`releases/NovaInsert/`](releases/NovaInsert/).

- [View the NovaInsert repository](https://github.com/jasoos-labs/NovaInsert) (private source repository)

---

## Feedback & Support

- **Bug or problem?** [Open an issue](https://github.com/jasoos-labs/releases/issues/new/choose) and choose **Bug report**.
- **Idea or improvement?** Open an issue and choose **Feature request**.
- **Other or private contact?** Use the public contact email on the JasoosLabs GitHub organization profile.

JasoosLabs builds practical software around AI-assisted work, experimentation, automation, music, media, and everyday computing. This repository collects public downloads and release notes; each project page provides its source and product information.
