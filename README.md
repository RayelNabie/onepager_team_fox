# Team Fox

Welcome to the official repository for **Team Fox**. This project is being developed during the interdisciplinary Semester 6 to showcase our team's progress, vision, and collective expertise in a professional and accessible way.

## Contents

- [What is this?](#what-is-this)
- [Getting Started](#getting-started)
- [Requirements](#requirements)
- [Install](#install)
- [Usage](#usage)

- [Technical Implementation](#technical-implementation)
- [Used Technologies](#used-technologies)
- [CI/CD Workflow](#cicd-workflow)

- [License](#license)

## What is this?

This onepager serves as the digital business card for our Sem6 project. It is designed to give partners and examiners immediate insight into our team structure and progress.

## Getting Started

### Requirements

- **Node.js**: Please refer to the `.nvmrc` file for the exact version.
- **pnpm**: We use `pnpm` as our package manager for its speed and reliable lockfile management.

### Install

Clone the repository and install the necessary dependencies:

```bash
git clone https://github.com/RayelNabie/onepager_team_fox.git
cd onepager_team_fox
pnpm install

```

### Usage

Run the development server locally:

```bash
pnpm dev

```

Create a production-ready build:

```bash
pnpm build

```

## Technical Implementation

### Used Technologies

- **Vite**: Our frontend tooling for lightning-fast HMR and optimized bundling.
- **TypeScript**: Providing a type-safe foundation for our scripts.
- **SCSS (Sass)**: Fully **Mobile-First** architecture following the 7-1 pattern.
- **BEM Methodology**: Used for clear, modular, and reusable CSS class naming (e.g., `.navbar__logo`).

### CI/CD Workflow

To maintain high code quality throughout the semester, we have implemented an automated pipeline via **GitHub Actions**:

- **Prettier Check**: Every push is automatically checked for consistent code formatting.
- **Automated Environment**: The workflow syncs with our local development environment by reading the Node version directly from `.nvmrc`.

## License

This project is licensed under the [MIT](https://choosealicense.com/licenses/mit/) License.

---

### What's next?

The README is now fully up to date with your project specs. Since the header and navbar are finished, would you like me to generate the **SCSS for the Team Member Cards** (the orange blocks with the LinkedIn links) next?
