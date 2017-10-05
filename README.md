### Usage

Installation:

```
$ bundle install --path vendor/bundle
```

Put `.env` file:

```
SLACK_API_TOKEN=<SLACK_API_TOKEN>
SLACK_CHANNEL=<SLACK_CHANNEL>
SLACK_USER_ID=<SLACK_USER_ID>
```

Post the daily report:

```
$ bundle exec bin/post-daily-report
```
