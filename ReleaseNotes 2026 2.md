<div align="center">Upcoming Release Notes for <b>06 February 2026</b></div>
<div align="center">Release Version: <b>Release version 2</b></div>

This communication is to notify users of NAV AI of enhancements made to the application on a biweekly basis.
_Please reference the attachment for additional photos of the features and enhancements._

**Features Released**
- Generative Interactive Tables
  - LLM-generated tables now render consistently with a normalized structure and preserve original data while enabling search, sorting, pagination, column visibility, copy, and CSV export. Skeleton loaders improve streaming feedback, malformed tables surface clear errors, and interactivity respects row/col spans; visual styling is allowed within fixed layout guidelines for reliable behavior.

**Additional Enhancements**
- Share worksheets via secure public links.
  - Create and copy shareable links from the Actions menu, retrieve previous shares, and rely on ownership checks and deletion safeguards for controlled access.
- More repeatable workflows with natural-language agent selection.
  - Workflows now route by human-readable agent names instead of database IDs, improving stability and reuse.
- Clear delivery status for emails sent from agents.
  - When sending emails via the function tool, conversations reflect success/failure state so users know the outcome of their request.
- Dataset name validation prevents chat errors.
  - UI and API validations enforce safe name lengths for datasets attached to agents, avoiding Bad Request errors and surfacing clear messages.
- Inline previews for text and markdown attachments.
  - Text files attached in chat display a content preview instead of a generic icon for faster verification of the right file.

**Bugs Fixed**
- Error Loading Dataset: Internal Server Error is coming to the History section when want to edit attach file to the conversation
  - Resolved history errors when editing attached files and fixed update failures after removing agent or super agent images; added missing validation messages when updating datasets, system prompts, visualizations, or starter prompts without selections to prevent silent failures and improve clarity.
- Import API skips selected Nav.AI Tools during agent import
  - Import now reliably includes all selected tools during agent import.
- User can add deleted tags under 'Tag' section of the agent
  - Deleted tags can no longer be re-added; tag integrity is maintained.
- Super Agent Conversation History shows NA in Date Created column
  - Date Created now displays correctly in conversation history.
- Super-agent conversation history DELETION giving 500 error
  - Deleting conversation history no longer triggers server errors.
- Export icon in chat input need to be changed as it is confusing with worksheet icon
  - The export icon has been updated to clearly differentiate it from the worksheet icon.