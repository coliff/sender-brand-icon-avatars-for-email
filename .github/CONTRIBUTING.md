# Contributing

We welcome your PRs! Especially for the following:

- **Adding a domain for an icon which is not currently included**.
  Example: We currently display the [Airbnb brand icon](https://fontawesome.com/icons/airbnb?s=brands) for emails from @airbnb.com.
  If you receive an email from Airbnb from a different domain (e.g. airbnb.net), you could add the following to the CSV:
  `email-match,@airbnb.net,fa-icon,airbnb,end`
  If possible, please include a screenshot to show the email address which you received without the icon.

Please don't add an `@` entry for a domain that gives out personal mailboxes (e.g. `@proton.me`, `@live.com`, `@qq.com`), as every person using that service would get the brand icon. Add the brand's specific sender addresses (e.g. `noreply@github.com`) or its `.` subdomain entry instead.
