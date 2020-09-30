# Milestone 10

```
From:           2020-10-01
To:             2020-10-31
```

## Planned work

In the previous milestone we get started with block subsidy, founders reward and funding streams calculations and validations. The majority of the work resulted in the(already merged) pull request: https://github.com/ZcashFoundation/zebra/pull/1051 . This work was done in cooperation with Zebra team member @teor.

The  mentioned work is a framework to do further validations, but it is incomplete. Among other validation missing we have that the miner subsidy is half done(need transaction fees), the funding streams are not implemented(however there is room already for them), the founders reward amount is validated but not the addresses, the ZIP-213 rules are not implemented, etc.

This milestone the main goal is to work in this missing validations as they are fundamental pieces of the overall success of the Zebra project.

Items below will be added as we create issues for each of the validations we have missing.

### Zebrad Consesus rules

- [ ] Coinbase rules ZIP-213 - https://github.com/ZcashFoundation/zebra/issues/608
- [ ] Tracking coinbase transactions validation - https://github.com/ZcashFoundation/zebra/issues/801

### Zebrad others
