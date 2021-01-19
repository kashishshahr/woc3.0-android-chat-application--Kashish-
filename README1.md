# [Checkpoint 5: Getting started with a very basic cross-platform chat Application]

-- Okay, so having completed mid-evaluation, you would've now got an idea of working with multiscreen apps, designing multiple layouts and how to connect the widgets on layout with Java logic.
-- Now, the next major topic to learn for making a chat application is how to store user data.
-- There are two ways of storing data in Android, one is in local database(does not require internet connection) while the other way is storing in some remote database like Firebase(requires Internet connection)
-- For a chat application, we can't store data just in local database as message sent by one user should not just get stored locally, it should also get transferred at the receiver end.
-- To achieve this what we would be doing is, storing the chat data entered at the sender end in remote database(Firebase in our case) and then retreiving data from there at the receiver end.

Concepts to Learn

**-- Linking your android application with Firebase**
**-- Adding User Authentication(preferably Google Account Authentication for now) using Firebase Authentication**
**-- Storing chat data(texts) in Firebase Realtime Database**
**-- Storing images in Firebase Storage**
**-- Retreiving the chat data and images at the user End using RecyclerView**
Resources to learn 

## How to create Firebase Account and connecting android app with Firebase

**https://youtube.com/playlist?list=PLlGT4GXi8_8dYpd8bUxAUmvAKYKd3R_t1**

## Implementing Google Account Authentication using Firebase

**-https://youtu.be/2iCx1kK6sOM**
**-https://youtu.be/etKnPu_Zfzg**
**-https://youtu.be/D9jb5tel_EM**
 
Storing texts and images in Firebase Realtime Database and Firebase storage respectively
 
# https://codelabs.developers.google.com/codelabs/firebase-android#0
# (Highly recommended, you would've developed a basic chat application on completing this  codelab) 

**Note: While completing the codelab, make sure you don't just blindly copy the code but also try to understand what you are doing at each step and how you are doing it.**
