# My Text Editor Settings

Includes configurations for ESLint, Stylelint, Prettier, and VSCode user settings for linting in a React environment.

### Notes

For a non-React environment, make the following changes to installed packages:

- Replace `eslint-config-airbnb` with `eslint-config-airbnb-base`
- Remove `eslint-plugin-jsx-a11y`, `eslint-plugin-react`, and `eslint-plugin-react-hooks`

And in `.estlintrc.json`, remove:

- ```
  "ecmaFeatures": {
      "jsx": true
  }
  ```
- ```
  "extends": ["prettier/react"]
  ```
