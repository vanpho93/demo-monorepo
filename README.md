# Development workflow

1. Add commits normally to trunk
2. Run `npm run release` to release all packages with unreleased commits

# Dependencies

1. Nx
2. semantic-release-plus

`semantic-release-plus` analyze unreleasaed commits base on commit prefix and changed files to bump up packages.
