# PlayList

These Screenshots and code, for this  Android application(Playlist APP) 

the code, allows users to manage and rate songs through a simple multi-screen interface. 

The main screen (MainActivity) serves as the entry point of the app, presenting two primary buttons: one for entering song details and another for navigating to the second screen. 

When the user start using the app, a custom dialog appears, allowing them to input the song title, artist name, a rating (as a number), and a comment. 

Each song entry and details is stored as an object of a Song data class, which holds the necessary information and implements the Parcelable interface to allow passing data between activities.
The second screen (SecondActivity) is responsible for displaying all entered songs and calculating the average rating across them. When the user clicks the "List of Songs & Avg Rating" button, the app lists each song’s details and computes the average rating.
 
The app uses multiple XML layout files (activity_main.xml, activity_second.xml, and activity_song_adaptation.xml) 
to define the UI for each screen. 
These layouts are designed using simple LinearLayout and ScrollView components for user-friendly form inputs and navigation buttons.

 This structure makes the app modular and easy to extend in future versions, such as adding persistent storage or handling more complex interactions between screens.

Simple Exlanation
playlist app to help create favourate songs
app stores song deatils
aloows users to create and manage playlist
able to rate songs
add comments
input informatiopn about the artist


conatins

main activity:
button for:
song title
artistname

second screen:
button to display songs
button to calculate and display the average rating
buttton to main screen


