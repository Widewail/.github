## Author Checklist

- [ ] I validated this in QA or have noted below why it cannot

## Release Notes

- [ ] Includes a migration
- [ ] Migration is [Zero Downtime](https://docs.gitlab.com/ee/development/database/avoiding_downtime_in_migrations.html)
- [ ] Includes Infrastructure Changes

## Reviewer Checklist

- [ ] Follows [best practices](https://github.com/Widewail/engineering-docs/wiki/BestPractices)
- [ ] Logging is sufficient to monitor correct behavior and diagnose errors
- [ ] No large transaction boundaries
- [ ] Queued messages published outside of transactions (if applicable)
- [ ] API calls happen outside of transactions (if applicable)

**This file is managed by [this template](https://github.com/Widewail/.github/edit/master/pull_request_template.md)**
