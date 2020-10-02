# ContactDirectory
you are expected to create a in-Memory contact directory. The data
shouldn’t be stored in any database, once application is killed the data stored will be
lost. Your app should perform the following functionalities:
1. On clicking a “plus floating button” the app should be directed to 2nd screen
in which we will add user details, i.e; profile image, name, address, phone number.
For this purpose you must be using startactivityforresult and get data back
from the 2nd activity in which you entered the user data

2. All the contacts will be added to the recyclerview on the first Screen.
3. When any item is clicked on the first screen, it should take us to the 4th screen
which will display us the details of that person.
4. On clicking the “ message floating button” you should go to the 3rd screen,
where you can type any of the name (Added in the 1st screen ) in the
AutocompleteTextView and select any one of them from the drop down.
You must be able to write some text in the Edit text. By clicking send you
application should send that text message to the contact number selected above.
Here is a piece of code that can be used to send a text message:
5. Testing your app is an integral part of the app development process. By running
tests against your app consistently, you can verify your app's correctness,
functional behavior
, and usability. So, you are required to test the working of
application by writing test cases for every activity using automated testing tool
Espresso. Here is a tutorial how you can add test to your application.
