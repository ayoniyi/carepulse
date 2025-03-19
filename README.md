# CarePulse

CarePulse is a modern healthcare management platform built with Next.js 14, TypeScript, and Tailwind CSS. It provides a comprehensive solution for managing patient records, appointments, and healthcare administration.

## 🚀 Features

- Modern, responsive UI
- Patient management system
- Administrative dashboard
- Secure authentication and authorization
- Form handling with validation
- File upload capabilities
- Real-time data management
- Error tracking with Sentry integration

## 🛠️ Tech Stack

- **Framework:** Next.js 14
- **Language:** TypeScript
- **Styling:** Tailwind CSS
- **UI Components:** Radix UI
- **Form Handling:** React Hook Form with Zod validation
- **State Management:** React
- **Error Tracking:** Sentry
- **Backend Integration:** Appwrite
- **Date Handling:** React DatePicker
- **Phone Input:** React Phone Number Input
- **File Upload:** React Dropzone

## 📋 Prerequisites

- Node.js 18.x or later
- npm or yarn package manager

## 🔧 Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/carepulse.git
cd carepulse
```

2. Install dependencies:

```bash
npm install
# or
yarn install
```

3. Set up environment variables:
   Create a `.env.local` file in the root directory and add the following variables:

```env
NEXT_PUBLIC_APPWRITE_URL=your_appwrite_url
NEXT_PUBLIC_APPWRITE_PROJECT_ID=your_project_id
NEXT_PUBLIC_SENTRY_DSN=your_sentry_dsn
```

## 🚀 Development

To start the development server:

```bash
npm run dev
# or
yarn dev
```

The application will be available at `http://localhost:3000`

## 🏗️ Building for Production

To create a production build:

```bash
npm run build
# or
yarn build
```

To start the production server:

```bash
npm run start
# or
yarn start
```

## 📁 Project Structure

```
carepulse/
├── app/                    # Next.js app directory
│   ├── admin/             # Admin dashboard routes
│   ├── api/               # API routes
│   ├── patients/          # Patient management routes
│   └── layout.tsx         # Root layout
├── components/            # Reusable UI components
├── lib/                   # Utility functions and shared logic
├── types/                 # TypeScript type definitions
├── constants/             # Application constants
└── public/               # Static assets
```

## 🔍 Code Quality

- ESLint for code linting
- TypeScript for type safety
- Prettier for code formatting

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 Support

For support, please open an issue in the GitHub repository or contact the development team.

---
