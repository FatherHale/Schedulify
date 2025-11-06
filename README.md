# Schedulify – Auto Scheduling MVP (React + Tailwind)
A lightweight scheduling tool that automatically distributes total crew hours, generates fair shift rotations, learns and adapts to staff preferences and culure patterns over time.
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
## Contributing Guide 🤝
We welcome contributions from developers, designers, and operations pros who want to help shape the future of ShiftGen.  
Here’s how you can get involved:
1. **Fork the repo** – Click “Fork” in the top-right corner of this repository.  
2. **Create a branch** – `git checkout -b feature/your-feature-name`.  
3. **Make your changes** – Keep commits focused and descriptive.  
4. **Run tests** – Make sure all tests pass before submitting.  
5. **Submit a Pull Request (PR)** – Include a short explanation of your update and any screenshots or demo notes if applicable.  **Good Pull Requests** clearly describe what was changed, why, and how it was tested.  
If you’re unsure where to start, check the open issues or suggest improvements — feedback and ideas are always appreciated.
> 💡 Tip: Even small fixes like improving readability or documentation are valuable contributions.
## Future Integrations
- Supabase database persistence for multi-store operations.
- PDF and ICS (calendar) exports.
- Employee self-service PTO requests.
- Auth + role-based access (managers, crew).
## Contact
Questions, ideas, or want to collaborate?  
Reach out directly through my Github Profile — I’d love to connect with others building the future of hospitality tech.
## License
MIT License.
