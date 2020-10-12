# Milestone 10

```
From:           2020-10-01
To:             2020-10-31
```

## Planned work

In the previous milestone we get started with block subsidy, founders reward and funding streams calculations and validations. The majority of the work resulted in the pull request: https://github.com/ZcashFoundation/zebra/pull/1051 . This work was done mainly in cooperation with Zebra team member @teor2345.

The  mentioned work is a framework to do further validations, but it is incomplete. Among other validation missing we have that the miner subsidy is half done(need transaction fees), the funding streams are not implemented(however there is room already for them), the founders reward amount is validated but not the addresses, the ZIP-213 rules are not implemented, etc.

This milestone the main goal is to work in this missing validations as they are fundamental pieces of the overall success of the Zebra project. It is recommended to continue the validation by writting an Zebra RFC before implementation.

Items below will be added as we create issues for each of the validations we have missing.

### Zebrad Consesus rules

- [ ] Coinbase rules ZIP-213 - https://github.com/ZcashFoundation/zebra/issues/608
- [ ] Tracking coinbase transactions validation - https://github.com/ZcashFoundation/zebra/issues/801
- [x] Write Block Subsidy RFC.

### Zebrad others

- [x] Move genesis parameters from `zebra-consensus` to `zebra-chain` - https://github.com/ZcashFoundation/zebra/issues/1134
- [x] Review add testing section to RFC template - https://github.com/ZcashFoundation/zebra/pull/1145

### Zcashd

- [x] Simplify `TestBlockValidity` - https://github.com/zcash/zcash/issues/4769
