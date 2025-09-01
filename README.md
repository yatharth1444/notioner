# Notioner

Notioner is a note-taking application. It's built with Next.js as a learning exercise.



## About This Project

This project is a fun experiment to create a functional clone of Notion, a popular note-taking and productivity
application. If you're looking to understand how to build complex applications using Next.js, then examining the code of
this project might be a good start.

## Built With

This project is built with the following technologies:

- [Next.js](https://nextjs.org/)
- [@blocknote/core and @blocknote/react](https://blocknote.net/)
- [@clerk/nextjs](https://docs.clerk.dev/)
- [Zustand](https://github.com/pmndrs/zustand)
- [Zod](https://github.com/colinhacks/zod)
- [Tailwind CSS](https://tailwindcss.com/)

For a complete list of the dependencies, refer to the `package.json` file.

## Getting Started

Firstly, you need Node.js and npm(you can use Yarn too) installed in your system. You can download Node.js
from https://nodejs.org/ and npm is included in the Node.js installation.

### Clone the Repository

You can clone this repository using the following command:

```bash
https://github.com/yatharth1444/notioner.git
```

### Installation

Navigate to the project directory and install the dependencies:

```bash
cd notioner
npm install
```

### Environment Variables

To run this project, you will need to add the following environment variables to your .env file:

`CONVEX_DEPLOYMENT` - You can set this value as needed for your Convex deployment.

`NEXT_PUBLIC_CONVEX_URL` - This should match the root URL of your Convex deployment.

`NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY` - Your Clerk publishable key, which you can find in your Clerk dashboard.

`CLERK_SECRET_KEY` - Your Clerk secret key, which you can also find in your Clerk dashboard.

`EDGE_STORE_ACCESS_KEY` and `EDGE_STORE_SECRET_KEY` - Your Edge Store access and secret keys.

### Running Notioner

You can start the development server using:

```bash
npm run dev
```

Then open http://localhost:3000 with your browser to see Notioner working in action.


## License

This project is licensed under the [MIT License](./LICENSE).
