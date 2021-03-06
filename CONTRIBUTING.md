# Contributing

1. Fork the repository
1. Clone the repository: `git clone https://github.com/[YourUserName]/react-picky.git`
1. `yarn install` you can use NPM if you wish but don't commit the `package.lock`
1. Write a failing test
1. Write your fix/optimisation
1. Stage your changes
1. We use conventional commits to help generate change logs and manage releases. For example you're making a bug fix, you commit message would be: `fix: added aria-role to button`. This is enforced by [commitlint](https://commitlint.js.org/#/). For more information regarding conventional commits [see here](https://www.conventionalcommits.org/en/v1.0.0-beta.4/#summary)
1. Create your Pull Request stating a reason for the PR and how your code resolves the issue.

# Running a sandbox

1. Run `yarn prepare-example` - This will install the node_modules for the example project
1. Run `yarn start`. This will start Rollup in watch mode and start the example project

Any changes you make to Picky will be reflected in the sandbox, the typical URL for the example project is http://localhost:1234
