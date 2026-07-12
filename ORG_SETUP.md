# Create a GitHub Organization (AI Plaza) — then transfer this repo

GitHub **does not allow creating Organizations via API** for normal accounts. Do this once in the browser (~2 minutes).

## 1. Create the Organization

1. Open: https://github.com/account/organizations/new?plan=free  
2. Suggested names (pick one available):
   - `aiplaza`
   - `ai-plaza`
   - `aiplaza-app`
3. Contact email: a company mailbox (e.g. `hello@aiplaza.app`) if you have one  
4. Choose **Free** plan → Create organization  

Keep your personal user (`leohuang921-code`) as Owner.

## 2. Transfer this repository into the Org

1. Open: https://github.com/leohuang921-code/aiplaza-prompts/settings  
2. Scroll to **Danger Zone** → **Transfer ownership**  
3. New owner = your Org name  
4. Confirm  

After transfer the URL becomes:

`https://github.com/<ORG>/aiplaza-prompts`

## 3. Why Org + personal?

| Role | Account |
|------|---------|
| Public brand / repo owner | **Organization** |
| HN / Reddit / X seeding posts | **Personal** profile (links to Org repo) |
| Private SaaS (`ai-hub`) | Stay **private** forever (never make public) |

## 4. What this repo intentionally excludes

- Product source code  
- API keys / `.env`  
- Auth, Stripe, Clerk, Supabase  
- Internal Auto-routing / billing logic  
