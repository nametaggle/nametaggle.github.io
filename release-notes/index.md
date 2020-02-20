### Release Notes

#### 0.1.3 (Build 41)
*Scheduled February 21, 2020*

##### What's New?
<ul class="release-bullets">
<li>We've improved usability for Apple Users.  It's not always intuitive to backswipe to return to a previous screen.  Apple users will now see a back arrow in bottom left corner of the screen.</li>
<li>Tapping on the Support URL in the Dialog will now lauch you into a web browser to review our online help.</li>
<li>Sticky Notes should look nicer when you view them from the sticky note search screen.</li>
</ul>

##### Bug Fixes?
<ul class="release-bullets">
<li>Apple users should be able to upload pictures from other cloud locations again. </li>
<li>Clickable links in user notifications should work correctly.</li>
<li>Passwords on the Login screen and new user data on the signup screen will only clear after a successful login or user creation.  This will give you a better chance to review the problem.</li>
<li>The list of organizations you belong to will now be in alphabetic order.</li>
<li>Printable Directory Delete and Cancel buttons moved to the 3-dot/more menu.</li>
<li>Activity Group descriptions now allow for multi-line content.</li>
</ul>
<hr>


#### 0.1.2 (Build 39)
*February 14, 2020*

##### What's New?
<ul class="release-bullets">
<li>We improved our color scheme control.  Organization Administrators can now select any color for their organization's color scheme</li>
<li>Groups with closed membership (i.e. the group owner manages the member list) now provide a hint in the "more actions" menu (three vertical dots) when the group is closed.</li>
</ul>

##### Bug Fixes?
<ul class="release-bullets">
<li>Some users weren't seeing confirmation their family was created and re-created them.  We've changed the create family process to confirm the family is present and associated with the individual profile.</li>
<li>NameTaggle was incorrectly rejecting email Addresses with underscore characters.  Those should be allowed without question after this release.</li>
</ul>
<hr>


#### 0.1.1 (Build 35)
*February 7, 2020*

##### What's New?
<ul class="release-bullets">
<li>The fast login option will now be enabled by default for new users.  This option allows users to login without authenticating after the application closes.
</li><li> No more hidden actions! All the actions that could be hidden for a screen have moved into the Vertical elipses menu at the top right corner of the screen.
</li>
</ul>
<hr>


#### 0.1.0 (Build 34)
*January 31, 2020*

##### What's New?
<ul class="release-bullets">
<li> Group managers will be able to copy the email addresses for the members on the focus screen.
</li><li> New users default settings will share their contact information with organizations by default.  When users join new organizations, the sharing preferences from their primary organization will be the initial preferences for the new organizations.
</li><li> NameTaggle added an additional production application server to improve response times.
</li><li> An individual's group membership was reporting inconsistently based on how the group/member was added (e.g. Groups added to an individual's profile would sometimes appear differently that individuals added on the Group Edit page. )
</li><li> Simplified Login screen labels - The "username" prompt highlights the Mobile Phone login option.  users can still login with username or email address.
</li><li> Switch inputs will be green when turned on.  These were formerly red and caused confusion.
</li><li> Individual Profiles now have an optional Work Phone #.
</li><li> Added a calendar web link for organizations to point users to their calendars.
</li><li> Several long running processes now signal to the user they are in process with a message on the loading indicator screen.
</li><li> New users will get a prompt to jump to their Individual Profile page to complete setup and update their picture.
</li><li> Apple users will now see a badge on their launch screen signaling they have notifications.  Android users with some phones may also see this.
</li><li> When a user arrives at their dashboard and they have a placeholder picture they'll get a popup prompt that takes them to their user profile edit screen to choose a picture.
</li><li> When a user enters an unknown phone number email at the login screen the app will prompt them to create an account (or try again).
</li><li> When a user launches the app on a new phone, NameTaggle will prompt them to create an account or sign in.  After the first launch they shouldn't see this screen.
</li></ul>



##### Bug Fixes:
<ul class="release-bullets">
<li> When creating individuals and families, the default values like "New" and "Person" will no longer be pre-populated.  These initial values were leaving spaces in the names and breaking the alphabetic order of these lists.
</li><li>Fixed alphabetic order on activity groups.
</li><li>The dashboard should now display behind popups.  Previously a popup user notification would hide the dashboard pictures.
</li><li>Apple users will now be able to choose pictures outside their photos when they choose "Other Files"
</li><li>Home Phone is no longer required.

<hr>
### RoadMap Improvments:
The following list of improvements have been proposed by users.  We're still discussing the best way to implement these features and target timelines:

</li><li>Leaders can see a count (and list) of individuals who will receive the notification and be able to see the notification.
</li><li>Notifications recipients can respond to notifications.
</li><li>Organizations should have the option to review and reject picture submissions before publishing in the app.
</li><li>Organization administrators will be able to pull a report of all address changes in their organization for a given time period.
</li><li>Organization administrators will be able to generate a report with members names and addresses formatted for stick-on labels based on groups.
</li><li>My Activity Groups page was cutting off some activity groups due to a scrolling configuration error.
</li><li>Notification senders can view read receipts.
</li><li>Organizaitons that wish to use the verified group should have a workflow to review and approve verification requests.
</li><li>Organizations can configure their mail server to deliver email notifications.
</li></ul>
