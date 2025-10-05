<!-- Sync Impact Report
Version change: 1.1.0 → 1.2.0
List of modified principles: N/A
Added sections: N/A
Removed sections: N/A
Templates requiring updates: N/A
Follow-up TODOs: N/A
-->

# VibeCoding Todo Constitution

## Core Principles

### I. User-Centric Design
The app must prioritize user experience, providing an intuitive canvas for visual task organization and natural language input for ease of use. Rationale: Ensures the app is accessible and enjoyable for users without technical barriers.

### II. Natural Language Processing
Every task creation and editing must support natural language input, parsing titles, reminders, and metadata accurately. Rationale: Allows users to create tasks quickly and naturally, improving productivity.

### III. Reminder Accuracy (NON-NEGOTIABLE)
Reminders must be scheduled and triggered precisely at the specified times, with user confirmation for ambiguous inputs. Rationale: Reliability in reminders is critical for user trust and task management.

### IV. Visual Organization
Tasks must be pinnable on a canvas, allowing free-form spatial arrangement and persistence of positions. Rationale: Visual organization helps users manage tasks spatially, leveraging human spatial memory.

### V. Simplicity and Focus
The app must remain simple, avoiding feature creep; start with core functionality and expand based on user needs. Rationale: Prevents complexity that could hinder usability and maintenance.

## Technical Constraints
The app must support web and mobile platforms initially. Authentication via username/password is required for user access. No cross-device sync or sharing required (single-user app). Push notifications are mandatory for reminders. Offline usage should persist items locally. Built using React 18 (with TypeScript) for web and mobile UI, React Native / Expo for mobile app development, Vite for build tool, Tailwind CSS for styling, React Router v6 for routing, local storage for persistence, React Context for state management, Jest + React Testing Library for testing, npm workspaces for monorepo management, and TypeScript for type safety.

## Development Workflow
Follow Test-Driven Development: write tests first, then implement features. Ensure all functional requirements are testable and unambiguous. Use natural language specifications for clarity. Code reviews must verify compliance with principles.

## Governance
Constitution supersedes all other practices. Amendments require documentation, justification, and a migration plan if needed. All PRs/reviews must verify compliance with principles. Complexity must be justified against the Simplicity principle.

**Version**: 1.2.0 | **Ratified**: 2025-10-05 | **Last Amended**: 2025-10-05