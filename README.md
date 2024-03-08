Soal 1
![image](https://drive.google.com/uc?export=view&id=1pJY0VCpN7BH5jRhANfHXGug0Jv6HFg3w)
In the picture, please browse what is meant by:
> TypeScript
> ESLint
> Tailwind CSS
> App Router
> Import Alias
A. TypeScript:
- TypeScript is a superset of JavaScript that adds static typing to the language. It allows developers to catch mistakes as they develop and provides an excellent tool for code navigation and re-factoring. TypeScript code is exported to standard JavaScript for execution.

B. ESLint:
- ESLint is a static code analysis tool for identifying and fixing problems in JavaScript and TypeScript code. It helps maintain a consistent coding style and encourages best practices. ESLint settings are usually defined in an .eslintrc file.

C. Tailwind CSS: 
- Tailwind CSS is a first-of-its-kind CSS framework that provides low-level functionality classes for direct design in your markup. It enables rapid development by creating methods using small, single-purpose utility classes, eliminating the need to overwrite custom CSS.

D. App Router
- Refers to a routing system in a web application that manages navigation between different views or pages. In a Node.js project, especially when using frameworks like Next.js, there might be a router involved. Next.js, for example, has a built-in router that simplifies client-side navigation and server-side rendering. This allows you to define routes for your application, making it easy to create a multi-page web application.

E. Import Alias:
Import aliases, also known as module aliases, allow you to create shorter or more readable names for your imports. When you customize default import aliases, you are setting up alternative names for modules or directories that you frequently use in your code. This customization can make your code more concise and improve readability. For example, instead of importing a module with a long path, you can set up an alias to simplify the import statement.

Difference between
![image](https://drive.google.com/uc?export=view&id=1ea-gSS_T4GjJGfn1dN9gtVSvJM2NduYy)

Next.js:

What it does: Helps build React web applications.
Key Features:
Makes your website fast with server-side rendering.
Easy navigation using the file system.
Good for dynamic web apps, blogs, and e-commerce.
https://drive.google.com/file/d/1GqfxFJd2pQNCpCccz4yWOjpJsu9WOUCX/view?usp=drive_link
https://drive.google.com/file/d/1g8V3fGGCu_Rq6acWDP5P7su76_sxbZXF/view?usp=drive_link

![image](https://drive.google.com/uc?export=view&id=1GqfxFJd2pQNCpCccz4yWOjpJsu9WOUCX)
![image](https://drive.google.com/uc?export=view&id=1g8V3fGGCu_Rq6acWDP5P7su76_sxbZXF)
Remix:

What it does: A full-stack framework for fast, scalable apps.
Key Features:
Supports server-side rendering and static rendering.
Special focus on separating concerns.
Great for building big, performance-oriented projects.

![image](https://drive.google.com/uc?export=view&id=1qSsdzveCVe3FA8LHUpYPgOB6OzO5JjCL)
![image](https://drive.google.com/uc?export=view&id=1kNuZv12hAWjxefifTGVvrxaNF1I4YD0s)

Gatsby:

What it does: Builds super-fast, optimized websites.
Key Features:
Creates static files for your site.
Uses GraphQL for efficient data fetching.
Perfect for content-driven sites like blogs and documentation.
In short, choose Next.js for dynamic web apps, Remix for big projects with a focus on performance, and Gatsby for fast, content-heavy websites.

![image](https://drive.google.com/uc?export=view&id=1cTD85zvoFmRZczQ-xhVTJZC2GktoBTJp)

Soal 2
*Folders:
A .next:

- This folder is generally used by Next.js, a React framework, to store its build output, including compiled JavaScript code and other artifacts needed for running the application.

B. node_modules:

- This is where npm (Node Package Manager) installs all the project's dependencies. These are external libraries or packages that your project depends on.

C. public:

- This folder is used to store static assets like images, fonts, and other files that should be publicly accessible. These assets can be referenced in your code and will be served directly by the web server.

D. src/app:

- This is likely the main source code directory of your application. It contains the application code, and the /app directory structure is a common convention for organizing source code in Next.js projects.

**Files:

A. .eslintrc.json:

- This file is used to configure ESLint, a tool for identifying and fixing problems in your JavaScript or TypeScript code. It defines coding style rules and helps maintain a consistent codebase.

B. .gitignore:

- This file specifies files and directories that should be ignored by Git when version controlling your project. Commonly included are folders like node_modules (contains dependencies), build artifacts, and other files that don't need to be tracked.

C. next-env.d.ts:

- This TypeScript declaration file is automatically generated by Next.js. It includes type definitions for environment variables used in your Next.js application.

D. next.config.mjs:

- This file is used to configure custom settings for Next.js. It allows you to customize various aspects of the Next.js build process and runtime behavior.

E. package-lock.json:

- This file is generated by npm and provides version information for all the installed packages. It helps ensure that all developers working on the project are using the same versions of dependencies.

F. package.json:

- This file contains metadata about the project and its dependencies. It also includes npm scripts, which are commands that can be run using npm.

G. postcss.config.js:

- PostCSS is a tool for transforming styles with JavaScript plugins. This configuration file is used to specify settings for PostCSS in your project.

H. readme.md:

 This file typically contains documentation for your project. It provides information on how to set up the project, install dependencies, and any other important details for developers working on the project.

I. tailwind.config.ts:

- If you're using Tailwind CSS, this file is its configuration file. It allows you to customize the default settings and define additional styles for your project.

J. tsconfig.json:

- This TypeScript configuration file specifies compiler options and settings for your TypeScript code. It defines how TypeScript should compile your code into JavaScript.


Soal 3 : 
- Hot Module Replacement which is called Fast Refresh inside Next.js is a feature that allows code changes to be applied directly without needing to reload the entire page. When you save changes to a file, development tools detect those changes and dynamically update the code running in the development environment without reloading the entire application. This saves time and allows developers to see the results of changes instantly.
