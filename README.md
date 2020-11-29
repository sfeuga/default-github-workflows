# Default Github Workflows

## A github workflows collection to add to your project.

Simply copy some `workflows/*.yml` files in a `.github/workflows/` folder (at the root of your repository) to setup new
 GitHub actions.

Current available workflows:
- [haml.yml](https://raw.githubusercontent.com/sfeuga/default-github-workflows/main/workflows/haml.yml): Run `haml-lint` on you files
- [reek.yml](https://raw.githubusercontent.com/sfeuga/default-github-workflows/main/workflows/reek.yml): Run `reek` on you files _(add a .reek.yml at the root of your repository)_
- [rubocop.yml](https://raw.githubusercontent.com/sfeuga/default-github-workflows/main/workflows/rubocop.yml): Run rubocop on you files _(add .rubocop.yml, .rubocop-md.yml & .rubocop-rails.yml at the root of your
  repository)_. Available Jobs:
  - rubocop (run only rubocop)
  - rubocop-md (run rubocop and rubocop-md)
  - rubocop-performance (run rubocop and rubocop-performance)
  - rubocop-rails (run rubocop and rubocop-rails)
  - rubocop-rake (run rubocop and rubocop-rake)
  - rubocop-rspec (run rubocop and rubocop-rspec)
  - rubocop-thread_safety (run rubocop and rubocop-thread_safety)
