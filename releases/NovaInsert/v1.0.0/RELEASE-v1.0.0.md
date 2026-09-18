# NovaInsert v1.0.0

NovaInsert is a Windows productivity app for keeping reusable text, commands, keyboard actions, and Library Insert Sets ready, then sending them to the exact destination you choose.

JasoosLabs: **Of the AI, By the AI and for the AI.**

## What NovaInsert does

NovaInsert helps with repeatable work. You can save common replies, PowerShell commands, development commands, AI prompts, testing checklists, and system-admin steps, then send them to Notepad, terminals, browsers, editors, or other linked Windows under your control.

NovaInsert does not guess where to type. You link a destination, choose an insert, and NovaInsert sends it there.

For the first tutorial, turn on **Enable sounds** and **Enable Nova dragon flight**. The sounds confirm what happened, and the dragon flight shows where NovaInsert is sending the insert.

## Downloads

### Recommended: Small ZIP

**NovaInsert-v1.0.0-win-x64-small.zip**

This is the preferred download for most users. It is small and fast to download. It requires the Microsoft **.NET 8 Desktop Runtime for Windows x64**.

If NovaInsert does not start, install the .NET 8 Desktop Runtime, then run `NovaInsert.exe` again.

### Full ZIP

**NovaInsert-v1.0.0-win-x64-full.zip**

This larger package includes the required .NET runtime. Use this if you do not want to install .NET separately.

## First run

1. Extract the ZIP.
2. Run `NovaInsert.exe`.
3. Open the built-in **README — Start Here** guide.
4. Turn on **Enable sounds** and **Enable Nova dragon flight** for the first tutorial.
5. Create a practice Project, link Notepad, and send your first Insert.

## Built-in Library Insert Sets

NovaInsert includes Starter Library Insert Sets so new users can see useful patterns immediately. These are not just shortcuts; they are examples of how to organize repeatable work.

### Everyday work

- **Everyday Replies** — reusable response text for common messages.
- **Issue Templates** — structured text for describing bugs, requests, and observations.

### Windows and PowerShell

- **Win - PowerShell** — common PowerShell command patterns.
- **Win - Diagnostics** — commands for checking Windows state and troubleshooting.
- **Win - Keyboard** — saved keyboard-action examples.
- **Win - Fields** — examples of reusable fields and placeholders.
- **Win - WSL Ubuntu** — starter commands for WSL workflows.

### Raspberry Pi and backup-node admin

- **Pi - Backup Node** — Raspberry Pi setup and admin commands for fixed IP checks, mounted shared drives, Samba status, Syncthing status, and backup-node maintenance.

This LIS is useful for users who want a small home-network backup node or shared-drive device and need repeatable commands without retyping them.

### Development workflows

- **Dev - Git** — common Git command sequences.
- **Dev - Dotnet** — .NET build, test, and run commands.
- **Dev - Node Vite** — Node/Vite development commands.
- **Dev - React Native** — React Native command patterns.
- **Dev - Android ADB** — Android device and ADB commands.

### Media workflows

- **Media - FFmpeg** — starter FFmpeg command patterns for media work.

### AI and LLM work

- **AI - 4E - LLM** — Explore, Engineer, Execute, Evaluate style LLM workflow support.
- **AI - LLM - Explore** — prompts for understanding the problem before acting.
- **AI - LLM - Engineer** — prompts for turning ideas into structured work.
- **AI - LLM - Evidence** — prompts for evidence, sources, and verification.
- **AI - LLM - Verify** — prompts for checking assumptions and results.
- **AI - LLM - Evaluate** — prompts for review and improvement.
- **AI - Code Review** — prompts and checklists for reviewing code.
- **AI - Red Team** — adversarial review prompts.

### Agentic AI management

- **AI - 4E - Agentic** — a structured model for agentic workflows.
- **AI - Agent - Boundaries** — defining what an agent may and may not do.
- **AI - Agent - Delegate** — assigning work to an agent clearly.
- **AI - Agent - Execute** — execution-focused prompts.
- **AI - Agent - Verify** — verification and completion checks.
- **AI - Agent - Escalate** — when an agent should stop and ask.
- **AI - Agent - Autonomy** — autonomy levels and control boundaries.
- **AI - Agent - Manage** — managing AI-agent work as a human owner.
- **AI - Agent - Manager** — manager-oriented agentic AI prompts.
- **AI - Agent - Development Testing** — testing AI-built or AI-assisted application changes.

### Testing and release discipline

- **AI - Test - Contract** — checking promises and expected behavior.
- **AI - Test - Regression** — regression-test thinking.
- **AI - Test - Change** — reviewing what changed.
- **AI - Test - Adversarial** — adversarial test prompts.
- **AI - Test - Impact** — impact and risk review.
- **AI - Test - Agent Evaluation** — evaluating agent behavior.
- **AI - Test - Production** — production-readiness review.
- **AI - Test - Release** — release-readiness checks.

## Why the Library matters

The Library is the quickest way to understand NovaInsert. It shows how small inserts become repeatable workflows:

- repeated replies become clean text inserts;
- shell commands become safer command sets;
- AI prompts become structured reusable methods;
- testing and release work become repeatable checklists;
- admin tasks become stored command groups with placeholders.

You can attach Library Insert Sets to your own Projects, edit them, or create your own sets.

## Notes

- Windows x64 release.
- Built and tested with .NET 8.
- Release build passed.
- Test suite passed: 319 tests.
