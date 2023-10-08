` 					`**TEST RUN REPORT**



Project Information

**Project Name:** PetsMeet mobile application

**Team assigned:** QA member Jelena Stankovic

This is a project created for pet lovers. Users can create a profile in the application, share content with friends, and interact with other users with pets. The application offers useful, interesting tips. Users can find lost pets, match pets or adopt a puppy, and find new locations to walk a pet. Also, someone who owns a business in the pet industry can become a PetsMeet partner and market their products and services.





Document overview



**Scope:**

Home Tab 

Explore Tab  

Reels Tab   



**Not in this scope:**

Login Page

Pet Page

Profile Tab



Test Objectives:

**6 potential defects found:**

0 of them are critical,

0 major,

2 medium

4 minor/low-priority bugs.



3 functional and 3 non-functional bugs (content, visual) were found.



The number of test cases executed:

The numbers of test cases pass: 21

The number of test cases fail: 6

Pass percentage: 77,8 %

Fall percentage: 22,2 %



Comments: Blockers and Critical issues are not found.



**Defect**

Total number of bugs: 6

Breakdown by severity and priority: There are 3 functional and 3 non-functional bugs which are mostly minor issues. There are 2 bugs with medium priority and low severity. Developers can fix them in the sprints. The other issues have both low severity and priority.



**Testing Executed**

Regression: 27 test cases



**Test Execution Details**

Test Suits: Regression testing



Numbers of tests by type

Passed: 21

Failed: 6

Skipped: 0



**Bugs:**



Number 1

Summary: Reels Tab - Thumbnail images of other users' profile photos are not visible 

Expected result: User can see a thumbnail image of users whose reels is watching. The smaller version of profile photos should be shown in the left-down corner next to the username.

Actual result: Thumbnail image/images are blank. After tapping the thumbnail image user can see the profile photo. 



Number 2

Summary: Explore Tab – “20 take care tips“ from the section Cat and dogs is showing tips only for dogs



Actual result: After tapping on “20 care tips cats and dogs“ user can read only tips for dogs.



Number 3

Summary: Explore Tab – Search option for people by username does not display correct data for the specified searches



Actual result: Different profiles are shown, including desired search data but also mixed, wrong data - profiles that don't include the chosen specific character “a”.





Number 4



Summary: Explore Tab – Contents of “Explore our partners“  sections are mixed

Description: This applies to the contents of sections “Adoptions“, “Vets“, “Pet shops“, “Groomers“.



Actual result: After tapping on Groomers, a list of premium pet stores and veterinary station is shown to the user.





Number 5



Summary: Explore Tab - The back button is not visible after the reel is opened and user cannot navigate one step back



Descriptions: This also happens when user opens some reel through Home tab.

Actual result: After reel is opened there is no option to navigate back to the pet's profile. If user taps to any part of the screen within the reel, only the mute option from the middle of the page is activated, must close the entire application to be able to use the app again regularly. 



The video is attached in the folder.



Number 6



Summary: Reels Tab – Report button is not redirecting user to dialogue for report and request is not sent

Description: User is not able to report content if it is innapropriate for some reason

Actual result: After Report box is chosen, user stays on the reel and there is no request.



The video is attached in the folder.





**Test environment:**



Devices: iPhone 11, iOS 15.3.1



**Recommendations:**

In the next sprint focus should be on Explore tab. Since it is the tab where the most bugs are detected, developers should pay extra attention to it and also fix all found bugs. Also, new improvements can be added, which will make it easier for users of the application. Certain improvements, including for this tab, are found below.



I suggest the following 5 improvements:



**Number 1**

**Current**: User can explore others' pet profiles on Pets details page (coming from Home tab, Explore tab or Reels tab) including gender, name and age but it is difficult to see the whole main images on the top of the details page. 

**Requested**: Create an option after user taps on image, it expands.

**Reason**: Whole images are displayed in the middle of the page, without being partially cut off by the information about the pet and the top of the page. User can see images more clearly.



**Number 2**

**Current**: User can select and go through Map on the Explore tab and can't take a look at the working hours and contact information of vet stations. 

**Requested**: Include working hours and a phone number, from where user can directly activate the call, below rating information.

**Reason**: The important information is visible to user, without going to Google to search for additional information by station name. It is simplified and user does not have to exit the application.



**Number 3**

**Current**: User can select the Unfollow option on Profile page from section Following and it is hard to return back that user, to follow again.

**Requested**: Create a confirmation box which will appear when user initiates removing users from Following list. Confirmation box “Are you sure?“ has 2 options:

-Yes

-No

**Reason**: User is able to easily undo unfollowing users by accident, instead of searching again for them on the Explore tab.






**Number 4**

**Current**: User can return to posts and reels on which a like is added and it is not so easy to find and see them again on Home tab and Reels tab.

**Requested**: On the Profile tab create a section Saved that will be used to review posts and reels that user found interesting. Add a “Save“ button on the Home tab.

**Reason**: User can simply back again to nice, interesting posts and reels.



**Number 5**

**Current**: User can search through profiles of users and pets on Explore tab and it is hard to find specific, desired profiles.

**Requested**: Create filters on top of the page, below “People“ and “Pets“ section.



People:

-Name A to Z

-Name Z to A

-Only people with profile images

-Type of pets they have: Dogs, Cats, Birds, Rodents, Turtles, Fishes (single choice and multiple choice)



Pets:

-Name A to Z

-Name Z to A

-Only pets with images

-Type of pet: Dogs, Cats, Birds, Rodents, Turtles, Fishes (single choice and multiple choice)


` `**Reason**: User can promptly find the desired or similar profiles. That can lead to more connected users.





**Exit criteria**

Blockers and Critical issues are not found. All current issues are planned to be resolved in the next sprint.

