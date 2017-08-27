# VSC Projects+ Todo+

<p align="center">
	<img src="https://raw.githubusercontent.com/fabiospampinato/vscode-projects-plus-todo-plus/master/resources/logo-128x128.png" alt="Logo">
</p>

Bird's-eye view over your projects, view all your todo files aggregated into one.

## Install

This extension uses [Projects+](https://marketplace.visualstudio.com/items?itemName=fabiospampinato.vscode-projects-plus) to get a list of your projects and [Todo+](https://marketplace.visualstudio.com/items?itemName=fabiospampinato.vscode-todo-plus) to provide support for the `Todo` language, having them installed is a requirement.

Run the following in the command palette:

```shell
ext install vscode-projects-plus
ext install vscode-todo-plus
ext install vscode-projects-plus-todo-plus
```

## Usage

It adds 1 command to the command palette:

```js
Projects: Todo // Open a file containg all todos across your projects
```

## Settings

```js
{
  "projectsTodo.indentation": "  ", // String used for indentation
  "projectsTodo.hideEmpty": true, // Hide groups and projects with no todos
  "projectsTodo.hideDone": true, // Hide any done todo
  "projectsTodo.hideCancelled": true, // Hide any cancelled todo
  "projectsTodo.hideComments": false, // Hide all the comments
  "projectsTodo.filterRegex": false // List only projects having a name matching this regex
}
```

## Demo

![Demo](resources/demo.gif)

## License

MIT © Fabio Spampinato
