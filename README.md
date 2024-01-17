# DayTasks

DayTasks is a browser extension that helps you manage your time and tasks. It shows how much time is left in your day and provides a simple todo list for you to keep track of your tasks.

## Features

- Countdown timer showing how much time is left in your day
- Todo list for managing your tasks
- Tasks are saved in your browser's local storage so they persist across sessions
- Tasks can be marked as done or undone

## Installation

1. Clone this repository: `git clone https://github.com/yourusername/DayTasks.git`
2. Navigate to `about:debugging` in your browser
3. Click on 'This Firefox' in the sidebar
4. Click on 'Load Temporary Add-on...'
5. Select the `manifest.json` file in the `DayTasks` folder
6. The extension should now be installed and you can use it in your browser

OR

1. Get the extension from the [Firefox Add-ons](https://addons.mozilla.org/en-US/firefox/addon/daytasks/)
2. The extension should now be installed and you can use it in your browser


## Usage

Click on the DayTasks icon in your browser toolbar to open the popup. Here you can see the countdown timer and your todo list. To add a task, type it into the input field and press Enter. To mark a task as done or undone, click on the checkbox next to it. To delete a task, click on the 'x' button next to it.

## Permissions

This extension requires the following permissions:

- `storage`: Needed to save your tasks in local storage
- `https://timely-note.vercel.app/*`: Needed to fetch data from this domain

## Contributing

Contributions are welcome! Please open an issue if you have any suggestions or find any bugs.

## License

MIT