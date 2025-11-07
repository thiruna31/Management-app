# InClass15 - Flutter Inventory Management App

## Project Overview
**InClass15** is a Flutter-based Inventory Management App that allows users to manage inventory items in real-time using **Firebase Firestore**. The app provides features for searching, filtering, adding, editing, and deleting items, along with a dashboard for insights. It also includes **role-based access control**, differentiating between admin users and viewers.

---

## Enhanced Features Implemented

### 1. Advanced Search & Filtering
- **Search Bar:** Filters the list by item name in real-time.  
- **Category Filter:** Users can filter items by categories such as fruits, vegetables, electronics, or clothes.  
- **Simultaneous Filtering:** Search and category filters work together for precise results.  
- Optional enhancement: Could be extended with additional filters like stock status (e.g., “Low Stock”).

### 2. Role-Based UI (Read-Only Mode)
- **Admin Users:** Full access to add, edit, delete items, and view the Dashboard.  
- **Viewer Users:** Read-only access; can view items but cannot modify them.  
- **Login Screen:** Simple login with predefined credentials for testing:  
  - Admin → `admin@example.com` / `admin123`  
  - Viewer → `viewer@example.com` / `viewer123`  
- Role determines which actions and UI elements are visible.

---

## Inventory Management (CRUD)
- Add, edit, and delete inventory items.  
- Real-time data updates using Firebase Firestore.  

---

## Data Insights Dashboard
- Accessible to admins only.  
- Shows key statistics:  
  - Total number of unique items  
  - Total inventory value (quantity × price)  
  - Out-of-stock items  

---

## User Interface
- Clean and intuitive design using Flutter widgets.  
- Floating action buttons for admin actions.  
- Responsive layout with proper feedback for empty states.  

---

## Tech Stack
- **Flutter:** Frontend framework for cross-platform mobile development  
- **Dart:** Programming language  
- **Firebase Firestore:** Cloud database for real-time inventory management  
- **Firebase Core:** Firebase integration for Flutter  

---

## Summary
- Fully functional Inventory Management App with CRUD operations.  
- Role-based access control for admin and viewer.  
- Advanced search and category filter for quick item lookup.  
- Admin Dashboard for inventory insights.  
- Clean, professional, and responsive UI.  
- Real-time updates via Firebase Firestore.  

---

## Instructions to Run the App
1. Open the project in **Flutter-supported IDE** (e.g., VS Code or Android Studio).  
2. Ensure **Flutter SDK** is installed and configured.  
3. Connect to Firebase and configure `firebase_options.dart`.  
4. Use the login credentials for testing roles:  
   - Admin → `admin@example.com` / `admin123`  
   - Viewer → `viewer@example.com` / `viewer123`  
5. Run the app on an emulator or physical device.  

