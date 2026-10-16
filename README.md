# Golf Practice Trainer

Practice tools for This Is Golf on Windows and Steam. Requires your own supported Steam installation (currently build 25921204). The installer contains trainer code only, with no game assets.

## Install

1. Open [the latest release](https://github.com/johle/golf-practice-trainer/releases/latest).
2. Under Assets, download the **Golf-Practice** ZIP. GitHub's Source code archives are not installers.
3. Extract the ZIP and double-click **Setup.cmd**.
4. Confirm your Steam game folder and choose a separate trainer folder.
5. Click **Play**, or use **Start Practice.cmd** in the trainer folder.

## Menus and swing guide

**F6 — Practice:** Practice, Shot Plan, Training, Stats and Tools.

**F7 — Display:** Overlays, Swing Guide and Appearance. All visibility controls, overhead inspection, overlay sizing, line appearance and Coach placement live here. Esc closes menus or finishes Coach placement. Switching menus preserves the original pause/mouse state; selected tabs save between sessions.

**F7 → Swing Guide** separately toggles the gold intended club-head path and faint blue actual trace. Both start enabled and work with Coach hidden, including for putter. Gold shows direction through backswing, contact and follow-through; planned curve changes its direction. Use the existing Coach speed/power meter for pace rather than treating the guide as a required backswing length. Blue retains follow-through, clears on a new attempt/reset or three idle seconds, and ignores paused time.

Old display keys F2/F3/F4/F5/F9/F11/F12 are retired. **F8** exports putting reads; **F10** toggles calibration. Display defaults preserve plans, drills, calibration and history.

## Swing Drill

**Shift+F6**, or **F6 → Training**, opens the drill section. Choose clubs and start the ladder. Each selected club gets five shots; Sand Wedge Ladder uses three per distance.

**Ctrl+Enter** or **Next club / distance** moves on early. On the final stage it finishes the drill. Unused swings are marked as skipped and add no attempts, misses or dispersion dots. The score uses actual completed shots.

**Auto advance clubs / distances** is on by default. Turn it off to wait after each completed stage. Selection and progression save between sessions.

Commands during ball flight queue one change until the result is recorded. An unstarted optional putt is skipped; a putt already moving finishes first. Aim and manual shot settings are preserved. Ctrl+Enter is inactive while typing in a field.

## Update

Close practice, download the latest Golf-Practice ZIP, and choose **Install shared ZIP** in Trainer Manager, also available through **F6 → Tools → Trainer updates**. Click **Install update** after verification. Settings, calibration and history are preserved. **Restore previous version** keeps current personal data while restoring the previous trainer.

Updates use signed packages. The trainer builds a separate practice copy and leaves the Steam installation unchanged. A live automatic update feed is not configured; use shared ZIP updates.

Release 1.0.3 adds the club swing guide and organized menus, retaining drill progression and smoother-contact improvements. Native shot physics are unchanged.
