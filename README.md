# Facebook App Project

## Overview
This project is a Facebook desktop application developed using C# and the Facebook Graph API.
It provides a variety of features that interact with the user’s Facebook account to enhance user engagement and functionality.
The app includes interactive games and utilities, such as photo-based quizzes and album downloads.

---

## Features
1. **GetRandomPhotoFromRandomAlbum**:
   - Description: This feature provides a fun game for the user. 
The system randomly selects an album and a photo from the user’s Facebook albums.
The user is then prompted to guess the date when the photo was uploaded
   - How It Works:
     - The app selects a random album and photo.
     - It displays the photo to the user along with a list of possible upload dates.
     - The user selects a date, and the app displays whether the guess is correct or incorrect.
       
2. **DownloadAlbum**:
   - Description: This feature allows the user to download entire photo albums from their Facebook account.
   - How It Works:
     - The app retrieves and displays a list of the user’s photo albums.
     - The user selects an album to preview its photos.
     - Upon confirmation, the app opens a file dialog where the user can choose a destination folder. The app then downloads all the photos from the selected album into the specified folder.
  
3. **User Pages**:
   - Show user pages and page photos

4. **User Groups**:
   - Show user Groups and page photos

5. **User Information**:
   -  Show user information

6. **User Albums**:
   - The app retrieves the list of albums from the user’s Facebook account.
   -  When the user selects an album, the first photo (if available) is displayed.
   -  The user can navigate through the photos in the album using Prev and Next buttons to explore all the images.
     
7. **User posts**:
   - Show user posts

