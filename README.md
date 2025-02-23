# Team Showcase for Dragonhack



## Prerequisites

Before you begin, ensure you have the following installed on your local machine:

- [Node.js](https://nodejs.org/) (version 14.x or later)
- npm (usually comes with Node.js)

## Installation

To get this project running on your local machine, follow these steps:

1. Clone the repository:
   \`\`\`bash
   git clone https://github.com/christymanthara/dragonhackentry.git
   cd team-showcase
   \`\`\`

2. Install the dependencies:
   \`\`\`bash
   npm install
   \`\`\`

## Running the Development Server

After the installation is complete, you can start the development server:

\`\`\`bash
npm run dev
\`\`\`

The application should now be running on [http://localhost:3000](http://localhost:3000).

## Project Structure

The main components of this project are:

- \`app/page.js\`: The main page component that renders the TeamShowcase
- \`app/team-showcase.js\`: The TeamShowcase component that displays the team members
- \`components/ui/\`: Contains the shadcn/ui components used in the project

## Customization

To customize the team members displayed in the showcase:

1. Open \`app/team-showcase.js\`
2. Modify the \`teamMembers\` array with your team's information
3. Replace the placeholder images with actual team member photos (place them in the \`public\` directory)

## Deployment

This project is ready to be deployed on Vercel. Simply push your changes to a GitHub repository and connect it to Vercel for automatic deployments.

## Built With

- [Next.js](https://nextjs.org/)
- [React](https://reactjs.org/)
- [shadcn/ui](https://ui.shadcn.com/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Lucide React](https://lucide.dev/)

