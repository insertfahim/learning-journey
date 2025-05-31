# 🎓 AI Learning Journey - Intelligent Course Generator

<div align="center">

![AI Course Generator](https://imgur.com/53XKpvr.png)

_Transform any topic into a comprehensive learning course with the power of AI_

🌟 **Featured Project** - An innovative AI-powered educational platform 🌟

[![Next.js](https://img.shields.io/badge/Next.js-13.4-black?style=for-the-badge&logo=next.js)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.1-blue?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org/)
[![OpenAI](https://img.shields.io/badge/OpenAI-GPT--3.5-green?style=for-the-badge&logo=openai)](https://openai.com/)
[![Prisma](https://img.shields.io/badge/Prisma-ORM-2D3748?style=for-the-badge&logo=prisma)](https://prisma.io/)
[![Stripe](https://img.shields.io/badge/Stripe-Payments-635BFF?style=for-the-badge&logo=stripe)](https://stripe.com/)

[🚀 Live Demo](#) • [📖 Documentation](#) • [⭐ Star on GitHub](#)

</div>

## 🌟 Overview

**AI Learning Journey** is a revolutionary platform I built that harnesses the power of artificial intelligence to create personalized, comprehensive learning courses from any topic. Simply input what you want to learn, and the AI will generate a structured course complete with YouTube videos, summaries, and interactive quizzes.

This project demonstrates advanced full-stack development skills, combining modern web technologies with AI integration to create an innovative educational platform.

## 🎥 Project Showcase

<div align="center">

### 🚀 What makes this special?

| Feature                      | Description                                                |
| ---------------------------- | ---------------------------------------------------------- |
| 🤖 **Smart AI Integration**  | Leverages OpenAI GPT-3.5 for intelligent course generation |
| 📱 **Responsive Design**     | Beautiful UI that works on all devices                     |
| ⚡ **Performance Optimized** | Built with Next.js 13 for lightning-fast performance       |
| 🔒 **Enterprise Security**   | Secure authentication and payment processing               |
| 📊 **Analytics Ready**       | Built-in progress tracking and user analytics              |

</div>

### ✨ Key Features

-   🤖 **AI-Powered Course Generation** - Transform any topic into a structured learning path
-   📺 **YouTube Integration** - Automatically curates relevant educational videos
-   📝 **Interactive Quizzes** - AI-generated questions to test your knowledge
-   🎨 **Beautiful UI** - Modern, responsive design with dark/light themes
-   💳 **Subscription Management** - Stripe-powered premium features
-   🔐 **Secure Authentication** - Google OAuth integration
-   📊 **Progress Tracking** - Monitor your learning journey
-   🎯 **Personalized Learning** - Courses tailored to your preferences
-   ⚡ **Real-time Generation** - Courses created in seconds, not hours
-   🌐 **Multi-language Support** - Learn in your preferred language

## 🛠️ Tech Stack

### Frontend

-   **Next.js 13.4** - React framework with App Router
-   **TypeScript** - Type-safe development
-   **Tailwind CSS** - Utility-first styling
-   **Shadcn/ui** - Beautiful component library
-   **Framer Motion** - Smooth animations
-   **React Hook Form** - Form management with Zod validation

### Backend & Database

-   **Prisma ORM** - Type-safe database access
-   **MySQL** - Relational database
-   **NextAuth.js** - Authentication system
-   **tRPC/TanStack Query** - Type-safe API calls

### AI & External Services

-   **OpenAI GPT-3.5** - Course content generation
-   **YouTube Data API** - Video curation
-   **Stripe** - Payment processing
-   **Unsplash API** - Course imagery

### DevOps & Deployment

-   **Docker** - Containerization
-   **DigitalOcean** - Cloud hosting
-   **GitHub Actions** - CI/CD pipeline

## 🏗️ Architecture

```mermaid
graph TB
    A[User Input] --> B[AI Course Generator]
    B --> C[OpenAI API]
    B --> D[YouTube API]
    C --> E[Course Structure]
    D --> F[Video Content]
    E --> G[Database]
    F --> G
    G --> H[Course Dashboard]
    H --> I[Interactive Learning]
    I --> J[Quiz System]
    J --> K[Progress Tracking]
```

## 🚀 Getting Started

### Prerequisites

-   Node.js 18+
-   MySQL database
-   OpenAI API key
-   YouTube Data API key
-   Google OAuth credentials
-   Stripe account (for payments)

### Installation

1. **Clone the repository**

    ```bash
    git clone https://github.com/insertfahim/ai-learning-journey.git
    cd ai-learning-journey
    ```

2. **Install dependencies**

    ```bash
    npm install
    ```

3. **Set up environment variables**

    ```bash
    cp .env.example .env.local
    ```

    Fill in your environment variables:

    ```env
    # Database
    DATABASE_URL="mysql://username:password@localhost:3306/learning_journey"

    # NextAuth
    NEXTAUTH_SECRET="your-secret-key"
    NEXTAUTH_URL="http://localhost:3000"

    # Google OAuth
    GOOGLE_CLIENT_ID="your-google-client-id"
    GOOGLE_CLIENT_SECRET="your-google-client-secret"

    # OpenAI
    OPENAI_API_KEY="your-openai-api-key"

    # YouTube
    YOUTUBE_API_KEY="your-youtube-api-key"

    # Stripe
    STRIPE_API_KEY="your-stripe-secret-key"
    STRIPE_WEBHOOK_SECRET="your-webhook-secret"
    ```

4. **Set up the database**

    ```bash
    npx prisma generate
    npx prisma db push
    ```

5. **Run the development server**
    ```bash
    npm run dev
    ```

Open [http://localhost:3000](http://localhost:3000) to see the application.

## 📱 Usage

### Creating a Course

1. **Navigate to Create Course** - Click "Create Course" in the navigation
2. **Enter Course Details** - Provide a course title and list of units/topics
3. **AI Generation** - The AI processes your input and generates course structure
4. **Review & Confirm** - Review the generated chapters and confirm
5. **Start Learning** - Begin your personalized learning journey

### Course Structure

Each generated course contains:

-   **Units** - Major topic divisions
-   **Chapters** - Specific learning modules within units
-   **Videos** - Curated YouTube content for each chapter
-   **Summaries** - AI-generated chapter summaries
-   **Quizzes** - Interactive questions to test understanding

## 🎯 Core Features

### 🤖 AI Course Generation

The heart of the platform uses OpenAI's GPT-3.5 to:

-   Generate structured course outlines
-   Create chapter summaries
-   Generate quiz questions
-   Suggest learning paths

### 📺 Smart Video Curation

Automatically finds and embeds relevant YouTube videos:

-   Searches for educational content
-   Filters for appropriate duration and quality
-   Embeds videos directly in the learning interface

### 🎯 Interactive Learning

-   **Progress Tracking** - Visual progress indicators
-   **Quiz System** - Multiple-choice questions with instant feedback
-   **Chapter Navigation** - Easy movement between course sections
-   **Responsive Design** - Works on all devices

### 💎 Premium Features

-   **Unlimited Courses** - Create as many courses as you want
-   **Advanced AI Features** - Enhanced course generation
-   **Priority Support** - Get help when you need it
-   **Export Options** - Download course materials

## 🔧 Development

### Project Structure

```
src/
├── app/                 # Next.js 13 App Router
│   ├── api/            # API routes
│   ├── course/         # Course viewing pages
│   ├── create/         # Course creation
│   └── gallery/        # Course gallery
├── components/         # Reusable UI components
├── lib/               # Utility functions and configs
├── validators/        # Zod schemas
└── prisma/           # Database schema
```

### Key Components

-   **CreateCourseForm** - Course creation interface
-   **ConfirmChapters** - Course review and confirmation
-   **ChapterCard** - Individual chapter display
-   **QuizCards** - Interactive quiz system
-   **CourseSideBar** - Course navigation

### API Routes

-   `/api/course/createChapters` - Generate course structure
-   `/api/chapter/getInfo` - Fetch chapter details
-   `/api/auth/` - Authentication endpoints
-   `/api/stripe/` - Payment processing

## 🚀 Deployment

### Docker Deployment

1. **Build the image**

    ```bash
    docker build -t learning-journey .
    ```

2. **Run with docker-compose**
    ```bash
    docker-compose up -d
    ```

### DigitalOcean Deployment

The project includes configuration for deployment on DigitalOcean with:

-   Automated builds
-   SSL certificates
-   Custom domain setup
-   GitHub Actions CI/CD

## 🤝 Contributing

I welcome contributions! Please see the [Contributing Guide](CONTRIBUTING.md) for details.

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Add tests if applicable
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

-   OpenAI for providing the powerful GPT-3.5 API
-   The Next.js team for creating an amazing React framework
-   Vercel for excellent hosting and deployment tools
-   The open-source community for valuable libraries and tools

## 📞 Support

-   📧 Email: faahim06@gmail.com
-   🐛 Issues: [GitHub Issues](https://github.com/insertfahim/ai-learning-journey/issues)

---

<div align="center">

**Built with ❤️ by Fahim**

⭐ Star this repository if you found it helpful!

</div>
