# Cahier des Charges

## **Project Overview**
This document outlines the requirements and tasks for developing a workout tracking app. The app will help users log their workouts, track progress, and analyze their performance through user-friendly features and visualizations.

---

## **Setup and Environment**

### **Technologies**
- Firebase for backend services.
- Firestore for database (NoSQL).
- React Native for frontend development.
- React Native Paper for UI components.
- Firebase Functions for server-side logic.
- Victory or Recharts for graphs and charts.

### **Initial Setup Tasks**
1. **Setup Firebase Project**
   - Create a Firebase project and enable Firestore and Authentication.
   - Configure Firebase SDK in the React Native app.

2. **Setup React Native Environment**
   - Install necessary tools and dependencies (Node.js, React Native CLI).
   - Add React Native Paper for UI components.

3. **Plan Firestore Schema**
   - Define collections: `users`, `workouts`, `exercises`, `goals`.

---

## **Must-Have Features**

### **Core Features**
1. **User Authentication**
   - Login, signup, and password recovery via Firebase Authentication.

2. **Workout Logging**
   - Add, edit, and delete exercises with sets, reps, and weights.
   - View a summary of ongoing and completed workouts.

3. **Progress Tracking**
   - Display personal records (PRs) for each exercise.
   - Show graphs of workout volume and consistency.

4. **Cardio Goals**
   - Set and track weekly running distance goals.

5. **Data Export**
   - Export user data (workouts, stats) as JSON.

---

## **Nice-to-Have Features**

### **Advanced Features**
1. **Exercise Library**
   - Preloaded library of common exercises with descriptions.
   - Allow users to add custom exercises.

2. **Workout Templates**
   - Save and reuse workout templates.
   - Modify templates during workouts.

3. **Rest Timer**
   - Timer with strength loss percentage for optimal rest periods.

4. **Body Measurements Tracking**
   - Log and view stats like weight and body fat percentage.

5. **Recovery Suggestions**
   - Analyze workout data and recommend recovery time.

---

## **UI Design and Usability**
1. **Customizable Dashboard**
   - Allow users to rearrange widgets (e.g., graphs, quick stats).

2. **Consistent and Polished UI**
   - Use React Native Paper for a visually appealing design.
   - Ensure responsive layouts for different screen sizes.

3. **Accessibility Improvements**
   - Add labels, tooltips, and high-contrast themes.

---

## **Testing and Debugging**
1. **Authentication Testing**
   - Ensure all login, signup, and logout flows are error-free.

2. **Firestore Data Testing**
   - Verify correct saving, retrieval, and updating of data.

3. **UI Testing**
   - Test for responsiveness and usability on various devices.

---

## **Bonus Tasks**
1. **AI Integration**
   - Use AI to parse workout notes into structured JSON for importing.

2. **Achievement Badges**
   - Award badges for milestones like consistent gym visits or new PRs.

3. **Offline Functionality**
   - Enable offline persistence for Firestore.

4. **Push Notifications**
   - Reminders for workouts, goals, or upcoming rest days.

---

## **Workflow**

### **Task Categories**
1. **Setup and Environment**
   - Firebase and React Native setup.
   - Firestore schema design.

2. **Core Features**
   - Authentication and workout logging.
   - Progress tracking and data export.

3. **Advanced Features**
   - Exercise library, templates, and timers.
   - Body measurement tracking and recovery suggestions.

4. **UI Design and Usability**
   - Dashboard customization and accessibility improvements.

5. **Testing and Debugging**
   - Thorough testing of features and resolving issues.

6. **Bonus Tasks**
   - AI parsing, achievement badges, and offline mode.

---

## **Next Steps**
- Prioritize tasks based on Must-Have Features.
- Start with setup and environment configuration.
- Begin developing core features alongside learning the necessary technologies.
