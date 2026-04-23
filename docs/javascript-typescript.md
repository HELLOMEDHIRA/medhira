# JavaScript/TypeScript Packages

MEDHIRA provides essential JavaScript and TypeScript libraries for various development needs.

## Packages

### n8n

- **n8n-nodes-medhira** - Convert Markdown to PDF inside n8n using Puppeteer

### Expo

- **medhira-expo-persist-secure-store** - Secure storage for Expo apps
- **medhira-rn-expo-json-ui-engine** - JSON-based UI engine for Expo

### React

- **medhira-react-typescript-hooks** - Custom React hooks with full TypeScript support

### Utilities

- **medhira-ajv-utils** - Ajv validation utilities
- **medhira-concurrency-utils** - Async concurrency utilities
- **medhira-eslint-rules** - Custom ESLint rules
- **medhira-jst-functions** - JavaScript utility functions
- **medhira-mongoose-utils** - Mongoose database utilities
- **medhira-otp-utils** - OTP generation and validation

## Installation

```bash
# npm
npm install <package-name>

# yarn
yarn add <package-name>

# pnpm
pnpm add <package-name>
```

### n8n Community Node Installation

```bash
# Docker
docker exec -it n8n sh
mkdir -p ~/.n8n/nodes && cd ~/.n8n/nodes
npm install n8n-nodes-medhira
docker restart n8n

# npx n8n / Global
mkdir -p ~/.n8n/nodes && cd ~/.n8n/nodes
npm install n8n-nodes-medhira
npx n8n
```

## More Information

- [GitHub](https://github.com/HELLOMEDHIRA)
- [NPM](https://www.npmjs.com/org/medhira)