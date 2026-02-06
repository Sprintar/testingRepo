<div align="center">Upcoming Release Notes for <b>06 February 2026</b></div>
<div align="center">Release Version: <b>Release version 2</b></div>

This communication is to notify users of NAV AI of enhancements made to the application on a biweekly basis.

**Features Released**
- Generative Interactive Tables
  - LLM-generated tables now render consistently with rich interactivity (search, sort, pagination, column toggles, copy/CSV export), glass-morphic loaders during generation, and clear error states for malformed markup; visual styles from the model are respected while data remains unaltered.

**Additional Enhancements**
- Share worksheets publicly with a secure link.
  - Generate, copy, and manage shareable worksheet links from the Actions menu; owners can view, update, and revoke shares, and public views show messages up to the share time with appropriate error handling if the source is removed.
- Stable agent selection using natural language names.
  - Workflows route to the intended agent by human-readable identifiers, improving repeatability and predictability.
- Clear delivery status for emails sent via agents.
  - When an agent sends email through the function tool, users receive explicit success or failure feedback from the mail server.
- Enforced dataset name length with clear error messages.
  - UI and APIs validate dataset names to prevent chat failures, and the message API surfaces actionable errors instead of generic 400 responses.
- Inline previews for text and markdown attachments in chats.
  - View the content of text files directly in the conversation to quickly confirm context and the correct attachment.

**Bugs Fixed**
- Import API skips selected Nav.AI Tools during agent import
  - Fixed to ensure all selected tools are correctly imported with the agent.
- User can add deleted tags under 'Tag' section of the agent
  - Prevented adding previously deleted tags and aligned tag validation with expected behavior.
- Error Loading Dataset: Internal Server Error is coming to the History section when want to edit attach file to the conversation
  - Resolved internal server errors when editing attachments in conversation history, restored update behavior after removing icon/banner images in Super Agent and Agent, and added validation messages when updating datasets or configurations without any selection.
- Super Agent Conversation History shows NA in Date Created column
  - Corrected date rendering to show the actual creation date.
- Super-agent conversation history DELETION giving 500 error
  - Eliminated 500 errors when deleting conversation history entries; deletions now complete reliably.
- Export icon in chat input need to be changed as it is confusing with worksheet icon
  - Updated the export icon to a distinct visual, reducing confusion with the worksheet icon.