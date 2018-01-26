# Abstract Guidelines & Best Practices

## Branch Naming {#branch-naming}

When branching from the UI Kit’s master, you should use one of the below tags as a prefix to your branch name. Doing this will let the rest of the team know what the purpose of the branch is, and connect it with the associated stage of work.

### **UPDATE** {#branch-naming-update}

The UPDATE prefix should be used when you are fixing or updating an existing component that is already part of the UI Kit.

**Do** use the UPDATE tag when:

* Changing the padding within or around buttons
* Fixing the way an icon behaves when the symbol is stretched to avoid distorting it

**Do not** use the UPDATE tag when:

* Adding a _new_ type of button

### **BETA** {#branch-naming-beta}

The BETA prefix should be used if you are experimenting with completely new components for the UI Kit, or proposing a new change to existing components.

**Do** use the BETA tag when:

* Experimenting with a completely new color palette
* Adding a google map component, when there are no current google map components already in the UI Kit

**Do not** use the BETA tag when:

* Adjusting the padding in an existing symbol to fit with the rest of our components.

### **PITCH** {#branch-naming-pitch}

The PITCH prefix should be used when preparing visuals for the pitch process.

This tag could be **a continuation of BETA work** or it could also be the **beginning stage of your work**.

---

## Branch Statuses {#branch-statuses}

Using Abstract’s built in status control is a great way to communicate to the rest of the team the status of your branch.

![](/assets/branch-statuses.png)

1. **Work in Progress - **Set this status when you are actively working on your branch and you don’t need any feedback on your work from the rest of the team. Newly created branches will have this status by default.
2. **Open for Feedback - **Set this status when you are done your initial build process and you’d like to get feedback from the rest of the team on your work.
3. **Ready for Review - **When you’ve resolved the feedback on your branch and you’re ready to merge it back to the master UI Kit, use this status. Lead designers should pay special attention to branches in this status and ensure that nothing in them will cause issues with the other items in the UI Kit.



