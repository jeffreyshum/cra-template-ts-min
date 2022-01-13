# cra-template-ts-min

# Usage

To use this template, append `--template ts-min` to `create-react-app` command.

```sh
npx create-react-app my-app --template ts-min

# or

yarn create react-app my-app --template ts-min
```

# Directory Structure

Changes made from `create-react-app`, along with some suggested directory guidelines.

```
.
├───public
│   └───index.html # Reduced Unnecessary HTML
│
├───src
│   ├───assets
│   │   └─── # Assets Go Here
│   │
│   ├───components
│   │   ├─── # React Components Go Here
│   │   └─── # Components Should Have Independent Sub-Directories Where Applicable (If Using Locally Scoped CSS)
│   │
│   ├───styles
│   │   ├──── # Global Imported CSS Files Should Go Here. Locally Scoped CSS Should Be In Their Respective Component Directory
│   │   └───globals.css # Application Default Global CSS
│   │
│   └───index.tsx # Entry Point File
│
├───.prettierrc  # Prettier Settings. Change This to Your Liking if Desired.
└───tsconfig.json # TypeScript Config Settings. Change This to Your Liking if Desired.
```
