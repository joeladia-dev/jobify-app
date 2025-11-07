💼 Jobify – Job Hunting CRUD App

Jobify is a modern web application designed to help job seekers and recruiters efficiently manage job postings.
It features CRUD operations for jobs, pagination, and query filtering to quickly find or manage job listings. Built with Next.js, Prisma, React, and TailwindCSS, Jobify offers a smooth, responsive, and user-friendly experience.

🚀 Features

📄 CRUD Operations – Create, read, update, and delete job listings

🔍 Query & Filtering – Quickly search jobs by title, company, or type

📊 Pagination – Easily navigate large sets of job data

🎨 Responsive UI – Styled with TailwindCSS and animations

🧩 Reusable Components – Built with Radix UI and Lucide icons

⚡ Data Fetching & Caching – Powered by React Query

🛡️ Form Validation – Using React Hook Form + Zod for safe and flexible forms

🌗 Theme Support – Dark/light mode support via next-themes

📈 Charts & Analytics – Visualize job-related stats using Recharts

🔐 Authentication – Managed by Clerk for secure user login

🧰 Tech Stack
Category	Technologies
Frontend	Next.js 14, React 18, TypeScript
Styling	Tailwind CSS, Tailwind Animate, clsx, class-variance-authority
State & Data	React Query, Axios
Database	Prisma + PostgreSQL (or your preferred DB)
Forms & Validation	React Hook Form, Zod
UI Components	Radix UI, Lucide React
Authentication	Clerk
Charts	Recharts
⚙️ Installation & Setup

Clone the repository

git clone https://github.com/yourusername/jobify.git
cd jobify


Install dependencies

npm install


Set up environment variables

Create a .env file in the root directory and add the following:

DATABASE_URL=your_database_connection_string
CLERK_FRONTEND_API=your_clerk_frontend_api
CLERK_API_KEY=your_clerk_api_key


Set up the database

npx prisma generate
npx prisma migrate dev


Run the development server

npm run dev


Build for production

npm run build
npm run start

📁 Project Structure
jobify/
├── prisma/               # Prisma schema and migrations
├── src/
│   ├── components/       # Reusable UI components
│   ├── features/         # Business logic & React Query hooks
│   ├── pages/            # Next.js pages
│   ├── store/            # (Optional) global state
│   ├── utils/            # Helper functions
│   └── App.tsx / main.tsx
├── public/               # Static assets
├── package.json
├── tailwind.config.js
├── tsconfig.json
└── next.config.js

🧾 Scripts
Command	Description
npm run dev	Start local development server
npm run build	Build for production
npm run start	Start production server
npm run lint	Run ESLint checks
📜 License

This project is licensed under the MIT License.
See the LICENSE
 file for details.

💡 Acknowledgements

Next.js

Prisma

Tailwind CSS

React Query

Clerk

Radix UI