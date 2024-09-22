# CC.00001: Use the system to update restrictions
## Primary Actor(s):
User, and User DB
## Precondition(s):
It can be assumed that the user is already a registered user of the system.
## Sunny-Day Scenario:
1.    The use ser will login using their email and password.
2.    The user will then navigate to their profile via the link on the homepage.<ul>
      <li> The link will be located in the top right corner of the screen.</li>
      </ul>
3.    The link will query the database to give all the information regarding the individual. 
4.    The uer will be able to view any basic information for their profile and all restrictions.
5.    The user can either remove a restriction or add one.<ul>
      <li>Two different paths are created here depending on what they pick.</li>
      </ul>
6.    If the user hits the remove restriction button a prompt will appear asking if they are sure.<ul>
      <li>This will talk to the user database and remove the restriction from the user.</li>
      </ul>
8.    If add restriction is selected then the user will be brought to another page to add a restriction.
9.    The user will then search for the restriction that they want to add.<ul>
      <li>There is an alternate path if restriction cannot be found.</li>  
      </ul>
10.    Once the restriction is found then the user will put whether it is an allergy or a preference.
11.  They will then hit the submit button.<ul>
    <li> This will talk with the user database and create a new restriction for the user.</li>
    </ul>
13.  The new restriction will be added to the user's profile.
## Alternate Paths:
1.    The app is down.<ul>
      <li>The user will be given a notification when they get to the login screen letting them know that the app is down.</li>
      </ul>
3.    The restriction is not found when they type it into the search bar.<ul>
    <li>  If the user happens to type in a restriction that isn’t in the DB then a new link will appear allowing them to recommend adding a restriction.</li>
      </ul>
5.    The app can’t update the database for some reason.<ul>
      <li> If the user gets through the process of either adding or removing a restriction and the app cannot connect to the user DB then a notification will appear telling them that the user DB is currently not working.</li>
      </ul>
## Postcondition
The user is able to update their profile by adding or/and removing a restriction.
## Linked Use-Cases
App Down CC.00002; Suggest New restriction CC.00003; User DB down CC.00004
## Summary
The functionality of the user being able to remove and add restrictions is vital in order for the application to work properly. In order to perform this function, however, the user needs to be a registered user on the application. Once that is completed then the user will be able to visit their profile page and perform this function. Once the user gets into their profile they will be able to view any current restrictions that they have set on their profile. From there they have two options.<ol>
<li>    Add restriction</li>
<li>    Remove Restriction</li>
</ol>
If the user selected to add a restriction then they will be brought to another page and will be able to search for the restriction that they would like to add. They then will tell the system if this restriction is an allergy or a preference. The user then can hit the submit button to add the restriction to their profile.
If remove restriction is selected then the user is able to hit the button next to the restriction and then a prompt will pop up asking them if they are sure. If they select yes then the restriction shall be removed from their profile.
