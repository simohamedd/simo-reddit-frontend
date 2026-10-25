# Simo Reddit — Frontend

Angular frontend for **Simo Reddit**, a Reddit-style discussion app. The backend lives in a separate repository (Spring Boot + MySQL).

> Based on [angular-reddit-clone](https://github.com/SaiUpadhyayula/angular-reddit-clone) by Sai Upadhyayula, from the Programming Techie Spring Boot + Angular tutorial. Original commit history is preserved.

## What's changed from the original

- **Works with the Spring Boot 3 backend** — updated API URLs (no trailing slashes; comments/posts-by-user now use query parameters).
- **Rich-text editor fixed** — TinyMCE 5 is bundled locally instead of loaded from Tiny Cloud, where keyless editors are now read-only.
- **New design** — a custom design system (Inter, purple and pink palette, rounded cards) across every page, responsive down to phone width.
- **UX fixes** — newest posts first, working profile and sign-up links, comment dates, "log in to vote/comment" prompts, form errors shown only after submit, and Discard no longer submits the form.
- **Simo Reddit branding** — new logo, favicon, banner and name.

## Running locally

Requires **Node 12** (Angular 9) and the backend running on `http://localhost:8080`.

```bash
npm ci
npx ng serve
```

Open http://localhost:4200.
