<img src="https://s3.eu-central-1.amazonaws.com/fluuu.id/fluuuid.svg" width="200">

## Extended Create-React-App

This project is bootstrapped using Create-react-app, see the original README.md file on the `docs` folder.

This boilerplate uses Typescript, Jest, Storybook, eslint, React and Styled-components on its core.

## Available Scripts

On the project folder in addition to the usual **start**, **build**, **test** and **eject** scripts you have available

### npm run storybook

Starts Storybook. This boilerplate automatically renders all components that have a `.stories.tsx` file.

### npm run build-storybook

Builds Storybook

### npm run lint:fix

Eslint fix the your source files.

### npm run cp

Run this command with the path of the component you want to create, e.g.

```bash
npm run cp ./src/components/Header
```

This command creates the usual React component folder containing:

```bash
- src/components/Component
  - Component.stories.tsx
  - Component.test.tsx
  - Component.tsx
  - index.tsx
```


