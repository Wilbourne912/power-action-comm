# Power Action Committee — Membership Website

Civil rights nonprofit membership platform for Power To The People Action Committee, based in Georgia.

## Live Site
- **Main Site:** https://wilbourne912.github.io/power-action-comm
- **Member App:** https://power-action-comm.onrender.com

## Member Pages
| Page | URL |
|---|---|
| Sign Up | /signup.html |
| Login | /login.html |
| Dashboard | /dashboard.html |

## Tech Stack
| Layer | Tool |
|---|---|
| Code Storage | GitHub |
| Hosting | Render (auto-deploys on push to main) |
| Auth & Database | Supabase |
| Payments | Stripe |

## Features
- Email/password account creation with email confirmation
- Member login and session management
- Member dashboard with status and dues payment
- Monthly membership dues via Stripe ($10/month)
- Mobile responsive design

## Deployment
Any push to the `main` branch automatically redeploys via Render. No manual steps needed.

## Environment Variables (set in Render)
- `SUPABASE_URL` — Supabase project URL
- `SUPABASE_KEY` — Supabase publishable key

## Status
Built June 2026. Currently in test/demo mode.
Stripe and Supabase are in sandbox — not yet accepting live payments.
