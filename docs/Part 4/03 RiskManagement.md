!!! quote "Sample narration"
    Now let’s look at risk management.
    First we’ll return to our project dashboard and once again we’ll switch back to the main team working area.

    Here on our dashboard we have two tabs of interest – FMEA or Failure Modes and Effects Analysis and Operational Hazard Analysis. There are many similarities between the two – they both examine failure modes, effects and causes – the primary difference is that operational hazard analysis focuses on what could go wrong if the product is used incorrectly whilst FMEA focuses on the identification of possible failures in the design of the product components.

    Lets start with FMEA. Our dashboard is surfacing the results of the FMEA analysis in a consumable way – for example at the top here we have a traceability view from the system requirement to a potential failure related to that requirement, to the safety requirement that was created to mitigate against the risk of that happening.

    On the right we have more of a metrics view – how many failure modes are mitigated by safety requirements and how many are not.

    These are not just pictures of course this is all live data. Let’s use the traceability view to navigate into the FMEA document and see the analysis.

    Here we can see the columns of information that allow us to perform the FMEA – the identified failure mode, the effects of that failure, its potential causes and any current controls we have in place. Those assessments allow us to assign numeric values for Severity, Probability and Detection – and those can then be used to calculate the Risk Priority Number or RPN which is a simple measure of comparison.

    Here too the platform can help by automating steps or performing calculations on the data.
    Lets see an example of this in action – we’’ll start by making a change set so we can make some changes to this data.

    Then lets edit this Risk Priority Number and actually delete that value.

    Now in our mini-dashboard we can expand this RPN Calculator which will perform that calculation for us and populate the field again. Of course that’s a very simple example and a very simple calculation but it shows how the basic capabilities of the platform may be extended with automation widgets like these.

    OK lets go ahead and discard that changeset – and as before we’ll also switch back to the team area.

    Back on our Project Dashboard lets now select Operational Hazard Analysis. That analysis is performed in much the same way as FMEA with the major difference being that these hazards are the result of user error rather than device failure.

    The ELM Platform allows for automatic generation of federated documentation. Here we have a link to an automatically generated document that combines both of those analyses into a Risk Management File.

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

There are many similarities between **operational hazard analysis** and **Failure Modes and Effects (FMEA)**. Both examine functions, failure ‘modes’ (equipment failures or incorrect operations), effects and causes. The primary difference is that operational hazard analysis focuses on what could go wrong if the device is not used correctly. FMEA focuses on identification of potential hazards in the design. Additionally, a hazard analysis focuses solely on safety hazards whereas the scope of an FMEA covers safety as well as performance, quality and reliability.

6. Click the **FEMA** tab.

![](_attachments/DashboardTabsFEMA.png)

7. Explore the **FMEA** page.

![](_attachments/FEMA.png)

Note that this tab is surfacing analysis reports such as traceability from **System Requirement** to **Failure Mode** to the **Safety Requirement** that mitigates it – and metrics such as how many Failure modes have mitigations versus those that do not.

8. Click the **current context button**.

![](_attachments/CurrentContext-FEMA.png)

9. Click **Create Change Set...**.

![](_attachments/CurrentContext-FEMA-CreateChangeSet.png)

10. Enter **RPN** in the **Name** field and click **OK**.

![](_attachments/FEMA-NewChangeSet.png)

11. Double-click inside the **RPN** field of the first row of the **FEMA Table**.

![](_attachments/FEMATable-RPN.png)

??? info "Birds eye view"
    ![](_attachments/FEMATable-RPN-BEV.png)

12. Delete the value of **12** and click **OK**
