# Using the UI Kit {#using-the-ui-kit}

With version 47, Sketch introduced [Libraries](https://www.sketchapp.com/docs/libraries/). A Library is just an ordinary Sketch document that contains [Symbols](https://www.sketchapp.com/docs/symbols/) which you can then use in any other Sketch document. If you [update any of those Symbols](https://www.sketchapp.com/docs/libraries/library-symbols) in your Library file, documents containing instances of those Symbols will receive a notification telling you that they can be updated.

Sketch Libraries are a foundational piece of the UI Kit, so please make sure that you understand how they work.

Now that you have Sketch and Abstract installed and configured, you can link the UI Kit Library into your new or existing Sketch files.

## Linking the UI Kit

Abstract manages all aspects of Libraries for us. Libraries are linked at the project level. To link the UI Kit Libraries to a project, do the following:

1. Open your project
2. View project files for any branch or `master`
3. Select **Add File **&gt; **Link Library…**
4. Choose **Starling Design System** from the list of projects
5. Choose **Starling UI Kit.sketch** from the list of library files<br>
_**Note:** The **Starling UI Kit.sketch** Library already has all of the other Library files linked to it. Inception! Choosing this Library file will automatically bring the other Libraries along for the ride._
6. Select **Link Library** at the bottom
7. Once you have linked the libraries you want to use in your project, open your project `.sketch` file through Abstract the normal way. You should see the libraries available to you under the the "Insert" menu of Sketch.

{% raw %}
 <video id="video-abstract-link-library" class="video-js" controls preload="auto" width="640" height="264" data-setup="{}">
  <source src="https://johnpeele.gitbooks.io/starling-ui-kit-guidelines/content/assets/abstract-link-library.mp4" type='video/mp4'>
  <p class="vjs-no-js">
    To view this video please enable JavaScript, and consider upgrading to a web browser that
    <a href="http://videojs.com/html5-video-support/" target="_blank">supports HTML5 video</a>
  </p>
</video>
{% endraw %}

### UI Kit Library Organization

The UI Kit is actually separated into several different libraries, each with a specific function. You can link the individual Library files \(prefixed with "_Library -"_\) using the same linking method described above.

Just remember, if you want to link all the Libraries, then you only have to link the `Starling UI Kit.sketch` Library file.

#### Available Libraries:

* **Starling UI Kit** - This is the **primary** Library file and should be linked in all of your projects. This will allow you access to common UI Components such as: tabs, buttons, form fields, etc.
_**Note:** Each of the Libraries below are already linked to Starling UI Kit Library._
   * **Library - Icons** - This Library contains all icons easily available to the developers through ACL-UI.
   * **Library - Variables** - This Library contains all colours, borders and other miscellaneous variables available through ACL-UI.
   * **Library - Navigation** - This Library contains common navigational design patterns in use throughout GRC, such as the sidepanel, left hand navigation panel, etc.

---

**TODO**

1. **CREATE A SKETCH TEMPLATE FROM THE 'New Project Template'**
2. **FIGURE OUT HOW TO START A NEW PROJECT FROM THE TEMPLATE AND LINK THE UI KIT LIBRARY TO IT**
