# projects

a vscode project manager extension

# Installation

Press `F1` in vscode, type `ext install` and then look for `projects`.

# Usage

## user settings

**projects.projectsLocation***

The absolute path of the folder where all your projects are stored，All primary directories below this folder will be a separate project。

Available variable `$home` for user directory

```
"projects.projectsLocation": "$home/web"
```

Or configure multiple project directories, each of which will be treated as a separate project。

```
"projects.projectsLocation": ["$home/web", "$home/client"]
```

**projects.showProjectNameInStatusBar**

Whether to display the current project name in the lower left corner of the status bar, click on the project name to quickly open the project list 。`default: true`

```
"projects.showProjectNameInStatusBar": false
```

![projects.showProjectNameInStatusBar](https://github.com/kurt67/vscode-projects/raw/master/images/screen/statusbar.png)

**projects.openInNewWindow**

Whether to open the project in a new window。`default: true`

```
"projects.openInNewWindow": false
```

**projects.ignoredFolders**

Ignore such folders under all project folders `default:["node_modules"]`

```
"projects.ignoredFolders": ["node_modules"]
```

## commands

- projects.list
- projects.reload
- projects.cresate

![commands](https://github.com/kurt67/vscode-projects/raw/master/images/screen/commands.png)

![projects.list](https://github.com/kurt67/vscode-projects/raw/master/images/screen/list.png)
