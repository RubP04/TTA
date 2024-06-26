# Hackathon Website Template

![Next.js](https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)
<br/>
![ESLint](https://img.shields.io/badge/ESLint-4B3263?style=for-the-badge&logo=eslint&logoColor=white)
![Prettier](https://img.shields.io/badge/prettier-1A2C34?style=for-the-badge&logo=prettier&logoColor=F7BA3E)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Cypress](https://img.shields.io/badge/-cypress-%23E5E5E5?style=for-the-badge&logo=cypress&logoColor=058a5e)

## Table of Contents

- Table of Contents
- Overview
- Figma Design
- Node.js
- Next.js
- Environment Variables
- Installation
- Running the Project
- Formatting and Linting
- Building the Project
- Contributing
- License

## Overview

The Hackathon Website Template is designed to facilitate the organization and management of hackathons. This project is built with modern web technologies including Next.js, TailwindCSS, and JavaScript.

## Figma

[Hackathon Website Template Figma Design File](https://www.figma.com/file/YsmdMaZuYrkiaiWcB9XY1P/Hackathon-2024-Backend?type=design&node-id=0%3A1&mode=design&t=OkgKqUOkpAYqfjXU-1)

## Node.js

Hackathon Website Template runs on Node.js Version 16.17.0 and higher. Please ensure you have Node.js installed via the [official website](https://nodejs.org/en).

## Next.js

This project is built using [Next.js](https://nextjs.org), a React framework. Next.js is automatically installed when you install all dependencies for this project.

## Environment Variables

The following environment variables are required and must be stored in an `.env` file:

```env
NEXT_PUBLIC_FIREBASE_API_KEY=
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=
NEXT_PUBLIC_FIREBASE_PROJECT_ID=
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=
NEXT_PUBLIC_FIREBASE_APP_ID=
NEXT_PUBLIC_FIREBASE_CLIENT_EMAIL=
NEXT_PUBLIC_FIREBASE_PRIVATE_KEY=
NEXT_PUBLIC_GOOGLE_CLIENT_ID=
NEXT_PUBLIC_GOOGLE_CLIENT_SECRET=
NEXTAUTH_SECRET=
NEXTAUTH_URL=
NEXT_PUBLIC_GOOGLE_CALENDAR_API_KEY=
NEXT_PUBLIC_GOOGLE_CALENDAR_EMAIL=
```

## Commands

### Dependencies

```bash
# Install dependencies
npm i

# Add dependency
npm i <dependency>

# Remove dependency
npm un <dependency>
```

### Running the Website Locally

```bash
# Open a browser at localhost:3000
npm run dev
```

### Formatting Code via Prettier

```bash
# Rewrite code recursively with proper formatting
npm run format

# Show formatting differences recursively
npm run check
```

### Linting Code via Eslint

```bash
npm run eslint
```

### Build the Website

```bash
npm run build
```

## Contributing

Contributions are welcome! Please open issues and submit pull requests for any improvements or bug fixes. For more details, please refer to the contribution guidelines in the repository.

## License

The project currently does not have a license. We suggest adopting the MIT License for its permissive nature, which allows for extensive use and modification of the code.
