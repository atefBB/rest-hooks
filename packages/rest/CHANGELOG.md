# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

### [0.6.1](https://github.com/coinbase/rest-hooks/compare/@rest-hooks/rest@0.6.0...@rest-hooks/rest@0.6.1) (2021-01-19)


### 💅 Enhancement

* Widen RestFetch types to make overriding not break ([#479](https://github.com/coinbase/rest-hooks/issues/479)) ([2bccf12](https://github.com/coinbase/rest-hooks/commit/2bccf12f7892ccbc1d342bd529b3659c2935fb71))


### 📝 Documentation

* Update nested response docs with behaviors of rest package ([#471](https://github.com/coinbase/rest-hooks/issues/471)) ([04fe9b3](https://github.com/coinbase/rest-hooks/commit/04fe9b390e4e097605a96f268168d8918c4948df))



## 0.6.0 (2021-01-15)

* feat: Resources can have nested entities (#469) ([4eeeaae](https://github.com/coinbase/rest-hooks/commit/4eeeaae)), closes [#469](https://github.com/coinbase/rest-hooks/issues/469)
* enhance: Remove Readonly on Resource endpoint schemas (#468) ([0b98987](https://github.com/coinbase/rest-hooks/commit/0b98987)), closes [#468](https://github.com/coinbase/rest-hooks/issues/468)


### BREAKING CHANGE

* Resources will resolve with any nested
entities from their schemas, rather than the `pk` of those
entities




## <small>0.5.1 (2021-01-06)</small>

* pkg: Use @babel/runtime @ 7.12 ([e631f6a](https://github.com/coinbase/rest-hooks/commit/e631f6a))





## 0.5.0 (2020-12-08)

* feat: Add RestEndpoint type (#427) ([dc47667](https://github.com/coinbase/rest-hooks/commit/dc47667)), closes [#427](https://github.com/coinbase/rest-hooks/issues/427)





## <small>0.4.1 (2020-09-08)</small>

* fix: TypeScript 4 compatibility (#406) ([5d82e24](https://github.com/coinbase/rest-hooks/commit/5d82e24)), closes [#406](https://github.com/coinbase/rest-hooks/issues/406)





## 0.4.0 (2020-08-09)

* feat: Simple AbortController integration (#392) ([899563d](https://github.com/coinbase/rest-hooks/commit/899563d)), closes [#392](https://github.com/coinbase/rest-hooks/issues/392)
* pkg: Rely on latest endpoint ([801f5e7](https://github.com/coinbase/rest-hooks/commit/801f5e7))





## <small>0.3.1 (2020-08-09)</small>

* enhance: Simplify endpoint memoization and provide new extensions (#391) ([d874d0b](https://github.com/coinbase/rest-hooks/commit/d874d0b)), closes [#391](https://github.com/coinbase/rest-hooks/issues/391)
* fix: Resource endpoint memoization ([744431e](https://github.com/coinbase/rest-hooks/commit/744431e))





## 0.3.0 (2020-08-08)

* enhance: Memoize Resource endpoints (#390) ([67bc90f](https://github.com/coinbase/rest-hooks/commit/67bc90f)), closes [#390](https://github.com/coinbase/rest-hooks/issues/390)
* internal: Test using endpoints directly (#389) ([bb0e8fd](https://github.com/coinbase/rest-hooks/commit/bb0e8fd)), closes [#389](https://github.com/coinbase/rest-hooks/issues/389)
* feat: Support extra endpoint members and inheritance (#387) ([6ad5486](https://github.com/coinbase/rest-hooks/commit/6ad5486)), closes [#387](https://github.com/coinbase/rest-hooks/issues/387)





## <small>0.2.1 (2020-08-04)</small>

* fix: Handle entities updated with new indexes (#384) ([2ee3bb6](https://github.com/coinbase/rest-hooks/commit/2ee3bb6)), closes [#384](https://github.com/coinbase/rest-hooks/issues/384)
* fix: Infer useFetcher() has no body when not present in fetch (#385) ([22dd399](https://github.com/coinbase/rest-hooks/commit/22dd399)), closes [#385](https://github.com/coinbase/rest-hooks/issues/385)





## 0.2.0 (2020-07-31)

* feat: Re-export normalizr from 'rest' lib ([4362686](https://github.com/coinbase/rest-hooks/commit/4362686))





## 0.1.0 (2020-07-27)

* enhance: Keep legacy Resource (#376) ([fdd1f7c](https://github.com/coinbase/rest-hooks/commit/fdd1f7c)), closes [#376](https://github.com/coinbase/rest-hooks/issues/376)
* feat: Add @rest-hooks/rest package (#375) ([5e5c125](https://github.com/coinbase/rest-hooks/commit/5e5c125)), closes [#375](https://github.com/coinbase/rest-hooks/issues/375)
