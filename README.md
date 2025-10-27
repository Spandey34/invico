Invico

A modern web application built with Next.js, featuring real-time video calls, screen sharing, and recording capabilities. It utilizes a robust tech stack including Stream, Convex, and Clerk for seamless performance and secure authentication.

✨ Highlights

Tech Stack: Next.js, TypeScript, Stream, Convex, Clerk

🚀 Video Calls: Real-time video communication.

🖥️ Screen Sharing: Share your screen during calls.

⚫ Screen Recording: Record your video sessions.

🔒 Authentication & Authorization: Secure user management with Clerk.

🧩 Modern Next.js: Utilizes Server Components, Layouts, and Server Actions.

🔄 Component Architecture: Both Client & Server Components.

🛣️ Routing: Dynamic & Static Routes.

💅 Styling: Beautifully styled with Tailwind CSS & Shadcn.

🛠️ Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

1. Clone the Repository

First, clone the repository to your local machine using git:

git clone [https://github.com/Spandey34/invico.git](https://github.com/Spandey34/invico.git)
cd invico


2. Install Dependencies

Next, install the project dependencies using your preferred package manager:

npm install
# or
yarn install
# or
pnpm install


3. Set up Environment Variables

Create a file named .env.local in the root of your project and add the following environment variables. You will need to get these keys from their respective services (Clerk, Convex, and Stream).

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=

CLERK_SECRET_KEY=

CONVEX_DEPLOYMENT=

NEXT_PUBLIC_CONVEX_URL=

NEXT_PUBLIC_STREAM_API_KEY=

STREAM_SECRET_KEY=


🚀 Run the App

Once you have installed the dependencies and set up your environment variables, you can run the application locally:

npm run dev


Open http://localhost:3000 with your browser to see the result.
