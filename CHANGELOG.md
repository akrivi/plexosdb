# Changelog

All notable changes to this project will be documented in this file.

## [1.4.0](https://github.com/akrivi/plexosdb/compare/v1.3.0...v1.4.0) (2026-02-09)


### 🚀 Features

* add `list_collections` method to db ([#43](https://github.com/akrivi/plexosdb/issues/43)) ([0ed0f91](https://github.com/akrivi/plexosdb/commit/0ed0f913b7b78b316261525e68f9b2c4f9c3a4a5))
* Add list_collections() method ([#42](https://github.com/akrivi/plexosdb/issues/42)) ([2157a42](https://github.com/akrivi/plexosdb/commit/2157a423d97fd720252f976ae3fbcb09bd7cfda6))
* Add new Class for interacting with Plexos ([#24](https://github.com/akrivi/plexosdb/issues/24)) ([b4cfc1f](https://github.com/akrivi/plexosdb/commit/b4cfc1ff3dd753f43ce284ea822b76aaee33a84b))
* Add time Slice query ([#14](https://github.com/akrivi/plexosdb/issues/14)) ([e64620b](https://github.com/akrivi/plexosdb/commit/e64620bb72501b6a565ce41e07c2ebaa6b762704))
* Adding bulk operations to plexosdb ([#30](https://github.com/akrivi/plexosdb/issues/30)) ([5bd4b4f](https://github.com/akrivi/plexosdb/commit/5bd4b4f502263f9607f4d7818d14331d2990ce18))
* Adding capability to remove object and cascade ([#47](https://github.com/akrivi/plexosdb/issues/47)) ([2812ec9](https://github.com/akrivi/plexosdb/commit/2812ec9ccce43c6c425ecfc8ee864e6a5c34333c))
* Adding capability to rename objects ([#33](https://github.com/akrivi/plexosdb/issues/33)) ([84596e2](https://github.com/akrivi/plexosdb/commit/84596e2bd49d92222d8ac6c1dfae51980e105da9))
* Adding iterate_properties with query instead of multiple functions ([#59](https://github.com/akrivi/plexosdb/issues/59)) ([0776af3](https://github.com/akrivi/plexosdb/commit/0776af3685702191eb48df9dadaa71ec076f0288))
* Adding method `add_datafile_tag` and refactor add_properties/add_properties_from_records ([#69](https://github.com/akrivi/plexosdb/issues/69)) ([1e6e018](https://github.com/akrivi/plexosdb/commit/1e6e01852e46fba89b16120c07d472f4c84f94ab))
* Adding new fixtures for cleaner testing. ([#68](https://github.com/akrivi/plexosdb/issues/68)) ([9062baa](https://github.com/akrivi/plexosdb/commit/9062baab8db1eb611dcb7364e952bbdb898fe36a))
* Adding query date_from and date_to to properties ([#67](https://github.com/akrivi/plexosdb/issues/67)) ([00d533b](https://github.com/akrivi/plexosdb/commit/00d533b4b547822a09984cf59e40738fea330f4a))
* Adding report writing capability ([#29](https://github.com/akrivi/plexosdb/issues/29)) ([0ab9bdd](https://github.com/akrivi/plexosdb/commit/0ab9bdda3ba697535fcf09827dce3c8a7321fea9))
* Adding support for adding attributes ([#27](https://github.com/akrivi/plexosdb/issues/27)) ([8deab88](https://github.com/akrivi/plexosdb/commit/8deab88c5a9d0705a3ee226b4acaf6bc11ccf012))
* Adds datafile text field for Data File object query ([#15](https://github.com/akrivi/plexosdb/issues/15)) ([4ea5263](https://github.com/akrivi/plexosdb/commit/4ea526366732f786da639d0ad976c14c17674d46))
* Consolidate code structure ([#26](https://github.com/akrivi/plexosdb/issues/26)) ([dc0952a](https://github.com/akrivi/plexosdb/commit/dc0952aa9a7f9ce4e1b8071b2f1fe162c06a9e16))
* Enable capability of find enums with spaces and new methods for easy interaction ([#17](https://github.com/akrivi/plexosdb/issues/17)) ([2e01616](https://github.com/akrivi/plexosdb/commit/2e0161688ebe19858db93ad57d8e6f23b7d3d413))
* Making add_from_records more robust ([#85](https://github.com/akrivi/plexosdb/issues/85)) ([827b2dd](https://github.com/akrivi/plexosdb/commit/827b2ddaa24cd5c9531d4f78fab8f4e1cb441ff2))
* New simple query for handling Plexos objects ([#18](https://github.com/akrivi/plexosdb/issues/18)) ([db16280](https://github.com/akrivi/plexosdb/commit/db162806542238df2ae208c5181297ea871f6d82))
* Refactor code for itererate_properties method  ([#35](https://github.com/akrivi/plexosdb/issues/35)) ([f2670cf](https://github.com/akrivi/plexosdb/commit/f2670cff9fa16283212a9100ab2cfe1d61fa2783))
* **scenarios:** Adding scenario manipulation. ([#28](https://github.com/akrivi/plexosdb/issues/28)) ([8ab1a43](https://github.com/akrivi/plexosdb/commit/8ab1a43ce0e766b06056711db0823f0defe452a4))
* updates to PlexosDB to make it compatble with the new R2X-PLEXOS plugin. ([#37](https://github.com/akrivi/plexosdb/issues/37)) ([d132b68](https://github.com/akrivi/plexosdb/commit/d132b682842e9ef1b4e1e5e697ab342f39636691))


### 🐛 Bug Fixes

* `has_property` to correctly check properties by membership_id ([#61](https://github.com/akrivi/plexosdb/issues/61)) ([f2287c9](https://github.com/akrivi/plexosdb/commit/f2287c9cf7a10eadec07ed43eecc114cea6beb8d))
* add formatter and increase test coverage ([538376a](https://github.com/akrivi/plexosdb/commit/538376a6c1a768f925a4232cdebda239e4aef592))
* add missing comment ([545291b](https://github.com/akrivi/plexosdb/commit/545291bfcd52332cab0436c3a31435951a5eaf50))
* Adding new release-please workflow ([#71](https://github.com/akrivi/plexosdb/issues/71)) ([1f8da38](https://github.com/akrivi/plexosdb/commit/1f8da384a9deb3edfa7a343e91999d3d37e07b17))
* allow commit from forked repo ([72a4b84](https://github.com/akrivi/plexosdb/commit/72a4b8493c43f143c42befe86864101fd82453cb))
* disclaimer ([cf14f9e](https://github.com/akrivi/plexosdb/commit/cf14f9eb66405dafe38f37463bb26365853c4e91))
* **get_memberships:** Updated `get_membership` function ([#6](https://github.com/akrivi/plexosdb/issues/6)) ([6335fca](https://github.com/akrivi/plexosdb/commit/6335fcaf43fcc718bc838dd3c8248f013bb7260d))
* get_scenario_id was returning bool ([#23](https://github.com/akrivi/plexosdb/issues/23)) ([f8c6e0a](https://github.com/akrivi/plexosdb/commit/f8c6e0afb954126f098b2a147e7841634f3c818c))
* handle property related attributes on "add_properties_from_records" method ([#78](https://github.com/akrivi/plexosdb/issues/78)) ([1776d2a](https://github.com/akrivi/plexosdb/commit/1776d2a614facef29d5a2a3df1f3a27dd154e359))
* pre-commit on readme ([8b0bac7](https://github.com/akrivi/plexosdb/commit/8b0bac740d16c3cdac6fe2388b9ea58d5abbbeb9))
* readme ([ca7c800](https://github.com/akrivi/plexosdb/commit/ca7c800339d23e98c6194134b4ba2f3aa84c0f2a))
* Removing reference to other package ([674a2a9](https://github.com/akrivi/plexosdb/commit/674a2a930317ef0e5d70e1176295d77fa66fde39))
* revert github token use ([db2c6cf](https://github.com/akrivi/plexosdb/commit/db2c6cf961fe79aa5bf9c45feeae00a770d2cf3f))
* Scenario filtering for scenarios not attached to the model ([#20](https://github.com/akrivi/plexosdb/issues/20)) ([24c1a0b](https://github.com/akrivi/plexosdb/commit/24c1a0ba97c0b3ea0de1a455ac7ea4ea92268937))
* Update battery collection enum naming and add increment to rank for same class enum ([#80](https://github.com/akrivi/plexosdb/issues/80)) ([e247e67](https://github.com/akrivi/plexosdb/commit/e247e6731f05eeef792cf8de09f0123e6f9d2995))


### 📚 Documentation

* add disclaimer ([dd574a2](https://github.com/akrivi/plexosdb/commit/dd574a222285216424c704d5db8e31692700b475))
* Adding bulk operations. ([23cf71b](https://github.com/akrivi/plexosdb/commit/23cf71ba20a6c882a1f8f69bbd4ce5d76460ad09))
* fixing `get_object_membership` example ([#40](https://github.com/akrivi/plexosdb/issues/40)) ([bc2c5d5](https://github.com/akrivi/plexosdb/commit/bc2c5d5180fb6e5e63ecffb1b31352f357457f53))
* updating docs for memberships ([#45](https://github.com/akrivi/plexosdb/issues/45)) ([74f91dc](https://github.com/akrivi/plexosdb/commit/74f91dcbf20c5f5955850d842e45838e2290bc18))


### 🧩 CI

* **actions:** Adding first version of GitHub actions ([#5](https://github.com/akrivi/plexosdb/issues/5)) ([36a9a73](https://github.com/akrivi/plexosdb/commit/36a9a7317b2510dce0f48a2fb6b6a0424871228e))
* **actions:** Fixing GitHub Actions and refactoring API ([#7](https://github.com/akrivi/plexosdb/issues/7)) ([d701510](https://github.com/akrivi/plexosdb/commit/d701510df0d902025568753ae5ff2668434eb5b0))
* Add right license file ([#12](https://github.com/akrivi/plexosdb/issues/12)) ([9185e50](https://github.com/akrivi/plexosdb/commit/9185e508b46e33f88e47d53155d71c4ad38af34d))
* Adding release action ([#25](https://github.com/akrivi/plexosdb/issues/25)) ([979994d](https://github.com/akrivi/plexosdb/commit/979994d7f20742962a42206ff7d99b0d9dd731be))
* Fixing  pre-commit errors and adding more workflows ([#9](https://github.com/akrivi/plexosdb/issues/9)) ([27c2d65](https://github.com/akrivi/plexosdb/commit/27c2d655bcc647e80ec6caadf046885345f24b2c))
* Fixing actions and coverage ([#11](https://github.com/akrivi/plexosdb/issues/11)) ([b432c99](https://github.com/akrivi/plexosdb/commit/b432c99b2cc5d825b3caaaf307dbcce7c7d7042f))
* Initial test PR ([#10](https://github.com/akrivi/plexosdb/issues/10)) ([c5c0993](https://github.com/akrivi/plexosdb/commit/c5c0993692334dcb2aad101cf4a336f200fc917b))
* removing trailwhitespace ([5ff0f54](https://github.com/akrivi/plexosdb/commit/5ff0f54b8a2651d00e417274f48d07d88b062c36))
* Workflow now runs as well on push to main ([#13](https://github.com/akrivi/plexosdb/issues/13)) ([383b289](https://github.com/akrivi/plexosdb/commit/383b2895149a34d9aa59ca5987f0235be50fd03a))


### 📦 Build

* **ci:** Changing labeler permissions ([61fe40f](https://github.com/akrivi/plexosdb/commit/61fe40ff31c5d7025bde3d03af216ff6993e5a23))
* **deps:** bump actions/checkout from 4 to 6 ([#74](https://github.com/akrivi/plexosdb/issues/74)) ([bb7be8d](https://github.com/akrivi/plexosdb/commit/bb7be8d0e36c332051ec1a1767b8862f4baec359))
* **deps:** bump actions/setup-python from 5 to 6 ([#73](https://github.com/akrivi/plexosdb/issues/73)) ([18a0d9d](https://github.com/akrivi/plexosdb/commit/18a0d9d26db2056d79bbdda6cec168e895abe0e9))
* **deps:** bump furo from 2024.8.6 to 2025.9.25 ([#77](https://github.com/akrivi/plexosdb/issues/77)) ([3dd6463](https://github.com/akrivi/plexosdb/commit/3dd64632666e31a38f6ed8f8bb15f9d333e64791))
* **deps:** bump ipython from 9.4.0 to 9.7.0 ([#76](https://github.com/akrivi/plexosdb/issues/76)) ([ca687df](https://github.com/akrivi/plexosdb/commit/ca687dfa466990e59c273c26908496c1fd5a8878))
* **deps:** bump pre-commit from 4.2.0 to 4.5.0 ([#82](https://github.com/akrivi/plexosdb/issues/82)) ([a590ce9](https://github.com/akrivi/plexosdb/commit/a590ce949bef17e8bfa81fe70bf75293d2e88aa8))
* **deps:** bump pytest from 8.4.1 to 9.0.1 ([#75](https://github.com/akrivi/plexosdb/issues/75)) ([5864d85](https://github.com/akrivi/plexosdb/commit/5864d85e69e5e6cc865fc389e6b15f8e63785001))
* **deps:** bump ruff from 0.14.7 to 0.14.8 ([#83](https://github.com/akrivi/plexosdb/issues/83)) ([c4123e1](https://github.com/akrivi/plexosdb/commit/c4123e13f38d43586e1ba306b09b7b73c04b7b59))

## [1.3.0](https://github.com/NREL/plexosdb/compare/v1.2.2...v1.3.0) (2025-12-11)


### 🚀 Features

* Making add_from_records more robust ([#85](https://github.com/NREL/plexosdb/issues/85)) ([827b2dd](https://github.com/NREL/plexosdb/commit/827b2ddaa24cd5c9531d4f78fab8f4e1cb441ff2))


### 📦 Build

* **deps:** bump pre-commit from 4.2.0 to 4.5.0 ([#82](https://github.com/NREL/plexosdb/issues/82)) ([a590ce9](https://github.com/NREL/plexosdb/commit/a590ce949bef17e8bfa81fe70bf75293d2e88aa8))
* **deps:** bump ruff from 0.14.7 to 0.14.8 ([#83](https://github.com/NREL/plexosdb/issues/83)) ([c4123e1](https://github.com/NREL/plexosdb/commit/c4123e13f38d43586e1ba306b09b7b73c04b7b59))

## [1.2.2](https://github.com/NREL/plexosdb/compare/v1.2.1...v1.2.2) (2025-12-06)


### 🐛 Bug Fixes

* Update battery collection enum naming and add increment to rank for same class enum ([#80](https://github.com/NREL/plexosdb/issues/80)) ([e247e67](https://github.com/NREL/plexosdb/commit/e247e6731f05eeef792cf8de09f0123e6f9d2995))

## [1.2.1](https://github.com/NREL/plexosdb/compare/v1.2.0...v1.2.1) (2025-12-04)


### 🐛 Bug Fixes

* handle property related attributes on "add_properties_from_records" method ([#78](https://github.com/NREL/plexosdb/issues/78)) ([1776d2a](https://github.com/NREL/plexosdb/commit/1776d2a614facef29d5a2a3df1f3a27dd154e359))

## [1.2.0](https://github.com/NREL/plexosdb/compare/v1.1.3...v1.2.0) (2025-12-02)


### 🚀 Features

* Adding method `add_datafile_tag` and refactor add_properties/add_properties_from_records ([#69](https://github.com/NREL/plexosdb/issues/69)) ([1e6e018](https://github.com/NREL/plexosdb/commit/1e6e01852e46fba89b16120c07d472f4c84f94ab))
* Adding new fixtures for cleaner testing. ([#68](https://github.com/NREL/plexosdb/issues/68)) ([9062baa](https://github.com/NREL/plexosdb/commit/9062baab8db1eb611dcb7364e952bbdb898fe36a))
* Adding query date_from and date_to to properties ([#67](https://github.com/NREL/plexosdb/issues/67)) ([00d533b](https://github.com/NREL/plexosdb/commit/00d533b4b547822a09984cf59e40738fea330f4a))


### 🐛 Bug Fixes

* Adding new release-please workflow ([#71](https://github.com/NREL/plexosdb/issues/71)) ([1f8da38](https://github.com/NREL/plexosdb/commit/1f8da384a9deb3edfa7a343e91999d3d37e07b17))


### 📦 Build

* **deps:** bump actions/checkout from 4 to 6 ([#74](https://github.com/NREL/plexosdb/issues/74)) ([bb7be8d](https://github.com/NREL/plexosdb/commit/bb7be8d0e36c332051ec1a1767b8862f4baec359))
* **deps:** bump actions/setup-python from 5 to 6 ([#73](https://github.com/NREL/plexosdb/issues/73)) ([18a0d9d](https://github.com/NREL/plexosdb/commit/18a0d9d26db2056d79bbdda6cec168e895abe0e9))
* **deps:** bump furo from 2024.8.6 to 2025.9.25 ([#77](https://github.com/NREL/plexosdb/issues/77)) ([3dd6463](https://github.com/NREL/plexosdb/commit/3dd64632666e31a38f6ed8f8bb15f9d333e64791))
* **deps:** bump ipython from 9.4.0 to 9.7.0 ([#76](https://github.com/NREL/plexosdb/issues/76)) ([ca687df](https://github.com/NREL/plexosdb/commit/ca687dfa466990e59c273c26908496c1fd5a8878))
* **deps:** bump pytest from 8.4.1 to 9.0.1 ([#75](https://github.com/NREL/plexosdb/issues/75)) ([5864d85](https://github.com/NREL/plexosdb/commit/5864d85e69e5e6cc865fc389e6b15f8e63785001))

## [0.0.1] - 2024-08-21

### 🐛 Bug Fixes

- *(get_memberships)* Updated `get_membership` function (#6)

### ⚙️ Miscellaneous Tasks

- *(actions)* Adding first version of GitHub actions (#5)
- *(actions)* Fixing GitHub Actions and refactoring API (#7)
- Removing trailwhitespace

<!-- generated by git-cliff -->
