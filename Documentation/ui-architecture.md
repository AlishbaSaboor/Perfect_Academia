# Website Pages and Components

---

## Website Pages

### 1. Home Page
**Description:**  
Displays a grid of field cards directly on page load to help users discover learning domains.

**Content:**  
- Field cards (e.g., Web Development, Data Science, Machine Learning, Cyber Security)  
- Each card includes field name and short description  
- Clicking a field card navigates to the Field Category page  

---

### 2. Field Category Page
**Description:**  
Shows available content types inside a selected field.

**Content:**  
- Field title and brief introduction  
- Three category cards:  
  - Courses  
  - Books  
  - Playlists  
- Clicking a category opens the respective listing page with the field filter applied  

---

### 3. Courses Page
**Description:**  
Displays all available courses across all fields, with filtering support.  
There will be one courses page, but if we navigate through a certain field (e.g., Data Science), it will show only that field's courses by automatically filtering from all courses.

**Content:**  
- Course cards with title and platform link  
- Field-based filtering (e.g., Data Science courses)  
- Search functionality  
- Bookmark option for each course  

---

### 4. Books Page
**Description:**  
Shows recommended books for all fields in a single listing page.

**Content:**  
- Book cards with title, author, and short description  
- Bookmark option for each book  

---

### 5. Playlists Page
**Description:**  
Displays curated YouTube playlists for different learning fields.

**Content:**  
- Playlist cards using YouTube’s own thumbnail images  
- Creator name and playlist title  
- Field-based filtering  
- Bookmark option for each playlist  

---

### 6. Bookmarks Page
**Description:**  
Shows all resources saved by the user.

**Content:**  
- List of bookmarked courses, books, and playlists  
- Accessible from the profile dropdown  

---

### 7. Authentication Pages
**Description:**  
Handles user access to the platform.

**Content:**  
- Login page  
- Signup page  

---

### 8. Account Settings Page
**Description:**  
Allows users to manage their account.

**Content:**  
- Change password  
- Delete account  
- Accessible from the profile dropdown  

---

### 9. Admin Dashboard
**Description:**  
Used by administrators to manage platform content.

**Content:**  
- Add new courses, books, and playlists  
- Edit existing resources  
- Delete resources  
- Accessible only to admin users via profile dropdown  

---

## Custom Components

### 1. Navbar
**Description:**  
Main navigation component visible on all pages.

**Includes:**  
- Website logo  
- Search bar  
- Navigation links: Books, Courses, Playlists  
- Profile dropdown (top-right)  

---

### 2. Card Component
**Description:**  
Reusable UI component used to display content consistently.

**Used for:**  
- Field cards  
- Course cards  
- Book cards  
- Playlist cards  

---

## Footer
- Contains a link to the project’s GitHub repository  
- Simple and minimal, visible on all pages  
- Can include other links as needed  

---