The following steps must be performed before delivering the demonstration. These steps should be performed several minutes prior to starting an actual client demonstration, as the software services used take a few minutes to start and enter a ready state.

## Prepare the browser-based web client

1. Open a browser window/tab using the URL found in the IBM Technology Zone email with the subject line "Your environment is ready".

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

![](_attachments/AdminLogin.png)

Note: the password contains two zero's and no capital Os.

The Jazz Servers are set to auto-start when Windows starts up, but they will take a few minutes before they are ready.

6. Click the **Chrome** browser icon ![](_attachments/ChromeIcon.png) on the taskbar at bottom of screen.

![](_attachments/WindowsTaskBar.png)

7. Click the Chrome bookmark **Project Dashboards** and select the **Infusion Pump** bookmark.

![](_attachments/ChromeBookmark.png)

!!! important
    All user names and passwords have been cached in the Chrome browser. This demonstration uses the **susan** user ID.

8. Click inside the User ID field and select **susan** from the list of users.

![](_attachments/SelectUser.png)

9. Click the **Log In** button.

![](_attachments/LoginIn.png)

The **Infusion Pump** demonstration dashboard is built of many different **widgets** as seen in the image below. When first loaded, some of the widgets may return an error (e.g. Error 400). This is expected and will be resolved later.

![](_attachments/WidgetError.png)

10. Click the **Mini Dashboard** icon ![](_attachments/MiniDashboardIcon.png) at top left of the **Infusion Pump** dashboard.

??? tip "Birds-eye view"
   ![](_attachments/Dashboard-MiniDashboard.png)

11. Click the **Log in** button in the **IBM Engineering Requirements XXXX** widget in the **Mini Dashboard**.

![](_attachments/SignInMiniDashboard.png)

A new browser tab will open.

12. Click the **Sign in** button.

The **Username** and **Password** fields are pre-populated with the **susanreq** ID and password. Do not change these fields.

![](_attachments/LoginMiniDashboards.png)

13. Close the web browser tab that was opened.

![](_attachments/CloseBrowserTab.png)

14. Click anywhere on dashboard to hide the **Mini Dashboard**.

![](_attachments/CompleteDashboard.png)

<!-- At this point the **Infusion Pump** dashboard should be fully loaded with out errors. If not, wait a minute and click the browser refresh icon ![](_attachments/ChromeRefresh.png). Repeat if necessary. -->
To fix the broken widgets, slowly click through each of the **Infusion Pump Requirements Project Dashboard's** tabs. If after returning to the **General** tab the widget at far right is still reporting an error, try clicking the browser's refresh/reload button. Repeat this process a couple of times. The errors should resolve and data will appear in those widgets.

![](_attachments/WidgetError2.png)

In **Act 1**, begin the journey to learn how to demonstrate IBM Engineering Lifecycle Management (ELM). Note, this is not a deep dive into IBM ELM, rather a brief overview of some of the major capabilities and benefits.
