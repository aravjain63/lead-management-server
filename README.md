# Lead (sales lead)

A sales lead is a potential sales contact, an individual or organization that expresses an
interest in your goods or services. Leads are typically obtained through the referral of an
existing customer, or through a direct response to advertising or publicity. A company's
marketing department is typically responsible for lead generation.

**How it works**

_Lead-Management_ in the call process, shows a notification. If the user clicks this
notification, they will simply be redirected to the application to save the contact. If the
contact exists, you will see details of the caller, if not you will be redirected to adding
this number as contact. After this, the app stores data of the caller in the local database.
This app is currently in development, which means that in the future, many more
features will be added.

## Work Flow

```
 A Splash Screen that Displays the app icon every time that app is launched.
 A Quick Walkthorugh(Slider) of the Visiting Card Android App when the App is
launched for the first time.
 A Login Activity to ensure only Authentic Users use the app - Implemented using
Firebase Authentication.
 A Base Activity with a Bottom Navigation Bar that allows the user to navigate
through the list of contacts and groups.
 Contacts Fragment that shows the saved contacts in a Recycler View with a FAB
to add a new contact
 Clicking on the Recycler View item opens a Dialog that shows the information for
that contact and allowing us to edit/call them.
 Clicking on the Edit Screen opens the EditContactActivity.
 Inside the Base Activity, click on the FAB opens the same EditContactActivity to
add a new contact.
 The app should also show a notification when the call is ended, asking the user to
save the details for that contact.
 On clicking the notification, if the caller's details exist on the server, it show it to
the user, else ask the user to enter their details.
```

# Flow Diagram for the app

# Setting up project

**1. Fork** this project by clicking the _Fork_ button on top right corner of this page.
**2. Clone** the repository by running following command in git:

$ git clone https://github.com/[YOUR-USERNAME]/lead-management-android.git

**3. Open the project** using Android Studio by clicking **Open an existing Android
Studio Project**.
**4. Run the project on an AVD** (Android Virtual Device) by clicking the **Run** button on
Android Studio Toolbar.


# Contributing

**1.** Make reasonable changes.
**2. Add all changes** by running this command on the terminal/command prompt:

$ git add.
Or to add specific files only, run this command:

$ git add path/to/your/file
Make sure you replace path/to/your/file with the actual path to the file you want to add
to the staging area.

**3. Commit** changes.

$ git commit - m "DESCRIBE YOUR CHANGES HERE"

**4. Push** your changes.

$ git push origin

**5. Create a Pull Request** by clicking the _New pull request_ button on your repository
page.

# Help

If you need any help anywhere in the process, you can always ask a question on
our Gitter Chat.


