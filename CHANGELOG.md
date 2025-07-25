### Changelog

All notable changes to this project will be documented in this file. Dates are displayed in UTC.

#### [0.3.31](https://github.com/sarbuk/AirCon/compare/0.3.29...0.3.31)
> 27 June 2025

- added additional definitions in ```__main__.py``` to expose additional topics for the following, outside of the HA climate control:
  - economy_mode [switch]
  - powerful_mode [switch]
  - af_vertical_direction [integer 1-4]
  - outdoor_temperature [sensor]

#### [0.3.29](https://github.com/sarbuk/AirCon/compare/0.3.24...0.3.29)
> 25 June 2025

- add temp_step = 0.5 to allow half degree increments in HA
- other changes due to forking from xury77

#### [0.3.24](https://github.com/xury77/AirCon/compare/0.3.23...0.3.24)
> 18 November 2024

- fix FAN_ONLY as mentioned in [`#4`]
- Bump aiohttp from 3.9.4 to 3.10.2

#### [0.3.23](https://github.com/xury77/AirCon/compare/0.3.22...0.3.23)
> 31 July 2024

- Add GitHub Action for Automated Container Creation and Publication to GHCR by @colino17 in [`#3`]
- Revert back 'temp_type' config
- 

#### [0.3.22](https://github.com/xury77/AirCon/compare/0.3.21...0.3.22)
> 30 July 2024

- bug in preset mode. Temporary disabled.

#### [0.3.21](https://github.com/xury77/AirCon/compare/0.3.20...0.3.21)
> 30 July 2024

- Adding some fgl properties: refresh,outdoor_temperature,powerful_mode and others

#### [0.3.20](https://github.com/xury77/AirCon/compare/0.3.19...0.3.20)
> 25 July 2024

- Fix display_temperature on HA thermostat card. Now current temperature is properly displayed.

Generated by [`auto-changelog`](https://github.com/CookPete/auto-changelog).
#### [0.3.19](https://github.com/xury77/AirCon/compare/0.3.18...0.3.19)
> 23 July 2024

- Edit README.md and update CHANGELOG.md

> 22 July 2024

- Get rid of colons in [`#224`](https://github.com/deiger/AirCon/pull/224) 
- Merge [`#222`](https://github.com/deiger/AirCon/pull/222)
- Create own multiarch docker images.

#### [0.3.18](https://github.com/xury77/AirCon/compare/0.3.17...0.3.18)

> 17 July 2024

- First try merge abandoned PR's [`#224`](https://github.com/deiger/AirCon/pull/224)

#### [0.3.17](https://github.com/deiger/AirCon/compare/0.3.16...0.3.17)

> 7 August 2023

- Add option to change the port for MQTT broker. [`#250`](https://github.com/deiger/AirCon/issues/250)
- Add hismart-us to the Celsius API list. [`#246`](https://github.com/deiger/AirCon/issues/246) [`#142`](https://github.com/deiger/AirCon/issues/142)

#### [0.3.16](https://github.com/deiger/AirCon/compare/0.3.15...0.3.16)

> 6 August 2023

- Remove setting of entity name to None. [`47ee470`](https://github.com/deiger/AirCon/commit/47ee4700f56f8f6c25e16f7a97d48d730add56a4)

#### [0.3.15](https://github.com/deiger/AirCon/compare/0.3.14...0.3.15)

> 3 August 2023

- Bump aiohttp from 3.7.4 to 3.8.5 [`#243`](https://github.com/deiger/AirCon/pull/243)
- Clear the entity name in order to conform with HA 2023.8 [`#248`](https://github.com/deiger/AirCon/issues/248)
- Add a multiarch container to facilitate the build. [`4c2184f`](https://github.com/deiger/AirCon/commit/4c2184fbcd774b816302a7adc3d5d235887a62fc)

#### [0.3.14](https://github.com/deiger/AirCon/compare/0.3.13...0.3.14)

> 7 May 2023

- Update properties.py [`#221`](https://github.com/deiger/AirCon/pull/221)

#### [0.3.13](https://github.com/deiger/AirCon/compare/0.3.12...0.3.13)

> 14 March 2023

- Remove non-mandatory flag from prepopulated null setting. [`edb0a5d`](https://github.com/deiger/AirCon/commit/edb0a5d2a90488aa461158040817f0e973619a80)

#### [0.3.12](https://github.com/deiger/AirCon/compare/0.3.11...0.3.12)

> 14 March 2023

- feat: Add option to specify local ip address to AC units to connect to [`#209`](https://github.com/deiger/AirCon/pull/209)

#### [0.3.11](https://github.com/deiger/AirCon/compare/0.3.10...0.3.11)

> 13 March 2023

- Remove the deprecated power_*_topic. [`#217`](https://github.com/deiger/AirCon/issues/217)
- Upgrade python to 3.10 [`48da9ba`](https://github.com/deiger/AirCon/commit/48da9ba3b3f119288109cdd6bdfc99609213b301)

#### [0.3.10](https://github.com/deiger/AirCon/compare/0.3.9...0.3.10)

> 31 January 2022

- Add t_sleep control [`#128`](https://github.com/deiger/AirCon/pull/128)
- Remove redundant parenthesis [`#93`](https://github.com/deiger/AirCon/issues/93)
- Accomodate A/C `f_votage` typo [`#108`](https://github.com/deiger/AirCon/issues/108)
- Explicitly create tasks for asyncio.wait [`#107`](https://github.com/deiger/AirCon/issues/107)
- Bump paho-mqtt version to 1.6.1 [`21d9d00`](https://github.com/deiger/AirCon/commit/21d9d005f11ec91167a63c5785016f8e4d0c73c9)

#### [0.3.9](https://github.com/deiger/AirCon/compare/0.3.8...0.3.9)

> 14 March 2021

- Bump aiohttp from 3.6.2 to 3.7.4 [`#86`](https://github.com/deiger/AirCon/pull/86)
- Set the temperature precision for fglair to 0.1. [`#85`](https://github.com/deiger/AirCon/issues/85)
- Update the A/C availability only on change. [`#83`](https://github.com/deiger/AirCon/issues/83)
- Removed default app info, since it seems to override user data [`3fd0b7d`](https://github.com/deiger/AirCon/commit/3fd0b7d93cc87177981a90e65ab84f8c1dcd6516)
- 0.3.8.2 [`544f7d0`](https://github.com/deiger/AirCon/commit/544f7d06721f56f9a022f1b12a772655933bd4d1)
- 0.3.8.1 [`5a975c9`](https://github.com/deiger/AirCon/commit/5a975c9d6a614c900bbb14d2622d0a47091b75a4)

#### [0.3.8](https://github.com/deiger/AirCon/compare/0.3.7...0.3.8)

> 9 February 2021

- bug fixes [`#81`](https://github.com/deiger/AirCon/pull/81)
- Prefer user generated commands to periodical status updates. [`834fab2`](https://github.com/deiger/AirCon/commit/834fab200b2e358cf3d2600d39cbfd1d089c68a3)
- Fix retry mechanism. [`f09a891`](https://github.com/deiger/AirCon/commit/f09a89165b31ff3a5535769e50ea30cbf658e2be)
- Fixed: status query now runs async for each device - faster [`f5bfc51`](https://github.com/deiger/AirCon/commit/f5bfc51410f3eaa844b8f3d95a44dc0dfb0c69ce)

#### [0.3.7](https://github.com/deiger/AirCon/compare/0.3.6...0.3.7)

> 30 January 2021

- Full changelog [`c338d92`](https://github.com/deiger/AirCon/commit/c338d926fff68abc31b1b3e51bb2068fe002042b)
- Run keep_alive concurrently, and don't over-retry failing A/Cs [`95b36f0`](https://github.com/deiger/AirCon/commit/95b36f0b90b59939abb0a7c8922cd3f73e098097)
- Convert ClientConnectorError to the internal error. [`b09bb61`](https://github.com/deiger/AirCon/commit/b09bb611c805f1e436ec520ec7d07ef87af7d50b)

#### [0.3.6](https://github.com/deiger/AirCon/compare/0.3.5...0.3.6)

> 15 January 2021

- Fixed syntax glich bug [`#69`](https://github.com/deiger/AirCon/pull/69)
- Bug fix. [`#67`](https://github.com/deiger/AirCon/issues/67)
- Update docs about the use of add-on store. [`450117d`](https://github.com/deiger/AirCon/commit/450117dc110110d16748b4dcaa186678f7749fd4)
- Add documentation for HA add-on. [`103b975`](https://github.com/deiger/AirCon/commit/103b9753eac974afd9b4130a1ab4761daba8ddc9)
- Make get_property return None on invalid property. [`6261752`](https://github.com/deiger/AirCon/commit/62617526c416558ce38a8bdf3e0857f966635bfa)

#### [0.3.5](https://github.com/deiger/AirCon/compare/0.3.4...0.3.5)

> 13 January 2021

- Move device type selection logic into the a model-based selection. [`1ef749f`](https://github.com/deiger/AirCon/commit/1ef749f5742ea87021b14a01273e4be14592d415)
- Add support for discovery in FGLair. [`cc053c0`](https://github.com/deiger/AirCon/commit/cc053c03b2ff7dbba42248c3f32fdfab71b10a7e)
- Fix docker-compose, make it copy the current config.json. [`6f6a337`](https://github.com/deiger/AirCon/commit/6f6a3375d32d7de9fb292e33907865a38d55ee2f)

#### [0.3.4](https://github.com/deiger/AirCon/compare/0.3.3...0.3.4)

> 12 January 2021

- Fix HA config schema. [`#66`](https://github.com/deiger/AirCon/issues/66)
- Install jq if it doesn't exist. [`2b51c88`](https://github.com/deiger/AirCon/commit/2b51c884bb4f5dc7bf114bd1776111a39bfe6a3e)

#### [0.3.3](https://github.com/deiger/AirCon/compare/0.3.2...0.3.3)

> 11 January 2021

- Fix the docker compose volume. [`#65`](https://github.com/deiger/AirCon/issues/65)
- Refactor the docker config to use HA-style options. [`68411b0`](https://github.com/deiger/AirCon/commit/68411b07eb3608d9a1d5c24cae1f352ebd6a9917)
- Add HA readme. [`26eb247`](https://github.com/deiger/AirCon/commit/26eb2473834f8f1098680eb0ccde989862481a53)
- Move the HA add-on config to a dedicated dir. [`3f5f526`](https://github.com/deiger/AirCon/commit/3f5f5261026746c26a0537ed35ad562a9a94ff82)

#### [0.3.2](https://github.com/deiger/AirCon/compare/0.3.1...0.3.2)

> 10 January 2021

- Add change log. [`cec1056`](https://github.com/deiger/AirCon/commit/cec1056aa36e6911a3b07ebae7ac26706c536f49)
- Avoid mandating a device IP when not needed. [`1808de3`](https://github.com/deiger/AirCon/commit/1808de3ed56afed42c9b4e0299288ba2f0bfe4d2)
- Move the logo into the subdir. [`6daf129`](https://github.com/deiger/AirCon/commit/6daf129bb1d11442fd72646fddb814a34969630e)

#### [0.3.1](https://github.com/deiger/AirCon/compare/0.3.0...0.3.1)

> 10 January 2021

- Handle the availability of each A/C on its own. [`8afbf4b`](https://github.com/deiger/AirCon/commit/8afbf4be02c79e57ed89a9c0a54f928a0303cd97)
- Fix the HA add ons store config. [`1127fd9`](https://github.com/deiger/AirCon/commit/1127fd9e942dcc112dc6b56b17a4e27e1db83f3d)
- Fix the config for HA addon. [`029fc9a`](https://github.com/deiger/AirCon/commit/029fc9a23cca4b986369f849d75404c221fd3cab)

#### [0.3.0](https://github.com/deiger/AirCon/compare/0.2.14...0.3.0)

> 9 January 2021

- Fix: allow keep alive error to continue to the next device [`#61`](https://github.com/deiger/AirCon/pull/61)
- Update README.md [`956fdf3`](https://github.com/deiger/AirCon/commit/956fdf35f009a0b711d9cb232977522badf55967)
- Create configuration for HA addon. [`b4273b4`](https://github.com/deiger/AirCon/commit/b4273b43831e956b8f20c6fb038f794274978316)
- Fixed: moved queues_empty = True to where it was [`dcdb756`](https://github.com/deiger/AirCon/commit/dcdb7565476c0f756428a82701f2cc1525551a96)

#### [0.2.14](https://github.com/deiger/AirCon/compare/0.2.13...0.2.14)

> 8 January 2021

- Properly handle t_power vs t_work_mode merge in HA. [`ef0ca94`](https://github.com/deiger/AirCon/commit/ef0ca9412bdd4ccf779a3514cc94a6f229a7a227)
- Use info rather than error in empty data response from the AC. [`34aaa87`](https://github.com/deiger/AirCon/commit/34aaa8763802736c87236e4a7c565e37a30b12da)
- Properly handle t_power vs t_work_mode merge in HA. [`aeb2b2c`](https://github.com/deiger/AirCon/commit/aeb2b2c924ef4d62772d348544767462874c8b5d)

#### [0.2.13](https://github.com/deiger/AirCon/compare/0.2.12...0.2.13)

> 8 January 2021

- Dockerfile support [`#55`](https://github.com/deiger/AirCon/pull/55)
- Dockerfile [`e3e722a`](https://github.com/deiger/AirCon/commit/e3e722ad52358515edbf0a5237109bb7a49b81c0)
- Add reason data to the response on error. [`65c334d`](https://github.com/deiger/AirCon/commit/65c334d4202256b8fa0d4d1ff1542a6c373d2bd9)
- Docker: Added support for config volume [`46131c1`](https://github.com/deiger/AirCon/commit/46131c1fcabcbb339854eeebde02339c70f7c3fc)

#### [0.2.12](https://github.com/deiger/AirCon/compare/0.2.11...0.2.12)

> 6 January 2021

- Propagate `temp_type` to config. [`#54`](https://github.com/deiger/AirCon/issues/54)
- Fetch MAC address from network as fallback. [`ec9b1a9`](https://github.com/deiger/AirCon/commit/ec9b1a942e54859c5ece21439e871944a24f7d3b)

#### [0.2.11](https://github.com/deiger/AirCon/compare/0.2.10...0.2.11)

> 6 January 2021

- Dockerfile [`e3e722a`](https://github.com/deiger/AirCon/commit/e3e722ad52358515edbf0a5237109bb7a49b81c0)
- Added log_level to Dockerfile env [`85ea281`](https://github.com/deiger/AirCon/commit/85ea281b61d3e75746ee8d30bd12f531ccbfd929)

#### [0.2.10](https://github.com/deiger/AirCon/compare/0.2.9...0.2.10)

> 5 January 2021

- Add `temp_type=C` to the AC config, for a predefined set of apps. [`#54`](https://github.com/deiger/AirCon/issues/54)
- Bug fix. [`58d12e7`](https://github.com/deiger/AirCon/commit/58d12e79da70efce013a0bb4e28ac2acefe6d675)
- Tiny bug fix. [`c1e2bd1`](https://github.com/deiger/AirCon/commit/c1e2bd1a9def008acfa6a5a85f85bf228d549caf)

#### [0.2.9](https://github.com/deiger/AirCon/compare/0.2.8...0.2.9)

> 29 December 2020

- Update documentation for `--type` and remove `--ip`. [`#48`](https://github.com/deiger/AirCon/issues/48)
- Get the right TimeoutError exception for asyncio, as it moved in Python3.8 [`#47`](https://github.com/deiger/AirCon/issues/47)
- Turn AC on on mode change (mitigate HA bug). [`#26`](https://github.com/deiger/AirCon/issues/26)
- Syntax fix [`df839f1`](https://github.com/deiger/AirCon/commit/df839f133aee19456f0c8fc08063559cb2fcac23)

#### [0.2.8](https://github.com/deiger/AirCon/compare/0.2.7...0.2.8)

> 28 December 2020

- Code formatting, using yapf. [`8b26064`](https://github.com/deiger/AirCon/commit/8b2606402471d5345723e36ae5efc019d8f784a0)

#### [0.2.7](https://github.com/deiger/AirCon/compare/0.2.6...0.2.7)

> 28 December 2020

- Refactoring. [`9f557f6`](https://github.com/deiger/AirCon/commit/9f557f628bd4d6342f0d541fe6103931ef409615)

#### [0.2.6](https://github.com/deiger/AirCon/compare/0.2.5...0.2.6)

> 28 December 2020

- Clean up control_value code. [`8156fcd`](https://github.com/deiger/AirCon/commit/8156fcd501f29882f4f7b6107107cc461c46add9)
- Fix the discovery code, reported in #46. [`3b6627e`](https://github.com/deiger/AirCon/commit/3b6627e3760a27e918524bb18f800d6a6430b52d)

#### [0.2.5](https://github.com/deiger/AirCon/compare/0.2.4...0.2.5)

> 27 December 2020

- Add discovery for HomeAssistant, auto-generating Lovelace. Also fix the code, that was broken by 044375d. [`e0cfd67`](https://github.com/deiger/AirCon/commit/e0cfd67b53455f3659474fe9fbd95c32fc35c1bf)
- Reference the newly added MQTT discovery support [`cbfd6e8`](https://github.com/deiger/AirCon/commit/cbfd6e83a4f83d13a60255e2ffe8b3c3a1b24d11)
- chmod [`d8630cd`](https://github.com/deiger/AirCon/commit/d8630cdda7895c0d336d204a33d0206c2dd78e91)

#### [0.2.4](https://github.com/deiger/AirCon/compare/0.2.3...0.2.4)

> 13 October 2020

- Decouple project  [`#29`](https://github.com/deiger/AirCon/pull/29)
- Apply changes after review [`9e628ee`](https://github.com/deiger/AirCon/commit/9e628ee491f78c17cd2714ee3330440318ad4696)

#### [0.2.3](https://github.com/deiger/AirCon/compare/0.2.2...0.2.3)

> 28 September 2020

- Add support for async [`04b36c7`](https://github.com/deiger/AirCon/commit/04b36c7b554af28f1cab804ea42713ceb3d3e7b8)
- Remove not needed import [`c3ee99e`](https://github.com/deiger/AirCon/commit/c3ee99e7318e596dd14342aa9dac0bb344f7a0e0)
- Migrate to aiohttp [`83ed9a6`](https://github.com/deiger/AirCon/commit/83ed9a65fc825e90f77412792158b2edb23daa00)

#### [0.2.2](https://github.com/deiger/AirCon/compare/0.2.1...0.2.2)

> 13 July 2020

- Remove Data class [`9a151e8`](https://github.com/deiger/AirCon/commit/9a151e83860eec66295c91b96640275016aa21a7)
- Add getters and setters to AcDevice [`3f0933c`](https://github.com/deiger/AirCon/commit/3f0933c44208f9403078dbf53f7f243da35fea1c)
- Allow multiple devices at once [`250d8d3`](https://github.com/deiger/AirCon/commit/250d8d370e7713eb097bca6cf797d132527fc6f7)

#### [0.2.1](https://github.com/deiger/AirCon/compare/0.2.0...0.2.1)

> 10 July 2020

- Added discovery command [`a8a5df1`](https://github.com/deiger/AirCon/commit/a8a5df132504e21c1f05593c0aa91abdd4fdae78)
- Fix small issues [`3bd7439`](https://github.com/deiger/AirCon/commit/3bd7439ee7e70fc4711f572b0274791302354de7)
- Fix build [`c902896`](https://github.com/deiger/AirCon/commit/c902896d653bc85d9b97f42bd689037e4f255e0b)

#### [0.2.0](https://github.com/deiger/AirCon/compare/0.1.21...0.2.0)

> 6 July 2020

- Copy files for refactoring. [`756c58c`](https://github.com/deiger/AirCon/commit/756c58cdce014a764fe7a9bdc3acfdf89608bb2d)
- Remove some of the duplicated code [`eba31d2`](https://github.com/deiger/AirCon/commit/eba31d24b8317f09c1628c0738575085b706feb5)
- Decouple [`f905db9`](https://github.com/deiger/AirCon/commit/f905db94cc690edf0459767d7e782e923392cf73)

#### [0.1.21](https://github.com/deiger/AirCon/compare/0.1.20...0.1.21)

> 17 July 2020

- Error messages [`9bc46d9`](https://github.com/deiger/AirCon/commit/9bc46d97edba5e07c86f70a0568f28e8f4e8a948)
- Explicitly shut down the http server on reg error. [`ffb2690`](https://github.com/deiger/AirCon/commit/ffb26909784ae3645d2ba37829f84bcfaff33fc6)
- Exit on failure to send local_reg keep alive. [`3b6b4ae`](https://github.com/deiger/AirCon/commit/3b6b4aec24328436516abfaf1876bf0540881635)

#### [0.1.20](https://github.com/deiger/AirCon/compare/0.1.19...0.1.20)

> 14 June 2020

- Add support for FGL devices [`6166f18`](https://github.com/deiger/AirCon/commit/6166f188b05573451595615d35dcd996fa111014)
- Separate FGL and FGL-B modules [`e11b224`](https://github.com/deiger/AirCon/commit/e11b2246111056ad2cd9059d422d5ae8116be54b)
- Document the support for FGLair [`f16f97d`](https://github.com/deiger/AirCon/commit/f16f97d9e845debfb674915b9c2441b76fe25a71)

#### [0.1.19](https://github.com/deiger/AirCon/compare/0.1.18...0.1.19)

> 4 June 2020

- Add retry for local_reg [`473dc54`](https://github.com/deiger/AirCon/commit/473dc54e5b0229c50f079c549a807a9db6f3ea42)
- Do not reuse the socket between retries. [`66e4ae2`](https://github.com/deiger/AirCon/commit/66e4ae22fa3dfe7a3fbb3348b527673da20df1ad)
- Fix handling of connection [`85933c2`](https://github.com/deiger/AirCon/commit/85933c2f2198178c255690b128186109e76a1b07)

#### [0.1.18](https://github.com/deiger/AirCon/compare/0.1.17...0.1.18)

> 1 June 2020

- Publish an update for new subscribers [`2f2ca59`](https://github.com/deiger/AirCon/commit/2f2ca59fbece64e78217a1d591eeb4c595deae82)
- Add section for multiple A/Cs [`5869222`](https://github.com/deiger/AirCon/commit/58692225b38228b4cac48f91d5f4fde5a32f0042)
- Accept (and round) float temperatures. [`6b08a35`](https://github.com/deiger/AirCon/commit/6b08a35581d95e47d20272ed3f1f44bc7ac65255)

#### [0.1.17](https://github.com/deiger/AirCon/compare/0.1.16...0.1.17)

> 31 May 2020

- Compare enum values by identity [`#19`](https://github.com/deiger/AirCon/issues/19)
- Configuration for Home Assistant [`f2d0245`](https://github.com/deiger/AirCon/commit/f2d02455d9f57febb1795bdb269a5a6b55b2d615)
- Document the HomeAssistant support. [`90d35d4`](https://github.com/deiger/AirCon/commit/90d35d49ba97cf965ee591ba6bdbe437a39bab98)
- Remove value_template, as JSON isn't used [`5adba58`](https://github.com/deiger/AirCon/commit/5adba5893e74c4e8aaaffaca6b18982f155a0c30)

#### [0.1.16](https://github.com/deiger/AirCon/compare/0.1.15...0.1.16)

> 12 May 2020

- Add support for Fujitsu FGLair [`7946404`](https://github.com/deiger/AirCon/commit/79464042cf7c6fb2340b6fafc00af6459114ace3)
- Add support for FGLair [`6055378`](https://github.com/deiger/AirCon/commit/6055378ee55cc8d5bd17e0520b5386288040d7c7)

#### [0.1.15](https://github.com/deiger/AirCon/compare/0.1.14...0.1.15)

> 5 May 2020

- Move to separate topics per property [`187928b`](https://github.com/deiger/AirCon/commit/187928ba5f80b5a42a6b9750f90b712629d8226d)
- Handle decimal temp [`813d6a4`](https://github.com/deiger/AirCon/commit/813d6a41fb01534f7e4570c924cae18169bed49a)
- Add logging for incoming MQTT messages. [`e5b992d`](https://github.com/deiger/AirCon/commit/e5b992df5f5b41294bea328183a6cb7888ea6372)

#### [0.1.14](https://github.com/deiger/AirCon/compare/0.1.13...0.1.14)

> 27 April 2020

- Set broadcast flags for socket on IP discovery [`00347c5`](https://github.com/deiger/AirCon/commit/00347c5018b3c4c0d0dc398334d0d774bb752782)

#### [0.1.13](https://github.com/deiger/AirCon/compare/0.1.12...0.1.13)

> 22 April 2020

- Add an option to print the properties [`7faec95`](https://github.com/deiger/AirCon/commit/7faec957907b02efd9a88cb0ca740cedc0832b70)
- More explicit warning for unsupported properties [`761f773`](https://github.com/deiger/AirCon/commit/761f773ed470035602ca367c0c98a550e281b3ba)

#### [0.1.12](https://github.com/deiger/AirCon/compare/0.1.11...0.1.12)

> 17 March 2020

- Support gzipped response. [`57870f9`](https://github.com/deiger/AirCon/commit/57870f9cec1c9ddf3435f24aa3c38f2af9e37194)
- Print the data when failing to parse JSON. [`bdeedf3`](https://github.com/deiger/AirCon/commit/bdeedf37199950dabb3f173796116466dc482831)
- Return deleted newlines [`c3aed6e`](https://github.com/deiger/AirCon/commit/c3aed6efb0a6c299f80414272d507739b2097f23)

#### [0.1.11](https://github.com/deiger/AirCon/compare/0.1.10...0.1.11)

> 28 January 2020

- Update documentation [`0536d89`](https://github.com/deiger/AirCon/commit/0536d89341f46107c17b880a0245d8d440b4ae64)
- Add support for Denali Aire [`f417a2a`](https://github.com/deiger/AirCon/commit/f417a2a0a6ca9fed0cde9849d7f68cb6ee554b11)
- Add support for HiSmart Home and AI-Home [`92691a3`](https://github.com/deiger/AirCon/commit/92691a31598840b194297f1600015e89e509801c)

#### [0.1.10](https://github.com/deiger/AirCon/compare/0.1.9...0.1.10)

> 12 January 2020

- Add support for hismartinternationalforandroid [`f952489`](https://github.com/deiger/AirCon/commit/f952489a1598277c89dc5d8ce567ebc6cdd5810f)
- Update app name [`848ef55`](https://github.com/deiger/AirCon/commit/848ef55997d92626afe6091a6d8c700f481b8f51)
- Add support for hismartinternationalforandroid [`591a7ae`](https://github.com/deiger/AirCon/commit/591a7aea0151f7282c9e55cbb215dc0cc618a80b)

#### [0.1.9](https://github.com/deiger/AirCon/compare/0.1.8...0.1.9)

> 16 December 2019

- Add support for humidifiers, that use the same protocol [`50910cb`](https://github.com/deiger/AirCon/commit/50910cbee04f5c11969a102af3495178a4406138)
- Add  enums for humidifiers [`8432a0f`](https://github.com/deiger/AirCon/commit/8432a0fd2c36c99ed6f3e439ad97bf59fc6b97a8)
- Update the CLI to handle SunHome [`cffd837`](https://github.com/deiger/AirCon/commit/cffd837e543b67256e9bf6ffa9362c871d0f9df1)

#### [0.1.8](https://github.com/deiger/AirCon/compare/0.1.7...0.1.8)

> 15 October 2019

- Properly handle logging on Windows [`e0abbf7`](https://github.com/deiger/AirCon/commit/e0abbf70fa25c3838c3616f6fbabb5fe43ee649a)
- Add missing import. [`c2cc7c4`](https://github.com/deiger/AirCon/commit/c2cc7c4ac65e5138ec93ac963ec36c2e531a2b7b)

#### [0.1.7](https://github.com/deiger/AirCon/compare/0.1.6...0.1.7)

> 12 October 2019

- Accommodate zeroed sequence number [`a62810e`](https://github.com/deiger/AirCon/commit/a62810e139247f94f40643f9a4693d14556eebe0)
- Use the regional servers for each different app. [`c710fcd`](https://github.com/deiger/AirCon/commit/c710fcd55222cf2e3c1edbf15b1c9962c9834829)
- Make the CLI error include the HTTP failure reason [`773046a`](https://github.com/deiger/AirCon/commit/773046a0ca276fae5a3ca2ebda5a6a96deef2df8)

#### [0.1.6](https://github.com/deiger/AirCon/compare/0.1.5...0.1.6)

> 13 September 2019

- First version of the ST device handler. [`e3b537d`](https://github.com/deiger/AirCon/commit/e3b537d31675d101caae70144a703402f8c97b2f)
- Fix indentation issues. [`96b733e`](https://github.com/deiger/AirCon/commit/96b733e0a5643c99cd03a76cb204ff039419a973)
- Stability updates [`cc3bb94`](https://github.com/deiger/AirCon/commit/cc3bb94027a5fb8267fcf4ff149ff6f9bc2e5f33)

#### [0.1.5](https://github.com/deiger/AirCon/compare/0.1.4...0.1.5)

> 9 September 2019

- Periodically update all properties [`e3c264e`](https://github.com/deiger/AirCon/commit/e3c264e3fc0806daafb00c3e617d8d1b2cd7279d)
- Get the current state for all properties at startup [`bdb74d5`](https://github.com/deiger/AirCon/commit/bdb74d59a503b1da2a6f1efcd8d49568ad17f1bc)
- Update the list of apps based on Xinlianfeng [`9940f19`](https://github.com/deiger/AirCon/commit/9940f19b3830a6ad021a65d93e2dd087469a5010)

#### [0.1.4](https://github.com/deiger/AirCon/compare/0.1.3...0.1.4)

> 8 September 2019

- Update README.md [`7cf4827`](https://github.com/deiger/AirCon/commit/7cf482768854cfdf0efcc36ff1b975a4414d76e3)
- Handle apps with non-standard prefix [`ecff1ba`](https://github.com/deiger/AirCon/commit/ecff1ba7ac11bec1287c74362cc05dc7847b50fa)
- Update the list of supported and unsupported apps [`73b7c39`](https://github.com/deiger/AirCon/commit/73b7c39097e688cfe5862d7c0515561534e077bb)

#### [0.1.3](https://github.com/deiger/AirCon/compare/0.1.2...0.1.3)

> 7 September 2019

- Publish to MQTT only the updated property [`fe92ff4`](https://github.com/deiger/AirCon/commit/fe92ff44b4932d81cb912c96f37573c8e6676835)
- Bug fixes [`bd26103`](https://github.com/deiger/AirCon/commit/bd26103ee1e89853d7678644bda4e21bddc34410)
- Bug fixes [`353782c`](https://github.com/deiger/AirCon/commit/353782c8e0b59d5d486a4b3caeeb9f4d596c0c88)

#### [0.1.2](https://github.com/deiger/AirCon/compare/0.1.1...0.1.2)

> 5 September 2019

- Properly handle all properties [`7314c32`](https://github.com/deiger/AirCon/commit/7314c32c30b44ca2440d1bbf6dc9ce2efeec211a)
- Switch to strings in enum values [`383bfe7`](https://github.com/deiger/AirCon/commit/383bfe784d5ae5123f5a507ce2b9587e3fa480a2)
- Update README.md [`26b8121`](https://github.com/deiger/AirCon/commit/26b81217b6c94a438cbe4cd3258e2c1dd18fe089)

#### [0.1.1](https://github.com/deiger/AirCon/compare/0.1.0...0.1.1)

> 4 September 2019

- Script to query HiSense servers [`28af9ba`](https://github.com/deiger/AirCon/commit/28af9ba8a0eee9f2367c3ffa73e97bd287d4ee74)
- Update README.md [`b5a558c`](https://github.com/deiger/AirCon/commit/b5a558cd69204d6a38faa23c3adfbb427d19d145)
- Documentation for CLI usage [`eb02ffa`](https://github.com/deiger/AirCon/commit/eb02ffac0d8e50e22b51c6724bf752be8c280fc1)

#### 0.1.0

> 11 August 2019

- Create LICENSE [`48fd9f4`](https://github.com/deiger/AirCon/commit/48fd9f47b8b7f543fa50a4944715b9b75d835ea7)
- Initial version for HiSense AC module [`e5306eb`](https://github.com/deiger/AirCon/commit/e5306ebd72b2ab4ad008cb90a70275276750327e)
- Create README.md [`a5301cb`](https://github.com/deiger/AirCon/commit/a5301cbff6833fa2bec475b49c555e12f42d05a0)
