# WordPress Bolierplate Block Plugin

This repository contains a WordPress block plugin that was generated using WordPress CLI. The plugin includes additional tools for code quality and formatting, such as ESLint, Stylelint, Prettier, and Husky.

## Installation

To install the plugin, follow these steps:

1. Clone the repository to your local machine.
2. Add to your WordPress plugin themes directory.
3. Navigate to the plugin directory.
4. Run `npm install` to install the required dependencies.

## Development Scripts

The following scripts are available in the `package.json` file:

- `build`: Builds the plugin using `wp-scripts`.
- `format`: Formats the code using `wp-scripts format` and `npx stylelint` with auto-fixing.
- `lint:css`: Lints the CSS files using `wp-scripts lint-style`.
- `lint:js`: Lints the JavaScript files using `wp-scripts lint-js`.
- `packages-update`: Updates the packages using `wp-scripts packages-update`.
- `plugin-zip`: Creates a zip file of the plugin using `wp-scripts plugin-zip`.
- `start`: Starts the development server using `wp-scripts start`.
- `prepare`: Installs the Husky pre-commit hook for code quality checks.

To run a script, use the following command:

```
npm run <script-name>
```

For example, to build the plugin, run:

```
npm run build
```

## Contributing

If you would like to contribute to this project, please follow these guidelines:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with descriptive messages.
4. Push your changes to your fork.
5. Submit a pull request to the main repository.

Please ensure that your code adheres to the provided code quality standards and passes the linting checks before submitting a pull request.

## License

This project is licensed under the GNU General Public License (GPL). See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- This plugin was generated with WordPress CLI (WP-CLI).
- ESLint, Stylelint, Prettier, and Husky were integrated for code quality and formatting.
