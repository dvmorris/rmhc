# rmhc

## Trello
https://trello.com/c/FPKxbzam/4-plan-out-features-and-make-people-into-groups


## Want to contribute? Follow these steps:

1. Fork the repo (in GitHub's interface)
2. Clone your fork to your machine (`git clone <ssh url from your fork> rmhc`)
3. Make sure [Meteor](https://www.meteor.com/install) is installed. On Mac OS, you can install Meteor with `curl https://install.meteor.com/ | sh`.
4. `cd` into your project folder, and open it with `atom .` or `sublime .` (depending on what editor you are using)
5. Create a feature branch for the feature you are adding, i.e. if I'm adding a map to a screen, I might do `git checkout -b feature/map`. Keep this branch checked out until the feature is complete.
6. Install npm packages with `meteor npm install --save react react-dom param-store lodash react-google-places-component react-addons-pure-render-mixin` 
7. Start your local dev server with `meteor`.
8. Get hacking.
9. When ready to create a pull request: Make your commit messages (i.e. `git add .; git commit -am "Adding a map"; git push ...;` Then go to GitHub, and create a pull request to the upstream repo.
