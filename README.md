A lightweight scheduling tool that automatically distributes total crew hours, generates fair shift rotations, and adapts to staff preferences and culture patterns over time.
## Features
- Random or manual hour assignment (global random distribution)
- Bias-based and rotating shift generation
- PTO and unavailability management per staff member
- Manager vs Crew logic with position rules
- Built-in chatbot to adjust scheduling patterns dynamically
- CSV export for reporting
- LocalStorage learning for patterns
- Frontend: React + Tailwind CSS + Lucide icons
## Setup
1. Clone the repository.
2. Run `npm install` or `yarn`.
3. Start the dev server with `npm run dev` or `yarn dev`.
4. Open `http://localhost:5173` (or similar, depending on your setup).
## Usage
1. Adjust week start and business hours.
2. Choose **Hours Mode**: `Per-employee` or `Global Random`.
3. Input total crew hours (e.g., 275) and distribute randomly.
4. Click **Generate** to build the weekly schedule.
5. Export results as CSV.
6. Optional: Use the chatbot to influence scheduling patterns.
## Future Integrations
- Supabase database persistence for multi-store operations.
- PDF and ICS (calendar) exports.
- Employee self-service PTO requests.
- Auth + role-based access (managers, crew).
## License
MIT License.
