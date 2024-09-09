# A Sass Structure Template + Gulp Task Flow
A Sass starter files/directory structure template with a Gulp task flow for compiling the stylesheets, watching for file changes, and triggering a refresh in the browser.

## Description
This template was created for you to NOT have to:
- Manually run the sass command,
- Manually refresh the browser after applying changes to any file, or
- Create a task flow for the above stated tasks.

The sourcemap is externally loaded in the same directory as the compiled stylesheet.

You may check out more details about the referenced Gulp set-up [here](https://github.com/israelmartins96/gulp).

## Installation and Usage
If you would like to use the template:
\
1. Fork the repository.
2. Create a local clone of your forked repo.
3. The files and directories locations are stored in the `paths` object in the `gulpfile.js`. Edit to match your desired file/directory structure.\
Don't forget to update `paths.projectURL` to match your environment.
4. Navigate to the root folder in the CLI and run `npm install` to install all the project's dependencies.
5. Run the `gulp` command in the CLI to test the successful installation. There should be no errors if the installation is successful.\
\
You may visit the BrowserSync `Local` and `UI` URLs to confirm that it's working as expected.\
The browser tab where the `Local` URL is opened will auto-refresh everytime you make changes to the source files.\
\
Now you can simply write CSS with super powers! :D

## Credits
- [Referenced Gulp task flow](https://github.com/israelmartins96/gulp)
- [Sass Docs](https://sass-lang.com/documentation)
- [Official Gulp repo.](https://github.com/gulpjs/gulp)