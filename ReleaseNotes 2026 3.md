<div align="center">Upcoming Release Notes for <b>06 February 2026</b></div>
<div align="center">Release Version: <b>Release version 3</b></div>

This communication is to notify users of NAV AI of enhancements made to the application on a biweekly basis.

**Additional Enhancements**
- Organize worksheets with tags for faster filtering and search.
  - You can add and remove tags on any worksheet you can access; tags are also available via the API in a standard format, including GET /api/v1/tags/ and GET /api/v1/tag/{tag_id}/.
- Delete worksheets from either the worksheet details view or directly within a conversation.
  - Deletion removes the worksheet from the system and clears all references so it no longer appears in related conversations or UI elements.
- Detach worksheets from chats without deleting them.
  - Remove a worksheet’s association with a conversation while keeping the worksheet available elsewhere.
- Tabs are now visually differentiated for quicker navigation.
  - Current Session and Worksheet tabs feature distinct icons and styling to make entity types immediately recognizable.

**Bugs Fixed**
- Attach image on chat section Unknown error message is coming with 500 error code
  - Resolved a failure that caused image attachments in chat to return a 500 error and display an “Unknown error” message.