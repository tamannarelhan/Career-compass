README.md
# CareerCompass
A free, volunteer-run chat app where job seekers can ask a recruiter for resume and interview advice.
## What it does
- **Public chat page** (`/`) — visitors can start an anonymous chat and ask career questions.
- **Admin dashboard** (`/admin`) — the recruiter can see incoming conversations and reply directly.
- **Real-time alerts** — the admin dashboard shows a toast and plays a sound when a new conversation starts.
- **No AI auto-replies** — every message is read and answered by you personally.
## Tech stack
- [TanStack Start](https://tanstack.com/start) (React + Vite)
- [Tailwind CSS](https://tailwindcss.com)
- [Lovable Cloud](https://lovable.dev) (Supabase backend, auth, database)
- [shadcn/ui](https://ui.shadcn.com) components
## Local development
1. Install dependencies:
   ```bash
   bun install
   ```
2. Copy environment variables:
   ```bash
   cp .env .env.local
   ```
   Fill in your Supabase URL and publishable key.
3. Run the dev server:
   ```bash
   bun dev
   ```
4. Open [http://localhost:8080](http://localhost:8080).
## Admin access
The first user who signs up is automatically granted the `admin` role and can access `/admin`.
## Deploy
This project is ready to deploy on Lovable. Push to a connected GitHub repo or publish directly from the Lovable editor.
## License
MIT — free to use and modify.
