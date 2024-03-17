# Inc42DevOpsAssignment

Components :
  1. CircleCI pipeline configuration (.circleci/config.yml) to trigger on pushes to the feature branches for Go, Next.js (TypeScript), and PHP(WordPress) by integrating linting and unit testing for each technology and ensuring that the CI pipelines fail if coding standards or tests are not met. Extended the CI/CD pipelines to include deployment stages by setting up automatic deployment to a staging environment for successful builds.

  2. Creating Dockerfiles for each application - Go, Next.js (TypeScript), and the WordPress site inside individual directories

  3. Docker compose file to include services for Go, Next.js, and WordPress and ensuring that the Compose file can be used to spin up the entire extended application stack locally.
