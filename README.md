<p align="center">
<img src="https://raw.githubusercontent.com/DigitxlLink-LLC/sysvia-release/main/media/hero.webp" alt="Sysvia. One desktop across every machine. Sync files and use one keyboard, mouse, and clipboard across your computers, privately, over your local network." width="100%">
</p>

<p align="center">
<a href="https://github.com/DigitxlLink-LLC/sysvia-beta-release/releases/latest"><img alt="Latest beta" src="https://img.shields.io/github/v/release/DigitxlLink-LLC/sysvia-beta-release?display_name=tag&style=flat-square&color=8f9cff&label=beta"></a>
<img alt="Pre-release software" src="https://img.shields.io/badge/status-pre--release-8f9cff?style=flat-square">
<img alt="Platforms: Windows and macOS" src="https://img.shields.io/badge/platforms-Windows%20%C2%B7%20macOS-1f2937?style=flat-square">
<img alt="For licensed members" src="https://img.shields.io/badge/for-licensed%20members-1f2937?style=flat-square">
</p>

<p align="center">
<a href="#join-the-beta">Join the beta</a>
&nbsp;·&nbsp;
<a href="#install">Install</a>
&nbsp;·&nbsp;
<a href="#what-to-expect">What to expect</a>
&nbsp;·&nbsp;
<a href="#whats-in-testing">What's in testing</a>
&nbsp;·&nbsp;
<a href="#report-a-problem">Report a problem</a>
&nbsp;·&nbsp;
<a href="#leave-the-beta">Leave the beta</a>
&nbsp;·&nbsp;
<a href="#reference">Reference</a>
</p>

# Sysvia Beta

This is where upcoming versions of [Sysvia](https://getsysvia.com) land first. Beta testers get new builds before the public release, tell us what breaks, and help decide what ships. If you want the stable app, the [public releases](https://github.com/DigitxlLink-LLC/sysvia-release/releases/latest) are the place to go.

> [!WARNING]
> Beta builds are unfinished. They can be unstable, change without notice, or lose data. Sysvia syncs and overwrites files, so keep a backup of anything you cannot afford to lose, and think twice before putting a beta on the computer you depend on for important work.

## Join the beta

The beta is open to members with an active Sysvia license. It is opt-in and it is one setting:

1. Sign in to Sysvia, open **Settings**, then **Updates**, and find **Beta program**. You can also use **Account**, then **Beta program**, on the website at [getsysvia.com](https://getsysvia.com/dashboard).
2. Read the [Beta Program Terms](https://getsysvia.com/beta-terms) and tick the box.
3. Choose **Join the beta**.

The app now looks for new builds in this repository instead of the public one, so the next beta arrives the way any update does. You do not need to download anything by hand. Your computers stay paired and your folders stay as they are.

**Your badge.** Beta testers get a **Beta tester** badge on their profile, in the app and on the website. It follows your account, so it shows on every computer you sign in on.

**Perks.** Testers also get priority access to discounts and offers on future releases. Perks are a thank-you and can change, so see the [terms](https://getsysvia.com/beta-terms) for what is promised.

## Install

You only need the files below for a computer that does not have Sysvia yet, or if you would rather install a beta by hand. Otherwise, join the beta in the app and let it update itself.

Download the installer for your computer from the [latest beta](https://github.com/DigitxlLink-LLC/sysvia-beta-release/releases/latest). Installer names carry the beta number, for example `Sysvia-2.3.0-beta.1`. A Linux installer is not available yet.

| Computer | File |
| --- | --- |
| Windows (x64) | `Sysvia-<version>-win-x64.exe` |
| Mac with Apple silicon (M1 and later) | `Sysvia-<version>-mac-arm64.dmg` |
| Mac with an Intel processor | `Sysvia-<version>-mac-x64.dmg` |

You still sign in with your Sysvia account, and the app only keeps updating from this repository while you are a beta tester. Installing a beta by hand without joining means the next update comes from the public releases.

**Windows.** Run the installer. It installs per machine, asks for a directory (default `C:\Program Files\Sysvia`), and adds Start menu and desktop shortcuts. It also adds Windows Firewall allow rules for Sysvia's two background services. Uninstalling removes the rules and leaves your folders and settings alone.

**macOS.** Open the `.dmg` and drag Sysvia into Applications. The app is signed and notarized by Apple. On first launch macOS asks for Local Network access, and keyboard and mouse sharing needs the permissions listed under [macOS permissions](#macos-permissions). Not sure which Mac you have? Apple menu, then About This Mac: "Chip" says Apple M1 or similar, "Processor" says Intel.

## What to expect

- **Updates.** The app checks this repository a few seconds after launch, every ten minutes while it is running, and when you come back to its window or wake the computer. A new beta shows up as an update like any other.
- **Versions.** Betas are numbered ahead of the release they lead up to, such as `2.3.0-beta.1`, then `2.3.0-beta.2`. When the public `2.3.0` ships, it counts as newer than every beta of it and you are moved onto it.
- **Public releases too.** Every public release is also published here, so testers are never left behind on an old beta.
- **Release notes.** Each beta lists what changed and what we most want tested. Read it before you update.
- **Computers on different versions.** Keep every computer on the same beta where you can. A beta can change how computers talk to each other, so a computer on an older version may not sync with one on a newer beta.
- **No promises.** A beta feature may change, be pulled, or never ship.

## What's in testing

This changes with every beta, and the release notes are the source of truth. The current round is about reaching your computers when they are not on the same network, and controlling them from afar:

| Area | What it is |
| --- | --- |
| **Connect from anywhere** | Find and reach your other computers across different networks, with no router changes. |
| **Relay** | Computers that cannot reach each other directly can go through a relay you run yourself. It cannot read what it carries. |
| **Remote terminal** | Use the command line of another of your computers from this one. |
| **Remote screen** | See and use another computer's screen from this one, including several screens at once. |
| **Sync and desk fixes** | Renames and moves that arrive at once, **Override the others** from a send-only folder, computers that were saved twice merging into one, and game mode fixes. |

## Report a problem

You are here to find bugs, so tell us when you hit one.

- **In the app.** Open **Advanced**, then **Maintenance**, and export a support bundle. It collects logs and a redacted configuration, and it is the most useful thing you can send. Email it to [support@getsysvia.com](mailto:support@getsysvia.com).
- **On the website.** Use the [feedback page](https://getsysvia.com/feedback) for ideas and anything that is not a bug.
- **What to include.** The beta number (**Settings**, then **Updates**), your operating system, what you did, what you expected, and what happened instead. If two computers were involved, say which was which.

Bug reports, feedback and suggestions may be used to improve Sysvia, as the [terms](https://getsysvia.com/beta-terms) say. Please do not post screenshots or write-ups of features we have not announced yet.

## Leave the beta

One click. Open **Settings**, then **Updates**, then **Beta program**, and choose **Leave the beta**. The same button is under **Account** on the website.

When you leave:

- Sysvia stops looking here and goes back to the public releases.
- Your Beta tester badge is removed.
- You stay on the version you have. Nothing is downgraded, and you move to the next public release as soon as it is newer than what you are running. If you want to go back to a public version sooner, install it from the [public releases](https://github.com/DigitxlLink-LLC/sysvia-release/releases/latest). Your computers stay paired and your folders stay as they are.
- You can rejoin whenever you like. We keep the date you first joined.

## Current limits

- No Linux installer yet.
- Beta builds can break sync between a beta computer and a computer on an older version.
- Betas carry no support commitment and no warranty.
- Everything in [Current limits](https://github.com/DigitxlLink-LLC/sysvia-release#current-limits) on the public page applies here too.

## Reference

The apps, ports, files on disk and macOS permissions are the same as in the public release. The parts you will need most:

<details>
<summary id="macos-permissions">macOS permissions</summary>

<br>

- **Local Network** must be allowed so Sysvia can find your other computers.
- **Accessibility** must be on for Sysvia and for `sysviad`. Restart after granting it.
- **Screen Recording** must be on for `sysviad` on any Mac whose screen you view from another computer.
- **Notifications** should be allowed if you want desktop alerts.

</details>

<details>
<summary>Network ports</summary>

<br>

| Port | Used for | Notes |
| --- | --- | --- |
| 22000 | Folder data | |
| 21037 UDP | Folder discovery on the LAN | |
| 8384 | Folder sync local API | `127.0.0.1` only. Do not publish it. |
| 24810 | Desk session | |
| 24811 | Window control | `127.0.0.1` only. |
| 24812 UDP | Desk discovery | |
| 24813 | Screen frames for the viewer | `127.0.0.1` only. |
| 5353 UDP | mDNS, `_sysvia._tcp` | |

</details>

<details>
<summary>Files on disk</summary>

<br>

Desk config, peers, role and layout live in `config.json`:

| OS | Location |
| --- | --- |
| Windows | `%APPDATA%\sysvia\config.json` |
| macOS | `~/Library/Application Support/sysvia/config.json` |
| Linux | `~/.config/sysvia/config.json` |

Stop Sysvia before editing it. The daemon rewrites the file.

Folder sync keeps its own keys, settings and index in a `sync-engine` folder in the same place. Deleting it creates a new Device ID, and other computers have to be paired again.

Files that sync removes are kept in a `.sysvia/trash` folder inside each synced folder. That folder is never synced.

</details>

<details>
<summary>Open-source components</summary>

<br>

The folder sync engine and the desk daemon are MIT. Interface icons are [Lucide](https://lucide.dev), ISC.

</details>

<details>
<summary>For the team: publishing a beta</summary>

<br>

Betas are built on the maintainers' machines and uploaded here with the release script, which reads this repository from `release-feed.json`:

```sh
npm run release -- --channel beta --version 2.3.0-beta.1 --notes "What changed and what to test."
```

- Give a beta a prerelease version (`x.y.z-beta.n`). Public releases go to [sysvia-release](https://github.com/DigitxlLink-LLC/sysvia-release) as usual. Then upload the same build here too, so testers always have something at least as new as the public release:

  ```sh
  npm run release -- --skip-build --target beta
  ```
- Releases here are normal releases, not GitHub pre-releases, so the updater finds them as the latest release.
- Testers are updated from this repository only while their account is in the beta program. The repository is public, so the installers are not secret. Joining is what makes the app look here.

</details>
