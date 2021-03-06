---
title: "Using and managing workspaces"
order: 77
page_id: "managing_workspaces"
contextual_links:
  - type: section
    name: "Prerequisites"
  - type: link
    name: "Creating workspaces"
    url: "/docs/collaborating-in-postman/using-workspaces/creating-workspaces/"
  - type: section
    name: "Additional Resources"
  - type: subtitle
    name: "Case Studies"
  - type: link
    name: "Giant Machines"
    url: "https://www.postman.com/resources/case-studies/giant-machines/"
  - type: section
    name: "Next Steps"
  - type: link
    name: "Viewing workspace activity"
    url: "/docs/collaborating-in-postman/using-workspaces/changelog-and-restoring-collections/"
warning: false
---

You can share your Postman components with collaborators and organize your work using workspaces. To select a workspace, use the control at the top of the Postman app in the center.

<img alt="New Workspace" src="https://assets.postman.com/postman-docs/new-workspace-in-dropdown.jpg" width="400px"/>

You can [create workspaces](/docs/collaborating-in-postman/using-workspaces/creating-workspaces/) in addition to the default personal and team workspaces.

## Contents

* [Accessing workspaces](#accessing-workspaces)
* [Sharing workspaces](#sharing-workspaces)
* [Joining workspaces](#joining-workspaces)
* [Adding elements to workspaces](#adding-elements-to-workspaces)
* [Removing elements from a workspace](#removing-elements-from-a-workspace)
* [Deleting a workspace](#deleting-a-workspace)
* [Managing workspace members](#managing-workspace-members)
* [Seeing who is in your workspace](#seeing-who-is-in-your-workspace)
* [Next steps](#next-steps)

## Accessing workspaces

To see your workspace details, from the Postman app workspace selector, hover over a workspace, click **...**, and select **View Details**.

[![view details app](https://assets.postman.com/postman-docs/docs6.1update/Screen+Shot+2018-05-09+at+2.34.21+PM.png)](https://assets.postman.com/postman-docs/docs6.1update/Screen+Shot+2018-05-09+at+2.34.21+PM.png)

You can also view the details and manage your workspaces from the [Workspaces dashboard](https://app.getpostman.com/dashboard).

[![Delete workspace menu](https://assets.postman.com/postman-docs/delete-workspace-menu.jpg)](https://assets.postman.com/postman-docs/delete-workspace-menu.jpg)

You can also edit the workspace details including renaming it and editing its description from here.

## Sharing workspaces

You can share workspaces with collaborators by inviting them. If you invite a collaborator to a personal workspace, Postman will convert it to a team workspace.

> You cannot convert the default __My Workspace__ to a team workspace.

Open your workspace in the Postman app by selecting it from the drop-down at the top in the center and click __Invite__.

<img alt="New Workspace" src="https://assets.postman.com/postman-docs/new-workspace-in-dropdown.jpg" width="400px"/>

Add email addresses for the collaborators you want to invite to the workspace. Select access levels for the workspace and click __Send Invitations__.

![Send invitations](https://assets.postman.com/postman-docs/send-workspace-invitations.jpg)

When your collaborators accept the invite from the notification they receive, they will be able to access the workspace.

## Joining workspaces

In some cases you will join a workspace by following the link in an email / notification when a member of the workspace invites you. If you are part of a team in Postman, you can find workspaces to join. Open the workspaces drop-down from the control at the top of Postman in the center. Select __Team__ and scroll to __Workspaces you can join__.

<img alt="Join Workspace" src="https://assets.postman.com/postman-docs/workspaces-you-can-join.jpg" width="350px">

Select the workspace, then click __Join__ at the top right.

![Join workspace](https://assets.postman.com/postman-docs/available-workspace-join-link.jpg)

Click __Start Building__ to open the __Build__ view in the workspace you just joined.

<img alt="Build in Workspace" src="https://assets.postman.com/postman-docs/build-from-workspace-join.jpg" width="300px">

You can also join a workspace from the [Dashboard](https://app.getpostman.com/dashboard) by clicking the **Join** button next to the workspace.

[![join by dashboard](https://assets.postman.com/postman-docs/dashboard-join.png)](https://assets.postman.com/postman-docs/dashboard-join.png)

> To leave a workspace, select the __Team__ tab in the workspaces [Dashboard](https://app.getpostman.com/dashboard) and select __Leave__.

[![Leave workspace](https://assets.postman.com/postman-docs/leaving-team-workspace.jpg)](https://assets.postman.com/postman-docs/leaving-team-workspace.jpg)

## Adding elements to workspaces

You can add existing collections and environments to another workspace by sharing them.

To share a collection, open it in __Collections__ on the left of the app, and choose __Share__ from the drop-down menu or overview.

[![Collection share](https://assets.postman.com/postman-docs/collection-share-button-locations.jpg)](https://assets.postman.com/postman-docs/collection-share-button-locations.jpg)

To share an environment, open __Manage Environments__ by clicking the gear icon at the top right of the app, and click __Share__.

<img alt="Share environment" src="https://assets.postman.com/postman-docs/share-env-manage.jpg" width="600px"/>

Select the workspace you want to share to, and choose whether you also want to remove the element from its current workspace. Click __Share__.

[![Collection share to workspace](https://assets.postman.com/postman-docs/share-collection-to-selected-workspace.jpg)](https://assets.postman.com/postman-docs/share-collection-to-selected-workspace.jpg)

### Adding from the Dashboard

To add from the [Workspaces dashboard](https://app.getpostman.com/dashboard), click **Add to workspace** next to the workspace you want to add an existing element to.

[![add to workspaces](https://assets.postman.com/postman-docs/add-to-workspace.png)](https://assets.postman.com/postman-docs/add-to-workspace.png)

Select the source workspace that contains the collection or environment. In the **Collections** or **Environments** tab, select the element(s) you want to add.

[![select for workspace](https://assets.postman.com/postman-docs/select-for-workspace.png)](https://assets.postman.com/postman-docs/select-for-workspace.png)

Click **Add to this Workspace**. The element(s) will now appear in your list of collections or environments in the target workspace.

## Removing elements from a workspace

When you remove an element from a workspace, it is no longer visible in that particular workspace. The element is still available in any other workspace where it has been added.

From the Postman app, you can remove a collection from the sidebar. Click **...** to open the collection menu. Select __Remove from Workspace__ and confirm that you would like to remove the collection from the current workspace. The collection will no longer be visible in the workspace.

[![remove collection from workspace](https://assets.postman.com/postman-docs/Workspaces_Remove.png)](https://assets.postman.com/postman-docs/Workspaces_Remove.png)

From the Postman app, you can remove an environment from the **Manage Environments** modal. Click **...** next to the environment you would like to remove. Select __Remove from Workspace__ and confirm that you would like to remove the environment from the current workspace. The environment will no longer be visible in the workspace.

<img alt="Remove environment from workspace" src="https://assets.postman.com/postman-docs/remove-env-from-workspace.jpg" width="600px"/>

You can also remove collections and environments from the [Workspaces dashboard](https://go.postman.co).

> Note that deleting an element is different to removing it. When you delete an element it is no longer available in any workspace. When you remove an element from a specific workspace, it will still be available in any other workspaces it was in.

## Deleting a workspace

When you delete a workspace, you erase its existence in Postman. Only the original creator of a workspace or a team admin can delete a workspace.

To delete a workspace, go to the [Workspaces dashboard](https://app.getpostman.com/dashboard) and select a workspace.

Click **...** next to the workspace you want to delete and select __Delete__.

[![Delete workspace menu](https://assets.postman.com/postman-docs/delete-workspace-menu.jpg)](https://assets.postman.com/postman-docs/delete-workspace-menu.jpg)

Confirm that you wish to delete the workspace—it will no longer be available.

## Managing workspace members

If you're a team administrators you can manage the members of your workspace, from the [Dashboard](https://app.getpostman.com/dashboard) via the **Team** tab.

[![Edit workspace](https://assets.postman.com/postman-docs/leaving-team-workspace.jpg)](https://assets.postman.com/postman-docs/leaving-team-workspace.jpg)

Click **...** next to the workspace you want to update, and select __Manage Members__.

<img alt="Edit workspace" src="https://assets.postman.com/postman-docs/edit-workspace-members.jpg" width="350px">

In __Edit workspace details__, add or remove team members in the __Members__ list, selecting access permissions depending on your account level, and save your changes.

## Seeing who is in your workspace

You can see all of the members of your workspace and keep track of who's working on your APIs at any given time. You can also make sure that all teammates who should be included in your workspace are there. The avatars of workspace members at the top of the screen in the Postman app and on the web Dashboard are bright when a member is active, and muted when someone hasn't been active for fifteen to twenty seconds.

Hover over the avatars to see your teammates names.

<img alt="Active user" src="https://assets.postman.com/postman-docs/Beesly+active+member.jpg" width="250px"/>

> You can only see workspace members if you are also a member. To see member avatars, and to make your avatar visible to the team, [join the relevant workspace](/docs/collaborating-in-postman/using-workspaces/managing-workspaces/#joining-workspaces).

If more than three people belong to a workspace, the fourth avatar will be a number representing the remaining members. Click the number to see a list of all active and inactive users.

<img alt="Active user list" src="https://assets.postman.com/postman-docs/Active+members+Stanely+open+list.jpg" width="300px"/>

The active and inactive user lists are collapsible.

<img alt="Active user list" src="https://assets.postman.com/postman-docs/Stanely+collapsed+list+w%3Aborder.jpg" width="250px"/>

## Next steps

You can view recent [activity](/docs/collaborating-in-postman/using-workspaces/changelog-and-restoring-collections/) within a workspace to keep track with developments on your projects.
