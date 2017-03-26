# Dvorak International - Windows 10

Everytime I install a fresh copy of Windows, I run into the same issue:
Getting the dvorak international layout to work.

So, here's what I found that seems to work on my last attempt.

## Requirements

First, make sure you have:

- .Net Framework 2.x. It can be found on the microsoft downloads page.
- Microsoft Keyboard Layout Creator 1.4 (if a newer version is ever released,
it might work as well).

## Instalation

Open MSKLC and load the `dvx.klc` keyboard layout. The layout can be customized at will
at this point.

- Build: Project -> `Build DLL and Setup Package`, click `Yes` when asked to open
the created folder.
- Install: On that folder, execute `setup` and click yes on the UAC message.
- Restart: Don't think "I don't want to restart my computer," do it.

> If you can't find the generated folder, it might be somewhere around
 `Documents/dvx`.

Now you are good to go; `Go to Settings`, `Time & Language`, `Region & Language`,
`English` (or whatever language you have) -> `Options`, `Add a keyboard` ->
`United States-Dvorak International` (Or the closest you see).

## What the keys?

Some of the default keys (If you are too lazy for checking them on MSKLC), are:

(being Alt the right Alt)

- Alt + a -> á
- Alt + e -> é
- Alt + i -> í
- Alt + o -> ó
- Alt + u -> ú
- Alt + n -> ñ
- Alt + y -> ü
- Alt + \ -> ¬

## Resources

FTR, keep in mind that these links could change or just stop working. In that
event, please google around and/or let me know.

- The starting point for building this guide: http://devblog.alexsapps.com/2014/06/international-dvorak-on-windows-81.html
- .Net framework download: https://www.microsoft.com/en-us/download/details.aspx?id=1639
- Microsoft Keyboard Layout Creator download: https://www.microsoft.com/en-us/download/details.aspx?id=22339
