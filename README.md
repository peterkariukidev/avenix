# Avenix Technologies

Corporate technology consultancy website built with Next.js 16, React 19 and TypeScript.

## Run locally

1. Install Node.js 22 or later.
2. Run `npm install`.
3. Run `npm run dev`.
4. Copy `.env.example` to `.env.local` and configure the verified business WhatsApp number if available.

## Current status

- Responsive editorial homepage, service catalogue and enquiry/consultation request UI.
- Enquiries currently use browser localStorage and optional WhatsApp handoff. **They are not stored in Neon**.
- Consultation dates are requests, not confirmed availability.
- Consultation prices in the initial form are illustrative and **not approved for publication**.
- No payment gateway, admin authentication, or customer database is active.
- External Unsplash photos are illustrative; they do not depict Avenix staff or premises.

## Deployment plan

Cloudflare hosting and Neon Postgres are planned, **not yet configured or deployed**. This source is the earlier Avenix website version, not an exact copy of the later Vercel preview. A Cloudflare-compatible Next.js adapter/build configuration and secure backend API must be added and tested before production deployment.

Never commit database passwords, Neon connection strings or other secrets to this public repository.
