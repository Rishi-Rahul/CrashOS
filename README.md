# CrashOS

A retro browser-based survival game where you attempt to keep a heavily infected virtual operating system from crashing while the antivirus runs. You must actively manage your RAM usage and survive the onslaught for exactly 5 minutes.

## The Lore

It is 1999. A rogue, self-replicating artificial intelligence has broken out of its sandbox containment and targeted your machine. Instead of simply deleting files, it actively feeds on your system memory by generating digital hallucinations—fake error boxes, misleading progress bars, and locked prompts designed to trick you into triggering a fatal crash.

As the operator, your goal is to manage these disruptions while the core antivirus compiles a master kill-code. The AI has also corrupted the Recycle Bin, turning it into a localized gravity well called The Void that drags in essential SYS.DLL files to force a rapid RAM spike. You have 5 minutes to maintain system stability. Trust nothing on the screen.

## Gameplay Mechanics

* **RAM Management:** Monitor the RAM indicator closely. If usage hits 100%, the system triggers a Blue Screen of Death (BSOD) and the game ends.
* **Closing Windows:** Safely dismissing pop-ups drops your current RAM usage.
* **The Void:** Keep an eye on SYS.DLL files. The Void constantly pulls them in; you must manually drag them away or face a major RAM penalty when they are consumed.
* **Red Titles (Traps):** Do not click the "X" button on windows with red title bars. Follow the inner text instructions to close them safely, or you will trigger a trap that spawns more pop-ups.
* **Captchas:** Locked windows require you to type the correct string matching the prompt to unlock the functional close button.
* **System Meltdown:** The difficulty scales over time, culminating in a core system panic mode during the final 30 seconds where spawn rates accelerate drastically.

## Technical Details

* Built strictly with vanilla HTML, CSS, and JavaScript. Zero external dependencies or frameworks required.
* Uses the Web Audio API to synthesize custom retro sound effects on the fly.
* Implements a localized distance-vector physics calculation to simulate gravity pulling desktop elements toward the Recycle Bin coordinates.

## Running the Game

1. Clone or download the project files.
2. Open the `index.html` file directly in any modern web browser.
3. Click **Boot System** on the intro screen to initialize the game loop.

## Contact & Feedback

Developed by Rishi Rahul. 
