# Github Random Commit Bot

This is a simple bot that generates random commits to a Github repository at regular intervals.

## Usage

1. Clone this repository to your local machine
2. Install the required packages by running `npm install`
3. Create a Github personal access token with the `repo` scope to authenticate the bot.
4. Set the `GITHUB_TOKEN` environment variable to your personal access token.
5. Set the `REPO_OWNER` and `REPO_NAME` environment variables to the owner and name of the Github repository you want to commit to.
6. Run the bot by executing `npm start`

## Configuration

The bot can be configured by modifying the following variables in the code:

- `COMMIT_MESSAGE`: The message to be used for each commit.
- `COMMIT_FILENAME`: The name of the file to be committed.
- `COMMIT_CONTENT`: The content of the file to be committed.
- `COMMIT_FREQUENCY`: The time interval between each commit, in minutes.

## Disclaimer

Please use this bot responsibly and do not make excessive or unnecessary commits to Github repositories. Keep in mind that making excessive or unnecessary commits can negatively impact the performance of Github and is against the [Github community guidelines](https://docs.github.com/en/github/site-policy/github-community-guidelines).
