# NEXTJS-ShadcnDarkMode

Welcome to the NEXTJS project! This comprehensive guide will walk you through every aspect of this project, including its structure, setup instructions, usage, API endpoints, backend, frontend, contributing guidelines, license information, and how to get in touch for support or inquiries.

## Introduction

This project is a Next.js application that features a theme toggle button, allowing users to switch between light and dark modes. The button is implemented using Shadcn UI components. This project demonstrates the integration of Next.js, TypeScript, and the next-themes library to manage theme changes, alongside the use of Shadcn UI for button styling.

## Features
- **Light/Dark Mode Toggle**: Users can switch between light and dark themes.
- **Shadcn UI Integration**: Custom styled button using Shadcn UI.
- **Responsive Navigation Bar**: Includes navigation links and a theme toggle button.
- **Next.js Server-Side Rendering**: Efficient server-side rendering and static site generation with Next.js.
- **TypeScript**: Ensures type safety throughout the application.
- **Theme Management**: Seamless theme management using next-themes.



## Live Demo

You can try out the live demo of the app [here](https://nextjs-shadcn-dark-mode-ms6n22tcy-nishkarsh25s-projects.vercel.app/).

## Folder Structure

```
.
├── components
│   ├── ToggleMode.tsx
│   ├── Nav.tsx
│   └── ThemeProvider.tsx
├── app
│   ├── page.tsx
│   ├── layout.tsx
│   └── ...
├── public
│   ├── ...
├── styles
│   ├── ...
├── .gitignore
├── README.md
├── package.json
├── tsconfig.json
└── ...

```


## Screenshots

<!-- Include screenshots or GIFs of your app here to give users a visual representation of what your app looks like. -->
<img src="https://github.com/nishkarsh25/NEXTJS-ShadcnDarkMode/blob/master/Screenshots/ss1.png" alt="Screenshot 1" width="1000"> 

<img src="https://github.com/nishkarsh25/NEXTJS-ShadcnDarkMode/blob/master/Screenshots/ss2.png" alt="Screenshot 1" width="1000"> 


## GIF's

<img src="https://github.com/nishkarsh25/NEXTJS-ShadcnDarkMode/blob/master/Screenshots/ss3.gif" alt="Screenshot 1" width="1000"> 


## Technologies Used
- Next.js: A React framework for server-side rendering and static site generation.
- TypeScript: A typed superset of JavaScript that compiles to plain JavaScript.
- Shadcn UI: A component library for building user interfaces.
- next-themes: A theme management library for Next.js applications.
- React: A JavaScript library for building user interfaces.
- Lucide Icons: Icon library used for theme toggle icons (Sun and Moon).


## Getting Started

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

## Prerequisites

Before running the project, ensure you have the following installed:

- [Node.js](https://nodejs.org/en/)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/nishkarsh25/NEXTJS-ShadcnDarkMode.git
   ```
2. Navigate to the project branch:

   ```bash
   git checkout <branch-name>
   ```
   Replace `<branch-name>` with the name of the branch you want to checkout.
   

3. Run the development server:

    ```bash
    npm run dev
    # or
    yarn dev
    # or
    pnpm dev
    # or
    bun dev
    ```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.js`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

## How to Use

### Light/Dark Mode Toggle
- **Description**: Users can switch between light and dark themes to suit their preference.
- **How to Use**: Click the theme toggle button in the navigation bar. The icon will change between a sun (for light mode) and a moon (for dark mode), indicating the current theme.

### Shadcn UI Integration
- **Description**: The project uses Shadcn UI for custom-styled buttons and other UI components.
- **How to Use**: Components from Shadcn UI are pre-configured in the project. The theme toggle button, for instance, is styled using Shadcn UI's button component.

### Responsive Navigation Bar
- **Description**: The navigation bar is responsive and includes links to different sections of the application along with the theme toggle button.
- **How to Use**: Navigate through the application by clicking the links in the navigation bar (e.g., Dashboard, Users, Tickets). The navigation bar will adjust its layout based on the screen size.

### Next.js Server-Side Rendering
- **Description**: Efficient server-side rendering and static site generation are handled by Next.js.
- **How to Use**: No additional steps are required by the user. This feature ensures that the application loads quickly and performs well.

### TypeScript
- **Description**: Ensures type safety throughout the application, reducing bugs and improving developer experience.
- **How to Use**: Developers can write TypeScript code, which will be type-checked during development. TypeScript configuration is already set up in the project.

### Theme Management with next-themes
- **Description**: Seamless theme management is provided by the next-themes library.
- **How to Use**: The theme management is integrated into the ToggleMode component. Users can change themes using the toggle button, and the selected theme is remembered across sessions.




## Contributing

Contributions to this project are highly appreciated! Whether you discover bugs, have feature requests, or wish to contribute improvements, your input is valuable. Here's how you can contribute:

- **Report Issues:** If you encounter any bugs or issues while using MyCalculatorApp, please open an issue on the GitHub repository. Be sure to provide detailed information about the problem and steps to reproduce it.

- **Submit Pull Requests:** If you have enhancements or fixes to propose, feel free to submit a pull request. Contributions that improve the functionality, usability, or performance of this app are welcomed and encouraged.

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. **Fork the Repository**.
2. **Create a New Branch** (`git checkout -b feature/your-feature-name`).
3. **Make Your Changes**.
4. **Commit Your Changes** (`git commit -am 'Add some feature'`).
5. **Push to the Branch** (`git push origin feature/your-feature-name`).
6. **Create a New Pull Request**.

## License

This project is licensed under the [The 3-Clause BSD License](LICENSE).Feel free to explore, modify, and contribute to this project as you see fit. Your feedback and contributions are greatly appreciated! 🚀✨


## Acknowledgments

This project is made possible by the contributions and support of various individuals and communities. Special thanks to:

- **Tailwind CSS Team:** For developing Tailwind CSS, a versatile CSS framework that simplifies web development and enhances user interfaces.
  
- **Open Source Community:** For fostering collaboration, innovation, and the sharing of knowledge, which enriches projects like My Form Validation and makes them accessible to all.



## Credits
This project uses the following open-source technologies:

- [Next.js](https://nextjs.org/): A React framework for server-side rendering and static site generation.
  
- [TypeScript](https://www.typescriptlang.org/): A typed superset of JavaScript that compiles to plain JavaScript.
  
- [Shadcn UI](https://shadcn.dev/): A component library for building user interfaces.
  
- [next-themes](https://github.com/pacocoursey/next-themes): A theme management library for Next.js applications.
  
- [React](https://reactjs.org/): A JavaScript library for building user interfaces.
  
- [Lucide Icons](https://lucide.dev/): Icon library used for theme toggle icons (Sun and Moon).

## Author

- **Nishkarsh Gupta**
  - GitHub: [nishkarsh25](https://github.com/nishkash25)
  - Email: bm21btech11016@gmail.com



