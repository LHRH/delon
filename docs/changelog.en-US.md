---
order: 100
title: Change Log
type: Other
---

NG-ALAIN strictly follows [Semantic Versioning 2.0.0](http://semver.org/lang/zh-CN/).

#### Release Schedule

* Weekly release: patch version at the end of every week for routine bugfix (anytime for urgent bugfix).
* Monthly release: minor version at the end of every month for new features.
* Major version release is not included in this schedule for breaking change and new features.

---

### Bug Fixes

* **abc:st:** fix don't interrupt when invalid get data ([#1079](https://github.com/ng-alain/delon/issues/1079)) ([d25996c](https://github.com/ng-alain/delon/commit/d25996c30b36ad2efadd0a564b849f6d5ec4d2d2))

### Performance Improvements

* **abc:st:** optimize reminder text ([#1081](https://github.com/ng-alain/delon/issues/1081)) ([0917357](https://github.com/ng-alain/delon/commit/0917357263917ff64a40337f89ced08e17b342ac))


## [10.1.1](https://github.com/ng-alain/delon/compare/10.1.0...10.1.1) (2020-11-18)

### Bug Fixes

* **abc:count-down:** fix timestamp of number type ([#1075](https://github.com/ng-alain/delon/issues/1075)) ([2a0fae8](https://github.com/ng-alain/delon/commit/2a0fae8169030902752fca0d1bf4d6a2647fd307))
* **form:** fix invalid condition in array ([#1072](https://github.com/ng-alain/delon/issues/1072)) ([45374a9](https://github.com/ng-alain/delon/commit/45374a96ede62f2b36e63c62e98026170406aa6c))
* **form:** fix invalid error style ([#1073](https://github.com/ng-alain/delon/issues/1073)) ([6f7efe7](https://github.com/ng-alain/delon/commit/6f7efe77d8402cffe4c1bc54cf760859f25f8a9f))
* **form:** pref style in small screen ([#1074](https://github.com/ng-alain/delon/issues/1074)) ([680237a](https://github.com/ng-alain/delon/commit/680237a43f993fa24785f77abad61f552661fd42))


# [10.1.0](https://github.com/ng-alain/delon/compare/10.0.3...10.1.0) (2020-11-17)

### Bug Fixes

* **abc:se:** fix invalid error style ([#1067](https://github.com/ng-alain/delon/issues/1067)) ([d8c1cee](https://github.com/ng-alain/delon/commit/d8c1cee92d6505cde2f7e97c08ee7e194723d249))
* **chart:timeline:** can't change line when click legend ([#1068](https://github.com/ng-alain/delon/issues/1068)) ([ba6f9b3](https://github.com/ng-alain/delon/commit/ba6f9b37cba0eb9836467431ed9d8b85166062a0))
* **form:** fix misalignment of inline mode ([#1069](https://github.com/ng-alain/delon/issues/1069)) ([18bb8a8](https://github.com/ng-alain/delon/commit/18bb8a8488facda4757e7ffcfa3022c9b4a4cd61))

### Features

* **abc:se,sv,form:** add `optionalHelpColor` ([#1070](https://github.com/ng-alain/delon/issues/1070)) ([125606c](https://github.com/ng-alain/delon/commit/125606cff431203de7f5f640cb4479ad1a6cc19e))
* **module:sf:date:** add `nzInputReadOnly` property ([#1066](https://github.com/ng-alain/delon/issues/1066)) ([c3b6b87](https://github.com/ng-alain/delon/commit/c3b6b878ec3cbc0f53e30fa1db3cf98b47733259))

## [10.0.3](https://github.com/ng-alain/delon/compare/10.0.2...10.0.3) (2020-11-12)

### Bug Fixes

* **g2:*:** fix view can't be refresh when the data structure changed ([#1063](https://github.com/ng-alain/delon/issues/1063)) ([ff14726](https://github.com/ng-alain/delon/commit/ff14726d3cd28345a079bb5bc38d309292148c99))


## [10.0.2](https://github.com/ng-alain/delon/compare/10.0.1...10.0.2) (2020-10-15)

### Bug Fixes

* **abc:st:** fix http params of `process` method ([#1059](https://github.com/ng-alain/delon/issues/1059)) ([4d2dd0a](https://github.com/ng-alain/delon/commit/4d2dd0aadade43857e875562b26e7052ce54f1ba))


## [10.0.1](https://github.com/ng-alain/delon/compare/10.0.0...10.0.1) (2020-10-02)

### Bug Fixes

* **abc:reuse-tab:** fix invalid this scope of hook events ([#1056](https://github.com/ng-alain/delon/issues/1056)) ([ccddfd9](https://github.com/ng-alain/delon/commit/ccddfd973794d93cb48dd37d8e28e39b121ec822))
* **abc:st:** fix blank area in virtual scroll ([#1055](https://github.com/ng-alain/delon/issues/1055)) ([698f8ac](https://github.com/ng-alain/delon/commit/698f8acf05d994a3555fc575c3178c5c1ed26dba))


# [10.0.0](https://github.com/ng-alain/delon/compare/9.5.5...10.0.0) (2020-09-29)

### Scaffold

* **package.json** use `ng-alain-plugin-theme` instand of `scripts/themes.js` ([#1815](https://github.com/ng-alain/ng-alain/pull/1815)) ([4b7b7e8](https://github.com/ng-alain/ng-alain/commit/4b7b7e87ea610e261c5e827c5fe47b3fedb58a39))
* **default.interceptor.ts** add refresh token by `TokenService.refresh` interface `TokenService.refresh` ([#1788](https://github.com/ng-alain/ng-alain/pull/1788)) ([dcc6149](https://github.com/ng-alain/ng-alain/commit/dcc6149813d2670e42f865415ce03df290251915))

### Bug Fixes

* **abc:reuse-tab:** fix remove tab when reuse is `false` ([#1021](https://github.com/ng-alain/delon/issues/1021)) ([e9f8ead](https://github.com/ng-alain/delon/commit/e9f8eadc6ee085fbcdc37cce184ef948ad0a0897))
* **abc:sidebar-nav:** fix space to avoid scroll ([#1046](https://github.com/ng-alain/delon/issues/1046)) ([7efa241](https://github.com/ng-alain/delon/commit/7efa241b7cc907e7a1725179c202d839464e73bc))
* **abc:st:** fix `width` can't be reset when refresh group columns ([#1027](https://github.com/ng-alain/delon/issues/1027)) ([6f86d8d](https://github.com/ng-alain/delon/commit/6f86d8db8f267fb5e136170ddffb54b7c23fced4))
* **abc:st:** fix reset pi is 1 when confirm filter ([#1020](https://github.com/ng-alain/delon/issues/1020)) ([9fa5de3](https://github.com/ng-alain/delon/commit/9fa5de310a37a500ce0fe7890730d84a22fdc7a5))
* **cli:** fix lose `</div>` in index.html ([#1030](https://github.com/ng-alain/delon/issues/1030)) ([a64f9ef](https://github.com/ng-alain/delon/commit/a64f9efdf73f3a3fea46ae664dca742dba8af18a))
* **form:object:** fix misalignment ([#1037](https://github.com/ng-alain/delon/issues/1037)) ([ed24223](https://github.com/ng-alain/delon/commit/ed24223150a540e2e17bf4560125acf1628e71be))
* **form:radio:** fix can't disabled item ([#1033](https://github.com/ng-alain/delon/issues/1033)) ([94998e1](https://github.com/ng-alain/delon/commit/94998e192119c40fca7ec6405b2a0ac0f222161d))
* **form:widget:string:** fix `autofocus` compatibility ([#1028](https://github.com/ng-alain/delon/issues/1028)) ([3f033c5](https://github.com/ng-alain/delon/commit/3f033c5657d82bf7a5de20fe54ea43e74bb42027))
* **mock:** show params in log ([#1017](https://github.com/ng-alain/delon/issues/1017)) ([3d01921](https://github.com/ng-alain/delon/commit/3d019217aadfca9868f3bf500dbbfd205d7fcb26))
* **theme:http:** fix ingored value handling when params is `HttpParams` type ([#1016](https://github.com/ng-alain/delon/issues/1016)) ([47ff3c3](https://github.com/ng-alain/delon/commit/47ff3c3e0b88a0312d4948e928931037d02addf8))
* **theme:menu:** fix processed logically of `setItem` method ([#1044](https://github.com/ng-alain/delon/issues/1044)) ([120f425](https://github.com/ng-alain/delon/commit/120f425b2e58869a307862950bbe23a687eaeb42))

### Features

* **abc:onboarding:** add onboarding component ([#986](https://github.com/ng-alain/delon/issues/986)) ([fbe46d5](https://github.com/ng-alain/delon/commit/fbe46d5e811b0b4ee9815369e4e6044256a3b40d))
* **abc:down-file:** add `pre` property ([#1032](https://github.com/ng-alain/delon/issues/1032)) ([5538ef8](https://github.com/ng-alain/delon/commit/5538ef8b34e74fe897fdd39272edbb002dbdfb5b))
* **abc:reuse-tab:** add `routeParamMatchMode` property ([#1018](https://github.com/ng-alain/delon/issues/1018)) ([05876ca](https://github.com/ng-alain/delon/commit/05876caa2c64ee5f5f4159e7f8aa68ba5fe50298))
* **abc:reuse-tab:** add lifecycle hook interfaces ([#1047](https://github.com/ng-alain/delon/issues/1047)) ([cba82ea](https://github.com/ng-alain/delon/commit/cba82eae078a5e2d419ea12f8350d76ac76dac06))
* **abc:reuse-tab:** add type of `_onReuseInit` ([#1026](https://github.com/ng-alain/delon/issues/1026)) ([69a04ee](https://github.com/ng-alain/delon/commit/69a04ee16c77ffd42475c25a0db0cc0036c13676))
* **abc:st:** add `className` of button ([#1034](https://github.com/ng-alain/delon/issues/1034)) ([26f60ce](https://github.com/ng-alain/delon/commit/26f60cec7e2a53f5d91c1c6c0a8428567fc39781))
* **abc:st:** add link title when type is link ([#1031](https://github.com/ng-alain/delon/issues/1031)) ([09dcc8d](https://github.com/ng-alain/delon/commit/09dcc8dc5994e1fbdea4b68395a25b00f12cde7e))
* **abc:st:** support resizable headers ([#1049](https://github.com/ng-alain/delon/issues/1049)) ([08de51c](https://github.com/ng-alain/delon/commit/08de51ce6efadd51d9e917a3e039f66bf4bc9c9f))
* **abc:st:** support TemplateRef of render & renderTitle ([#1050](https://github.com/ng-alain/delon/issues/1050)) ([be4f6da](https://github.com/ng-alain/delon/commit/be4f6dab85ccaa06ac9522a64842ef5bdba8f548))
* use `ng-alain-plugin-theme` instand of `scripts/themes.js` ([#1039](https://github.com/ng-alain/delon/issues/1039)) ([6c8e571](https://github.com/ng-alain/delon/commit/6c8e5710259ae13e06f00fef1c99a87773f988aa))
* **abc:st:** support array parameters of mulit sort ([#1015](https://github.com/ng-alain/delon/issues/1015)) ([e1119f5](https://github.com/ng-alain/delon/commit/e1119f5c98e883f8544e9e181464495095f34c14))
* **auth:** add `refresh` event ([#1011](https://github.com/ng-alain/delon/issues/1011)) ([3388e1f](https://github.com/ng-alain/delon/commit/3388e1fb071b99e02f87168ad8223101fe7f9c4d))
* **chart:water-wave:** add `render()` method ([#1014](https://github.com/ng-alain/delon/issues/1014)) ([c3d31c4](https://github.com/ng-alain/delon/commit/c3d31c4a1b6f116e88bb849c88999fccd8ee7f69))
* **cli:** use cnpm to interrupt the installation ([#1036](https://github.com/ng-alain/delon/issues/1036)) ([b2ff9e1](https://github.com/ng-alain/delon/commit/b2ff9e186d570590cd5d1fe79be545b4c2b142d3))

**Remove all deprecation items declared in `9.x`, including the following:**

| Package | Component | Deprecation |
|---|----|-----|
| `@delon/chart` | `tag-cloud` | Date item `x`, `category` |
| `@delon/chart` | `timeline` | Date item `x` |
| `@delon/util` | `lazy` | `LazyResult.loaded` |

## Old Version

All releases notes can be found [here](https://github.com/ng-alain/ng-alain/releases)
