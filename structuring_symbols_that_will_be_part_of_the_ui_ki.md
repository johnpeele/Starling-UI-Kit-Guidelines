## Structuring symbols that will be part of the UI Kit {#structuring-symbols-that-will-be-part-of-the-ui-kit}

When building symbols for the UI Kit, there’s a few minimum requirements you need to meet to ensure that your symbol will be usable by the rest of the team. If your symbols aren’t built and named correctly, your branch might not be merged with the master branch until it’s fixed.

### **Naming your Symbols**

It’s important to make sure your symbols will fit in with the UI Kit’s existing items. The easiest way to do that is to make sure you use the right naming convention. The following naming convention should be followed:

Components / &lt;Component Name&gt; / &lt;Variation&gt; / &lt;State&gt;

Each /  in your component name will create a new level of nesting in the Sketch Symbol menu…

#### **Component Name**

After the **Components /** prefix, you should choose a short, descriptive name for your new component \(Pill, Badge, Toggle, etc\). **IMPORTANT -** **This name should correspond with the name of the component on the Starling site, and in ACL UI. **

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

You need to ensure that you include all the variations of your new component so that UX devs and other designers know how it will work in all situations. Look to existing naming patterns to find the best name for your state\(s\), this will help to establish guidelines over time.

### **Master Symbols**

When building these different states, consider using a Master symbol that allows users to easily apply different states to your component. A Master symbol is a parent symbol containing multiple Nested symbols, each Nested symbol represents a state of the Master symbol. Read the inspiration article by Andrew Couldwell for further instruction and an example .sketch file.

### **Symbol Overrides**

Finally, make sure that you name any overrides in your symbols in a logical way - remember that other designers may be looking at your component 6 months from now, trying to determine how to use it.

