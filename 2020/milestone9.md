# Milestone 9

```
From:           2020-09-01
To:             2020-09-30
```

## Planned work

In this milestone the main plan is to implement some zcash consensus rules into zebra. In particular block subsidy, founders reward, coinbase and dev fund. There are several issues open in the zebra repo for this consensus rules that will be enumerated below. Several "smaller" tasks will also be addressed in zebrad and zcashd if possible and they will be enumerated here during the milestone.

### Zebrad Consesus rules

- [ ] Create functions for block subsidy and founders reward - https://github.com/ZcashFoundation/zebra/issues/338
- [ ] Validate block subsidy - https://github.com/ZcashFoundation/zebra/issues/297
- [ ] Coinbase rules ZIP-213 - https://github.com/ZcashFoundation/zebra/issues/608
- [ ] Tracking - https://github.com/ZcashFoundation/zebra/issues/801
- [x] Consensus error enums - https://github.com/ZcashFoundation/zebra/issues/1029

### Zebrad others

- [x] Remove option to read config from current directory - https://github.com/ZcashFoundation/zebra/issues/976
- [x] Rename some old references - https://github.com/ZcashFoundation/zebra/issues/968
- [x] Metrics and Tracing endpoint tests - https://github.com/ZcashFoundation/zebra/issues/995
- [x] Implement `Add` and `Sub` operators for `Height` - https://github.com/ZcashFoundation/zebra/issues/1055
- [x] Opened issue for block tests - https://github.com/ZcashFoundation/zebra/issues/1091 - Approved submitted PR - https://github.com/ZcashFoundation/zebra/pull/1096

### Zcashd

- [x] Refine with more code review the GetFilteredNotes refactor - https://github.com/zcash/zcash/pull/4399 
