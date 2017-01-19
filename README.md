##Project developed by Mentor Amogh Chitnis ad part of DT Evaluation process##


For the "collaboration and Chat" project I have created a frontend project and a
backend project to seperate the presentation logic from database.
Backend contains following folders which is user to commect to Orcle Database
Config folder contains information and data needed by server for autherisation 
purpose . It has database url id and password details for connecting frontend to database

**/CollaborationBackEndJava/src/main/java/com/niit/collaborationbackend**

	Config
		- AppConfig.java
		- AppInitializer.java
		- ApplicationConfig.java
		- WebSocketCOnfig.java
	
	Controller
		- BlogController.java
		- BulletinController.java
		- ChatController.java
		- EventController.java
		- ForumController.java
		- FriendsController.java
		- HomeController.java
		- JobController.java
		- Message.java
		- OutputMessage.java
		- RoleController.java
		- UserProfileController.java
		- UserTypeController.java			
	DAO
		- BulletinDAO_Impl.java		
		- EventMasterDAO_Impl.java
		- ForumCategoryDAO_Impl.java
		- FriendsDAO_Impl.java
		- JobDAO_Impl.java
		- UserBlogDAO_Impl.java
		- UserForumDAO_Impl.java
		- UserProfileDAO_Impl.java
		- UserRoleDAO_Impl.java
		- UserTypeDAO_Impl.java
		- BulletinDAO.java		
		- EventMasterDAO.java
		- ForumCategoryDAO.java
		- FriendsDAO.java
		- JobDAO.java
		- UserBlogDAO.java
		- UserForumDAO.java
		- UserProfileDAO.java
		- UserRoleDAO.java
		- UserTypeDAO.java
	Model
		- BaseDomain.java	
		- Bulletin.java	
		- ChatForum.java
		- ChatForumComment.java
		- CORSFilter.java		
		- EventMaster.java
		- ForumCategory.java
		- Friends.java
		- Job.java
		- JobApplication.java
		- UserBlog.java
		- UserForum.java
		- UserForumComments.java
		- UserProfile.java
		- UserRole.java
		- UserType.java
##The frontend contains following directory structure##
	/CollaborationFrontEndJava/src/main/webapp
		resources
			- asssets
				---css
				---fonts
				---images
				---js
				---css
		v_blog
			- BlogController.js
			- BlogService.js
			- frmBlog.html
			- frmListBlog.html
			- frmMyBlog.html
			- frmUserBlogAdmin.html
		v_bulletin
			- BulletinController.js
			- BulletinService.js
			- frmBulletin.html
			- frmListBulletin.html
		v_chat
			- ChatController.js
			- ChatService.js
			- frmChat.html
			- frmEnterChat.html
			- lodash.min.js
			- stockjs.min.js
			- stomp.min.js
			- stomp.node.js
		v_common
			- adminview.html
			- common.html
			- CommonController.js
			- commeonService.js
			- userview.html
		v_event
			- EventController.js
			- EventService.js
			- frmEvent.html
			- frmEventList.html
		v_forum
			- ForumController.js
			- ForumService.js
			- frmAddComment.html
			- frmForum.html
			- frmListForum.html
			- frmMyForum.html
			- frmUserForumAdimin.html
		v_friend
			- FriendController.js
			- FriendService.js
			- frmAllUsers.html
			- frmForum.html
			- frmPendingRequest.html
			- frmViewFriends.html
		v_home
			- HomeController.js
			- welcome.html
		v_job
			- frmJob.html
			- frmListJob.html
			- frmViewMyJobApply.html
			- JobController.js
			- JobService.js
		v_user
			- frmLogin.html
			- frmUserListAdmin.html
			- frmUserProfile.html
			- UserProfileController.js
			- UserProfileService.js
		v_userrole
			- frmUserRole.html
			- UserRoleController.js
			- UserRoleService.js
		v_usertype
			- frmUserType.html
			- UserTypeController.js
			- UserTypeService.js
		web-inf
