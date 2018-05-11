# sketch-mail-merge

Sketch plugin to merge CSV data with a template

![Animation](https://raw.githubusercontent.com/kumo/sketch-mail-merge/master/docs/animation.gif)

## Usage

Prepare a template and add numeric tags to your text. The first tag should start wih the number 1, for example "Hello {1}, do you '{2}'?":

![Template](https://raw.githubusercontent.com/kumo/sketch-mail-merge/master/docs/template.png)

Prepare your data in CSV format, for example:

```
cat,miao
dog,woof
fox,???
```

Select the template and then choose the plugin `Mail Merge` from the menu. Paste in the CSV format and you should see something like:

![Merged Result](https://raw.githubusercontent.com/kumo/sketch-mail-merge/master/docs/merged-result.png)

### Advanced usage

If you want to layout the template vertically or have more choice over the distance between the results, then you should create two templates and select both of them before using the plugin. The distance between the two templates will be applied to the new tempates.

### Notes

- if a layer's name contains tags, these too will be mail merged

## Installation

Make sure you have the latest version of Sketch 3 installed.

1. [Download the ZIP file with the Plugin](https://github.com/kumo/sketch-mail-merge/archive/master.zip)
2. Double click on mail-merge.sketchplugin

## Feature requests, bugs & feedback

Ping me on [twitter](http://twitter.com/kumo) or follow for updates.

## Contributors

- Florian Schulz (improved text input and customisable layout)

## Find this useful?

If you find this plugin useful, consider [buying me a cake](https://paypal.me/dakegumo/5) (it goes very well with coffee!)
