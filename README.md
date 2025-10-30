# blakeniebrugge.com Source Code

Hi! This is the repository holding all the source code for blakeniebrugge.com. It was written in majority by Claude AI with some human interaction needed here and there. Since this is being hosted as a static web app, the code is really just HTML, CSS, and some minimal Javascipt.

## Structure:

- `.github` has the Continuous Integration/Continuous Deployment (CI/CD) runners for automatic deployment
- `assets` really just holds the favicon at this point.
- `resume` is a nested repo for resume.blakeniebrugge.com:
    - `resume/assets` holds the pictures and documents used on that page
    - `resume/styles` holds the custom stylesheets for the page
- Both the root and `resume` directories have an `index.html` file that serves as the main HTML file for each page.

## External Libraries/Connections:

- Github CI/CD runners for automatic deployment to Azure Web Apps whenever changes are pushed to the `main` branch.
- Bulma (v0.9.4) for some styling

## How to Contribute:

I welcome contributions to the site! To contribute, follow these steps:

1. Fork the repository.
2. Create a new branch for your changes: `git checkout -b feature/your-feature-name`.
3. Make your changes and commit them: `git commit -m "Add your changes"`.
4. Push the changes to your forked repository: `git push origin feature/your-feature-name`.
5. Create a pull request targeting the `main` branch of this repository.

Please ensure your code follows the existing coding standards and conventions.

## License:

This project is licensed under the [MIT License](LICENSE). Feel free to copy and make it your own. Its largely AI generated anyway...

## Current Issues:

None that I know of yet, but there might be some styling issues with odd viewports as I only optimized this for PC and Mobile.

## Future Plans:

Nothing concrete at this time - I would like to see the site evolve into something more useful/functional while staying within the free tier of Azure, or within the resources of my Homelab.

## Contact:

If you have any questions or suggestions, feel free to reach out to me at blake@blakeniebrugge.com.

<br/>

##### README Last Updated:
<sup>October 30, 2025</sup>