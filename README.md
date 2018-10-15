# Pull request reviews and CODEOWNERS

[Pull request reviews](https://help.github.com/articles/about-pull-request-reviews/) are a GitHub feature that allow you to protect a branch by requiring reviews from an individual or team. [CODEOWNERS](https://help.github.com/articles/about-codeowners/) can be used in combination with pull request reviews to request specific individuals or teams. 

### See it in action

1. Fork this repository.
1. Make a change to a Markdown file in the codebase.
1. Create a pull request against the upstream repository.
1. A pull request review is required from @hectorsector before the PR can be merged. 

### Implement it

1. In your fork, change the file in the `.github` folder titled `CODEOWNERS`. Change the @hectorsector username to your own.
1. Add another workshop participant as a collaborator in your repository. 
1. Navigate to repository Settings > Branches > Branch protection rules > Add rule
1. Select: Apply rule to `master`
1. Select: Require pull request reviews before merging
1. Select: Require reviews from CODEOWNERS
1. Ask your partner workshop participant to make changes to a Markdown file in your repository.
1. You'll be notified that your review is required, Approve or Request Changes.
1. Once approved, as your partner to merge their PR. 
