# Example prompts for the PostHog MCP server

These work as written in Claude, ChatGPT, Cursor, Codex, Gemini CLI and the other clients listed in the README. Anything that changes the account comes back as an approval first.

## Read and report

- Ask Sprites which utm_campaign brought the users who finished onboarding last month.
- With Sprites, show the signup-to-activation funnel for Google Ads visitors versus Meta visitors.
- Have Sprites compare 4-week retention for users from paid search against organic.
- With Sprites, find the Meta ad sets whose visitors never reach the pricing page.

## Change, create and launch

- Use Sprites to check what events our PostHog project actually tracks before we build the report.

## Tips

- Name the campaign, ad set or page in full. Sprites receives only the request, not the earlier chat.
- Say the period ("last 30 days", "this quarter"); your client passes today's date so it resolves correctly.
- Working on several businesses? Say "switch to <business name>" first (`choose_business`).
- To compare channels, ask about them in one request, for example "compare Google and Meta CPA last month".
