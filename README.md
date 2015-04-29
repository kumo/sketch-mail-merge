# sketch-mail-merge

Sketch plugin to merge CSV data with a template

![Animation](https://raw.githubusercontent.com/kumo/sketch-mail-merge/master/docs/animation.gif)

## Usage

Prepare a template and add numeric tags to your text, for example:

![Template](https://raw.githubusercontent.com/kumo/sketch-mail-merge/master/docs/template.png)

Prepare your data in CSV format, for example:

```
cat,miao
dog,woof
fox,???
```

Select the template and then choose the plugin `Mail Merge` from the menu. Paste in the CSV format and you should see something like:

![Merged Result](https://raw.githubusercontent.com/kumo/sketch-mail-merge/master/docs/merged-result.png)

If you want to layout the template vertically or have more choice over the distance between the results, then should create two templates and select both of them before using the plugin.

### Notes

- tags inside an artboard name will be mail merged too

## Installation

Make sure you have the latest version of Sketch 3 installed.

1. [Download the ZIP file with the Plugin](https://github.com/kumo/sketch-mail-merge/archive/master.zip)
2. Double click on mail-merge.sketchplugin

## Feature requests, bugs & feedback

Ping me on [twitter](http://twitter.com/kumo) or follow for updates.

## Contributors

- Florian Schulz (improved text input and customisable layout)
