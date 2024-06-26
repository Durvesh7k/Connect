# Connect

## Description
Connect is an videocalling , allowing users to conduct video meetings with features similar to Zoom's platform.

## Features
- **User Authentication**: Integrated Clerk for secure user authentication.
- **Video Chatting**: Utilized Stream for seamless video chatting functionality.
- **Screen Recording**: Allows users to record video meetings.
- **Meeting Scheduling**: Provides the ability to schedule meetings for future dates.
- **Screen Sharing**: Enables users to share their screens during video calls.
- **Styling**: Implemented with Tailwind CSS for a modern and responsive UI.
- **Type Safety**: Developed using TypeScript for enhanced code readability and type safety.
- **UI Components**: Used Shadcn UI for reusable UI components, enhancing development efficiency.


## Technologies Used
- **Frontend**:
  - [Next.js](https://nextjs.org/): React framework for building server-side rendered applications.
  - [Tailwind CSS](https://tailwindcss.com/): Utility-first CSS framework for styling.
  - [TypeScript](https://www.typescriptlang.org/): Superset of JavaScript for type safety.
  - [Shadcn UI](https://github.com/shadcn/shadcn-ui): UI component library for React.
- **Authentication**:
  - [Clerk](https://clerk.dev/): User authentication and management platform.
- **Video Chat**:
  - [Stream](https://getstream.io/): API for building scalable video chat applications.

## Screenshots

### Home Page
![Screenshot 2024-04-13 184602](https://github.com/Durvesh7k/Connect/assets/113430857/830e8e04-35d2-4c13-b012-9684e3a3f288)

### Video Chat
![Screenshot 2024-04-13 184705](https://github.com/Durvesh7k/Connect/assets/113430857/be4e6ee4-84aa-42ce-b7a2-ae6b152500ab)

### Authentication
![Screenshot 2024-04-13 184738](https://github.com/Durvesh7k/Connect/assets/113430857/d730cf67-1d06-47d9-93ac-ff99135314c4)

## Getting Started
1. Clone the repository.

```
git clone https://github.com/durvesh7k/connect.git

```
2. Install Dependencies

```
npm Install
```

3. Set up Clerk authentication and Stream API keys.

```
cp .env.example .env

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

NEXT_PUBLIC_STREAM_API_KEY=
```

4. Start the development server.
```
npm run dev
```

## LICENCE
This project is licensed under the MIT License - see the LICENSE file for details.








