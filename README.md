# The Wild Oasis: Staff Management Dashboard

An internal application for hotel staff to handle bookings, cabins and guest check-ins. Built while learning React and Supabase.

## What This Project Does

- Dashboard displaying daily statistics including sales, occupancy rates, and stay durations.
- Complete booking management system allowing staff to check guests in, check guests out, or delete bookings.
- Cabin management features for creating, editing, duplicating, or removing cabin records with image uploads.
- Guest check-in workflow with optional breakfast add-ons and payment confirmations.
- Dark mode and light mode theme toggle for custom user preference.
- User management for staff account creation and profile updates.

## Tech Stack

- **Frontend**: React.js and Vite
- **Backend & Database**: Supabase (Authentication, PostgreSQL Database, and Storage)
- **State Management**: TanStack React Query (server state caching and updates)
- **Form Handling**: React Hook Form
- **Styling**: Styled Components
- **Charts & Data**: Recharts and Date-fns

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/Bhavyajain14/the-wild-oasis.git
   cd the-wild-oasis
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Copy `.env.example` to `.env` and fill in your Supabase project values:
   ```env
   VITE_SUPABASE_URL=your_supabase_url
   VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
   ```

4. Run the development server:
   ```bash
   npm run dev
   ```

5. Open `http://localhost:5173` in your browser.
