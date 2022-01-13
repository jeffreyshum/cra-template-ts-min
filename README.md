# cra-template-ts-min

[![npm Version](https://img.shields.io/npm/v/cra-template-ts-min?style=for-the-badge)](https://www.npmjs.com/package/cra-template-ts-min)

[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Prettier](https://img.shields.io/badge/prettier-1A2C34?style=for-the-badge&logo=prettier&logoColor=F7BA3E)](https://prettier.io/)

An Opinionated Directory Structure For React Using TypeScript.

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
