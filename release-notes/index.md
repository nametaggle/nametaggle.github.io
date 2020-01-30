### Release Notes

#### 0.1.0 (Build 30)
*January 31, 2020*

##### What's New?
* Group managers will be able to copy the email addresses for the members on the focus screen.
* New users default settings will share their contact information with organizations by default.  When users join new organizations, the sharing preferences from their primary organization will be the initial preferences for the new organizations.
* NameTaggle added an additional production application server to improve response times.
* An individual's group membership was reporting inconsistently based on how the group/member was added (e.g. Groups added to an individual's profile would sometimes appear differently that individuals added on the Group Edit page. )
* Simplified Login screen labels - The "username" prompt highlights the Mobile Phone login option.  users can still login with username or email address.
* Switch inputs will be green when turned on.  These were formerly red and caused confusion.
* Individual Profiles now have an optional Work Phone #.
* Added a calendar web link for organizations to point users to their calendars.
* Several long running processes now signal to the user they are in process with a message on the loading indicator screen.
* New users will get a prompt to jump to their Individual Profile page to complete setup and update their picture.
* Apple users will now see a badge on their launch screen signaling they have notifications.  Android users with some phones may also see this.
* When a user arrives at their dashboard and they have a placeholder picture they'll get a popup prompt that takes them to their user profile edit screen to choose a picture.
* When a user enters an unknown phone number email at the login screen the app will prompt them to create an account (or try again).
* When a user launches the app on a new phone, NameTaggle will prompt them to create an account or sign in.  After the first launch they shouldn't see this screen.




##### Bug Fixes:
* When creating individuals and families, the default values like "New" and "Person" will no longer be pre-populated.  These initial values were leaving spaces in the names and breaking the alphabetic order of these lists.
* Fixed alphabetic order on activity groups.
* The dashboard should now display behind popups.  Previously a popup user notification would hide the dashboard pictures.
* Apple users will now be able to choose pictures outside their photos when they choose "Other Files"
* Home Phone is no longer required.


### RoadMap Improvments:
The following list of improvements have been proposed by users.  We're still discussing the best way to implement these features and target timelines:

* Leaders can see a count (and list) of individuals who will receive the notification and be able to see the notification.
* Notifications recipients can respond to notifications.
* Organizations should have the option to review and reject picture submissions before publishing in the app.
* Organization administrators will be able to pull a report of all address changes in their organization for a given time period.
* Organization administrators will be able to generate a report with members names and addresses formatted for stick-on labels based on groups.
* My Activity Groups page was cutting off some activity groups due to a scrolling configuration error.
* Notification senders can view read receipts.
* Organizaitons that wish to use the verified group should have a workflow to review and approve verification requests.
* Organizations can configure their mail server to deliver email notifications.
