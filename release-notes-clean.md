
# NiuxAgent v0.6.0 — Invite-Only Trial

The first trial build of NiuxAgent, a personal AI agent that runs on your own Windows PC. This release is **invite-only**: you need a personal invite code to activate it, and everything is **free during the trial**, including the cloud relay.

## Highlights

- **Runs on your own computer** — the agent lives on your PC, not on someone else's cloud. Send tasks from your phone; your PC does the work.
- **Your data stays yours** — conversations, files and the agent's memory are stored on your own machine. We do not sell your data, move it to our servers, or use it to train models.
- **It remembers** — memory persists across sessions: your preferences, ongoing tasks and where you left off.
- **Bring your own model** — connect the AI model you choose with your own API key. No markup on model usage; usage is visible in the app and you can set daily limits.
- **Phone remote + cloud relay** — pair your phone as the remote control. The optional cloud relay (free during the trial) keeps your agent reachable even when your PC is asleep or off.
- **You stay in control** — everyday actions are one tap to approve; risky actions require a confirmation code; keys are entered through a secure local field, never into chat.
- **Skills built in** — ready-made skills included, with the built-in Niux Skill Platform opening in stages during the trial.

## System requirements

- Windows 10 or later (64-bit), with an internet connection. The PC must be on for the agent to work locally; the cloud relay covers it while it sleeps.
- A phone: Android (remote app) or iPhone (web app added to the home screen).
- Your own model provider API key (several providers offer free tiers to get started).
- macOS is not supported in this release.

## Install

1. Download **NiuxAgent-Setup-0.6.0.exe** below and run it.
2. **Windows may show a blue screen: "Windows protected your PC" (SmartScreen).** This is expected: the trial build is not yet code-signed, so Windows warns about any program it does not recognise. It does not mean the file is harmful.
   - Click **More info**.
   - Then click **Run anyway**.
   Code signing will be added before the general release.
3. Follow the installer to the end — no command line, no extra setup.
4. NiuxAgent starts automatically and opens in your browser.

## Activate

5. When asked, enter your **personal invite code** (from your invitation message) to activate the trial.
6. Add your **model API key** when prompted — choose your provider and paste your own key. The key is stored only on your PC.
7. Pair your phone using the on-screen steps, and you are ready.

## Android remote app

The Android remote-control app is attached to this release as **NiuxAgent-Android-0.2.0.apk** (Android 8.0+). Download it on your phone and install it — Android will ask you to allow installs from your browser because the trial is not on an app store yet; you can revoke that permission afterwards. The app is only the remote control: the agent itself runs on your Windows PC. iPhone users: open the web app in Safari and use "Add to Home Screen" — there is no App Store build during the trial.

## Verify your download (SHA-256)

- File: `NiuxAgent-Setup-0.6.0.exe` (62,149,042 bytes)
- SHA-256: `43a5b1678c24a51e5d8c63152e088ccca32c7a3d69b4a8e2e338a4fcb9f1c3c7`
- File: `NiuxAgent-Android-0.2.0.apk` (647,977 bytes)
- SHA-256: `bbdc9a56419cb045a3da9d4c148e699625b2080993fd07df44415ec6108f95bf`

## Known limitations

- **Windows only** in this release; the agent itself does not run on macOS or on the phone (the phone is a remote control).
- **Invite-only trial** — the app will not activate without a valid invite code, and codes are personal to the invitee.
- **Not yet code-signed** — expect the SmartScreen prompt described above.
- This is an early trial build; some features (including parts of the skill platform) open in stages.

## Feedback

This trial exists to learn from real use. Tell us what worked, what did not, and what you wish it could do: **support@niuxagent.com** — please note which step you reached if you hit a problem. Invite code not accepted? Check for extra spaces when pasting, and make sure you are using the code from your own invitation.

NiuxAgent is operated by VIICAD CO., LTD.
