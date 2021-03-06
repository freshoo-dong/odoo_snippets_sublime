Several snippets to be used with Sublime 3 in Odoo v8,v9,v10,v11,v12 developments

## Installation

This plugin is not available in common Sublime repository, you will need to add the repository which contains the plugin first.

### The repository

1. Goto **Preferences**->**Package Control**
1. Click in **Add Repository**
1. Adds the following URL: [https://github.com/freshoo-dong/odoo_snippets_sublime](https://github.com/freshoo-dong/odoo_snippets_sublime) and press **enter**.

### The pluggin

1. Goto **Preferences**->**Package Control**
1. Click in **Install package**
1. Search **sublime-odoo-snippets** plugin in list and **click** it.


> Plugin setup proccess requires **[Sublime Text](http://www.sublimetext.com/)** with **[Package Control](https://packagecontrol.io/installation)** installed.

## Commands

Project has a Python file with some useful utilities to work in Odoo code files, these are the following:

### dashes

When a Python code file is too long, reorder the code in blocks divided by horizontal rules makes more easy read them.

This command replaces selection by a dashed line with selected text in center. The result is like the following:

```python
    # ------------------------------- PRUEBA ----------------------------------
```

- Line starts at the selection beginning and ends in the column 79.
- Text will have two spaces, one before and another after.
- If there is not selected text when command is invoked, line will be printed without any text.

### finddashes

Once the Python code file has been divided by horizoantal rules, will be very useful to jump to the next line of dashes. This command does just that.
