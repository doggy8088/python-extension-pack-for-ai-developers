# Python Extension Pack for AI Developers

This extension pack packages some of the most popular (and some of my favorite) Python extensions. If you like it, please leave your `Rating & Review` and share with your friends. If you know any extension that is good for Angular development, just let me know by [creating an issue](https://github.com/doggy8088/python-extension-pack-for-ai-developers/issues).

## Extensions Included

* [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)

    Python language support with extension access points for IntelliSense ([Pylance](https://marketplace.visualstudio.com/items?itemName=ms-python.vscode-pylance)), Debugging ([Python Debugger](https://marketplace.visualstudio.com/items?itemName=ms-python.debugpy)), linting, formatting, refactoring, unit tests, and more.

* [autopep8](https://marketplace.visualstudio.com/items?itemName=ms-python.autopep8)

    Formatting support for Python files using the `autopep8` formatter.

    ```json
    "[python]": {
        "editor.formatOnSave": true,
        "editor.defaultFormatter": "ms-python.autopep8",
        "editor.codeActionsOnSave": {
            "source.organizeImports.ruff": "explicit"
        }
    }
    ```

* [Pylint](https://marketplace.visualstudio.com/items?itemName=ms-python.pylint)

    Linting support for Python files using `Pylint`.

* [Python Environment Manager](https://marketplace.visualstudio.com/items?itemName=donjayamanne.python-environment-manager)

    View and manage Python environments & packages.

* [Python Indent](https://marketplace.visualstudio.com/items?itemName=KevinRose.vsc-python-indent)

    Correct Python indentation

* [autoDocstring - Python Docstring Generator](https://marketplace.visualstudio.com/items?itemName=njpwerner.autodocstring)

    Generates python docstrings automatically

* [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)

    Jupyter notebook support, interactive programming and computing that supports Intellisense, debugging and more.

## Some other extensions you may need (Optional)

* [Ruff](https://marketplace.visualstudio.com/items?itemName=charliermarsh.ruff)

    A Visual Studio Code extension with support for the Ruff linter.

## The VS Code User Settings for Newbies

```json
{
    "workbench.sideBar.location": "right",

    "files.autoGuessEncoding": true,
    "files.trimTrailingWhitespace": true,
    "files.defaultLanguage": "${activeEditorLanguage}",

    "editor.codeLens": true,
    "editor.minimap.enabled": true,
    "editor.minimap.renderCharacters": false,
    "editor.multiCursorModifier": "ctrlCmd",
    "editor.wordWrap": "on",
    "editor.tabCompletion": "on",
    "editor.cursorSmoothCaretAnimation": "on",

    "[python]": {
        "editor.formatOnSave": true,
        "editor.defaultFormatter": "ms-python.autopep8",
        "editor.codeActionsOnSave": {
            "source.fixAll": "explicit",
            "source.organizeImports": "explicit"
        }
    },

    "terminal.integrated.showExitAlert": false,
    "terminal.integrated.allowChords": false,
    "terminal.integrated.defaultProfile.windows": "Command Prompt",

    "notebook.formatOnSave.enabled": false,
    "notebook.codeActionsOnSave": {
        "notebook.source.fixAll": "explicit",
        "notebook.source.organizeImports": "explicit"
    },

    "git.autofetch": true,
    "git.enableSmartCommit": true
}
```

**Enjoy!**
