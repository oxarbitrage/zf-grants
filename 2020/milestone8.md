# Milestone 8

```
From:           2020-08-01
To:             2020-08-31
```

## Planned work

In this milestone the main focus will remain in zebra as past milestone was productive so we want to repeat it. There is also going to be some room to do some zcashd, there are old pull requests that had been reviewed and there are new issues that i could take.

We are also repeating the mechanics of adding issues to the list as they are happening, this is mainly because zebra development is too fast to create a realistic list of issues to work on for an entire month.

### Zebrad

- [x] Change default path in zebrad tests - https://github.com/ZcashFoundation/zebra/issues/806 
- [x] Change default ports in zebrad tests - https://github.com/ZcashFoundation/zebra/issues/807
- [x] Check for panics in zebrad tests - https://github.com/ZcashFoundation/zebra/issues/804
- [x] Review https://github.com/ZcashFoundation/zebra/pull/827
- [x] Review canopy testnet protocol - https://github.com/ZcashFoundation/zebra/pull/810
- [x] Change logs level - https://github.com/ZcashFoundation/zebra/pull/842
- [x] Open bug and review fix - https://github.com/ZcashFoundation/zebra/issues/844 - https://github.com/ZcashFoundation/zebra/pull/848
- [x] Add valid confi acceptance test - https://github.com/ZcashFoundation/zebra/issues/845
- [x] Refactor consensus chain tests to use transcript - https://github.com/ZcashFoundation/zebra/pull/858
- [x] Test for valid output in non server commands - https://github.com/ZcashFoundation/zebra/issues/847
- [x] Convert consensus chain tests to transcript - part of https://github.com/ZcashFoundation/zebra/issues/610
- [x] Add byte metrics - https://github.com/ZcashFoundation/zebra/issues/753
- [x] Create new test for possible port conflict - https://github.com/ZcashFoundation/zebra/issues/807#issuecomment-672439063
- [x] Systemd service file - https://github.com/ZcashFoundation/zebra/issues/562
- [x] Review https://github.com/ZcashFoundation/zebra/pull/933
- [x] Review https://github.com/ZcashFoundation/zebra/pull/903
- [x] Review https://github.com/ZcashFoundation/zebra/pull/935
- [x] Review https://github.com/ZcashFoundation/zebra/pull/931
- [x] Review https://github.com/ZcashFoundation/zebra/pull/939
- [x] Review https://github.com/ZcashFoundation/zebra/pull/940
- [x] Participated in Alianza Blockchain(Spanish) program talking about crypto privacy - https://www.youtube.com/watch?v=qrL4AeVyDvI (Thanks to @elenita for making the contact)
- [x] Review https://github.com/ZcashFoundation/zebra/pull/941
- [x] Set config path to acceptance tests - https://github.com/ZcashFoundation/zebra/issues/943
- [x] add RUST_BACKTRACE to CI tests - https://github.com/ZcashFoundation/zebra/issues/945
- [x] <strike>Support hostnames in listeners - https://github.com/ZcashFoundation/zebra/issues/948</strike> Issue scope reduced by design, rest moved to next milestone.
- [ ] <strike>Show stderr in child functions - https://github.com/ZcashFoundation/zebra/issues/944</strike> Moved to the next milestone

### Zcashd

- [ ] Make changes from code review to wallet state logging PR - https://github.com/zcash/zcash/pull/4423
- [x] Rebase and apply fixes to add shielded balance to getwalletinfo - https://github.com/zcash/zcash/pull/4300
- [x] Apply review suggestion to Tx expiry test - https://github.com/zcash/zcash/pull/4347
- [x] Rebased and applied code review suggestions to Prevent creation of shielded transactions when chain is not synced up - https://github.com/zcash/zcash/pull/4349
- [x] Rebase https://github.com/zcash/zcash/pull/4350
- [x] Rebase GetFilteredNotes refactor - https://github.com/zcash/zcash/pull/4399
