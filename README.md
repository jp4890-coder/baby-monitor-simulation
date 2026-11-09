# Little Nest — Baby Monitor Simulation

A classroom project built with HTML, CSS, and JavaScript. Open `index.html` in a browser; no installation is required.

## Try it

1. Turn on the monitor.
2. Raise the room sound slider. It controls synthetic audio and the illustrated baby's fussing.
3. Choose alert sensitivity: high (25), medium (50), or low (80).
4. Keep sound at or above the threshold for two seconds to send an on-page notification.
5. Choose a pause between repeat alerts: 10 seconds for a quick demo, one minute, or five minutes.

Dropping below the threshold resets the two-second check. After each pause, another two-second check is required. Turning off stops audio and resets the timers.

## Model

Variables track power, sound level, alert threshold, sound confirmation time, last alert time, waiting period, and notification count. States are off, monitoring, detecting, and waiting. Event listeners connect the buttons, slider, and settings to the logic; a timer updates the checks and countdowns.

Sound values are illustrative, not decibels. The project uses generated sound, not a microphone or recordings. It does not identify crying or assess a baby's well-being. Notifications appear only within the page.

## Publishing

For GitHub Pages, serve the `main` branch from `/ (root)`, with `index.html` at the repository root. Only `index.html` and this README are intended for publication; the transcript is submitted separately.
