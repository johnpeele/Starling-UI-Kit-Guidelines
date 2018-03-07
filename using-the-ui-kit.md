# Using the UI Kit {#using-the-ui-kit}

Now that you have Sketch and Abstract set up, you can link the UI Kit into your new or existing sketch files.

## Linking the UI Kit

To link the UI Kit libraries to an existing sketch file, do the following:

1. Access your existing project in Abstract.
   If you haven't created a project or or branch in Abstract, you need to do so to properly link to the ui kit libraries.
2. Click on the "add file" button in Abstract and select the "Link Library" option.
   ![](/assets/Screen Shot 2018-02-09 at 11.08.54 AM.png)
3. Select the "Starling Design System" project from the popup window. Once you've selected that project, you will have a list of libraries to choose from:
   ![](/assets/Screen Shot 2018-02-09 at 11.27.48 AM.png)
4. The UI Kit is actually separated into several different libraries, each with a specific function. You can link all or some of the Libraries to your Sketch file by selecting them and clicking "Link Libraries". Please note: they all work independantly  from each other.
   As of today, the libraries available are:
   1. **Library - Icons **- This contains all icons easily available to the developers through ACL-UI
   2. **Library - Variables** - This contains all colours, borders and other miscellaneous variables available through ACL-UI
   3. **Library - Navigation** - This contains common navigational design patterns in use throughout GRC, such as the sidepanel, left hand navigation panel, etc.
   4. **Starling UI Kit** - This is the UI Kits **primary** file and should be linked in the majority of your projects. This will allow you access to common UI Components such as: tabs, buttons, form fields, etc.
5. Once you have linked the libraries you want to use in your project, open your project sketch file through abstract the normal way. You should see the libraries avaialable to you under the the large "Insert" option in the upper left of Sketch.
   ![](/assets/Screen Shot 2018-02-09 at 1.02.48 PM.png)



---

**JP's work below...**

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
