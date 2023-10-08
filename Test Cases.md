

**TEST CASES**

Example number 1

**Test case ID:** TC01

**Test case name:** Verify that pet name cannot include numbers or special characters

**Preconditions:** User is logged in to the PetsMeet app.

**Additional note:** In this test case the Error guessing technique was used, to check if the app does not allow the creation of a profile for a pet using a pet name that contains unallowable characters and numbers.


|**Test Steps**|**Test Data**|**Expected Result**|
| :- | :- | :- |
|Tap on the Profile Tab||User is redirected to the Profile Tab.|
|Tap on “Add pet“ option||The data entry form is displayed.|
|Choose the desired type of pet by tapping on the icon|Fish|The provided type of pet has been selected and the chosen icon has a blue circle around it.|
|Fill in Pet username field|coi|The provided data is visible in the Pet username field.|
|Fill in Pet name field|5&|The provided data is visible in the Pet name field.|
|Select the Breed option and choose breed from drop-down menu|Golden fish|The provided breed has been selected and displayed in Breed field.|
|Tap on Gender and select the gender of pet|Male|The selected gender of a pet is displayed in the Gender field.|
|Select the Birthday option and press OK button|Pick a date from the calendar or write down a date in the format mm/dd/yyyy |The provided data is visible in the Birthday field.|
|Tap on City,  write down a city in the search bar, and pick the city displayed by the search below|Belgrade|The provided data is displayed in the City field.|
|Click on “Add pet“ option||The title “Pet name“ with an error message “Field can only contain letters.“ is visible and profile of the pet is not created, user stays on Add pet page.|

Example number 2

**Test case ID:** TC02

**Test case name:** Verify that user can add a post

**Preconditions:** User is logged in to the PetsMeet app and gave permission to an app to access gallery from the mobile phone.


|**Test Steps**|**Test Data**|**Expected Result**|
| :- | :- | :- |
|Tap on Home Tab||Home Tab is opened.|
|Select the first icon in the upper right corner, a square with a plus sign, to add content||Two options – Create post and Create reel are displayed at the bottom of the page.|
|Tap on Create post||User is redirected to the page Select pet that includes pet profile/profiles and the button Continue.|
|Select a pet for which a post will be added and tap Continue||User is redirected to the gallery with content from a mobile phone.|
|Pick a desired image||The desired image is shown in a bigger format at the top of the page.|
|Tap on the blue arrow in the upper right corner||Preview is displayed.|
|Tap on Finish button||Field Say something, option add location and option Turn off comments are displayed.|
|Tap on orange check mark in the upper right corner||The post is released and user is redirected to the Home page. Post is visible on the Home Page.|










Example number 3

**Test case ID:** TC03

**Test case name:** Verify that user cannot select an hourly rate in the past for pet walking

**Preconditions:** User is logged in to the PetsMeet app and has a pet account.

**Description:** In this test case the Boundary values technique was used, to check if the app does not allow selecting the time in the past for walking a pet.

**Additional note:** Bug is detected, app allows user to pick a time in past, a ticket will be created. Also, once when Walk pet section is completed, time and date in notification section are wrong, not showing the selected time and date.


|**Test Steps**|**Test Data**|**Expected Result**|
| :- | :- | :- |
|Tap on the Pet page Tab||The pet page is opened.|
|Select “Walk pet“ option at the top of the page||The data entry form is displayed.|
|Scroll up and down to choose hour and minutes|Choose 13:19 while is currently 13:20|The selected time is displayed.|
|Scroll to the right or to the left to select a date from mini calendar form|07/09/2023|The propper error message “Pick a valid time” is displayed, user cannot continue filling in other fields until he changes the time to a valid time, in the future.|












<a name="_heading=h.gjdgxs"></a>Example number 4

**Test case ID:** TC04

**Test case name:** Verify that user can delete pet account

**Preconditions:** User is logged in to the PetsMeet app and has a pet account.


|**Test Steps**|**Test Data**|**Expected result**|
| :- | :- | :- |
|Tap on the Profile tab||Profile tab is opened.|
|Tap on the Settings icon in the upper right corner||User is redirected to Settings options.|
|Choose Security||A list of 3 options is displayed - Change password, Delete account, and Delete pet account.|
|Select Delete pet account||Pet username/usernames are visible on the left upper corner and the bin icon/icons are on the right side.|
|Tap on the bin icon of the pet we want to delete	||Title named as the chosen pet for deleting is displayed with the message “Are you sure you want to delete your pet account?“.|
|Choose Yes button||User stays on Delete pet account page and pet profile is deleted successfully, it is not on the list anymore.|










Example number 5

**Test case ID:** TC05

**Test case name:** Log in 

**Description:** The description table was used in this test case because it is a simple way to cover all cases of login.  



|**Conditions**|**Rule 1**|**Rule 2**|**Rule 3**|**Rule 4**|
| :- | :- | :- | :- | :- |
|Username|F|T|F|T|
|Password|F|F|T|T|
|Output|E|E|E|H|

**Legend:**

**F** - Incorrect Username/Password

**T** - Correct Username/Password

**E** - Error message Wrong login credentials. Check your credentials and try again is displayed

**H** - Home Tab is displayed

**Explanation:**

**Case 1** - Username and password are incorrect. An error message “Wrong login credentials. Check your credentials and try again“ is displayed to the user.

**Case 2** - Username is correct and password is incorrect. An error message “Wrong login credentials. Check your credentials and try again“ is displayed to the user.

**Case 3** - Username is incorrect and password is correct. An error message “Wrong login credentials. Check your credentials and try again“ is displayed to the user.

**Case 4** - Username and password are correct. User is redirected to the Home tab.
