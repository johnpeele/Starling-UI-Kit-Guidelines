# Sketch Plugins

We have identified a set of mandatory and optional plugins that will make working with, and contributing to, the UI Kit much more enjoyable.

## Mandatory for consuming \(using\) {#sketch-plugins-mandatory-consuming}

[Relabel Button](https://github.com/kenmoore/sketch-relabel-button)
Quickly change the label for a button and update dimensions without affecting padding.

[Craft Library](https://www.invisionapp.com/craft)
We will use Craft Library, for the time being, for layer and text styles, but we are currently evaluating it’s future usage with the UI Kit.<br>
_**Note:** JP is currently experimenting with a plugin called _[_Style Libraries_](https://github.com/sigtm/sketch-style-libraries)_ that could easily replace Craft Library functionality._

[Stark](http://www.getstark.co/)
Easily apply color blindness filters to your designs and check contrast between 2 colors.<br>
_**Note: **Feel free to use any contrast checker. The requirement here is that you use some kind of contrast tool._

## Mandatory for contributing {#sketch-plugins-mandatory-contributing}

[Relabel Button](https://github.com/kenmoore/sketch-relabel-button)
Same as above...

[Symbol Organizer](https://github.com/sonburn/symbol-organizer)
We use this plugin to keep symbol insanity to a minimum in the Starling UI Kit `.sketch` file

[Artboard Manager](https://github.com/bomberstudios/artboard-manager)
Because moving Artboards manually is **so 2016.** This plugin keeps your artboards neatly arranged in columns and rows. Rearranging is simply as dragging artboards to a new position and the plugin will snap all other artboards into their new position.

---

## **Optional, but highly recommended** {#sketch-plugins-optional}

[Sketch Runner](http://sketchrunner.com/)
A very, very useful command palette for Sketch.

[Rename It](http://rodi01.github.io/RenameIt/)
Effectively naming your layers is crucial when working within a team. This plugin helps you to quickly batch rename layers using simple regex methods.

---

## **Symbol Organizer settings** {#sketch-plugins-symbol-organizer}

The plugin has 2 commands:

1. **Configure Symbol Organizer**- this command is performed only once per file.
2. **Run Symbol Organizer** - this command is performed regularly as needed and is required before merging branches back to **Master.**

Each designer will need to perform the following steps when working in the UI Kit, **but only once!** You do not have to run the configuration command any more.

1. Run the configuration command **Plugins &gt; Symbol Organizer &gt; Configure Symbol Organizer**
2. Enter the settings below...
3. Click **Organize**. This will configure **and** run the plugin for the first time
4. From now on, you only need to use the **Run Symbol Organizer** command as you're working and before merging any branches into **Master**.

![](/assets/symbol-organizer-settings.png)

