# AutoClick

**A free Windows auto clicker that clicks the spot you choose at the interval you choose — and can remember a sequence of spots to click one after another.**

English · [한국어](README.ko.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [Español](README.es.md) · [Português (Brasil)](README.pt-BR.md) · [Français](README.fr.md)

> This document is a translation. If anything differs, the [Korean version](README.ko.md) is authoritative.

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011%20(64--bit)-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
![Version](https://img.shields.io/badge/version-2.0.0-blue)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/autoclick?lang=en)

![AutoClick screen](images/autoclick-en.webp)

## Overview

Some jobs mean clicking the same button dozens or hundreds of times. AutoClick does that clicking for you.

Choose the button to press (left, right or wheel), whether to click once or twice, and how often to click, then press the hotkey (**F3** by default) to start. Press the same hotkey again to stop. The hotkey works even while you are looking at another program, so the AutoClick window does not need to be in front.

If you need to click several spots in turn rather than just one, use **Record**. Put the mouse over a spot and press the hotkey (**F4** by default) to add that position to the list, one line at a time. Check **Use Record** and run, and AutoClick clicks through the list in order.

## Features

- **Automatic mouse clicks** — repeatedly presses the left, right or wheel button with a single or double click.
- **Interval range** — click at a fixed interval such as every second, or at a different interval each time between, say, 1 and 3 seconds. Set to 1/100 of a second.
- **Global hotkeys** — start and stop with one key, even while another program is in front. Change the keys to any combination you like.
- **Record** — build a pattern that clicks several positions in order, with its own button, click and interval for each position.
- **Save patterns** — save a record list to a file and open it when you need it. The last list comes back the next time you start.
- **Repeat count** — stops by itself after a set number of clicks. Leave it empty to keep clicking until you stop it.
- **Keep the cursor** — after clicking the chosen spot, moves the mouse cursor back to where it was.
- **Notices** — a Windows notification tells you when clicking starts and stops. The start notice also shows the stop hotkey.
- **Dark mode** — follows the Windows app mode (light or dark).
- **8 languages** — Korean · English · Japanese · Chinese · Russian · Italian · French · Spanish.

## Download / Installation

| Type | Link |
|---|---|
| Installer | [Download](https://down.kilho.net/autoclick?lang=en) |
| Portable (ZIP) | [Download](https://down.kilho.net/autoclick?lang=en&nosetup) |

The installer starts AutoClick as soon as installation finishes. For the portable version, unzip it and run `AutoClick.exe`. Both versions have the same features.

## Usage

### Getting started

1. Start AutoClick.
2. Under **Mouse settings**, choose the button to press (**Mouse**), whether to click once or twice (**Click**) and the interval between clicks (**Delay**). At first it is set to press the left button once every second.
3. Put the mouse cursor over the spot to click.
4. Press **F3**. The status bar at the bottom changes to **Running** and AutoClick starts clicking that spot at the interval you set.
5. When you are done, press **F3** again. The status bar returns to **Waiting**.

### Screen layout

| Element | Purpose |
|---|---|
| **Home** · **Test** · **Donate** | Top menu. **Test** opens a mouse test page where you can try out clicks |
| KILHO.net logo | Opens the AutoClick page |
| **Mouse settings** | **Mouse** (Left · Right · Wheel) · **Click** (Single · Double) · **Delay** (interval between clicks; the two boxes form a range) |
| **Hotkey settings** | **Run/Stop** (F3 by default) · **Add Record** (F4 by default) |
| **Other setting** | **Repeat** · **Position** (Hold · Modify) · **Use notice** (On · Off) |
| **Record** list | The positions to click, in order. Columns: **Position** · **Mouse** · **Click** · **Delay** |
| **Use Record** | When checked, runs click through the list in order |
| **Clear** · **Open** · **Save** | Clear the whole list / open a saved list / save the list to a file |
| Status bar | **Waiting** or **Running** |

### Tips for common tasks

**Keep clicking one spot**
Put the cursor on the spot and press **F3**; AutoClick keeps clicking the spot where the cursor was when you started. With **Position** set to **Hold**, it moves the cursor back to where it was after every click, so you can move the mouse elsewhere in the meantime and the clicked spot stays the same.

**Click wherever the cursor is**
Set **Position** to **Modify** and AutoClick clicks wherever the cursor is at the moment of each click, not the spot where you started. This is handy when you want to move the mouse around during a run to change what gets clicked.

**Vary the interval a little each time**
Enter a range in the two **Delay** boxes. For example, `00:01.00` and `00:03.00` clicks at a different interval between 1 and 3 seconds each time. If both boxes are the same, the interval is always the same. The boxes use the form `minutes:seconds.hundredths`, so just type the digits in order and they fall into place; the longest value is 99 minutes 59.99 seconds.

**Do I have to fill in both boxes?**
When you change the first box and move to another box, the second box follows the first. Once you edit the second box yourself, AutoClick keeps that value, so to set a range enter the first box first and the second box after it. If the second box is smaller than the first, it is raised to match the first.

**Click a set number of times and stop**
Enter a number in **Repeat**. AutoClick stops by itself after that many clicks and, if **Use notice** is on, shows the notice "The run finished after the repeat count was reached." while AutoClick flashes on the taskbar. Leave the box empty (with **none** shown faintly) to keep clicking until you stop it. A double click counts as one.

**Click several spots in turn (Record)**
1. Choose the button, click and delay under **Mouse settings**.
2. Put the cursor on the first spot and press **F4**. A line with that position and the button, click and delay you chose is added to the **Record** list.
3. Press **F4** the same way at each next spot. To use a different button or delay for a line, change **Mouse settings** before pressing **F4**.
4. Check **Use Record** and press **F3**. AutoClick clicks from the first line down, and after the last line goes back to the first. The line being clicked is highlighted in the list.

Each line's **Delay** is how long AutoClick waits after clicking that spot before moving to the next line.

**Reorder lines or delete just one**
Right-click a line in the list for **Move Up** · **Move Down** · **Delete**. To clear the whole list, click **Clear** and then **Yes** in the confirmation. The list cannot be changed during a run, so stop first.

**Keep several patterns and pick one**
Use **Save** to keep the current list as a file, and **Open** to load it when you need it. Keeping one file per job is convenient. Even without saving, the list you had when you closed AutoClick comes back the next time you start it. Record files saved by earlier versions open as they are.

**Reading delays in the record list**
A single interval appears like `00:01.00` and a range like `01:01.00~05:03.00`, the same form as the input boxes. If a long range looks cut off, hover over it or drag the border between column headers to widen the column.

**Change a hotkey**
Click a box under **Hotkey settings** and it changes to "Press a key". Press the key you want, or a combination with **Ctrl** · **Alt** · **Shift** (for example **Ctrl+Shift+F3**), and it is changed and saved right away. Press **Esc** in the box to clear that hotkey (**None**). Pick a key that games or other programs you use don't rely on.

**When a hotkey clashes with another program**
If another program is already using the same key, AutoClick tells you. Change to a different key or close that program; once that program is closed, restarting AutoClick picks up your original key again. If you enter the same key for both hotkeys, AutoClick tells you it is already used by the other function and does not accept it.

**If you don't need notices**
Set **Use notice** to **Off** and AutoClick shows no start, stop or repeat-finished notices. With it on, the start notice reminds you how to stop, such as "Press the same shortcut again to stop (F3)" — useful if you forget the hotkey.

**Pressing the wheel button**
Choosing **Wheel** for **Mouse** presses the wheel (middle) button rather than scrolling. Use it wherever the middle button does something, such as opening a link in a new browser tab.

**Try it out before you start**
Click **Test** at the top to open a mouse test page in your browser that counts clicks and double clicks for the left, wheel and right buttons. You can change the button, click and delay and check that clicks land the way you want first.

**Changing settings during a run**
During a run, the input boxes are locked so nothing changes by accident. Stop with **F3**, make your changes and press **F3** again.

**Starting it again while it is already running**
Only one copy of AutoClick runs at a time. Starting it again does not open a new one; the window that is already open comes to the front. The window title shows the current version.

## Configuration

There is no separate settings window. Hotkeys, **Position** and **Use notice** are remembered as soon as you change them, and the record list is saved when you close AutoClick and comes back the next time. AutoClick follows these on its own:

| Item | Follows |
|---|---|
| Language | Windows regional settings (English if the language is not supported) |
| Colors | Windows app mode (light or dark) — changes apply immediately while AutoClick is open |

## Requirements

- Windows 10 · Windows 11 (64-bit)
- No administrator rights needed.
- No other components need to be installed.
- The internet connection is used only for new-version notices. Every feature works without a connection.

## Updates

AutoClick does **not** update itself. When it starts, it checks for a new version and shows a notice; clicking **[Yes]** opens the download page and closes the program. New versions are released manually after internal verification and announced on the [AutoClick page](https://kilho.net/autoclick). See the [update policy notice](https://en.kilho.net/archives/notice/2940).

## License

AutoClick is **freeware**. Use it free of charge and without restriction anywhere — at work, at home, in government offices or at school — and redistribute it freely.

## Links

- Website: <https://kilho.net/autoclick>
- Forum: <https://kilho.top/forum/qna>
- X (Twitter): <https://www.twitter.com/kilhonet>

© KILHO.NET
