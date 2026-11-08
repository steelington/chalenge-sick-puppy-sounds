# Chalenge's Sick Puppy Sound Pack for Aces High III

![Cripes A' Mighty 3rd - for Chalenge](for_Chalenge.jpg)

## In memory of Chalenge

Chalenge made the Sick Puppy Sound Pack for Aces High III and gave it to the community in 2019. He died in
November 2022. The sounds here are his: every plane he covered plays his engines, and the planes added since are
built on his designs.

This copy has been repaired and filled in so it can keep being flown. It is shared with the permission of Fuji
(The Fugitive) and the blessing of Chalenge's squadmates, who asked only one thing: that it is always known as
**Chalenge's sound pack**.

## Download

Get **SickPuppySounds-fixed-v19.zip** from the [Releases](../../releases) page.

## Install

1. Close Aces High III.
2. In your Aces High III folder (the one with the game's .exe), make a folder `CustomSounds`, and inside it a folder
   `Desktop`:

   ```
   <your Aces High III folder>\CustomSounds\Desktop\
   ```

3. If that `Desktop` folder already has another sound pack in it, move those files somewhere safe first.
4. Copy the four `.bank` files from the zip into the `Desktop` folder: `CustomDefault.bank`,
   `CustomDefault.strings.bank`, `CustomEffects.bank` and `CustomMusic.bank`. All four go in together.
5. Start the game. There's no setting to switch on.

**Back to stock sounds:** delete or rename the `CustomSounds\Desktop` folder and restart the game.

## What's new in v19

- **The "EVENT ... is not stopping after timeout" alert is fixed.** Reported by **JimmyD3** (a flood of them sitting
  in a T-34/85 with the engine off; his film and screenshot showed exactly which sounds wouldn't stop) and by
  **Fuji (The Fugitive)** (the P-47M's stall buffet). The game ends a sound by switching it off and gives it 20
  seconds. In some cases that "off" never reached the sound; the game's own sounds start switched off, so they end
  anyway, but the pack's started switched on, so they played on. Now every pack sound starts switched off, like the
  game's own.
- **The T-34/76 and T-34/85 have the pack's sounds again** (v18 had put them on stock while this was tracked down).
- Whenever the game sets the switch itself, sounds play exactly as before (checked on the tanks, sample for sample).
- **Updating from v17 or v18:** copy `CustomEffects.bank` and `CustomDefault.strings.bank` (or all four files).
- **To check it** (if you saw the alert before): sit in a T-34/85 with the engine off for a couple of minutes, near
  another tank if you can, then start up, drive, stop and switch views; and fly a P-47M slowly into the stall a few
  times. The text buffer should stay clear. If you still see one, say which vehicle and what it was doing, and send a
  film if you can.

## What's been fixed

- Levels evened out between planes, so the one "your engine" slider works for all of them; cruise matches stock.
- 64 engine loops that clicked or pumped at the loop point repaired.
- Planes that come into view already flying no longer play a start-up first.
- Start-ups and shut-downs capped at each engine's full-throttle level; WEP clearly audible.
- Every sound stops when the game switches it off, including when the game's "off" goes missing (v19): no more
  "... not stopping after timeout" messages in the text buffer.
- The M4A3(76) tracks follow the tank's speed.
- About 50 planes the original pack didn't cover now have engines; the WWI planes stay on stock sounds.

## Credits

- **Chalenge**: the Sick Puppy Sound Pack, all of its original sounds, events and design.
- **Mitsu**: engine loops from Mitsu's Sounds Collection (Aces High II) for the planes Chalenge's pack lacks.
- **The recordists of the IL-2 1946 "412 Soundpack"**: the Tu-2S, Me 262, Ar 234 and C.205 engines. The pack
  doesn't name them and we couldn't find out who they were. We salute and thank them, and we'll gladly add their
  names if they make themselves known.
- Fixes and additions: Steely.

Aces High III is by HiTech Creations. Full credits are in `CREDITS.txt` inside the zip.
