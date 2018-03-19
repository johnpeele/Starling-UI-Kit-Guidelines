---
search:
  keywords:
    - sketch
    - best practices
---

# Sketch Guidelines & Best Practices

These are the guidelines and best practices for using Sketch in general, but more specifically for contributing to the UI Kit.

## Name your files consistently {#sketch-naming}

Even though Abstract negates the need for any kind of versioning info in our file names, we still need a nice flexible naming pattern. The _general guideline_ here is to make sure a teammate can easily understand your work by reading the file name.

* `ModuleName ProjectName.sketch`
* `ModuleName ProjectName ComponentName.sketch`

Example:

* `Projects Dashboard.sketch`
* `ComputedFields FormulaBuilder.sketch`
* `Visualizer Storyboards Filters.sketch`

---

## Label layers in a meaningful way {#sketch-label}

How many layers does your typical Sketch file contain that are named “Rectangle 2 Copy 5” or “Type something”? And how often did you struggle to find a certain layer in a cluttered artboard because they were basically all named the same? Do yourself and your colleagues a favor and clean up your layers.

---

## Organize your artboards {#sketch-organize}

Because Sketch exports artboards nicely into files or pushes them directly into our prototyping platform, [InVision](https://acl.invisionapp.com), it’s a very good idea to keep their naming consistent, transparent and in a sequential order.

Using horizontal rows to group related views together with a sequential naming pattern is one way to accomplish this. The designer group should decide this together…

The [Artboard Manager](https://github.com/bomberstudios/artboard-manager) plugin will take care of this for us.

![](/assets/artboard-organization.png)

---

## Use pages to distribute your work {#sketch-pages}

\(Still not sure about this recommendation. Pages can appear quite hidden in the Sketch UI\)

---

## Structuring UI Kit symbols {#sketch-symbols}

When building symbols for the UI Kit, there’s a few minimum requirements you need to meet to ensure that your symbol will be usable by the rest of the team. If your symbols aren’t built and named correctly, your branch might not be merged with the master branch until it’s fixed.

### **Naming your Symbols** {#sketch-symbols-naming}

It’s important to make sure your symbols will fit in with the UI Kit’s existing items. The easiest way to do that is to make sure you use the right naming convention. The following naming convention should be followed:

Components / &lt;Component Name&gt; / &lt;Variation&gt; / &lt;State&gt;

Each **/** (forward slash) in your component name will create a new level of nesting in the Sketch Symbol menu…

#### **Component Name**

After the **Components /** prefix, you should choose a short, descriptive name for your new component \(Pill, Badge, Toggle, etc\).
**Important Note:** This name should correspond with the name of the component on the Starling site, and in ACL UI.

#### **Variation**

The Buttons have the best examples of **variation** naming:

Component / Button / **Default / Large** / Normal state

Component / Button / **Default / Large** / Hover state

Component / Button / **Default / Large** / Active state

Component / Button / **Default / Medium** / …

Component / Button / **Default / Small** / …

Component / Button / **Primary** / …

Component / Button / **Secondary** / …

Component / Button / **Destructive** / …

So on and so forth…

#### **State**

When you are building a component for the UI Kit, you need to consider what your component will look like in all of it’s possible states. For example - a single form field actually has 5 different possible states:

“has Value”

“Disabled”

“has Placeholder Text”

“Focused”

“has Error”

You need to ensure that you include all the variations of your new component so that UX devs and other designers know how it will work in all situations. Look to existing naming patterns to find the best name for your states, this will help to establish guidelines over time.

### **Master symbols** {#sketch-symbols-master}

When building these different states, consider using a Master symbol that allows users to easily apply different states to your component. A Master symbol is a parent symbol containing multiple Nested symbols, each Nested symbol represents a state of the Master symbol. Read the [inspiration article by Andrew Couldwell](https://medium.com/@andrewcouldwell/harness-the-power-of-symbols-204448baaef3) for further instruction and an example `.sketch` file.

### **Symbol overrides** {#sketch-symbols-overrides}

Finally, make sure that you name any overrides in your symbols in a logical way - remember that other designers may be looking at your component 6 months from now, trying to determine how to use it.

