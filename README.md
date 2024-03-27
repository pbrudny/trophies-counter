
# Trophies Counter [WIP]
This is a simple Slack Bolt application that demonstrates how to use the Slack Bolt framework to build a Slack app that updates the Home tab for a user when they open your app within Slack.

The main goal for this app is to count the Trophies assigned to the user in Slack messages


## Features

- Initializes a Slack Bolt App with environment variables for bot token and signing secret.
- Updates the Home tab with a welcome message and a button when the app is opened in Slack.
- Count trophy emojis

## Prerequisites

Before you can run this application, you will need:

- A Slack account and a Slack workspace where you have permissions to install apps.
- A Slack app created in your workspace. Follow [Slack's guide](https://api.slack.com/start) to create one if you haven't already.
- The Bot User OAuth Token and Signing Secret from your Slack app's settings page.

## Installation

1. Clone this repository to your local machine.

```bash
git clone pbrudny/trophies-counter
```

2. Navigate to the project directory.

```bash
cd trophies-counter
```

3. Install the dependencies.

```bash
pip install slack_bolt
```

## Configuration

Set the following environment variables in your development environment:

- `SLACK_BOT_TOKEN`: Your Slack app's Bot User OAuth Token.
- `SLACK_SIGNING_SECRET`: Your Slack app's Signing Secret.
- Optionally, `PORT`: The port you want the app to run on (defaults to 3000 if not set).

## Running the App

1. Start the app with the following command:

```bash
python app.py
```

2. Make sure your application is reachable by Slack (you might need to use tools like ngrok to expose your local development environment).

3. Open your Slack workspace and navigate to the app. You should see the Home tab being updated with a welcome message and a button.

## Contributing

Contributions to this project are welcome! Please fork the repository and submit a pull request with your improvements.

## Acknowledgments

- Thanks to the Slack API team for creating the Bolt framework that makes building Slack apps fun and easy.

