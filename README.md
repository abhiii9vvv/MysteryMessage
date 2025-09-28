# MysteryMessage 🕵️‍♂️

A full-stack web application built with the MERN stack that allows users to send and receive anonymous messages. Users can create profiles, manage their message preferences, and interact through anonymous messaging.

## 🚀 Tech Stack

- **Frontend**: Next.js 15, React 19, TypeScript, Tailwind CSS
- **Backend**: Next.js API Routes
- **Database**: MongoDB with Mongoose ODM
- **Validation**: Zod for schema validation
- **Development**: Turbopack for faster builds

## 📁 Current Project Structure

```
src/
├── model/
│   └── user.ts              # User and Message MongoDB models
└── Schemas/
    ├── acceptMessageSchema.ts    # Schema for message acceptance settings
    ├── messagesSchema.ts         # Schema for message validation
    ├── signInSchema.ts           # Schema for user sign-in
    ├── signUpSchema.ts           # Schema for user registration
    └── verifySchema.ts           # Schema for email verification
```

## ✅ Features Implemented

### Backend/Models
- **User Model**: Complete user schema with authentication fields
  - Username, email, password management
  - Email verification system with expiry
  - Message acceptance preferences
  - Embedded messages array
- **Message Model**: Schema for anonymous messages with timestamps
- **Validation Schemas**: Zod schemas for form validation (structure ready)

### Database
- MongoDB integration with Mongoose
- User model with message embedding
- Email validation and verification system
- Unique constraints for username and email

## 🔧 Getting Started

### Prerequisites
- Node.js 18+ 
- MongoDB database
- npm/yarn/pnpm

### Installation

1. Clone the repository:
```bash
git clone https://github.com/abhiii9vvv/MysteryMessage.git
cd MysteryMessage
```

2. Install dependencies:
```bash
npm install
```

3. Set up environment variables:
```bash
# Create .env.local file with:
MONGODB_URI=your_mongodb_connection_string
NEXTAUTH_SECRET=your_nextauth_secret
```

4. Run the development server:
```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to view the application.

## 🚧 Work in Progress

- [ ] Authentication system implementation
- [ ] User registration and login pages
- [ ] Message sending/receiving functionality
- [ ] User dashboard
- [ ] Message management interface
- [ ] Email verification system
- [ ] API routes for CRUD operations

## 📋 Next Steps

1. Implement authentication with NextAuth.js
2. Create user registration and login forms
3. Build message sending/receiving API endpoints
4. Design and implement user interface
5. Add email verification functionality
6. Implement message management features

## 🛠️ Development Scripts

```bash
npm run dev      # Start development server with Turbopack
npm run build    # Build for production with Turbopack
npm run start    # Start production server
npm run lint     # Run ESLint
```

## 📈 Project Progress

- ✅ Project setup and configuration
- ✅ MongoDB models and schemas
- ✅ TypeScript configuration
- ✅ Validation schemas structure
- 🔄 Authentication system (in progress)
- ⏳ Frontend UI/UX
- ⏳ API endpoints
- ⏳ Email verification

## 🤝 Contributing

This project is currently in development. Feel free to contribute by:
1. Forking the repository
2. Creating a feature branch
3. Making your changes
4. Submitting a pull request

## 📄 License

This project is private and currently under development.
