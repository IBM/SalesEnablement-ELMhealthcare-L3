!!! quote "Sample narration"
    As per ISO 13485, requirements need to be approved and reviewed. Lets return to our dashboard and see how a review cycle takes place. Here we have a work item to review the System Requirements for the Infusion Pump. Here on the approvals tab there are several approvals that are required to complete this work – the reviews themselves and a final managerial approval. Here on the links tab there are several links: The review baseline is the document that our reviewers have been asked to review.  This child task is an issue that was raised during the review and lastly the approved baseline is a link to the baselined document after the review was completed and the requirements were approved.

    Lets start by clicking the Review baseline link. Note that the system requirements document has opened – but in the context of a Baseline, and so these artifacts are all frozen and cannot be edited.

    Lets go back to the work item and click the child task. Here we can see that this is an Issue – raised by one of our reviewers, Dan, and he’s assigned the work item to Susan to resolve. At the bottom we can see a description of Dan’s issue – he doesn’t think the requirement is complete enough and has also identified a potential missing requirement. Further down we can see that Susan has replied – she agreed and made some changes to the document in response to the review comment.

    On the Approvals tab, Dan added himself as the approver. Note that the parent review work item would not have been allowed to close until all of its children were also approved and closed – so any issues raised during the review would prevent it from completing until they were addressed.

    On the links tab there is a link to the requirement that had a problem – which helped Susan identify it in the document. Lets follow that link and take a look.

    Again we are in the context of the review baseline and the requirement reads The system shall perform a self test on initiation. As we saw in the work item, Susan agreed with the review comment that is was not complete enough and made some changes – after that the review work item was approved and closed, and another baseline was taken and electronically signed. Let’s switch to that baseline and see what happened. It may not be immediately obvious what the changes were but the ELM Platform allows us to compare artifacts to see any differences – in this case let’s compare this approved baseline to the original review baseline.

    Here we can see the additional requirement that Susan added as well as the existing requirement that was modified – highlighted in blue. We can dive deeper into that requirement and see the modifications that were made.

    Lets now close that comparison and return to the document. Next we can follow this link to the actual approved baseline where we can see its electronic signature.

1. Click the **Project Dashboard** tab in the top header bar.

![](_attachments/PD-headerbar.png)

2. Notice there are several **reviews** on the dashboard.

![](_attachments/PD-Reviews.png)

??? info "Birds eye view"
    ![](_attachments/PD-Reviews-BEV.png)

3. Click **470: Review Infusion Pump System Requirements**.

![](_attachments/PD-Reviews-470.png)

Note that the **470: Review Infusion Pump System Requirements** is already complete (green checkbox). In a real project a quality review would be performed before baselining requirements and before entering a review cycle.

4. Notice that **Review 470** is a **Work Item**.

![](_attachments/Req470-WorkItem.png)

5. Click the **Approvals** tab.

![](_attachments/Req470-WorkItemApprovalsClick.png)

6. Notice the different types of **approvals**  and **approvers**.

![](_attachments/Req470-WorkItemApprovals.png)

7. Click the **Links** tab.

![](_attachments/Req470-WorkItemLinksClick.png)

8. Notice the different **Links** shown.

![](_attachments/Req470-WorkItemLinks.png)

Note that there are links to the baseline of the requirements the review was created against, another link to the final approved baseline (created after the review), and a link to a child work item (this was a problem identified during the review).

9. Click the **Review baseline** link.

![](_attachments/Req470-ClickReviewBaseline.png)

10. Notice that the link opens a view to the module in the context of the **Review Baseline**.

![](_attachments/Req470-ReviewBaseline.png)

11. Click the web browser **Back** button.

![](_attachments/Req470-BrowserBackButton.png)

12. Click the **483: Issue with Self Test Requirement** link.

![](_attachments/Req470-ClickIssue.png)

13. Notice the information captured for **Problem 483**.

![](_attachments/Problem483-top.png)

14. Scroll down and notice the comment added by Susan.

![](_attachments/Problem483-bottom.png)

15. Scroll up and click the **Approvals** tab.

![](_attachments/Problem483-topApprovalTab.png)

16.  Notice that Dan has added himself as the approver for the **work item**.

![](_attachments/Problem483-ApprovalTab.png)

A parent review work item cannot be closed until all children have been approved and closed.

17. Click the **Links** tab.

![](_attachments/Problem483-ApprovalTabLinks.png)

18. Click the **5103: The system shall perform a self test on initiation** under **Related Artifacts**.

![](_attachments/Problem483-Links-RelatedArtifacts.png)

19. Notice the link returns to the **Requirements Review Basesline** with **5103: The system shall perform a self test on initiation** selected.

![](_attachments/Problem483-RequirementsReview.png)

20. Click the **current configuration button**.

![](_attachments/CurrentConfig-Review.png)

21. Click the **Switch** button.

![](_attachments/CurrentConfig-ReviewSwitchButton.png)

22. Click the **Requirements Management Configuration** tab in the **Configuration Context** dialog.

![](_attachments/SwitchDialog1.png)

23. Select **Baselines** in the **Component** pull-down menu.

![](_attachments/SwitchDialog2.png)

24. Enter an ***** in the search box to show all **Baselines**.

![](_attachments/SwitchDialog3.png)

25. Click **Infusion Pump Base Requirements Approved** in the list of **All configurations**.

![](_attachments/SwitchDialog4.png)

26. Click the **OK** button.

![](_attachments/SwitchDialog5.png)

27. Click the **current context button**.

![](_attachments/CurrentConfig-Review.png)

28. Click **Compare Configuration...** under **Local Configuration**.

![](_attachments/CurrentConfig-Review-CompareOption.png)

29. Click **Baselines** in the **Component** pull-down menu.

![](_attachments/CompareDialog1.png)

30. Select **Infusion Pump Base Requirements Review** in the table.

![](_attachments/CompareDialog2.png)

31. Click **OK**.

![](_attachments/CompareDialog3.png)

32. Click **Next** two (2) times in the **Compare wizard**.

![](_attachments/CompareWizard-1.png)

33. Click **In both, but different (2)** button at the bottom of the side bar.

![](_attachments/InBoth.png)

??? info "Birds eye view"
    ![](_attachments/InBoth-BEV.png)

34. Click **4777: Infusion Pump System Requirements**.

![](_attachments/InBothReport.png)

35. Click the **5103** requirement to select it in left-hand table.

![](_attachments/InBothReportTable.png)

!!! bug
    Ignore the orange boxes. This is a known issue with the user interface.

36. Click the **Show changes** link.

![](_attachments/ShowChanges.png)

If the **Show changes** link doesn't appear, hover the mouse over the text for the requirement.

37. Explore the information provided on the comparison screen.

![](_attachments/ArtifactComparison.png)

38. Click the **X** at top right to close the **Artifact compare** dialog.

![](_attachments/ArtifactComparisonClose.png)

39. Click the **Close** button to close the **Comparison wizard**.

![](_attachments/ComparisonWizardClose.png)

The platform can be configured such that changes cannot be delivered unless those changes are linked to a work item with the appropriate approvals. In this project, after the review cycle was completed and approved, a new baseline was taken and signed with an electronic signature as shown in the next steps.

40. Click the **current configuration** button.

![](_attachments/CurrentConfig-Signature.png)

41. Click the **Infusion Pump Base Requirements Approved** local configuration.

![](_attachments/CurrentConfig-SignatureSelect.png)

42. Click the **Electronic Signatures** tab.

![](_attachments/Baseline-ESig-Description.png)

43. Click the **Show Details** link.

![](_attachments/Baseline-ESig-Summary.png)

44. Review the **Electronic Signatures** details and then click the **OK** button.

![](_attachments/Baseline-ESig-Details.png)

The Review also has electronic signatures both for the Approval and also the final state change to Approved – this only appears in the History of the Review work item. Feel free to show that before showing Risk Management below. The project dashboard also has a Reviews tab showing reports and summaries of Reviews.