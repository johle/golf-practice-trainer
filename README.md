# Golf Practice Trainer

Practice tools for This Is Golf on Windows and Steam. Requires your own supported Steam installation (currently build 25921204). The installer contains trainer code only, with no game assets.

## Install

1. Open [the latest release](https://github.com/johle/golf-practice-trainer/releases/latest).
2. Under Assets, download the **Golf-Practice** ZIP. GitHub's Source code archives are not installers.
3. Extract the ZIP and double-click **Setup.cmd**.
4. Confirm your Steam game folder and choose a separate trainer folder.
5. Click **Play**, or use **Start Practice.cmd** in the trainer folder.

F6 opens the practice tools. **F6 → Trainer updates** opens the update manager.

## Update

Close the practice game, download the latest Golf-Practice ZIP, and choose **Install shared ZIP** in Trainer Manager. Click **Install update** after verification. Settings, calibration and shot history are preserved. **Restore previous version** keeps current personal data while restoring the previous trainer.

Updates use signed packages. The trainer builds a separate practice copy and leaves the Steam game installation unchanged. A live automatic update feed is not configured; use shared ZIP updates.

## Release 1.0.1

Reduces work at contact by reusing unchanged predictions, saving swing history in the background, cancelling dispersion work once a shot starts, and avoiding hidden chart refreshes at contact. Changes to shot settings still recalculate predictions. Native physics and drill progression are unchanged.
