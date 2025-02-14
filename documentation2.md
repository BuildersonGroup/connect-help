
## **Manual.md**

# User Manual for Connect & Help Super Admin Dashboard

This manual provides an overview of the screens and functionalities available in the Connect & Help Super Admin Dashboard. Each section explains the purpose of the screen, its features, and how to use it.

---

## **1. Super Admin Dashboard**

### **Overview**
The Super Admin Dashboard is the main screen for super admins. It provides an overview of the system, including user activity, organization management, and access reports.

### **Features**
- **Profile Section**: Displays the super admin's profile picture, username, and role.
- **Manage Section**: Provides quick access to manage group admins, organizations, access reports, and monitor usage.
- **Activity Chart**: Shows a visual representation of active users over time.
- **Navigation**: Allows navigation to other screens like profile editing, notifications, and settings.

### **How to Use**
- Click on the **Edit Profile** icon to update your profile details.
- Use the **Manage Section** cards to navigate to specific management screens.
- Adjust the time filter (Daily, Weekly, Monthly, Yearly) to view user activity for different periods.

---

## **2. Super Admin Profile Screen**

### **Overview**
This screen allows super admins to view and edit their profile information, including username, email, phone number, and profile picture.

### **Features**
- **Edit Mode**: Toggle between view and edit modes to update profile details.
- **Profile Picture**: Upload or crop a new profile picture.
- **Form Validation**: Ensures all required fields are filled correctly.

### **How to Use**
- Click the **Edit** button to enable edit mode.
- Update your details and click **Save Changes** to save.
- Use the **Back** button to return to the dashboard.

---

## **3. Organizations Management**

### **Overview**
This screen allows super admins to manage organizations, including adding, editing, and assigning organizations to group admins.

### **Features**
- **Add/Edit Organization**: Create new organizations or edit existing ones.
- **Organization List**: View all organizations with details like name, description, and member count.
- **Assign Organization**: Assign organizations to group admins.

### **How to Use**
- Click the **+** button to add a new organization.
- Click the **Edit** button on an organization card to edit its details.
- Use the **Assign** button to assign an organization to a group admin.

---

## **4. Group Admins Management**

### **Overview**
This screen allows super admins to manage group admins, including adding, editing, and assigning organizations to them.

### **Features**
- **Add/Edit Group Admin**: Create new group admins or edit existing ones.
- **Group Admin List**: View all group admins with details like username, email, and assigned organization.
- **Assign Organization**: Assign an organization to a group admin.

### **How to Use**
- Click the **+** button to add a new group admin.
- Click on a group admin card to view or edit their details.
- Use the **Assign** button to assign an organization to a group admin.

---

## **5. Monitor Usage**

### **Overview**
This screen provides insights into application usage, including active users, age and gender distribution, and user growth.

### **Features**
- **Active Users Chart**: Shows the number of active users over time.
- **Age and Gender Chart**: Displays the distribution of users by age and gender.
- **User Growth Chart**: Tracks the growth of users over months.

### **How to Use**
- Adjust the time filter to view data for different periods.
- Hover over charts to view detailed information.

---

## **6. Access Reports**

### **Overview**
This screen allows super admins to generate and view custom reports.

### **Features**
- **Custom Reports**: Create reports based on user activity, organization data, and more.
- **Visualization**: View reports in a visually appealing format.

### **How to Use**
- Click the **Create Custom Reports** button to generate a new report.
- Use filters to customize the report data.

---

---

## **Documentation.md**

# Code Documentation for Connect & Help Super Admin Dashboard

This documentation provides an overview of the code structure, classes, and methods used in the Connect & Help Super Admin Dashboard.

---

## **Directory Structure**

```
📁 lib/
  📄 SuperUserEditProfile.dart
  📄 SuperAdminDashboard.dart
📁 organizations/
  📄 AddEditOrganizationScreen.dart
  📄 organization_screen.dart
📁 access/
  📄 access_screen.dart
📁 Monitor-Usage/
  📄 monitor_usage_screen.dart
📁 users/
  📄 AddEditProfileScreen.dart
  📄 GroupAdmins.dart
```

---

## **1. SuperUserEditProfile.dart**

### **Classes**
- `SuperUserProfileScreen`: A StatefulWidget for the super admin profile screen.
- `_SuperUserProfileScreenState`: Manages the state of the profile screen.

### **Methods**
- `initState()`: Initializes the user data.
- `_initializeUserData()`: Loads the user's data into the form fields.
- `_pickImage()`: Allows the user to pick and crop a profile picture.
- `_handleSubmit()`: Handles form submission and updates the profile.
- `build()`: Builds the UI for the profile screen.

---

## **2. SuperAdminDashboard.dart**

### **Classes**
- `SuperUserDashboard`: A StatefulWidget for the super admin dashboard.
- `_SuperUserDashboardState`: Manages the state of the dashboard.
- `ChartData`: A data model for chart data.

### **Methods**
- `_buildProfileSection()`: Builds the profile section of the dashboard.
- `_buildManageSection()`: Builds the management section with cards.
- `_buildActivityChart()`: Displays a chart of active users.
- `build()`: Builds the UI for the dashboard.

---

## **3. AddEditOrganizationScreen.dart**

### **Classes**
- `AddEditOrganizationScreen`: A StatefulWidget for adding/editing organizations.
- `_AddEditOrganizationScreenState`: Manages the state of the organization form.

### **Methods**
- `initState()`: Initializes the form data if editing an organization.
- `_pickImage()`: Allows the user to pick and crop an organization logo.
- `_handleSubmit()`: Handles form submission for creating/updating organizations.
- `build()`: Builds the UI for the organization form.

---

## **4. organization_screen.dart**

### **Classes**
- `OrganizationScreen`: A StatefulWidget for viewing and managing organizations.
- `_OrganizationScreenState`: Manages the state of the organization list.

### **Methods**
- `initState()`: Initializes the organization list.
- `_buildAppBar()`: Builds the app bar with a search bar and add button.
- `_buildOrgListCard()`: Displays a card for each organization.
- `build()`: Builds the UI for the organization list.

---

## **5. access_screen.dart**

### **Classes**
- `ReportPage`: A StatefulWidget for viewing access reports.
- `_ReportPageState`: Manages the state of the report screen.

### **Methods**
- `build()`: Builds the UI for the report screen.

---

## **6. monitor_usage_screen.dart**

### **Classes**
- `MonitorUsageScreen`: A StatefulWidget for monitoring application usage.
- `_MonitorUsageScreenState`: Manages the state of the usage screen.
- `ChartData`, `GenderData`, `UserGrowthData`: Data models for charts.

### **Methods**
- `build()`: Builds the UI for the usage screen.

---

## **7. AddEditProfileScreen.dart**

### **Classes**
- `AddEditProfileScreen`: A StatefulWidget for adding/editing group admin profiles.
- `_AddEditProfileScreenState`: Manages the state of the profile form.

### **Methods**
- `initState()`: Initializes the form data if editing a profile.
- `_pickImage()`: Allows the user to pick and crop a profile picture.
- `_handleSubmit()`: Handles form submission for creating/updating profiles.
- `build()`: Builds the UI for the profile form.

---

## **8. GroupAdmins.dart**

### **Classes**
- `GroupAdminsScreen`: A StatefulWidget for managing group admins.
- `_GroupAdminsScreenState`: Manages the state of the group admin list.
- `GroupAdminstratorEdit`: A model for managing group admin edit actions.

### **Methods**
- `initState()`: Initializes the group admin list.
- `_buildAdminList()`: Displays a list of group admins.
- `_buildAdminCard()`: Displays a card for each group admin.
- `build()`: Builds the UI for the group admin list.

---

This documentation provides a comprehensive overview of the codebase. For more details, refer to the inline comments in the source files.

---
