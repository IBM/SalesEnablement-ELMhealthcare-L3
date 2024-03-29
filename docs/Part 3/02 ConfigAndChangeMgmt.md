Notice the banner at the top of the **Artifacts** tab.

![](_attachments/ChangeSetMessage.png)

The message informs users that the module is under change management. Later in the demonstration script, a new change set will be created. For now, learn about the audit and traceability capabilities of ELM.

1. Click the **Open History** menu item under the hamburger menu ![](_attachments/hamburgerIcon.png) icon.

![](_attachments/OpenHistory.png)

??? info "Birds-eye view"
    ![](_attachments/OpenHistory-BEV.png)

2. Click the **Audit History** tab.

![](_attachments/AuditHistoryTab.png)

3. Click the **Expand All** link.

![](_attachments/ExpandAll.png)

4. Notice the full audit trail.

From this view, auditors can view who changed what, when the change was made, and in which **change set**.

![](_attachments/AuditHistoryExpanded.png)

5. Click the **Close History** button.

![](_attachments/CloseHistory.png)

6. Click the **3. Satisfied By** link in the **Views** panel.

![](_attachments/Artifacts-ViewsMenu-3.png)

7. Notice the columns can show **traceability**.

![](_attachments/Artifacts-traceability.png)

Here, **traceability** is seen in the **Satisfied By** column. Rows with data in the **Satisfied By** column provide links to the downstream system requirements that satisfy these higher-level requirements. Notice that several rows have no information in the **Satisfied By** column. These empty fields illustrate **gaps** in the requirements providing a **gap analysis** traceability view.

8. Hover the mouse over the **4968** link in the **ID** column (don't click the link).

![](_attachments/Artifacts-HoverID.png)

Notice the additional details about the requirement that are visible by simply hovering over the item in the table.

9. Click the first **question icon** ![](_attachments/questionIcon.png) icon in the **Satisfied By** columns.

![](_attachments/Artifacts-questionIcon.png)

??? warning "Don't see the question icon"
    If the **question icon** doesn't appear, try clicking the refresh button for the widget at the top right.
    ![](_attachments/Artificats-questionIconRefresh.png) 

Notice the options available to set the **link validity** for the requirement.

![](_attachments/Artifacts-linkValidityOptions.png)

Traditionally, traceability is maintained in separate documents such as spreadsheets. This is a manual process, prone to error, very costly to maintain, and usually outdated as soon as the author clicks “save”. Here traceability is added, maintained, and tracked directly in the IBM solution and can easily be reported on.

To learn more about **link validity** go <a href="https://www.ibm.com/docs/en/elm/7.0.3?topic=configurations-link-validity-in-elm" target="_blank">here</a>.

For Act 3, remain on the current browser page and learn about ELM's design input capabilities.
