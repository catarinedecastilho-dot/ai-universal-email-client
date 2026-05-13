# Agents, Skills, and Hooks

## Agents
- **InboxManager**: Orchestrates the unified inbox and account switching.
- **ContentAnalyst**: Runs summaries and sentiment analysis.
- **ResponseGenerator**: Crafts drafts based on thread history.

## Skills & Hooks
- `useEmailSync`: Hook for real-time IMAP/O365 synchronization.
- `aiSummarize`: Skill to compress long threads into 2-3 sentences.
- `priorityScoring`: Logic to flag urgent emails based on sender and keywords.
