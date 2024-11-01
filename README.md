# Project1

# Mumbai GitHub User Analysis

- This dataset was created by scraping GitHub users in Mumbai with over 50 followers using the GitHub API.
- Interesting finding: The majority of developers seem to prefer Python and JavaScript in their repositories.
- Recommendation: Developers could enhance visibility by adding documentation to each repository.

## Files Included

- **users.csv**: Contains information about GitHub users in Mumbai with over 50 followers, such as name, company, bio, and public repository count.
- **repositories.csv**: Contains up to 500 of each user's most recent public repositories with details like star count, language, and license.

## How to Use the Code

The Python script in this repository fetches user and repository data using the GitHub API. To use the code:
1. Obtain a GitHub API token and add it to the `GITHUB_TOKEN` variable in the script.
2. Run the script to generate `users.csv` and `repositories.csv`.
