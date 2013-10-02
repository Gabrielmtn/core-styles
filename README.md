# Startup Institute Core Styles
These are the core styles for Startup Institue. Sweet.


##Installation

If you haven't added any styles to your project, run `compass init` from your theme root to build the folder structure.

Once your folder structure for your SASS project is built, add this repo as a submodule.

1. Navigate to the root of your GIT repo.
2. run `git submodule add git@github.com:StartupInstitute/core-styles.git [path to sass folder]/core-styles`. This will add the core styles as a submodule to your current project.
3. Add a line to the beginning of your main SASS file: `@import "core-styles/si-library";`
4. Find your 'config.rb' and add 'require "zen-grids"' to the 2nd line.
5. Compass watch, and you're all set.

Note: To make changes to the submodule repo, you must run git commands from within the submodule directory.

## Deployment to Heroku
If deploying a Git submodule to Heroku that include core-styles, you've gotta deal with authorization stuff by adding your un:password to .gitmodules.  See [the Heroku docs on submodules](https://devcenter.heroku.com/articles/git-submodules#protected-git-submodules).

---
