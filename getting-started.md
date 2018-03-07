# Getting Started

Getting the UI Kit integrated into your design workflow is relatively simple.The first step is preparing your environment, which only has to be done once.

## Preparing your Environment

1. Install [Sketch](https://www.sketchapp.com/) - Ensure you have Sketch installed on your computer and that it is up to date with the latest publically released version.
2. Install [Abstract](https://www.goabstract.com/) - The UI Kit is stored in the UX design team's shared repository, which is managed by Abstract. Ensure you have Abstract installed on your computer and that you are a part of the ACL organization in Abstract.
_**Note:** licenses and access to the above software should be arranged during your onboarding, if not please ask a senior member of the UX team._
3. Once you have Abstract installed, ensure that you have the [Starling Design System](https://share.goabstract.com/2a3f637c-1f60-47a1-887e-dbd002f44b18) project downloaded and sync'd.
4. The UI Kit depends on a few vital Sketch plugins to function properly. The **mandatory plugins** are broken into 2 categories:
   1. Mandatory for **contributing to** the UI Kit
      1. [Symbol Organizer](https://github.com/sonburn/symbol-organizer) - This is used to automatically organize all the symbols in the UI Kit. This should be run as part of your commit process when updating the UI Kit.
      2. [Artboard Manager](https://github.com/bomberstudios/artboard-manager) - This is used to automatically preserver the order and spacing between artboards in order to match the Table of Contents in the UI Kit.
      3. [Relabel Button](https://github.com/kenmoore/sketch-relabel-button) - Quickly change the label for a button and update dimensions without affecting padding.
   2. Mandatory for **consuming \(using\)** the UI Kit:
      1. [Relabel Button](https://github.com/kenmoore/sketch-relabel-button) - Same as above...
      2. [Craft](https://www.invisionapp.com/craft) - We will use Craft, for the time being, for layer and text styles, but we are currently evaluating it’s future usage with the UI Kit.
      3. [Stark](http://www.getstark.co/) - Easily apply color blindness filters to your designs and check contrast between 2 colors.
      _**Note:** Feel free to use any contrast checker. The requirement here is that you use some kind of contrast tool._

These are the minimum required plugins and programs for using, and contributing to, the UI Kit. We've also included suggestions for other plugins that will help you design under the Sketch Plugins section.

Once you have access to abstract and installed the above plugins, you're ready to start using the UI Kit.

---

## Consume \(Use\)

To get up and running designing with the Starling UI Kit, follow these instructions:

1. Create your New Project in Abstract \(_**insert animated gif here...**_\)
2. Link the UI Kit Library to your new project \(_**insert animated gif here...**_\)
   1. In the `Master` branch of your new project, navigate to the `Files` tab
   2. Select `Link Library...` in the `Add File` dropdown menu \(_**insert animated gif here...**_\)
   3. In the modal window, select the `Starling Design System` project in the left column
   4. Then select the `Starling UI Kit.sketch` file in the right column
   5. Click the `Link Library` button
3. The UI Kit will now be available to your entire project! Welcome to the future.
4. Now create your working branch

\*\*\***TODO\*\*\***

1. **CREATE A SKETCH TEMPLATE FROM THE 'NEW PROJECT TEMPLATE'**
2. **FIGURE OUT HOW TO START A NEW PROJECT FROM THE TEMPLATE AND LINK THE UI KIT LIBRARY TO IT**

---

## Contribute \(Make Better\)

If you wish to contribute to the UI Kit by updating/improving an existing component or by experimenting with a brand new component, follow these instructions:

1. In Abstract, open the [`Starling Design System`](https://share.goabstract.com/2a3f637c-1f60-47a1-887e-dbd002f44b18) project from the Projects screen.
2. Mash the `New Branch` button to create your new working branch. **NOTE: **Abstract will NOT let you work in the `Master` branch or any other branch that you do not own yourself. So any new work must start in a new branch.
3. Give your branch a descriptive, but concise, name using one the [standard branch prefixes.](/abstract-guidelines-and-best-practices.md#abstract-name)
4. Get to work yo! Design your heart out. [Commit your work often](/abstract-guidelines-and-best-practices.md#abstract-commit) to Abstract so that you have a thorough history. A solid commit history will be a lifesaver if you ever need to revert back to an earlier state of your design and start over.
5. When you are finished, [update the status of your branch](/abstract-guidelines-and-best-practices.md#abstract-status) and ask another designer\(s\) to review your work and provide feedback. Slack is a great place for this type of collaboration.
6. After you and your design buddies have had their say and all work is complete, merge your working branch back into `Master` so that the rest of the team can revel in your awesomeness.
