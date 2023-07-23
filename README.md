# blakeniebrugge.com Source Code

Hi! This is the repository holding all the source code for blakeniebrugge.com. As of right now, the website is a simple HTML/CSS setup (with a sprinkle of JavaScript in the resume index HTML file).

## Structure:

- `.github` has the Continuous Integration/Continuous Deployment (CI/CD) runners for automatic deployment
- `assets` has the background picture for the main page
- `resume` is a nested repo for resume.blakeniebrugge.com:
    - `resume/assets` holds the pictures used on that page
    - `resume/styles` holds the custom stylesheets for the page
- Both the root and `resume` directories have an `index.html` file that serves as the main HTML file for each page.

## External Libraries/Connections:

- Github CI/CD runners for automatic deployment to Azure Web Apps whenever changes are pushed to the `main` branch.
- Bulma (v0.9.4) for some styling
- FontAwesome for Icons

## How to Contribute:

I welcome contributions to the site! To contribute, follow these steps:

1. Fork the repository.
2. Create a new branch for your changes: `git checkout -b feature/your-feature-name`.
3. Make your changes and commit them: `git commit -m "Add your changes"`.
4. Push the changes to your forked repository: `git push origin feature/your-feature-name`.
5. Create a pull request targeting the `main` branch of this repository.

Please ensure your code follows the existing coding standards and conventions.

## License:

This project is licensed under the [MIT License](LICENSE).

## Current Issues:

None that I know of yet, but there might be some styling issues with odd viewports as I only optimized this for PC and Mobile.

## Future Plans:

Nothing concrete at the time of writing - I would like to see the site evolve into something more useful/functional while staying within the free tier of Azure.

## Contact:

If you have any questions or suggestions, feel free to reach out to me at blake@blakeniebrugge.com.



