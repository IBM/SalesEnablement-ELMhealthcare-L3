1. Click the **Project Dashboard** tab in the top header bar.

![](_attachments/ProjectDashboard-2.png)

2. Click the **current context** button.

![](_attachments/CurrentContext-3.png)

3. Click the **dropdown** button to see the recently used and favorite configurations.

![](_attachments/CurrentContext-3-Pulldown.png)

4. Click **Infusion Pump Base** under **Favorite Global Configurations**.

![](_attachments/CurrentContext-3-IPB.png)

5. Notice the **FMEA** and **Operational Hazard Analysis** tabs on the **Infusion Pump Requirements Project Dashboard**.

![](_attachments/DashboardTabs.png)

There are many similarities between **operational hazard analysis** and **Failure Modes and Effects (FMEA)**. Both examine functions, failure ‘modes’ (equipment failures or incorrect operations), effects, and causes. The primary difference is that operational hazard analysis focuses on what could go wrong if the device is not used correctly. FMEA focuses on identification of potential hazards in the design. Additionally, a hazard analysis focuses solely on safety hazards, whereas the scope of an FMEA covers safety as well as performance, quality, and reliability.

6. Click the **FMEA** tab.

![](_attachments/DashboardTabsFEMA.png)

7. Explore the **FMEA** page.

![](_attachments/FEMA.png)

Note that this tab is surfacing analysis reports such as traceability from **System Requirement** to **Failure Mode** to the **Safety Requirement** that mitigates it – and metrics such as how many Failure modes have mitigations versus those that do not.

8. Right-click the first **Failure Mode** box and click **Open Artifact**.

![](_attachments/FMEA-FailureNode.png)

9. Click **FMEA View** in the **Views** panel.

![](_attachments/FMEA-FailureNode-FMEAView.png)

10. Explore the various columns in the analysis.

![](_attachments/FMEA-FailureNode-Explore.png)

11. Click the **current context button**.

![](_attachments/CurrentContext-FEMA.png)

12. Click **Create Change Set...**.

![](_attachments/CurrentContext-FEMA-CreateChangeSet.png)

13. Enter **RPN** in the **Name** field and click **Create**.

![](_attachments/FEMA-NewChangeSet.png)

14. Double-click in the **Risk Priority Number** field of the first row of the table.

![](_attachments/FMEA-1stRow.png)

15. Delete the value **12** and click **OK** so the cell is empty.

![](_attachments/FMEA-EditRPN.png)

16. Expand the **Mini Dashboard** and **pin** it open.

![](_attachments/FMEA-ExpandAndPinMD.png)

17. Expand the **FMEA-RPN** widget in the **Mini Dashboard**.

![](_attachments/FMEA-RPNPanel.png)

18. Scroll down in the **FMEA-RPN** widget and click the **Calculate RPN** button.

![](_attachments/FMEA-RPNPanelExpanded.png)

19. Notice that the correct value is re-inserted into the RPN cell.

![](_attachments/FMEA-RPNReCalculated.png)

20. Click the **current context button**.

![](_attachments/FMEA-CurrentContextToDelete.png)

21. Click **Discard Change Set..**.

![](_attachments/DiscardRPNChangeSet.png)

22. Click **Discard the Change Set** in the pop-up dialog.

![](_attachments/DiscardRPNChangeSetDialog.png)

23. Click the **Unpin** icon in the **Mini Dashboard** and click away from the **Mini Dashboard**.

![](_attachments/FMEA-UnpinMDB.png)

24. Switch back to **Infusion Pump Base** under **Favorite Global Configurations** in the **current context button**.

![](_attachments/ChangeContextIPB.png)

25. Click the **Project Dashboard** in the top header bar.

![](_attachments/TopHeaderBar.png)

26. Click the **Operational Hazard Analysis** tab.

![](_attachments/ProjectDashboardTabs.png)

27. Explore the **Operational Hazard Analysis** tab.

![](_attachments/OHA-Explore.png)

Note, the tab has a table of hazards containing their possible causes, actions, and the safety requirements that mitigate the hazards. The analysis is done in a similar way as FMEA, so no need to dive into this one.

28. Click the **Risk Management File** link in the **Generated Documentation** widget.

![](_attachments/OHA-generatedDocs.png)

??? info "Birds-eye view"
    ![](_attachments/OHA-generatedDocs-BEV.png)

29. Explore the **Risk Management File** generated document.

![](_attachments/OHA-generatedDocument.png)

This document was generated from the platform by Document Builder and delivered in Portable Document Format (PDF) for convenience. The Risk Management File combines both types of fault and hazard analysis into a single document and includes both tables and metric graphs.

30. Close the **Risk Management File** and **Requirements Management (RM)** browser tabs.

![](_attachments/OHA-CloseTab.png)
