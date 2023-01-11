The following steps must be performed before delivering the demonstration. These steps should be performed prior to starting an actual client demonstration, as the software services used take a few minutes to start and enter a ready state.

<!-- 1. Open a browser window/tab using the URL found in the IBM Technology Zone email with the subject line "Your environment is ready".

![](_attachments/TZURL.png)

If prompted for a **Virtual machine access** password like in the image below, enter the **Desktop password** specified in the IBM Technology Zone email with the subject line "Your environment is ready" (highlighted in the above image) and click **Submit**.

![](_attachments/TZVMPassword.png)

2. Click the **play** button to start the demonstration virtual machine (VM).

![](_attachments/TZVM.png)

Wait until the VM changes from **Busy** to **Running** before proceeding.

3. Click on the **computer screen icon** to open the VM.

![](_attachments/TZVMReady.png)

4. Click anywhere on the background to display the Administrator login prompt.
5. Log into Microsoft Windows using the ID: **Administrator** and Password: **{{tz_environment.adminPW}}**.

![](_attachments/AdminLogin.png) -->



1. Click the **Chrome** browser icon ![](_attachments/ChromeIcon.png) on the taskbar at bottom of screen.

![](_attachments/WindowsTaskBar.png)

2. Click the Chrome bookmark **Project Dashboards** and select the **Infusion Pump** bookmark.

![](_attachments/ChromeBookmark.png)

<!-- !!! important
    All user names and passwords have been cached in the Chrome browser. This demonstration uses the **susan** user ID. If the password is not auto populated, use **susan** as the password. -->

3. In the **Log in** dialog, enter **susan** for the User ID (all lower case) and **susan** for the Password.

<!-- ![](_attachments/SelectUser.png) -->
![](_attachments/SusanLogin.png)

??? error "Popup warning"
    In some instances the Chrome browser may issue a warning that a pop window was blocked. If this occurs, simply click the **Login** link to allow the popup.

4.  Click the **Log In** button.

The **Infusion Pump** demonstration dashboard is built using many different **widgets** as seen in the image below. When first loaded, some of the widgets may return an error (e.g. Error 400). This is expected and the next steps should fix the problems. These issues are believed to be caused by some artifact type models not being updated with some applications when the server is restarted. There is a periodic renewal every 12 hours, but who wants to wait that long. The following sections should resolve the issues. Perform only the tasks required for widgets that are not loading properly.

## Error with **Infusion pump Systems Requirements to Test...** widget on **General** tab

If the **Infusion pump Systems Requirements to Test...** widget is showing an error, perform the following steps.

![](_attachments/WidgetErrors-SysReq.png)

1. Click the **Log in** link in the **Infusion Pump Systems Requirements to Test...** widget at far right, if the widget is showing an error.

![](_attachments/WidgetErrors-SysRequirements.png)

If a second error is shown, follow the next set of instructions:

![](_attachments/WidgetErrors-SysReq-2ndError.png)

2. Click the **rs setup** bookmark in the **Admin** bookmarks folder.

![](_attachments/WidgetErrors-SysReq-Bookmarks.png)

4. Click the **Data Sources** link in the **Connect to data sources** tile.

![](_attachments/WidgetErrors-SysReq-DS-tiles.png)

4. Click the **Lifecycle Query Engine** link.

![](_attachments/WidgetErrors-SysReq-DS-LifecycleQueryLink.png)

5. Click the **Refresh** button.

![](_attachments/WidgetErrors-SysReq-DS-LifecycleQueryLink-Refresh.png)

The refresh will take a few minutes to complete. Wait until the **Successfully updated the type system models for this data source** message appears.

![](_attachments/WidgetErrors-SysReq-DS-LifecycleQueryLink-RefreshComplete.png)

6. Return to the **Infusion Pump** dashboard by clicking the **Infusion Pump** bookmark under the **Project Dashboards** bookmark folder.

![](_attachments/WidgetErrors-InfusionPumpBookmark.png)

The **Infusion Pump Systems Requirements to Test...** widget should now be loaded properly.

![](_attachments/WidgetErrors-InfusionPumpSysReqGood.png)


## Error with **Problem Tracker** widget on **General** tab

If the **Problem Tracker** widget is showing an error, perform the following steps.

![](_attachments/WidgetErrors-ProblemTracker.png)

1. Click the **Problem Tracker** widget name label.

![](_attachments/WidgetErrors-ProblemTracker-Label.png)

2. Click the refresh button.

![](_attachments/WidgetErrors-ProblemTracker-Refresh.png)

The **Problem Tracker** widget should now be loaded properly. A second refresh may be required in some instances. Click the browser's back button to return to the dashboard.

![](_attachments/WidgetErrors-ProblemTracker-Reloaded.png)

## Error with **Satisfied by Partial Coverage Analysis** widget on **General** tab

The **Satisfied by Partial Coverage Analysis** widget may initially show an error like below.

![](_attachments/WidgetErrors-SatisfiedByPartial.png)

If the previous errors have been fixed, the following will likely be seen:

![](_attachments/WidgetErrors-SatisfiedByPartial3.png)

1. Click the **OK** button.

![](_attachments/WidgetErrors-SatisfiedByPartial3-OK.png)

If this does not resolve the issue, click the **Satisfied By Partial Coverage Analysis** widget label and then click the widget refresh button like in the previous fix for the **Problem Tracker** widget.

<!-- 10. Click the **Mini Dashboard** icon ![](_attachments/MiniDashboardIcon.png) at top left of the **Infusion Pump** dashboard.

??? tip "Birds-eye view"
   ![](_attachments/Dashboard-MiniDashboard.png)

11. Click the **X** button in the **IBM Engineering Requirements** widget in the **Mini Dashboard**.

Note, if the widget does not exist, skip this step and the next step.

![](_attachments/BrokenWidgetInMiniDashboard.png)

12. Click the **OK** button on the confirmation window.

![](_attachments/ConfirmWidgetRemoval.png)

<!-- The **Username** and **Password** fields are pre-populated with the **susanreq** ID and password. Do not change these fields.

![](_attachments/LoginMiniDashboards.png)

13. Close the web browser tab that was opened.

![](_attachments/CloseBrowserTab.png)

13. Click anywhere on dashboard to hide the **Mini Dashboard**.

![](_attachments/CompleteDashboard.png) -->

At this point the **Infusion Pump** dashboard should be fully loaded with out errors. If not, wait a minute and click the browser refresh icon ![](_attachments/ChromeRefresh.png). Repeat if necessary. If individual widgets on other tabs do not load or show an error, try the same steps as performed on the **Problem Tracker** widget. In testing, the others ones that typically need to be refreshed are the **FMEA** widget on the **FMEA** tab and all the widgets on the **Design Validation** tab (clicking the refresh button at the top right multiple times will typically get the widgets to complete the loading process).

<!-- To fix the broken widgets, slowly click through each of the **Infusion Pump Requirements Project Dashboard's** tabs. If after returning to the **General** tab the widget at far right is still reporting an error, try clicking the browser's refresh/reload button. Repeat this process a couple of times. The errors should resolve and data will appear in those widgets.

![](_attachments/WidgetError2.png) -->

Note: if a reboot of the virtual machine occurs, the above steps will need to be repeated.

In **Act 1**, begin the journey to learn how to demonstrate IBM Engineering Lifecycle Management (ELM). Note, this is not a deep dive into IBM ELM, rather a brief overview of some of the major capabilities and benefits.
