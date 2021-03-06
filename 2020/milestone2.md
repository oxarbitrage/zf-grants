# Milestone 2

```
From:           2020-02-01
To:             2020-02-29
```

## Planned work

Code cleanup, small bug fixes, bitcoin updates.

### Week 1

- [x] Fix test case https://github.com/zcash/zcash/issues/2986 

- [x] Research and implement https://github.com/zcash/zcash/issues/3083

- [x] Create a patch and apply to all related methods. https://github.com/zcash/zcash/issues/3118

- [x] Review https://github.com/zcash/zcash/pull/4320

- [x] Review https://github.com/zcash/zcash/pull/4324

### Week 2

- [x] https://github.com/zcash/zcash/issues/3996 . Group together code and discussions of different implementations, create PR with it.

- [x] Port option to change log filename and location from bitcoin, solving issue https://github.com/zcash/zcash/issues/3740

- [ ] <strike>Remove dead code https://github.com/zcash/zcash/issues/2447</strike>

- [ ] <strike>Implement -lightwalletd experimental feature https://github.com/zcash/zcash/issues/4326</strike> Moved to Milestone 3

### Week 3

Code duplication refactors:

- [x] Research and implement solution to reduce duplication: https://github.com/zcash/zcash/issues/3344

- [ ] <strike>Remove code duplication if possible: https://github.com/zcash/zcash/issues/2961</strike>

- [ ] <strike>Remove code duplication https://github.com/zcash/zcash/issues/3121</strike>

- [x] Remove debug noise from gtests: https://github.com/zcash/zcash/issues/4286

- [x] Add null check to std:feof: https://github.com/zcash/zcash/issues/2880

- [x] Add wrapper functions: https://github.com/zcash/zcash/issues/3235

- [x] Change tuples to classes: https://github.com/zcash/zcash/issues/1361

- [x] Review notes: https://github.com/zcash/zcash/pull/4366 

- [x] Review address refactor: https://github.com/zcash/zcash/pull/4362  

### Week 4

- [x] Isolate bitcoin https://github.com/bitcoin/bitcoin/pull/6057 from https://github.com/zcash/zcash/pull/2225 to fix https://github.com/zcash/zcash/issues/4080 . Create PR that should be easier to review and faster to merge.

- [x] PR for zcashd and create first PR to librustzcash: https://github.com/zcash/zcash/issues/3446 

- [x] Review all rpc calls and create pr if needed: https://github.com/zcash/zcash/issues/4085
