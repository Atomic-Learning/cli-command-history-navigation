Many CLIs support the ability to scroll through previous commands using the <kbd>Up</kbd> and <kbd>Down</kbd> arrow keys. This allows you to quickly access and reuse commands you've previously entered without having to retype them. When you press the <kbd>Up</kbd> arrow key, the CLI will display the last command you entered. Pressing it multiple times will continue to scroll back through your command history. Conversely, pressing the <kbd>Down</kbd> arrow key will move forward through the command history, allowing you to access more recent commands. This process will not automatically execute commands, giving you the opportunity to review and modify them before running.

![CLI history navigation example](resources/command-history-navigation.gif)

In the example above, the user types an initial `ls`{.bash} command. After executing it, they press the <kbd>Up</kbd> arrow key to recall the command, which allows them to quickly modify it to `ls resources/`{.bash} After executing that command they press <kbd>Up</kbd> twice to scroll back through the command history, before pressing the <kbd>Down</kbd> arrow key to move forward again.

Using command history navigation can dramatically improve your productivity when working with CLIs, particularly when you need to repeat commands, or variations of them.

# Try it Yourself

Use the button at the top of the page to open this content in a Codespace, enter a couple of commands in the terminal and try using the <kbd>Up</kbd> and <kbd>Down</kbd> arrow keys to navigate through your command history in the terminal.
