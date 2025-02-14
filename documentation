# Flutter Project Documentation

## File: main.dart
**Path**: `main.dart`

### Class: MyApp
**Extends**: `StatefulWidget`

### Class: _MyAppState
**Extends**: `State`

### Class: StartPage
**Extends**: `StatefulWidget`

### Class: _StartPageState
**Extends**: `State`

### Class: ErrorScreen
**Extends**: `StatelessWidget`

### Class: LoadingScreen
**Extends**: `StatelessWidget`

### Class: RouterScreen
**Extends**: `StatelessWidget`

### Methods
#### `void initState()`

#### `void setLocale(Locale locale)`

#### `Widget build(BuildContext context)`

#### `void initState()`

#### `void dispose()`

#### `Widget build(BuildContext context)`

#### `return ErrorScreen(
        message: _errorMessage!,
        onRetry: ()`

#### `return ErrorScreen(
            message: 'Authentication error: ${authSnapshot.error}',
            onRetry: ()`

#### `return ErrorScreen(
                message: 'Failed to load user data: ${userSnapshot.error}',
                onRetry: ()`

#### `Widget build(BuildContext context)`

#### `Widget build(BuildContext context)`

#### `Widget build(BuildContext context)`

#### `return ErrorScreen(
            message: 'Failed to determine user route',
            onRetry: ()`


---

# Directory: constants

## File: app_constants.dart
**Path**: `constants/app_constants.dart`

### Description
app_constants.dart
/// Created at: 2024-11-06 13:51:33
/// Description: Add description and implementation here


---

## File: text_constants.dart
**Path**: `constants/text_constants.dart`

### Description
text_constants.dart
/// Created at: 2024-11-06 13:51:33
/// Description: Add description and implementation here


---

## File: asset_constants.dart
**Path**: `constants/asset_constants.dart`

### Description
asset_constants.dart
/// Created at: 2024-11-06 13:51:33
/// Description: Add description and implementation here


---

## File: api_constants.dart
**Path**: `constants/api_constants.dart`

### Description
api_constants.dart
/// Created at: 2024-11-06 13:51:33
/// Description: Add description and implementation here


---

## File: color_constants.dart
**Path**: `constants/color_constants.dart`

### Description
color_constants.dart
/// Created at: 2024-11-06 13:51:33
/// Description: Add description and implementation here


---

# Directory: providers

## File: LanguageProvider.dart
**Path**: `providers/LanguageProvider.dart`

### Class: LanguageProvider
**Extends**: `ChangeNotifier`


---

## File: UserProvider.dart
**Path**: `providers/UserProvider.dart`

### Class: UserProvider
**Extends**: `ChangeNotifier`

### Class: UserException
**Implements**: `Exception`

### Methods
#### `void _setLoading(bool value)`

#### `void _setError(String? error)`

#### `void setUserAccount(AppUser user)`

#### `void clearError()`

#### `void reset()`

#### `String toString()`


---

## File: RequestProvider.dart
**Path**: `providers/RequestProvider.dart`

### Class: RequestProvider
**Extends**: `ChangeNotifier`

### Methods
#### `void reset()`


---

## File: ChatProvider.dart
**Path**: `providers/ChatProvider.dart`

### Class: ChatProvider
**Extends**: `ChangeNotifier`

### Methods
#### `void _setLoading(bool value)`

#### `void dispose()`

#### `bool _isValidChatData(Map<String, dynamic> data)`

#### `void _scheduleRetry()`


---

## File: AuthProvider.dart
**Path**: `providers/AuthProvider.dart`

### Class: AuthProvider
**Extends**: `ChangeNotifier`

### Methods
#### `void _initializeAuthStateListener()`

#### `String _getReadableErrorMessage(FirebaseAuthException e)`


---

## File: OrganizationProvider.dart
**Path**: `providers/OrganizationProvider.dart`

### Class: OrganizationProvider
**Extends**: `ChangeNotifier`

### Methods
#### `void reset()`


---

# Directory: utils

## File: helpers.dart
**Path**: `utils/helpers.dart`

### Description
helpers.dart
/// Created at: 2024-11-06 13:51:33
/// Description: Add description and implementation here


---

## File: functions.dart
**Path**: `utils/functions.dart`

### Methods
#### `String formatDate(Timestamp? timestamp)`

#### `String renderYearDate(Timestamp? timestamp)`

#### `String formatTimestamp(Timestamp timestamp)`

#### `String requestFormatTimestamp(DateTime date)`

#### `String formatTimeRange(DateTime start, DateTime end)`

#### `String formatDay(DateTime date)`

#### `Timestamp createTimestamp(DateTime date, TimeOfDay time)`


---

## File: extensions.dart
**Path**: `utils/extensions.dart`

### Description
extensions.dart
/// Created at: 2024-11-06 13:51:33
/// Description: Add description and implementation here


---

## File: excelHelper.dart
**Path**: `utils/excelHelper.dart`

### Class: ExcelValidationResult

### Class: ExcelHelper


---

## File: appUtils.dart
**Path**: `utils/appUtils.dart`

### Class: AppUtils

### Class: AnimatedContainerWidget
**Extends**: `StatefulWidget`

### Class: _AnimatedContainerWidgetState
**Extends**: `State`

### Methods
#### `_AnimatedContainerWidgetState createState()`

#### `void initState()`

#### `void dispose()`

#### `Widget build(BuildContext context)`

#### `return AnimatedBuilder(
      animation: _positionAnimation,
      builder: (context, child)`


---

## File: validators.dart
**Path**: `utils/validators.dart`

### Description
validators.dart
/// Created at: 2024-11-06 13:51:33
/// Description: Add description and implementation here


---

## File: TabItem.dart
**Path**: `utils/TabItem.dart`

### Class: TabItem
**Extends**: `StatelessWidget`

### Methods
#### `Widget build(BuildContext context)`


---

## File: snackBar.dart
**Path**: `utils/snackBar.dart`

### Class: AppSnackBar


---

# Directory: models

## File: ChatModel.dart
**Path**: `models/ChatModel.dart`

### Class: Chat

### Class: Message

### Methods
#### `Chat copyWith({
    String? id,
    String? requestId,
    String? endUserId,
    String? volunteerId,
    Timestamp? createdAt,
    String? lastMessage,
    Timestamp? lastMessageTime,
    String? lastMessageSenderId,
    bool? lastMessageRead,
    List<String>? deliveredTo,
    Map<String, bool>? typingUsers,
  })`

#### `Message copyWith({
    String? id,
    String? senderId,
    String? content,
    Timestamp? timestamp,
    bool? read,
    Timestamp? readAt,
    List<String>? deliveredTo,
    MessageType? type,
    Map<String, dynamic>? metadata,
    String? repliedToId,
  })`


---

## File: ReportModel.dart
**Path**: `models/ReportModel.dart`

### Class: Report


---

## File: OrganizationModel.dart
**Path**: `models/OrganizationModel.dart`

### Class: Organization


---

## File: RequestModel.dart
**Path**: `models/RequestModel.dart`

### Class: Request

### Class: UserRequest
**Extends**: `Request`


---

## File: UserModel.dart
**Path**: `models/UserModel.dart`

### Class: AppUser

### Methods
#### `AppUser copyWith({
    String? uid,
    String? username,
    String? email,
    String? userType,
    String? profilePicture,
    Timestamp? createdAt,
    String? phoneNumber,
    String? password,
    String? status,
    String? orgId,
    bool? isOnline,
    Timestamp? lastSeen,
    List<String>? activeChats,
    bool? isAvailable,
    int? completedRequests,
    double? rating,
    List<String>? skills,
    String? fcmToken,
    List<Availability>? availability,
  })`


---

## File: AvailabilityModel.dart
**Path**: `models/AvailabilityModel.dart`

### Class: Availability


---

# Directory: extensions

## File: LocalizationExtension.dart
**Path**: `extensions/LocalizationExtension.dart`

### Methods
#### `String translate(String key)`


---

# Directory: screens/super-admin-screens

## File: SuperUserEditProfile.dart
**Path**: `screens/super-admin-screens/SuperUserEditProfile.dart`

### Class: SuperUserProfileScreen
**Extends**: `StatefulWidget`

### Class: _SuperUserProfileScreenState
**Extends**: `State`

### Methods
#### `void initState()`

#### `void _initializeUserData()`

#### `Widget build(BuildContext context)`

#### `void dispose()`


---

## File: SuperAdminDashboard.dart
**Path**: `screens/super-admin-screens/SuperAdminDashboard.dart`

### Class: SuperUserDashboard
**Extends**: `StatefulWidget`

### Class: _SuperUserDashboardState
**Extends**: `State`

### Class: ChartData

### Methods
#### `Widget _buildProfileSection(UserProvider userProvider, bool isLargeScreen)`

#### `Widget _buildManageSection(bool isLargeScreen)`

#### `Widget _buildManageCard({
    required String title,
    required String description,
    required IconData icon,
    required Color color,
    required String route,
    required bool isLargeScreen,
  })`

#### `return InkWell(
      onTap: ()`

#### `Widget _buildActivityChart(bool isLargeScreen)`

#### `Widget build(BuildContext context)`


---

# Directory: screens/super-admin-screens/organizations

## File: AddEditOrganizationScreen.dart
**Path**: `screens/super-admin-screens/organizations/AddEditOrganizationScreen.dart`

### Class: AddEditOrganizationScreen
**Extends**: `StatefulWidget`

### Class: _AddEditOrganizationScreenState
**Extends**: `State`

### Methods
#### `void initState()`

#### `Widget build(BuildContext context)`

#### `void dispose()`


---

## File: organization_screen.dart
**Path**: `screens/super-admin-screens/organizations/organization_screen.dart`

### Class: OrganizationScreen
**Extends**: `StatefulWidget`

### Class: _OrganizationScreenState
**Extends**: `State`

### Methods
#### `void initState()`

#### `void _initializeControllers()`

#### `Widget build(BuildContext context)`

#### `PreferredSizeWidget _buildAppBar(bool isLargeScreen)`

#### `Widget _buildSearchSection()`

#### `Widget _buildOrgListCard(
      Organization org, UserProvider userProvider, bool isLargeScreen)`

#### `Widget _buildLoadingList()`

#### `Widget _buildShimmerCard()`

#### `Widget _buildEmptyState()`

#### `Widget _buildShimmerPlaceholder()`

#### `void _showAssignConfirmation(
      BuildContext context, Organization org, UserProvider userProvider)`

#### `Widget _buildConfirmationButton(
      String text, Color bgColor, Color textColor, VoidCallback onPressed)`

#### `void dispose()`


---

# Directory: screens/super-admin-screens/access

## File: access_screen.dart
**Path**: `screens/super-admin-screens/access/access_screen.dart`

### Class: ReportPage
**Extends**: `StatefulWidget`

### Class: _ReportPageState
**Extends**: `State`

### Methods
#### `Widget build(BuildContext context)`


---

# Directory: screens/super-admin-screens/Monitor-Usage

## File: monitor_usage_screen.dart
**Path**: `screens/super-admin-screens/Monitor-Usage/monitor_usage_screen.dart`

### Class: MonitorUsageScreen
**Extends**: `StatefulWidget`

### Class: _MonitorUsageScreenState
**Extends**: `State`

### Class: ChartData

### Class: GenderData

### Class: UserGrowthData

### Methods
#### `Widget build(BuildContext context)`


---

# Directory: screens/super-admin-screens/users

## File: AddEditProfileScreen.dart
**Path**: `screens/super-admin-screens/users/AddEditProfileScreen.dart`

### Class: AddEditProfileScreen
**Extends**: `StatefulWidget`

### Class: _AddEditProfileScreenState
**Extends**: `State`

### Methods
#### `void initState()`

#### `void _initializeData()`

#### `Widget build(BuildContext context)`

#### `void dispose()`


---

## File: GroupAdmins.dart
**Path**: `screens/super-admin-screens/users/GroupAdmins.dart`

### Description
Type of entity being edited ('group', 'org', etc.)
  final String? type;

  /// Action being performed ('add', 'edit', 'view', 'assign')
  final String? action;

  /// User object when editing/viewing an existing user
  final AppUser? user;

  final Organization? org;

  /// Optional route for navigation after action
  final String? route;

  /// Creates a new instance of GroupAdminstratorEdit
  GroupAdminstratorEdit({
    this.org,
    this.type,
    this.action,
    this.user,
    this.route,
  });

  /// Checks if this is an add operation
  bool get isAdd => action == 'add';

  /// Checks if this is an edit operation
  bool get isEdit => action == 'edit';

  /// Checks if this is a view operation
  bool get isView => action == 'view';

  /// Checks if this is an assign operation
  bool get isAssign => action == 'assign';
}

### Class: GroupAdminsScreen
**Extends**: `StatefulWidget`

### Class: _GroupAdminsScreenState
**Extends**: `State`

### Class: GroupAdminstratorEdit

### Methods
#### `void initState()`

#### `void _initializeAnimations()`

#### `void _showErrorSnackBar(String message)`

#### `void _showAssignOrganizationSheet(AppUser user)`

#### `Widget _buildOrganizationPicker()`

#### `Widget _buildPullIndicator()`

#### `Widget _buildPickerHeader()`

#### `Widget _buildPickerSearchBar()`

#### `Widget _buildOrganizationsList()`

#### `return Expanded(
      child: Consumer<OrganizationProvider>(
        builder: (context, orgProvider, _)`

#### `Widget _buildLoadingList()`

#### `Widget _buildEmptyState()`

#### `Widget _buildOrganizationItem(Organization org)`

#### `Widget _buildOrgLogo(Organization org)`

#### `Widget _buildAssignButton(Organization org)`

#### `return ElevatedButton(
      onPressed: ()`

#### `Widget _buildAdminList()`

#### `Widget _buildLoadingAdminList()`

#### `Widget _buildEmptyAdminState()`

#### `Widget _buildAddAdminButton()`

#### `Widget build(BuildContext context)`

#### `Widget _buildAdminCard(AppUser user, int index)`

#### `Widget _buildAdminAvatar(AppUser user)`

#### `Widget _buildAvatarPlaceholder()`

#### `Widget _buildAvatarError()`

#### `Widget _buildAdminInfo(AppUser user)`

#### `Widget _buildAssignedBadge()`

#### `Widget _buildAdminActions(AppUser user)`

#### `Widget _buildAssignButtonUser(AppUser user)`

#### `return _buildActionButton(
      onTap: ()`

#### `Widget _buildEditButton(AppUser user)`

#### `return _buildActionButton(
      onTap: ()`

#### `Widget _buildActionButton({
    required VoidCallback onTap,
    required Color color,
    required IconData icon,
    required String tooltip,
  })`

#### `void dispose()`


---

# Directory: screens/auth

## File: SplashScreen.dart
**Path**: `screens/auth/SplashScreen.dart`

### Class: SplashScreen
**Extends**: `StatefulWidget`

### Class: _SplashScreenState
**Extends**: `State`

### Class: AssetLoadingError
**Extends**: `StatelessWidget`

### Methods
#### `void initState()`

#### `void _initializeAnimations()`

#### `void _setupNavigationTimer()`

#### `void _navigateToNextScreen()`

#### `void dispose()`

#### `Widget build(BuildContext context)`

#### `return Scaffold(
      backgroundColor: Colors.white,
      body: AnimatedBuilder(
          animation: _controller,
          builder: (context, child)`

#### `Widget _buildBackground()`

#### `Widget _buildLogo()`

#### `Widget _buildAppName()`

#### `Widget build(BuildContext context)`


---

## File: LoginScreen.dart
**Path**: `screens/auth/LoginScreen.dart`

### Class: LoginScreen
**Extends**: `StatefulWidget`

### Class: _LoginScreenState
**Extends**: `State`

### Class: ForgotPasswordScreen
**Extends**: `StatefulWidget`

### Class: _ForgotPasswordScreenState
**Extends**: `State`

### Methods
#### `_LoginScreenState createState()`

#### `void initState()`

#### `void dispose()`

#### `Widget build(BuildContext context)`

#### `return Scaffold(
      backgroundColor: Colors.grey.shade50,
      body: SafeArea(
        child: AnimatedBuilder(
          animation: _controller,
          builder: (context, child)`

#### `_ForgotPasswordScreenState createState()`

#### `Widget build(BuildContext context)`

#### `void dispose()`


---

# Directory: screens/common

## File: SettingsBottomSheet.dart
**Path**: `screens/common/SettingsBottomSheet.dart`

### Class: _LanguageOption
**Extends**: `StatelessWidget`

### Methods
#### `void showSettingsBottomSheet(BuildContext context)`

#### `Widget build(BuildContext context)`


---

## File: BottomNavBar.dart
**Path**: `screens/common/BottomNavBar.dart`

### Class: BottomNavBar
**Extends**: `StatefulWidget`

### Class: _BottomNavBarState
**Extends**: `State`

### Class: NavItem

### Methods
#### `void initState()`

#### `void _initializeControllers()`

#### `void _initializeNavigation()`

#### `void _onPageChanged(int page)`

#### `Widget build(BuildContext context)`

#### `return Scaffold(
      backgroundColor: Colors.white,
      body: GestureDetector(
        onHorizontalDragEnd: (DragEndDetails details)`

#### `Widget _buildNavItem(NavItem item, int itemIndex)`

#### `return Material(
      color: Colors.transparent,
      child: InkWell(
        onTap: ()`

#### `void dispose()`


---

## File: ChatHistory.dart
**Path**: `screens/common/ChatHistory.dart`

### Class: ChatHistory
**Extends**: `StatefulWidget`

### Class: _ChatHistoryState
**Extends**: `State`

### Methods
#### `void initState()`

#### `Request _convertToRequest(UserRequest userRequest)`

#### `Widget _buildChatGroups(BuildContext context, List<Chat> chats)`

#### `Widget _buildStatusHeader(String status, int count)`

#### `Widget _buildChatCard({
    required BuildContext context,
    required Chat chat,
    required RequestProvider requestProvider,
    required ChatProvider chatProvider,
  })`

#### `Widget _buildRequestInfoHeader(Request request)`

#### `Widget _buildUserInfoAndMessage(
      AppUser? otherUser, Chat chat, bool isEndUser)`

#### `Widget _buildUserAvatar(AppUser? otherUser, bool isEndUser)`

#### `Widget _buildRequestDetailsFooter(Request request)`

#### `Widget _buildEmptyState()`

#### `String _getLastSeenText(Timestamp lastSeen)`

#### `String _formatLastSeen(Timestamp lastSeen)`

#### `String _formatTimestamp(Timestamp timestamp)`

#### `String _formatDate(Timestamp timestamp)`

#### `IconData _getRequestTypeIcon(String type)`

#### `Color _getStatusColor(String status)`

#### `Widget build(BuildContext context)`

#### `void dispose()`


---

## File: ChatScreen.dart
**Path**: `screens/common/ChatScreen.dart`

### Class: ChatScreen
**Extends**: `StatefulWidget`

### Class: _ChatScreenState
**Extends**: `State`

### Methods
#### `void initState()`

#### `Widget _buildHeader()`

#### `Widget _buildMessageList()`

#### `Widget _buildMessageItem(Message message, bool isMe)`

#### `Widget _buildMessageInput()`

#### `Widget _buildDateDivider(DateTime date)`

#### `String _formatMessageDate(DateTime date)`

#### `String _formatDate(Timestamp timestamp)`

#### `IconData _getRequestTypeIcon(String type)`

#### `Color _getStatusColor(String status)`

#### `bool _isSameDay(DateTime date1, DateTime date2)`

#### `Widget build(BuildContext context)`

#### `void dispose()`


---

# Directory: screens/end-users-screens

## File: EndUserRequests.dart
**Path**: `screens/end-users-screens/EndUserRequests.dart`

### Class: EndUserRequests
**Extends**: `StatefulWidget`

### Class: _EndUserRequestsState
**Extends**: `State`

### Methods
#### `Widget _buildTabBar()`

#### `Widget _buildRequestsList(List<Request> allRequests, String tabStatus)`

#### `Color _getStatusBackgroundColor(String status)`

#### `Color _getStatusTextColor(String status)`

#### `Widget build(BuildContext context)`

#### `return DefaultTabController(
      length: 2,
      child: Consumer<RequestProvider>(
        builder: (context, reqProvider, _)`


---

## File: RequestAddloc.dart
**Path**: `screens/end-users-screens/RequestAddloc.dart`

### Class: MyApp
**Extends**: `StatelessWidget`

### Class: AddLocationScreen
**Extends**: `StatefulWidget`

### Class: _AddLocationScreenState
**Extends**: `State`

### Methods
#### `void main()`

#### `Widget build(BuildContext context)`

#### `_AddLocationScreenState createState()`

#### `Widget build(BuildContext context)`


---

## File: BottomSheet.dart
**Path**: `screens/end-users-screens/BottomSheet.dart`

### Class: CustomBottomSheet
**Extends**: `StatefulWidget`

### Class: _CustomBottomSheetState
**Extends**: `State`

### Methods
#### `_CustomBottomSheetState createState()`

#### `void initState()`

#### `Widget _buildStepIndicator()`

#### `void _unfocus()`

#### `Widget _buildDescriptionStep()`

#### `Widget _buildDateTimeStep()`

#### `Widget _buildSearchBar()`

#### `Widget _buildLocationStep()`

#### `Widget _buildNavigationButtons()`

#### `bool _validateDescription()`

#### `bool _validateDateTime()`

#### `bool _validateLocation()`

#### `Widget build(BuildContext context)`

#### `void dispose()`


---

## File: EndUserDashboard.dart
**Path**: `screens/end-users-screens/EndUserDashboard.dart`

### Class: EndUserDashboard
**Extends**: `StatefulWidget`

### Class: _EndUserDashboardState
**Extends**: `State`

### Methods
#### `Widget _buildProfileSection(UserProvider userProvider, bool isLargeScreen)`

#### `Widget _buildServicesSection(bool isLargeScreen)`

#### `Widget _buildServiceCard({
    required String title,
    required String description,
    required IconData icon,
    required Color color,
    String? imagePath,
    required bool isLargeScreen,
  })`

#### `return InkWell(
      onTap: ()`

#### `Widget build(BuildContext context)`


---

## File: FaqScreen.dart
**Path**: `screens/end-users-screens/FaqScreen.dart`

### Class: FaqScreen
**Extends**: `StatefulWidget`

### Class: _FaqScreenState
**Extends**: `State`

### Methods
#### `void initState()`

#### `Widget build(BuildContext context)`

#### `Widget _buildCategoryButton({
    required Color color,
    required IconData icon,
    required String text,
    required String subtext,
    Color? iconColor,
  })`


---

# Directory: screens/group-admin-screens

## File: GroupAdminEditAddScreen.dart
**Path**: `screens/group-admin-screens/GroupAdminEditAddScreen.dart`

### Class: GroupAdminEditAddScreen
**Extends**: `StatefulWidget`

### Class: _GroupAdminEditAddScreenState
**Extends**: `State`

### Methods
#### `void initState()`

#### `void _initializeScreen()`

#### `void _showDeactivateDialog(UserProvider userProvider)`

#### `Widget _buildDialogButton(
    String text,
    Color bgColor,
    Color textColor,
    VoidCallback onPressed,
  )`

#### `Widget build(BuildContext context)`

#### `void dispose()`


---

## File: GroupAdminDashboard.dart
**Path**: `screens/group-admin-screens/GroupAdminDashboard.dart`

### Class: GroupAdminDashboard
**Extends**: `StatefulWidget`

### Class: _GroupAdminDashboardState
**Extends**: `State`

### Methods
#### `Widget _buildProfileSection(UserProvider userProvider, bool isLargeScreen)`

#### `Widget _buildStatCard(
    String title,
    int count,
    IconData icon,
    Color color,
    bool isLargeScreen,
  )`

#### `Widget _buildManageSection(bool isLargeScreen)`

#### `Widget _buildManageCard({
    required String title,
    required String description,
    required IconData icon,
    required Color color,
    required String route,
    String? imagePath,
    required bool isLargeScreen,
  })`

#### `return InkWell(
      onTap: ()`

#### `Widget build(BuildContext context)`


---

# Directory: screens/group-admin-screens/manage-users

## File: manage_users.dart
**Path**: `screens/group-admin-screens/manage-users/manage_users.dart`

### Class: UserManagementScreen
**Extends**: `StatefulWidget`

### Class: _UserManagementScreenState
**Extends**: `State`

### Class: UploadResponse

### Methods
#### `void initState()`

#### `void dispose()`

#### `void _showLoadingDialog()`

#### `void _showAddUserDialog()`

#### `void _showErrorsDialog(List<dynamic> errors)`

#### `Widget _buildUserTypeOption({
    required IconData icon,
    required String title,
    required String subtitle,
    required Color color,
    required VoidCallback? onTap,
    bool isLoading = false,
  })`

#### `Widget build(BuildContext context)`

#### `return DefaultTabController(
      length: 2,
      child: Consumer<UserProvider>(
        builder: (context, userProvider, _)`


---

# Directory: screens/group-admin-screens/request-details

## File: RequestDetails.dart
**Path**: `screens/group-admin-screens/request-details/RequestDetails.dart`

### Class: RequestDetailsScreen
**Extends**: `StatefulWidget`

### Class: _RequestDetailsScreenState
**Extends**: `State`

### Methods
#### `void initState()`

#### `Widget build(BuildContext context)`

#### `Widget _buildRequestHeader()`

#### `Widget _buildTimeLocationSection()`

#### `Widget _buildVolunteerSection(RequestProvider reqProvider)`

#### `Widget _buildVolunteerItem(AppUser volunteer, RequestProvider reqProvider)`

#### `return TextButton(
                onPressed: isDisabled
                    ? null
                    : ()`

#### `Widget _buildEmptyState()`


---

# Directory: screens/group-admin-screens/supervise-activity

## File: oversee_activity_d.dart
**Path**: `screens/group-admin-screens/supervise-activity/oversee_activity_d.dart`

### Class: RequestDetailScreen
**Extends**: `StatelessWidget`

### Methods
#### `Widget build(BuildContext context)`

#### `Widget _buildProgressBar()`

#### `Widget _buildSectionHeader(String title)`

#### `Widget _buildUserCard({
    required String name,
    required String joinDate,
    required String assists,
    required Color backgroundColor,
  })`

#### `Widget _buildAssistanceDetails()`


---

## File: oversee_activity.dart
**Path**: `screens/group-admin-screens/supervise-activity/oversee_activity.dart`

### Class: ActivityScreen
**Extends**: `StatelessWidget`

### Class: RoutePainter
**Extends**: `CustomPainter`

### Methods
#### `Widget build(BuildContext context)`

#### `Widget _buildTab(String text, bool isActive)`

#### `Widget _buildRequestCard(BuildContext context,
      {required String title,
      required String subtitle,
      required Color color,
      required Color routeColor})`

#### `void paint(Canvas canvas, Size size)`

#### `bool shouldRepaint(covariant CustomPainter oldDelegate)`


---

## File: SuperviseActivity.dart
**Path**: `screens/group-admin-screens/supervise-activity/SuperviseActivity.dart`

### Class: SuperviseActivityScreen
**Extends**: `StatefulWidget`

### Class: _SuperviseActivityScreenState
**Extends**: `State`

### Methods
#### `Widget build(BuildContext context)`

#### `Widget _buildEmptyState()`

#### `Widget _buildStatisticsSection(int activeRequests, bool isLargeScreen)`

#### `Widget _buildStatCard(
    String title,
    String value,
    IconData icon,
    Color color,
    bool isLargeScreen,
  )`

#### `Widget _buildRequestCard(UserRequest request, bool isLargeScreen)`

#### `Widget _buildInfoRow(String label, String value, IconData icon)`


---

## File: oversee_activity_vol.dart
**Path**: `screens/group-admin-screens/supervise-activity/oversee_activity_vol.dart`

### Class: ActivityTimelineScreen
**Extends**: `StatelessWidget`

### Class: TimelineItem

### Methods
#### `Widget build(BuildContext context)`

#### `Widget _buildTimelineCard(TimelineItem item)`


---

# Directory: screens/group-admin-screens/manage-tasks

## File: index.dart
**Path**: `screens/group-admin-screens/manage-tasks/index.dart`


---

## File: ManageRequestList.dart
**Path**: `screens/group-admin-screens/manage-tasks/ManageRequestList.dart`

### Class: RequestCard
**Extends**: `StatelessWidget`

### Methods
#### `Widget build(BuildContext context)`

#### `Widget _buildTypeChip(String type)`

#### `Widget _buildInfoRow(IconData icon, String text)`

#### `Widget _buildActionButton(BuildContext context)`

#### `return IconButton(
        onPressed: ()`

#### `return IconButton(
      onPressed: ()`

#### `Widget _buildStatusButtons(BuildContext context)`


---

## File: DistributeTasksScreen.dart
**Path**: `screens/group-admin-screens/manage-tasks/DistributeTasksScreen.dart`

### Class: DistributeTasksScreen
**Extends**: `StatefulWidget`

### Class: _DistributeTasksScreenState
**Extends**: `State`

### Methods
#### `Widget build(BuildContext context)`


---

## File: ManageRequest.dart
**Path**: `screens/group-admin-screens/manage-tasks/ManageRequest.dart`

### Class: ManageRequest
**Extends**: `StatefulWidget`

### Class: _ManageRequestState
**Extends**: `State`

### Class: RequestCard
**Extends**: `StatelessWidget`

### Methods
#### `Widget build(BuildContext context)`

#### `return TabBarView(
              children: [
                _buildTabContent(
                  reqProvider,
                  requests
                      .where((req)`

#### `Widget _buildTab(String title, String status, Color statusColor)`

#### `Widget _buildTabContent(
      RequestProvider provider, List<UserRequest> requests)`

#### `return RequestCard(
          request: requests[index],
          onAccept: ()`

#### `Widget _buildEmptyState()`

#### `Widget build(BuildContext context)`

#### `Widget _buildTypeChip(String type)`

#### `Widget _buildInfoRow(IconData icon, String text)`

#### `Widget _buildActionButton(BuildContext context)`

#### `return IconButton(
        onPressed: ()`

#### `return IconButton(
      onPressed: ()`

#### `Widget _buildStatusButtons(BuildContext context)`


---

# Directory: screens/group-admin-screens/generate-reports

## File: GenerateReportVolunteer.dart
**Path**: `screens/group-admin-screens/generate-reports/GenerateReportVolunteer.dart`

### Class: VolunteerReportScreen
**Extends**: `StatefulWidget`

### Class: _VolunteerReportScreenState
**Extends**: `State`

### Methods
#### `_VolunteerReportScreenState createState()`

#### `void initState()`

#### `Widget build(BuildContext context)`


---

# Directory: screens/volunteer-screens

## File: ShowBottomSheet.dart
**Path**: `screens/volunteer-screens/ShowBottomSheet.dart`

### Methods
#### `Widget showEditBottomSheet(BuildContext context, Availability availability)`

#### `return EmbeddedDateTimeRangePicker(
    color: Colors.purple.shade50,
    onDateTimeSelected: (date, startTime, endTime)`


---

## File: VolunteerAvaList.dart
**Path**: `screens/volunteer-screens/VolunteerAvaList.dart`

### Class: VolunteerAvaList
**Extends**: `StatelessWidget`

### Methods
#### `Widget build(BuildContext context)`

#### `Widget _buildAvailabilityCard(
      BuildContext context, dynamic availability, bool isLargeScreen)`

#### `Widget _buildEmptyState()`

#### `return showDialog(
      context: context,
      builder: (context)`


---

## File: VolunteerRequests.dart
**Path**: `screens/volunteer-screens/VolunteerRequests.dart`

### Class: VolunteerRequests
**Extends**: `StatefulWidget`

### Class: _VolunteerRequestsState
**Extends**: `State`

### Class: NestedTabController
**Extends**: `StatelessWidget`

### Methods
#### `Widget build(BuildContext context)`

#### `return DefaultTabController(
      length: 2,
      child: Consumer<RequestProvider>(
        builder: (context, reqProvider, _)`

#### `Widget _buildTab(String title, int count)`

#### `Widget build(BuildContext context)`


---

## File: VolunteerDashboard.dart
**Path**: `screens/volunteer-screens/VolunteerDashboard.dart`

### Class: VolunteerDashboard
**Extends**: `StatefulWidget`

### Class: _VolunteerDashboardState
**Extends**: `State`

### Methods
#### `Widget _buildProfileSection(UserProvider userProvider, bool isLargeScreen)`

#### `Widget _buildOngoingAssistance(bool isLargeScreen)`

#### `Widget _buildEmptyTaskContainer(BuildContext context, bool isLargeScreen)`

#### `Widget _buildInfoRow(IconData icon, String text, bool isLargeScreen,
      {int maxLines = 1})`

#### `Widget _buildScheduleSection(bool isLargeScreen)`

#### `Widget build(BuildContext context)`


---

# Directory: theme

## File: text_styles.dart
**Path**: `theme/text_styles.dart`

### Description
text_styles.dart
/// Created at: 2024-11-06 13:51:33
/// Description: Add description and implementation here


---

## File: app_theme.dart
**Path**: `theme/app_theme.dart`

### Description
app_theme.dart
/// Created at: 2024-11-06 13:51:33
/// Description: Add description and implementation here


---

## File: custom_colors.dart
**Path**: `theme/custom_colors.dart`

### Description
custom_colors.dart
/// Created at: 2024-11-06 13:51:33
/// Description: Add description and implementation here


---

# Directory: routes

## File: routes.dart
**Path**: `routes/routes.dart`

### Class: AppRoutes


---

# Directory: services

## File: OrganizationServices.dart
**Path**: `services/OrganizationServices.dart`

### Class: OrganizationServices


---

## File: AuthServices.dart
**Path**: `services/AuthServices.dart`

### Class: AuthService


---

## File: LocalizationService.dart
**Path**: `services/LocalizationService.dart`

### Class: LocalizationService

### Class: _AppLocalizationsDelegate
**Extends**: `LocalizationsDelegate`

### Methods
#### `bool isSupported(Locale locale)`

#### `bool shouldReload(_AppLocalizationsDelegate old)`


---

## File: ApiServices.dart
**Path**: `services/ApiServices.dart`

### Class: ApiServices

### Methods
#### `DioMediaType _getExcelContentType(String fileName)`


---

## File: NotificationService.dart
**Path**: `services/NotificationService.dart`

### Class: NotificationService

### Methods
#### `void _setupNotificationHandlers()`


---

## File: StorageServices.dart
**Path**: `services/StorageServices.dart`

### Description
storage_service.dart
/// Created at: 2024-11-06 13:51:33
/// Description: Add description and implementation here

### Class: StorageService


---

## File: UserServices.dart
**Path**: `services/UserServices.dart`

### Class: UserServices


---

## File: RequestServices.dart
**Path**: `services/RequestServices.dart`

### Class: RequestServices

### Methods
#### `else if (status == 'Completed')`


---

# Directory: widgets/chat

## File: ChatBubble.dart
**Path**: `widgets/chat/ChatBubble.dart`

### Class: ChatBubble
**Extends**: `StatelessWidget`

### Methods
#### `Widget build(BuildContext context)`


---

# Directory: widgets/common

## File: custom_tab.dart
**Path**: `widgets/common/custom_tab.dart`

### Class: CustomTab
**Extends**: `StatelessWidget`

### Methods
#### `Widget build(BuildContext context)`


---

## File: custom_app_bar.dart
**Path**: `widgets/common/custom_app_bar.dart`

### Class: CustomAppBar
**Extends**: `StatelessWidget`
**Implements**: `PreferredSizeWidget`

### Methods
#### `Widget build(BuildContext context)`


---

## File: RequestsLists.dart
**Path**: `widgets/common/RequestsLists.dart`

### Class: RequestCard
**Extends**: `StatefulWidget`

### Class: _RequestCardState
**Extends**: `State`

### Methods
#### `IconData _getRequestTypeIcon(String type)`

#### `Color _getStatusColor(String status)`

#### `String _getStatusMessage(String status)`

#### `Widget build(BuildContext context)`


---

## File: custom_add_new_user_text_field.dart
**Path**: `widgets/common/custom_add_new_user_text_field.dart`

### Methods
#### `Widget buildTextField(
    BuildContext context, String label, TextEditingController controller,
    {bool obscureText = false})`


---

## File: custom_manager_user_card.dart
**Path**: `widgets/common/custom_manager_user_card.dart`

### Class: UserCard
**Extends**: `StatelessWidget`

### Methods
#### `Widget build(BuildContext context)`


---

## File: UserList.dart
**Path**: `widgets/common/UserList.dart`

### Class: UsersListsWidget
**Extends**: `StatelessWidget`

### Methods
#### `Widget build(BuildContext context)`


---

## File: custom_button.dart
**Path**: `widgets/common/custom_button.dart`

### Class: CustomButton
**Extends**: `StatelessWidget`

### Methods
#### `Widget build(BuildContext context)`


---

## File: VolunteerRequestList.dart
**Path**: `widgets/common/VolunteerRequestList.dart`

### Class: VolunteerRequestList
**Extends**: `StatefulWidget`

### Class: _VolunteerRequestListState
**Extends**: `State`

### Methods
#### `Widget build(BuildContext context)`

#### `Widget _buildRequestCard(
    BuildContext context,
    UserRequest request,
    RequestProvider reqProvider,
    UserProvider userProvider,
    bool isLargeScreen,
  )`

#### `Widget _buildStatusBadge(String status)`

#### `Widget _buildInfoRow(IconData icon, String text)`

#### `Widget _buildActionButtons(
    UserRequest request,
    RequestProvider reqProvider,
    UserProvider userProvider,
  )`

#### `return Row(
      children: [
        Expanded(
          child: ElevatedButton(
            onPressed: ()`

#### `Widget _buildInProgressActions(RequestProvider provider, String id)`

#### `Widget _buildEmptyState()`


---

## File: DatePicker.dart
**Path**: `widgets/common/DatePicker.dart`

### Class: EmbeddedDateTimeRangePicker
**Extends**: `StatefulWidget`

### Class: _EmbeddedDateTimeRangePickerState
**Extends**: `State`

### Methods
#### `_EmbeddedDateTimeRangePickerState createState()`

#### `void initState()`

#### `Widget _buildAddButton()`

#### `Widget build(BuildContext context)`


---

## File: reusable_search_bar.dart
**Path**: `widgets/common/reusable_search_bar.dart`

### Class: SearchBarWidget
**Extends**: `StatefulWidget`

### Class: _SearchBarWidgetState
**Extends**: `State`

### Methods
#### `_SearchBarWidgetState createState()`

#### `void updateSearch(String input)`

#### `Widget build(BuildContext context)`


---

## File: custom_gridItem.dart
**Path**: `widgets/common/custom_gridItem.dart`

### Methods
#### `Widget buildGridItem(BuildContext context, String title, String description,
    Color color, String? imagePath, String route)`

#### `return GestureDetector(
    onTap: ()`


---

## File: custom_Detailsedit_text_field.dart
**Path**: `widgets/common/custom_Detailsedit_text_field.dart`


---
