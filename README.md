# MARS Production Tracker

`MARS_Production_Tracker.html` is a single HTML page that tracks how long you spend on each process and works out your production per hour against the target. Open it in Chrome or Edge. It needs no install and no internet, apart from the fonts and the Drive links.

Your data is saved in the browser on your own computer. Nobody else can see it, and clearing your browser data deletes it.

## Daily use

1. Type your name in the box at the top right (once; it is remembered).
2. When you start work, click the process you are on. A timer starts.
3. When you switch, click the new process. The previous one is closed automatically.
4. Click **Break** when you go on break and click your process again when you come back.
5. Click **End of Shift** when you finish.
6. Type your counts into **Before 11 AM** and **After 11 AM** in the summary table (up to 4 digits). Prod/hr, % of target and Balance update by themselves.

**Previous day** fills in with your total from the last day you logged. Type a number to override it; clear the box to go back to the automatic value.

## Keyboard shortcuts

| Key | Action |
|---|---|
| 1 to 9 | Switch to a process (the number is shown on each button) |
| B | Break |
| E | End of Shift |
| Ctrl + Z | Undo the last change |

Shortcuts are ignored while you are typing in a box.

## Fixing mistakes

- Pressed the wrong button? Press **Ctrl + Z** or the **Undo** button.
- To fix an older entry, click it in the **Activity log**. You can change the process, the start and end times, or delete it.
- If you forget End of Shift, the page warns you once an entry has been running for more than 10 hours. You can end it at the last time you used the page.

## Other features

- **Quick copy** (right side): click a phrase such as "- Name Match Confusion" to copy it.
- **Quick files** (left column, under the process buttons): opens 1000 Common Names, MS Unrestricted List, Fortune 500 List and USA Map in Google Drive. You need access to those files.
- **Hour** cells: click to copy the time. Pick h:mm:ss or decimal (1.42) with the switch above the table.
- **Copy summary** copies the day's table so you can paste it into Excel. **Download CSV** saves the day's activity log.
- **Date** picker above the log shows any earlier day.
- **Hide unused** hides processes you haven't touched that day.
- **Dark / Light** theme switch at the top.

## Good to know

- Opening the page in two tabs is fine; they stay in sync.
- **Clear log** removes the selected day's entries. **Reset everything** wipes all days. Both can be undone with Ctrl + Z as long as the page stays open.
- To change the quick-copy phrases, edit the `QUICK_COPY` list in the file with any text editor.
