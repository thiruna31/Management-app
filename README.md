Features
Role-Based UI

Admin Users: Full access to add, edit, delete items, and view the Dashboard.

Viewer Users: Read-only access; can view items but cannot modify them.

Simple login screen with predefined credentials for testing:

Admin → admin@example.com / admin123

Viewer → viewer@example.com / viewer123

Inventory Management (CRUD)

Add, edit, and delete inventory items.

Data stored in Firebase Firestore for real-time updates.

Search and Filter

Search Bar: Filter items by name in real-time.

Category Filter: Filter items by categories such as fruits, vegetables, electronics, or clothes.

Filters work simultaneously for precise results.

Data Insights Dashboard

Accessible to admins only.

Shows key statistics:

Total number of unique items

Total inventory value (quantity × price)

Out-of-stock items

User Interface

Clean and intuitive design using Flutter widgets.

Floating action buttons for admin actions.

Responsive layout and proper feedback for empty states.

Tech Stack

Flutter: Frontend framework for cross-platform mobile development

Dart: Programming language

Firebase Firestore: Cloud database for real-time inventory management

Firebase Core: Firebase integration for Flutter

Summary

Fully functional Inventory Management App with CRUD operations.

Role-based access control for admin and viewer.

Search and category filter for quick item lookup.

Admin Dashboard for inventory insights.

Clean, professional, and responsive UI.

Real-time updates via Firebase Firestore.