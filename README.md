# EduMentor AI

EduMentor AI is a Next.js-based study platform designed for competitive exams like JEE, NEET, and Boards. It features chapter-wise question banks, AI-powered tagging, mock test generation, personalized revision planning, formula sheets, and real-time doubt resolution.

## Features

- **Chapter-wise Question Bank:** Organized by subject and chapter, with page references and difficulty tagging.
- **Mock Test Generator:** Create full or partial mock tests based on selected topics and difficulty.
- **AI Tagging Tool:** Automatically classify question difficulty and tag concepts, including past paper identification.
- **Revision Planner:** Generate a personalized, spaced-repetition revision calendar based on your performance.
- **Formula Sheets & Concept Maps:** Quick access to important formulas, derivations, and visual concept maps.
- **AI Doubt Solver:** Get instant answers and explanations for your academic questions, including document/image analysis.
- **Achievements & Progress Tracking:** Unlock badges for study streaks, chapter mastery, and more.

## Getting Started

1. **Install dependencies:**
   ```sh
   npm install
   ```

2. **Run the development server:**
   ```sh
   npm run dev
   ```

3. **Explore the main features:**
   - Home: [`src/app/page.tsx`](src/app/page.tsx)
   - Question Bank: [`src/app/question-bank/page.tsx`](src/app/question-bank/page.tsx)
   - Mock Test: [`src/app/mock-test/page.tsx`](src/app/mock-test/page.tsx)
   - Revision Planner: [`src/app/revision-planner/page.tsx`](src/app/revision-planner/page.tsx)
   - Formula Sheets: [`src/app/formulas/page.tsx`](src/app/formulas/page.tsx)
   - Doubt Solver: [`src/app/doubt-solver/chat-interface.tsx`](src/app/doubt-solver/chat-interface.tsx)
   - Achievements: [`src/app/achievements/page.tsx`](src/app/achievements/page.tsx)
   - Resources: [`src/app/resources/page.tsx`](src/app/resources/page.tsx)

## Data Structure

- **Questions:** Organized in [`src/lib/data/`](src/lib/data/) by chapter (e.g., [`atomic-structure.ts`](src/lib/data/atomic-structure.ts), [`chemical-bonding.ts`](src/lib/data/chemical-bonding.ts), [`mole-concept.ts`](src/lib/data/mole-concept.ts), [`states-of-matter.ts`](src/lib/data/states-of-matter.ts)).
- **AI Flows:** Located in [`src/ai/flows/`](src/ai/flows/), including tagging, revision planning, and doubt resolution.

## Contributing

1. Fork the repo and clone your fork.
2. Create a new branch for your feature or fix.
3. Submit a pull request with a clear description.

## License

MIT

---
For more details, see [docs/blueprint.md](docs/blueprint.md)