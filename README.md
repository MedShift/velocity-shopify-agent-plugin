# Velocity for Shopify

Manage sales reps, teams, customer ownership, and commissions in
[Velocity](https://apps.shopify.com/velocity-commission-maps) for your Shopify store.

Velocity is a Shopify app for B2B brands that sell through sales reps: manufacturers, distributors, and wholesalers
whose field and inside reps manage accounts and place orders. Velocity calculates commission on every order. It pays
reps by account ownership or by territory, and pays each manager above them on the team.

## Install

Find **Velocity for Shopify** in the Claude directory or the ChatGPT plugin directory. For other MCP clients, see the
[setup guide](https://api-docs.velocity.shop/guides/velocity-mcp).

## What you can do

- **Reps**: add, update, enable, or disable reps.
- **Rep Portal access**: give reps a portal login, change what they can see, or remove access.
- **Teams**: get the rep and manager structure of each team.
- **Account ownership**: assign Shopify customers, companies, and locations to reps.
- **Commissions**: find commissions by rep, order, or date range.

Connect Shopify in the same AI assistant to find customer, company, and order names and IDs.

## Example prompts

- "Give the 5 new reps on the West team Rep Portal access."
- "Which rep owns this company, and who is their manager?"
- "Move all of Alex's accounts to Jordan."
- "Show Jane Smith's commissions for last month."

## Requirements

- The [Velocity Premium plan](https://apps.shopify.com/velocity-commission-maps).
- A staff login for the store in Shopify Admin.

## How it works

This plugin adds one remote MCP server, `https://api.velocity.shop/mcp`. It runs no local code and sends data to no
other destination.

When you connect, Shopify Admin opens so you can sign in, then you approve the connection on the Velocity MCP page.
Each connection belongs to the staff member who approved it. To disconnect, open **MCP** under **Integration Settings**
in Velocity's
[Settings](https://admin.shopify.com/apps/velocity-commission-maps/settings) and select **Revoke**.

Each connection is limited to 60 tool calls per minute.

## Support

- [Documentation](https://api-docs.velocity.shop/guides/velocity-mcp)
- [Contact support](https://docs.medshift.com/velocity-commission-maps/en/)
- [Privacy policy](https://velocity.medshift.com/privacy-policy/)
- [Terms of service](https://velocity.medshift.com/terms-of-service/)
