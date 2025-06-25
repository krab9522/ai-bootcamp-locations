## Test Cases Documentation

### Table of Contents
- [TC001: New User Registration](#tc001-new-user-registration)
- [TC002: User Authorization](#tc002-user-authorization)
- [TC003: Video Lessons List Display](#tc003-video-lessons-list-display)
- [TC004: Video Lesson Playback](#tc004-video-lesson-playback)
- [TC005: Pause Functionality](#tc005-pause-functionality)
- [TC006: Lesson Completion](#tc006-lesson-completion)
- [TC007: Lesson Search](#tc007-lesson-search)
- [TC008: Notifications on New Lessons](#tc008-notifications-on-new-lessons)
- [TC009: Profile Settings Update](#tc009-profile-settings-update)
- [TC010: Logout Function](#tc010-logout-function)

### TC001: New User Registration
**Description:**
- Validate the ability to register a new student with valid data.

**Preconditions:**
- Application is installed.

**Steps:**
1. Open the application.
2. Navigate to the registration screen.
3. Fill out the required details.
4. Click on "Register".

**Expected Result:**
- User is successfully registered and redirected to the main page.

---

### TC002: User Authorization
**Description:**
- Validate login functionality for registered students.

**Preconditions:**
- Student is already registered.

**Steps:**
1. Launch the application.
2. Enter valid username and password.
3. Click on "Login".

**Expected Result:**
- User is redirected to the student's profile main page.

---

### TC003: Video Lessons List Display
**Description:**
- Validate display of available video lessons to the student.

**Preconditions:**
- User is logged in.

**Steps:**
1. Open the main menu.
2. Navigate to the "Video Lessons" section.

**Expected Result:**
- List of available video lessons is displayed.

---

### TC004: Video Lesson Playback
**Description:**
- Validate playback of a selected video lesson.

**Preconditions:**
- User is logged in.

**Steps:**
1. Navigate to the "Video Lessons" section.
2. Select a lesson.
3. Click "Play".

**Expected Result:**
- Video lesson plays.

---

### TC005: Pause Functionality
**Description:**
- Validate the "Pause" button functionality during video playback.

**Preconditions:**
- Video lesson is playing.

**Steps:**
1. Click on the "Pause" button.

**Expected Result:**
- Video lesson pauses.

---

### TC006: Lesson Completion
**Description:**
- Validate application response at the end of a lesson.

**Preconditions:**
- Video lesson is playing.

**Steps:**
1. Watch the video lesson until the end.

**Expected Result:**
- Notification is displayed about lesson completion with a suggestion for the next lesson.

---

### TC007: Lesson Search
**Description:**
- Validate video lesson search by title.

**Preconditions:**
- The application must have a list of lessons.

**Steps:**
1. Go to the "Video Lessons" section.
2. Enter the lesson title in the search bar.
3. Click "Search".

**Expected Result:**
- Search results show the relevant video lessons.

---

### TC008: Notifications on New Lessons
**Description:**
- Validate notifications for newly added lessons.

**Preconditions:**
- Notifications are enabled.

**Steps:**
1. Wait for a new lesson to be added.

**Expected Result:**
- Notification about the addition of new lessons is received.

---

### TC009: Profile Settings Update
**Description:**
- Validate the ability to modify profile settings.

**Preconditions:**
- User is logged in.

**Steps:**
1. Navigate to the "Profile" section.
2. Update the profile information.
3. Click "Save".

**Expected Result:**
- Profile information is updated successfully.

---

### TC010: Logout Function
**Description:**
- Validate user logout functionality.

**Preconditions:**
- User is logged in.

**Steps:**
1. Go to the settings menu.
2. Click the "Logout" button.

**Expected Result:**
- User is logged out and the login screen appears.

---
