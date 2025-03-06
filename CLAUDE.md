# Mobile Template 1 - Development Guide

## Commands
- **Run**: `bun mobile start` or `cd packages/mobile && bun start`
- **Build**: `bun mobile ios/android` or `cd packages/mobile && bun ios/android`
- **Test**: `bun mobile test` or `cd packages/mobile && bun test`
- **Lint**: `bun mobile lint` or `cd packages/mobile && bun lint`
- **DB**: `bun mobile db:generate/db:migrate/db:view`

## Code Style
- **TypeScript**: Strict mode with absolute imports (`@/path`)
- **Formatting**: Prettier (80 chars, 2 spaces)
- **React/Components**: React Native best practices, function components
- **Styling**: NativeWind/Tailwind CSS preferred, StyleSheet for complex styles
- **Naming**: PascalCase for components, camelCase for variables/functions
- **Error Handling**: Try/catch with appropriate error messaging
- **Imports**: Group by external, internal, relative importance

## Project Structure
- `src/app` - Expo Router screens
- `src/components` - Reusable UI components
- `src/lib` - Utilities, constants, database