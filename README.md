# Startup Institute Core Styles
These are the core styles for Startup Institue. Sweet.


##Installation

If you haven't added any styles to your project, run `compass init` from your theme root to build the folder structure.

Once your folder structure for your SASS project is built, add this repo as a submodule.

1. Navigate to the root of your GIT repo.
2. run `git submodule add [core styles git url] [path to sass folder]/core-styles`. This will add the core styles as a submodule to your current project.
3. Add a line to the beginning of your main SASS file: `@import "core-styles/si-library";`
4. Compass watch, and you're all set.

> Note: To make changes to the submodule repo, you must run git commands from within the submodule directory.
---
