# CC.00005: Restaurant updating their profile
## Primary Actor(s):
Restaurant, and Restaurant Database
## Precondition(s):
It can be assumed that the restaurant has an active profile within the app and they have information within the database.
## Sunny-Day Scenario: 
<ol>
<li>The restaurant will login to the system. </li> <ul>
<li>     The email that they use will be one that they give the system as the main contact for the restaurant.</li> 
<li>      The password will be one that they create.</li> 
       </ul>
<li>      The restaurant will be able to go to their profile.</li>
<li>       They can then view the contents within their profile like contact information, menu, logo, and profile picture.</li>
<li>      The restaurant can then edit their profile.</li><ul>
<li>        This will be via a button in the top right corner.</li>
  </ul>
<li>      Restaurants can edit their logo, profile picture, menu, or contact information.</li>
<li>      If they choose to update their logo they will be prompted to add a new picture for the logo.</li>
<li>      If they choose to edit the profile picture then they will be prompted to add a new picture of the store.</li>
<li>      If they select the edit menu they will be brought to a secondary page.</li>
<li>      Each menu item menu will be shown in individual boxes along with all ingredients and calories.</li><ul>
   <li>   The restaurant will have to type in the changes that they wish to make to any specific items on the menu.
   </ul>
<li>  If edit, contact information is selected. They will be given contact information in boxes and type in changes from there.</li>
<li>  Once they are done editing the profile they can select an apply button in the top right corner.</li><ul>
   <li>  They will also be able to select a cancel button in the top right corner.
   </ul>
</ol>

## Alternate Paths:
<ol>
<li> The app is down. </li><ul>
  <li> The restaurant will be given a notification when they get to the login screen letting them know that the app is down.</li>
  </ul>
<li>  When updating contact information the user entered a invalid email.</li><ul>
  <li> If the restaurant enters an invalid email the page will provide an error and wont apply anything till the email is right.</li>  
  </ul>
<li>  The user provided an invalid phone number.</li><ul>
  <li>     If the restaurant enters an invalid phone number the page will provide an error and wont apply anything till the email is right.</li>
  </ul>
<li>      The system can’t update the restaurant database.</li> <ul>
  <li>      If the app can’t connect to the restaurant DB the user will be prompted to try again later.</li>
  </ul>
</ol>

## Postcondition
The restaurant was able to update the information within their profile.
## Linked Use-Cases
App Down CC.00002; Res DB down CC.00006; Invalid email CC.00007; Invalid email CC.00008
## Summary
Overall, the main function of this use case is to show how a restaurant is going to interact with the system. It can be assumed that restaurant already is a registered user of the app and will be able to login with the credentials that they were provided. They will then have the option between two paths. Either just view what is currently already in their profile or edit their profile. If they select to edit their profile they will have the following options.
<ul>
  <li>Change Contact Info.\</li>
  <li>Edit Menu</li>
  <li>Change Logo</li>
  <li>Change Picture</li>
</ul>
<p>If the restaurant chooses the change, contact info button they will be allowed to change their info view boxes on the info page.</p>
<p>If they choose to edit the menu, then they will be brought to a new page that has all menu items in editable boxes</p>
<p>If they choose to change their logo, they will be prompted to upload a picture of their logo from their device. The logo will either need to be PNG or JPEG.</p>
<p>Finally, if they choose to change their picture they will have an option to either take the picture using the device they are on currently or upload an image to the sight once again this will need to be a PNG or a JPEG.</p>
<p>After they are done with the editing of the profile, they will be able to select a apply button in the top right corner of the screen.</p>
