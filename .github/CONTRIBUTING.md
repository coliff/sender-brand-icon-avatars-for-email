# Contributing

We welcome your PRs! Especially for the following:

- **Adding a domain for an icon which is not currently included**.
  Example: We currently display the [Adobe brand icon](https://fontawesome.com/icons/adobe?style=brands) for emails from @adobe.com and adobesystems.com.
  If you receive an email from adobe.net for example you could add the following to the CSV
  `email-match,@adobe.net,fa-icon,adobe,end`
  If possible, please include a screenshot to show the email address which you received without the icon.

- **Removing or modifying a rule if an email already has an icon displaying**
  Example: We currently display the [Adobe brand icon](https://fontawesome.com/icons/adobe?style=brands) in place of the avatar for all @adobe.com email addresses.
  If you receive an email from someone at `adobe.net` with a personal avatar already set then the Font Awesome brand icon from this extension may overlay it.
  In this case we could remove the 'catch-all' `@adobe.com` rule and instead just specify `newsletters@adobe.com` or `noreply@adobe.com` to just list the
  system sent emails which don't have avatars which are already set.
  If possible, please include a screenshot to show the issue.
