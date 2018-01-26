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

---

## Committing {#committing}

Unlike Github, we don’t have ways to handle either Pull Requests or Commit message templates.

---

## Commenting on Branches {#commenting-on-branches}

We have several different communication channels in use at ACL \(slack, email, invision, etc.\). With so many options to discuss new ideas, it is easy for the conversations to fragment and valuable feedback missed.

Ideally, commenting should be kept as close to the thing be commented on as possible. For UI Kit changes, the closest communication “channel” is the commenting system within abstract. For example, annotations can be placed directly on designs by clicking on the Files tab in Abstract, clicking on a specific file and then clicking on the associated page/symbol.

![](/assets/branch-commenting.png)

This isn’t a hard and fast rule - If it makes more sense to discuss a branch in slack or in invision,  then that should be done. But the name of the branch should be referenced, to help find that feedback later on.

\*_Please note that while abstract has a web based browser, you need an abstract account to view and comment using the browser._

---

## Merging Branches into the Master Branch {#merging-branches-into-the-master-branch}

Once a branch is merged into the master branch, all symbols will become available to the entire UX design team. Any changed symbols will be updated in all existing mockups. So it’s very important to ensure any changes merged to the master branch are:

1. Accepted by the rest of the UX team
2. Are built and designed properly to work in all states
3. Are in ACL-UI, or will shortly be in ACL-UI. What is the development plan?

To make sure the branch meets all of the above, after you’ve resolved the UX team’s feedback, change the status of your branch to **Ready for Review** and one of the lead designers will take a final look at your branch. Once they give the okay, you can merge your branch with master.

In some cases, using Abstract’s default merging action might not be the best approach. If you aren’t sure of the best way to merge your changes, let a lead designer know.

