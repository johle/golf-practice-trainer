# Golf Practice Trainer

Practice tools for This Is Golf on Windows and Steam. Requires your own supported Steam installation (currently build 25921204). The installer contains trainer code only, with no game assets.

## Install

1. Open [the latest release](https://github.com/johle/golf-practice-trainer/releases/latest).
2. Under Assets, download the **Golf-Practice** ZIP. GitHub's Source code archives are not installers.
3. Extract the ZIP and double-click **Setup.cmd**.
4. Confirm your Steam game folder and choose a separate trainer folder.
5. Click **Play**, or use **Start Practice.cmd** in the trainer folder.

F6 opens the practice tools. **F6 → Trainer updates** opens the update manager.

## Swing Drill

**Shift+F6**, or **F6 → Swing drill**, opens the drill section. Choose the clubs you want, then start the ladder. Each selected club gets five shots; Sand Wedge Ladder uses three per distance.

**Ctrl+Enter** or **Next club / distance** moves on early. On the final stage it finishes the drill. Unused swings are marked as skipped and add no shot attempts, misses or dispersion dots. The score uses actual completed shots.

**Auto advance clubs / distances** is on by default. Turn it off to wait after each completed stage, then move on with the button or shortcut. Selection and the automatic-progression setting save between sessions.

Commands during ball flight queue one change until the current result is recorded. An unstarted optional putt is skipped; a putt already moving finishes first. Aim and manual shot settings are preserved. Ctrl+Enter is inactive while typing in a field.

## Update

Close the practice game, download the latest Golf-Practice ZIP, and choose **Install shared ZIP** in Trainer Manager. Click **Install update** after verification. Settings, calibration and shot history are preserved. **Restore previous version** keeps current personal data while restoring the previous trainer.

Updates use signed packages. The trainer builds a separate practice copy and leaves the Steam game installation unchanged. A live automatic update feed is not configured; use shared ZIP updates.

Release 1.0.2 adds drill progression controls and retains the smoother-contact improvements from 1.0.1. Native shot physics are unchanged.
