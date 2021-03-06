### Changelog
All notable changes to this project will be documented in this file.

#### [v3.7.4](https://github.com/GladysProject/Gladys/compare/v3.7.3...v3.7.4)
> 28 January 2018
- correction of the UPDATE function in HOUSESERVICE. [`#243`](https://github.com/GladysProject/Gladys/pull/243)
- Don&#x27;t change name of device when updating it [`#257`](https://github.com/GladysProject/Gladys/pull/257)
- Fix #278 : add snow.svg in white [`#278`](https://github.com/GladysProject/Gladys/issues/278)
- Fix #262 : house.getUsers() function now return user back-at-home + user-seen-at-home events [`#262`](https://github.com/GladysProject/Gladys/issues/262)
- Fix #264 : Remove sensible data in brain classify response [`#264`](https://github.com/GladysProject/Gladys/issues/264)
- update CHANGELOG.md [`1a08460`](https://github.com/GladysProject/Gladys/commit/1a08460720d59fc9c7b6be6ba5bd37eed833e7c1)
- Add tooltip in views &amp; update fr and en json [`b8b0ad3`](https://github.com/GladysProject/Gladys/commit/b8b0ad35405e33b9adad4e2e4773f16e2dadb4f4)
- Add .vscode to gitignore [`6d83794`](https://github.com/GladysProject/Gladys/commit/6d83794a6245e515375fc77b7a80533e3b16dcb2)

#### [v3.7.3](https://github.com/GladysProject/Gladys/compare/v3.7.2...v3.7.3)
> 14 November 2017
- Fix #236 : Handle null value &amp; uppercase value in house, room &amp; deviceType name in parser [`#236`](https://github.com/GladysProject/Gladys/issues/236)
- Fix #216 : Now able to upgrade a module directly from the UI ! [`#216`](https://github.com/GladysProject/Gladys/issues/216)
- Fix #220 : Now adding a wait modal when clicking on reboot button with a regular healthcheck [`#220`](https://github.com/GladysProject/Gladys/issues/220)
- Fix #251 : Brain UI is now setting correctly the service field when updating sentences [`#251`](https://github.com/GladysProject/Gladys/issues/251)
- Fix #249 : If user has only one house and say &quot;I&#x27;m back home&quot;, Gladys should suppose it&#x27;s his only house [`#249`](https://github.com/GladysProject/Gladys/issues/249)
- Fix #226 : Add infinite scrolling in My Devices view [`#226`](https://github.com/GladysProject/Gladys/issues/226)
- Add /system/health route to healthCheck Gladys [`222ad36`](https://github.com/GladysProject/Gladys/commit/222ad36dac3c34911c0c289ccc3d76f8424ae30d)
- Replace the button with the switch [`077dccf`](https://github.com/GladysProject/Gladys/commit/077dccfa40f1102d821aea20affd272360cccd9b)
- add onoffswitch css file to pipeline.js [`4b2d147`](https://github.com/GladysProject/Gladys/commit/4b2d14733dcc84c175feab89f8dc16c51a142e70)

#### [v3.7.2](https://github.com/GladysProject/Gladys/compare/v3.7.1...v3.7.2)
> 21 October 2017
- bugfix in scenario.export, group scenario params not by code but by id [`fbc86f5`](https://github.com/GladysProject/Gladys/commit/fbc86f57921199614822ecee75379bb745aa5b4c)

#### [v3.7.1](https://github.com/GladysProject/Gladys/compare/v3.7.0...v3.7.1)
> 15 October 2017
- ES6 &#x3D;&gt; ES5 on client side [`23a7fb5`](https://github.com/GladysProject/Gladys/commit/23a7fb515aaecc6e8f9f4fe84aa4597dbde394b0)

#### [v3.7.0](https://github.com/GladysProject/Gladys/compare/v3.6.3...v3.7.0)
> 15 October 2017
- Sentence ui [`#242`](https://github.com/GladysProject/Gladys/pull/242)
- Connaitre le paramètre introuvable. [`#120`](https://github.com/GladysProject/Gladys/pull/120)
- Update HouseController.js [`#237`](https://github.com/GladysProject/Gladys/pull/237)
- put old behaviour on connections.js ( default value ) [`99106e8`](https://github.com/GladysProject/Gladys/commit/99106e88bb97af3a6035a6d166994f935cd96cb5)
- let not supported in vode4 [`d9c0c3e`](https://github.com/GladysProject/Gladys/commit/d9c0c3e8ad6cb41a01cb35ddf97d9cf39372d86c)
- set sentence status &#x3D; &#x27;official&#x27; when inserting batch [`855ad5a`](https://github.com/GladysProject/Gladys/commit/855ad5a4a8dd5ebee486ad2e5de6a2256a7b85ab)

#### [v3.6.3](https://github.com/GladysProject/Gladys/compare/v3.6.2...v3.6.3)
> 26 September 2017
- Update deviceType.queries.js [`#221`](https://github.com/GladysProject/Gladys/pull/221)
- Fix #222 : Do not send websocket notification when device is updated [`#222`](https://github.com/GladysProject/Gladys/issues/222)
- Update last event user-seen-at-home instead of creating one new every time [`924b282`](https://github.com/GladysProject/Gladys/commit/924b282142abff40e6dbc3d19fc618ba862cb6e2)
- Switch Dockerfile from argon to boron [`61bcc34`](https://github.com/GladysProject/Gladys/commit/61bcc346ceee6e3c330416c164ad4b9080e0f785)
- test gladys with Node 8 [`2093984`](https://github.com/GladysProject/Gladys/commit/209398495a1b31ded11e6a8b2e41736a5216df4c)

#### [v3.6.2](https://github.com/GladysProject/Gladys/compare/v3.6.1...v3.6.2)
> 10 September 2017
- Fix #217 : StateTypeParam are no longer inserted in duplicate [`#217`](https://github.com/GladysProject/Gladys/issues/217)
- Fix #215 : Remove &quot;view all&quot; link in notification list [`#215`](https://github.com/GladysProject/Gladys/issues/215)
- Fix #200 : Scenario now have a title ! [`#200`](https://github.com/GladysProject/Gladys/issues/200)
- Fix #214 : Get /devicestate now return all devicestate ! [`#214`](https://github.com/GladysProject/Gladys/issues/214)
- Fix #198 : Now using websocket to tell front-end that module is installed [`#198`](https://github.com/GladysProject/Gladys/issues/198)
- Fix #196 : Script errors now displayed in script view ! [`#196`](https://github.com/GladysProject/Gladys/issues/196)
- Fix #197 : Script UI is now more clear ! :) [`#197`](https://github.com/GladysProject/Gladys/issues/197)
- Fix #207 : Add all field in GROUP BY clause in Get user location query [`#207`](https://github.com/GladysProject/Gladys/issues/207)
- Fix #199 : Add more feedback on most form validation when form is invalid [`#199`](https://github.com/GladysProject/Gladys/issues/199)
- Fix #206 : update all dependencies in package.json &amp; removed unused ones [`#206`](https://github.com/GladysProject/Gladys/issues/206)
- Fix #169 : Fix bug in house.checkUsersPresence() when multiple users are at home [`#169`](https://github.com/GladysProject/Gladys/issues/169)
- Get command weather at a specific time! [`b397cc7`](https://github.com/GladysProject/Gladys/commit/b397cc7c12ab2909e94b8de202bbd6b9f1c1a101)
- pass user id in script context even when starting script from scenario [`e8428b1`](https://github.com/GladysProject/Gladys/commit/e8428b11a743404041e269a756bfeae0fc7f2322)
- bugfix weather.command() test [`209c80c`](https://github.com/GladysProject/Gladys/commit/209c80c73df16bc334777a7079e69aba03f5659c)

#### [v3.6.1](https://github.com/GladysProject/Gladys/compare/v3.6.0...v3.6.1)
> 28 May 2017
- update changelog [`3338566`](https://github.com/GladysProject/Gladys/commit/3338566a530fabd7118ee60a56acb065ec899c24)
- exit process when app is init [`b26a781`](https://github.com/GladysProject/Gladys/commit/b26a78160294cf6df73a06797725a57680848904)

#### [v3.6.0](https://github.com/GladysProject/Gladys/compare/v3.5.4...v3.6.0)
> 28 May 2017
- gladys autoWake up feature [`c7949c4`](https://github.com/GladysProject/Gladys/commit/c7949c40803c3a1de19ee444bc2a9ddbd7ad4db0)
- calendar.getFirstEventTodayUser() [`d5bf175`](https://github.com/GladysProject/Gladys/commit/d5bf17574ede993ac92d42aa9bc9b610fc483aea)
- change translation in Alarm vie [`d34c48f`](https://github.com/GladysProject/Gladys/commit/d34c48f20cd63d23291037d7772852b9143f1dca)

#### [v3.5.4](https://github.com/GladysProject/Gladys/compare/v3.5.3...v3.5.4)
> 27 May 2017
- remove arrow function in client code [`8e9ccab`](https://github.com/GladysProject/Gladys/commit/8e9ccabce92b73d4d89916f362b478241914dc4e)

#### [v3.5.3](https://github.com/GladysProject/Gladys/compare/v3.5.2...v3.5.3)
> 27 May 2017
- add validation errors message in House &amp; rooms view [`05a72dd`](https://github.com/GladysProject/Gladys/commit/05a72dd949eca90903c9a254dc43049bce921b3e)
- recognizing house &amp; rooms in event.command() [`1e6f64c`](https://github.com/GladysProject/Gladys/commit/1e6f64cdfa07e4015bb597f5c816a2bc3899f03f)
- trying to call Gladys service first before module service in notification.create() [`26036aa`](https://github.com/GladysProject/Gladys/commit/26036aa7bdd7f0843c6de0808aa26b8be542af65)

#### [v3.5.2](https://github.com/GladysProject/Gladys/compare/v3.5.1...v3.5.2)
> 16 May 2017
- rpi-update.sh moved to /home/pi [`#179`](https://github.com/GladysProject/Gladys/pull/179)
- add house description in parameters to help user [`a6d0394`](https://github.com/GladysProject/Gladys/commit/a6d0394a2dfcd3284b7e8e0363b1738f1b4a436a)
- Update general.ejs [`e4d119d`](https://github.com/GladysProject/Gladys/commit/e4d119ddaf27cd212b43012e2c8bf9e08e17c44f)
- Update general.ejs [`3c322c8`](https://github.com/GladysProject/Gladys/commit/3c322c8e1b56026ae1b04ed7884d348fdd53c02d)

#### [v3.5.1](https://github.com/GladysProject/Gladys/compare/v3.5.0...v3.5.1)
> 10 April 2017
- bugfix in brain answer : keep only 2 first character of user language [`c4f5412`](https://github.com/GladysProject/Gladys/commit/c4f54129f497cdd9e15b5b7824e1a0ca0285e703)
- update rpi-update.sh, start directly node init.js in folder instead of using absolute path [`83622e6`](https://github.com/GladysProject/Gladys/commit/83622e62ab41a374a5c75b9f6af252662f54f79c)

#### [v3.5.0](https://github.com/GladysProject/Gladys/compare/v3.4.4...v3.5.0)
> 9 April 2017
- Add a Gitter chat badge to README.md [`#168`](https://github.com/GladysProject/Gladys/pull/168)
- created alarm.command, you can now create alarm while speaking with Gladys ! [`569c33c`](https://github.com/GladysProject/Gladys/commit/569c33cce41cade30999b6aec5e1bc5b8c6b867b)
- install notification only if not exist [`137c84d`](https://github.com/GladysProject/Gladys/commit/137c84db7d3aa3b961f33efe917c5fdbe9228210)
- create notification type socket at startup if not exist [`7e88db7`](https://github.com/GladysProject/Gladys/commit/7e88db7b40d0d16d309f1c3f139b583d51a95be8)

#### [v3.4.4](https://github.com/GladysProject/Gladys/compare/v3.4.3...v3.4.4)
> 8 March 2017
- remove log in init.js [`277a12e`](https://github.com/GladysProject/Gladys/commit/277a12e63caef8378513e0b822776878eb665285)

#### [v3.4.3](https://github.com/GladysProject/Gladys/compare/v3.4.2...v3.4.3)
> 7 March 2017
- Fix #150 : devicetype in lowercase in SQL request for case sensitive system [`#150`](https://github.com/GladysProject/Gladys/issues/150)
- add clear icon svg weather [`e2c8009`](https://github.com/GladysProject/Gladys/commit/e2c800969c41746144175ce52cb7e76569ef7ff5)
- remove update button, clarify memory [`f3d029d`](https://github.com/GladysProject/Gladys/commit/f3d029de32f07e76ffbbf72fdafff750e57e20b6)
- postcode in house is now a string [`5901eb5`](https://github.com/GladysProject/Gladys/commit/5901eb56ce310e5d38e08e2fd35151217db3f96d)

#### [v3.4.2](https://github.com/GladysProject/Gladys/compare/v3.4.1...v3.4.2)
> 11 February 2017
- Fix #149 : Alarm now scheduled at startup [`#149`](https://github.com/GladysProject/Gladys/issues/149)
- add wind icon [`cd5ed0a`](https://github.com/GladysProject/Gladys/commit/cd5ed0ab0b7b8f63309424cb8f0faa89c1891201)
- fix issue with maps icon when running in production mode [`80e61e5`](https://github.com/GladysProject/Gladys/commit/80e61e574d4aa9802913e0e8bd7b8831db786c42)
- update CHANGELOG [`16d6173`](https://github.com/GladysProject/Gladys/commit/16d6173fe85bd49d516f6e1f976a961465c47de0)

#### [v3.4.1](https://github.com/GladysProject/Gladys/compare/v3.4.0...v3.4.1)
> 31 January 2017
- update CHANGELOG for Gladys 3.4 [`81286e0`](https://github.com/GladysProject/Gladys/commit/81286e08abca9392261aca0c862190f454ad1592)
- boxType.create now update boxType if already exist [`3f53415`](https://github.com/GladysProject/Gladys/commit/3f534158197a43fe349ca84f05be1c5a67ed7874)

#### [v3.4.0](https://github.com/GladysProject/Gladys/compare/v3.3.4...v3.4.0)
> 30 January 2017
- add purge function on devicestate [`#138`](https://github.com/GladysProject/Gladys/pull/138)
- add sun.getState, sun.isItDay, sun.isItNight [`#135`](https://github.com/GladysProject/Gladys/pull/135)
- Update fs-extra to version 1.0.0 🚀 [`#108`](https://github.com/GladysProject/Gladys/pull/108)
- Update bcrypt to version 1.0.0 🚀 [`#124`](https://github.com/GladysProject/Gladys/pull/124)
- Proposal for allowing users to set their own env vars directly in the project. [`#130`](https://github.com/GladysProject/Gladys/pull/130)
- sync all calendars directly threw gladys api [`c391f59`](https://github.com/GladysProject/Gladys/commit/c391f5984077fc10f48d785986cb255db784326a)
- add error when geolocation failed [`55eed38`](https://github.com/GladysProject/Gladys/commit/55eed3855e01203a10258da1a94509251dbb622c)
- commit changes to layout.ejs &amp; index.ejs [`9002e40`](https://github.com/GladysProject/Gladys/commit/9002e40d0039c723ce673d7deaa602379fb7568d)

#### [v3.3.4](https://github.com/GladysProject/Gladys/compare/v3.3.3...v3.3.4)
> 10 December 2016
- add unit test to GET /devicetype/room [`3272562`](https://github.com/GladysProject/Gladys/commit/327256206c4f4451d99474af23e2cc340fe61fe9)
- updated changelog for 3.3.3 [`a7eb514`](https://github.com/GladysProject/Gladys/commit/a7eb514b109aa695f46ca14079633624c33640a4)
- fix critical bug when getting deviceType by room [`a6d263d`](https://github.com/GladysProject/Gladys/commit/a6d263d45db8f9a61b341457b6c085ad3e23fc56)

#### [v3.3.3](https://github.com/GladysProject/Gladys/compare/v3.3.2...v3.3.3)
> 10 December 2016
- Close #122, scenario now accepts empty templates [`#122`](https://github.com/GladysProject/Gladys/issues/122)
- Close #121, brain now call module functions and not global services [`#121`](https://github.com/GladysProject/Gladys/issues/121)
- send mode id into scope in mode change [`24484be`](https://github.com/GladysProject/Gladys/commit/24484be39a7bd5623c6c3eff0935c8ccd616878b)
- GET routes on event and deviceState are linked to new controller [`2ca1c40`](https://github.com/GladysProject/Gladys/commit/2ca1c4099d1b4cb9f4b29582778e131efdce272c)
- add documentation URL to apidoc.json [`2213033`](https://github.com/GladysProject/Gladys/commit/2213033087efaf963ca4cfe70a5994cf6ff90503)

#### [v3.3.2](https://github.com/GladysProject/Gladys/compare/v3.3.1...v3.3.2)
> 13 November 2016
- add roomName in deviceType get requests [`2dd7e9d`](https://github.com/GladysProject/Gladys/commit/2dd7e9d8180f7de0ff8299be3c401a47850ad783)
- modified CHANGELOG [`992db63`](https://github.com/GladysProject/Gladys/commit/992db63a84c4f0caaf336ce3477b9b5735c83510)

#### [v3.3.1](https://github.com/GladysProject/Gladys/compare/v3.3.0...v3.3.1)
> 12 November 2016
- test if scope has property before overidding it [`1a2388d`](https://github.com/GladysProject/Gladys/commit/1a2388d6439fdd62fc914b57ed4c1b17508e5666)
- update CHANGELOG [`579923e`](https://github.com/GladysProject/Gladys/commit/579923ef346af390687aaec93522a3c44a9a67c4)

#### [v3.3.0](https://github.com/GladysProject/Gladys/compare/v3.2.4...v3.3.0)
> 12 November 2016
- return boxId and display it in init function [`b551e80`](https://github.com/GladysProject/Gladys/commit/b551e802cadc9c9242e6885e74a9b3e673e76279)
- init music controller with boxId [`8f77cc3`](https://github.com/GladysProject/Gladys/commit/8f77cc3fb0fd3dcf9db539c53b8d72c9bd7e63ac)
- Added music service in changelog ! [`0b4b48f`](https://github.com/GladysProject/Gladys/commit/0b4b48f21ad46cf733cf204c556acdfa9387ac43)

#### [v3.2.4](https://github.com/GladysProject/Gladys/compare/v3.2.3...v3.2.4)
> 11 November 2016
- Introducing CHANGELOG ! [`17b895e`](https://github.com/GladysProject/Gladys/commit/17b895e489c5f6952b043b462576e73576b376c9)
- clone params in scenario.trigger function so that original object is not modified [`ae88c2a`](https://github.com/GladysProject/Gladys/commit/ae88c2a085647893cabe1fff8713b1279237ce85)

#### [v3.2.3](https://github.com/GladysProject/Gladys/compare/v3.2.2...v3.2.3)
> 11 November 2016
- add event params to scope so that conditions can be verified [`ed8c4c2`](https://github.com/GladysProject/Gladys/commit/ed8c4c25cc2d6dad88f8f43af49186531ff25392)

#### [v3.2.2](https://github.com/GladysProject/Gladys/compare/v3.2.1...v3.2.2)
> 8 November 2016
- fixed error in README.md from 9 PM -&gt; 9 AM [`#110`](https://github.com/GladysProject/Gladys/pull/110)
- Prepare front app to event box in dashboard [`5e99592`](https://github.com/GladysProject/Gladys/commit/5e9959227d17a25221ffaae7efdd81f1d965f07f)
- bugfix: Create event in scenario now working [`a430286`](https://github.com/GladysProject/Gladys/commit/a4302864bd8456d30b1194d2bd47b1e92c4c0958)
- get users and houses in event create box [`92fbc60`](https://github.com/GladysProject/Gladys/commit/92fbc604b8e485749963367b4ca2ab5c2d455f87)

#### [v3.2.1](https://github.com/GladysProject/Gladys/compare/v3.2.0...v3.2.1)
> 27 October 2016
- Fixed two typos in en.json [`#101`](https://github.com/GladysProject/Gladys/pull/101)
- apidoc comments in EventController [`ed127a0`](https://github.com/GladysProject/Gladys/commit/ed127a0eaac31230a02a5789b7e3cfd65b709698)
- apidoc implementation [`beb9e3c`](https://github.com/GladysProject/Gladys/commit/beb9e3c4792cf1626ebb5f9de0e1753412101958)
- authenticated middleware authenticated [`dfe5a9d`](https://github.com/GladysProject/Gladys/commit/dfe5a9d14e4b53df6904723217381b404ce6afca)

#### [v3.2.0](https://github.com/GladysProject/Gladys/compare/v3.1.11...v3.2.0)
> 3 October 2016
- Update notification README [`#96`](https://github.com/GladysProject/Gladys/pull/96)
- Close #95 : Device.getByIdentifier &amp; deviceType.getByIdentifier [`#95`](https://github.com/GladysProject/Gladys/issues/95)
- close #97 : deviceType getByDevice performance improvements [`#97`](https://github.com/GladysProject/Gladys/issues/97)
- deviceType.getById &amp; deviceType.getByType [`32c7866`](https://github.com/GladysProject/Gladys/commit/32c7866757b0207556bb8e2213c4c71475e47508)
- fix test [`9400118`](https://github.com/GladysProject/Gladys/commit/94001181ec6bea6c4283bd75c554915898f3ecd9)
- change d.name by dt.name [`08a48ec`](https://github.com/GladysProject/Gladys/commit/08a48ec1f9d56186c657cadcd25f66b57207eb60)

#### [v3.1.11](https://github.com/GladysProject/Gladys/compare/v3.1.10...v3.1.11)
> 25 September 2016
- update script updated [`b91507f`](https://github.com/GladysProject/Gladys/commit/b91507fa8d7050636767973cd26794a649eddcb1)

#### [v3.1.10](https://github.com/GladysProject/Gladys/compare/v3.1.9...v3.1.10)
> 25 September 2016
- Accept string in deviceType exec and parseFloat instead of parseInt [`9176b8b`](https://github.com/GladysProject/Gladys/commit/9176b8bdc78f9d58c2f844564e69fdf918280e66)
- accept boolean &amp; string in deviceState.create [`a49b29a`](https://github.com/GladysProject/Gladys/commit/a49b29adf7b7161e3cb1ab6cf9d76739bca9c6f4)
- add deviceType identifier in getDeviceType query [`b29b82a`](https://github.com/GladysProject/Gladys/commit/b29b82a5e75336da8066c1048c16e1e27cc7fd04)

#### [v3.1.9](https://github.com/GladysProject/Gladys/compare/v3.1.8...v3.1.9)
> 25 September 2016
- Create or update device &amp; deviceType [`c945c61`](https://github.com/GladysProject/Gladys/commit/c945c61631e697f68ff7d43b63c4a6dc3531957b)
- deviceState createByDeviceTypeIdentifier [`b5a4027`](https://github.com/GladysProject/Gladys/commit/b5a4027022c819c560fe49b4407d1c232425a887)
- Delete deviceType delete all his deviceState [`4b36ce6`](https://github.com/GladysProject/Gladys/commit/4b36ce60c43389733d9862c2deec8b42051fbd45)

#### [v3.1.8](https://github.com/GladysProject/Gladys/compare/v3.1.7...v3.1.8)
> 24 September 2016
- Feature : Configure machines in web view [`afd2c4f`](https://github.com/GladysProject/Gladys/commit/afd2c4f1a7e7919a1b3bf6cfbd7bcda9578e199c)
- Feature : gladys.machine.getMyHouse [`3408318`](https://github.com/GladysProject/Gladys/commit/34083184172b8c14f2c1f5cb4b8bfa15a9654102)
- host is not required in a machine [`b060a9c`](https://github.com/GladysProject/Gladys/commit/b060a9c3ce2fb3438ea51d33a3b92f44f2f63c37)

#### [v3.1.7](https://github.com/GladysProject/Gladys/compare/v3.1.6...v3.1.7)
> 24 September 2016
- Add possibilities to create device and devicetype in web view [`f42348f`](https://github.com/GladysProject/Gladys/commit/f42348f952979299ac4b46ddd957c7eb7016a3d5)
- new method : house.isUserAtHome [`721b7ed`](https://github.com/GladysProject/Gladys/commit/721b7ed066977abba45315b7505b70bbeb8f9925)
- new route : DELETE /devicetype/:id [`67f7f81`](https://github.com/GladysProject/Gladys/commit/67f7f81c0d4bfdbb2d49c3a6d4c683957865c794)

#### [v3.1.6](https://github.com/GladysProject/Gladys/compare/v3.1.5...v3.1.6)
> 22 September 2016
- add user to notify function so that the notification module have data about the user [`a30b4e6`](https://github.com/GladysProject/Gladys/commit/a30b4e67d2ee50043f0423b922d55d708a417da7)

#### [v3.1.5](https://github.com/GladysProject/Gladys/compare/v3.1.4...v3.1.5)
> 19 September 2016
- use fonts over HTTPS [`c3de8a5`](https://github.com/GladysProject/Gladys/commit/c3de8a58bf85c0b8f194e51f95154c4b21058ef0)
- remove old favicon [`0fc23a8`](https://github.com/GladysProject/Gladys/commit/0fc23a8951447ec6910ed25af9f608d196302dcf)

#### [v3.1.4](https://github.com/GladysProject/Gladys/compare/v3.1.3...v3.1.4)
> 18 September 2016
- bugfix : read notification on click on notification [`557797f`](https://github.com/GladysProject/Gladys/commit/557797f532ba6d7ef5f5e0753567891e6b5bceb0)

#### [v3.1.3](https://github.com/GladysProject/Gladys/compare/v3.1.2...v3.1.3)
> 18 September 2016
- bugfix : exec update script in detached process [`11dec2e`](https://github.com/GladysProject/Gladys/commit/11dec2e11c9d36fb0add59c6353910f745094ef7)

#### [v3.1.2](https://github.com/GladysProject/Gladys/compare/v3.1.1...v3.1.2)
> 18 September 2016
- ensure that update script has exec permission on start [`15e1f9f`](https://github.com/GladysProject/Gladys/commit/15e1f9f69130571bc19b529187c8d10a723f92fa)

#### [v3.1.1](https://github.com/GladysProject/Gladys/compare/v3.1.0...v3.1.1)
> 18 September 2016
- bugfix script update path [`91b299d`](https://github.com/GladysProject/Gladys/commit/91b299d6744a3b349283db30de8c8d2d72b992a6)

#### [v3.1.0](https://github.com/GladysProject/Gladys/compare/v3.0.8...v3.1.0)
> 18 September 2016
- close #79 : Get notifications with infinite scrolling and read when clicks [`#79`](https://github.com/GladysProject/Gladys/issues/79)
- close #81 : you can update Gladys IN Gladys ! :D [`#81`](https://github.com/GladysProject/Gladys/issues/81)
- No sudo required anymore in  rpi-update.sh, because pm2 now handle non sudo auto restart [`398ce91`](https://github.com/GladysProject/Gladys/commit/398ce9138f79b36b3c08f844f882e3054717b505)
- use latest version of Node.js LTS [`6db0b16`](https://github.com/GladysProject/Gladys/commit/6db0b16d5522c69346c14612505abca72677fba0)

#### [v3.0.8](https://github.com/GladysProject/Gladys/compare/v3.0.7...v3.0.8)
> 17 September 2016
- Update supertest to version 2.0.0 🚀 [`#68`](https://github.com/GladysProject/Gladys/pull/68)
- Update include-all to version 1.0.5 🚀 [`#76`](https://github.com/GladysProject/Gladys/pull/76)
- Update grunt-mocha-test to version 0.13.0 🚀 [`#87`](https://github.com/GladysProject/Gladys/pull/87)
- Update should to version 11.1.0 🚀 [`#73`](https://github.com/GladysProject/Gladys/pull/73)
- Update mocha to version 3.0.2 🚀 [`#71`](https://github.com/GladysProject/Gladys/pull/71)
- Update grunt-contrib-uglify to version 2.0.0 🚀 [`#66`](https://github.com/GladysProject/Gladys/pull/66)
- Update should to version 10.0.0 🚀 [`#65`](https://github.com/GladysProject/Gladys/pull/65)
- Update async to version 2.0.0 🚀 [`#64`](https://github.com/GladysProject/Gladys/pull/64)
- close #82 : Now possible to create user in param view [`#82`](https://github.com/GladysProject/Gladys/issues/82)
- close #91 : Text from modal module view updated [`#91`](https://github.com/GladysProject/Gladys/issues/91)
- close #78 : store now load modules very quickly ! [`#78`](https://github.com/GladysProject/Gladys/issues/78)
- close #84 : Lock page now working [`#84`](https://github.com/GladysProject/Gladys/issues/84)
- close #89 : Check if version is superior when auto update [`#89`](https://github.com/GladysProject/Gladys/issues/89)
- close #83 : Do not display ugly avatar and useless search bar [`#83`](https://github.com/GladysProject/Gladys/issues/83)
- close #90 : Do not exec install function when module does not exist [`#90`](https://github.com/GladysProject/Gladys/issues/90)
- close #80 : Now possible to update a user in profile page in parameters [`#80`](https://github.com/GladysProject/Gladys/issues/80)
- update install and update script [`bdc5c8a`](https://github.com/GladysProject/Gladys/commit/bdc5c8a7f96371c11192919fcb08f891563caf27)
- System.update start update script [`95cb03b`](https://github.com/GladysProject/Gladys/commit/95cb03be376277b20c8bed80a30c9e6e5a247316)
- bugfix add create user modal title [`209f72a`](https://github.com/GladysProject/Gladys/commit/209f72a58dcaae01654864eb380f06a757e873d3)

#### [v3.0.7](https://github.com/GladysProject/Gladys/compare/v3.0.6...v3.0.7)
> 14 September 2016
- Update deviceType.exec and script.exec to handle scenarios [`e989a0a`](https://github.com/GladysProject/Gladys/commit/e989a0a51ea2a4b32b674b39c80d6c3e5cdb848f)

#### [v3.0.6](https://github.com/GladysProject/Gladys/compare/v3.0.5...v3.0.6)
> 14 September 2016
- Downloading new action in installation steps and in update page [`ed34563`](https://github.com/GladysProject/Gladys/commit/ed34563e9cf3f35d3ea7b2eeb818d6c35a41b110)
- new route : /update/action to update action in scenario [`bd58186`](https://github.com/GladysProject/Gladys/commit/bd581864bf8da860816c17ed01bb457208000f68)

#### [v3.0.5](https://github.com/GladysProject/Gladys/compare/v3.0.4...v3.0.5)
> 14 September 2016
- ensure that api/hooks folder exist in grunt task [`d328b9a`](https://github.com/GladysProject/Gladys/commit/d328b9a37aaf8c0d0331cd7905caa857a7f01d16)
- fs-extra is not a dev dependency. moving it in package.json [`1751769`](https://github.com/GladysProject/Gladys/commit/17517697c012e6e576fbbaf0e477e917843219d6)

#### [v3.0.4](https://github.com/GladysProject/Gladys/compare/v3.0.3...v3.0.4)
> 14 September 2016
- actionType create or update [`ae2487a`](https://github.com/GladysProject/Gladys/commit/ae2487a61057e3215047fd6c9127bac71a7f2263)
- actionTypeParam create or update [`f481cf3`](https://github.com/GladysProject/Gladys/commit/f481cf310adfbad9143a97e9de57edd6bf7be886)

#### [v3.0.3](https://github.com/GladysProject/Gladys/compare/v3.0.2...v3.0.3)
> 26 August 2016
- SQL optimization on deviceType getByRoom [`ebbc4e0`](https://github.com/GladysProject/Gladys/commit/ebbc4e0852b995221b0ca6eeeb712aeb6e48b474)
- add LEFT JOIN to deviceType.getByRoom  query [`9f5d3c1`](https://github.com/GladysProject/Gladys/commit/9f5d3c1ceb3cc7073e3f3a2eba4cc2d903244109)

#### [v3.0.2](https://github.com/GladysProject/Gladys/compare/v3.0.1...v3.0.2)
> 8 August 2016
- ng-device-detector, detect the browser device and save it as a device in gladys ( work in progress ) [`3efab20`](https://github.com/GladysProject/Gladys/commit/3efab201f666c39230c2855d43ba6605cc2dfe85)
- DeviceState create route ( POST &amp; GET ) [`1721868`](https://github.com/GladysProject/Gladys/commit/172186893c394627920ecbcea22ef26cc8448886)
- chore(package): update should to version 10.0.0 [`6418a01`](https://github.com/GladysProject/Gladys/commit/6418a01d85709547433ea3d2d932ca0f343005c0)

#### [v3.0.1](https://github.com/GladysProject/Gladys/compare/v3.0.0-alpha1...v3.0.1)
> 9 June 2016
- Update all dependencies 🌴 [`#59`](https://github.com/GladysProject/Gladys/pull/59)
- fix error meteo [`#58`](https://github.com/GladysProject/Gladys/pull/58)
- remove googlecalendarservice [`f421aeb`](https://github.com/GladysProject/Gladys/commit/f421aeb8026eb157dc3b50cd8127fde85293b51a)
- chore(package): update dependencies [`d9c19e4`](https://github.com/GladysProject/Gladys/commit/d9c19e471929d24373fc45e0f7bbfc4093da73cf)
- remove beta in version number [`23a0e2d`](https://github.com/GladysProject/Gladys/commit/23a0e2d6c19155ed15575bd6df900fbb3ef2436a)

#### [v3.0.0-alpha1](https://github.com/GladysProject/Gladys/compare/v2.1.9...v3.0.0-alpha1)
> 27 March 2016
- Sleep graph text translation in french [`#53`](https://github.com/GladysProject/Gladys/pull/53)
- I18 birthdate placeholder. Fix #14  [`#50`](https://github.com/GladysProject/Gladys/pull/50)
- ngcloak installation page [`6c0845f`](https://github.com/GladysProject/Gladys/commit/6c0845fa9a835b55160dbe6578af69bb84362817)
- Clean module view [`7c83f7f`](https://github.com/GladysProject/Gladys/commit/7c83f7fc56686c0fb4922936d56aacea5f0744a9)
- gladys alpha1 [`ae350b4`](https://github.com/GladysProject/Gladys/commit/ae350b41b42bf536513321296824827924b53245)

#### [v2.1.9](https://github.com/GladysProject/Gladys/compare/v2.1.8...v2.1.9)
> 30 December 2015
- Remove serialport, motion sensors, phenixElectricdevice, RFListener, Timer from core ( will be modules ) [`9222b4b`](https://github.com/GladysProject/Gladys/commit/9222b4b1487cfd027e0c462b2ebac3f92d8f04b2)
- AlarmService to folder [`dfd6020`](https://github.com/GladysProject/Gladys/commit/dfd60203cb362e61c608b0a6ce3a8851458f3be7)
- Remove sails-hook-dev dependecy, causing bug on case sensitive system [`c794d21`](https://github.com/GladysProject/Gladys/commit/c794d2117808673db6975a7de04434abb3ba10ac)

#### [v2.1.8](https://github.com/GladysProject/Gladys/compare/v2.1.6...v2.1.8)
> 29 December 2015
- motion to motionRoom in launcherTypes. Fix #42 [`#42`](https://github.com/GladysProject/Gladys/issues/42)
- Change node.js version in README and installation process [`e1c9302`](https://github.com/GladysProject/Gladys/commit/e1c93021954d3e086f55415817dbe91e61eb1669)
- Change again from bcryptjs to bcrypt because bcryptjs is very slow on unusable on Raspberry Pi B/B+ ( 50 seconds to hash a password... compared to 2 seconds for bcrypt ) [`78b6733`](https://github.com/GladysProject/Gladys/commit/78b67339925e31f53933886c55ba4fe1278f3bca)
- Saving grunt-cli dependency version in package.json [`92fab84`](https://github.com/GladysProject/Gladys/commit/92fab847035faf50d0f40279e1f4f291443f6d24)

#### [v2.1.6](https://github.com/GladysProject/Gladys/compare/v2.1.5...v2.1.6)
> 29 November 2015
- Adding footer, version and links in front [`#44`](https://github.com/GladysProject/Gladys/pull/44)
- houseValidator [`084323c`](https://github.com/GladysProject/Gladys/commit/084323ce66dc16149142b9ea866a2daac2eb5622)
- LifeEventValidator. Removed LiveEventController tests [`301a23e`](https://github.com/GladysProject/Gladys/commit/301a23edb049180b5ac47c79c6d151b71c26d5cb)
- LifeEventControllerTest [`e2aca89`](https://github.com/GladysProject/Gladys/commit/e2aca8961bf29fcd8c5f7272a4ab3327bd9e8879)

#### [v2.1.5](https://github.com/GladysProject/Gladys/compare/v2.1.4...v2.1.5)
> 18 November 2015
- Update dependencies ( bcrypt &#x3D;&gt; bcryptjs &amp; MD5 deprecated &#x3D;&gt; md5 )  [`#43`](https://github.com/GladysProject/Gladys/pull/43)
- Update package.json ( add keywords, bin, bugs, repository ) [`efe85ba`](https://github.com/GladysProject/Gladys/commit/efe85ba1f368f567210a08484e7f2f76b966ff5d)
- Adding all mp3 and wav file to gitignore [`fb1d4ad`](https://github.com/GladysProject/Gladys/commit/fb1d4ad6fa26d678c1418ad8179ce59706a5b8bf)
- Package.json : Added npm publish scripts [`04e06a2`](https://github.com/GladysProject/Gladys/commit/04e06a2ae6c7243b3ccd0090d52f1ac74c1bcd21)

#### [v2.1.4](https://github.com/GladysProject/Gladys/compare/v2.1.3...v2.1.4)
> 9 November 2015
- Loading hooks services in sandboxed scripts. Fixes #34 [`#34`](https://github.com/GladysProject/Gladys/issues/34)
- More cleaner, using older function [`b71aefd`](https://github.com/GladysProject/Gladys/commit/b71aefdf1d34fe4776b341303e4fbfe970bb843b)
- Valid ExampleService [`774dbbe`](https://github.com/GladysProject/Gladys/commit/774dbbe575fa023c11b90fe2eb05f2c8975f08c9)
- Gladys 2.1.4 [`682dcbf`](https://github.com/GladysProject/Gladys/commit/682dcbfe808a01188244961bbcf2bda8f3c141f6)

#### [v2.1.3](https://github.com/GladysProject/Gladys/compare/v2.1.1...v2.1.3)
> 3 October 2015
- Fix #17 - Problem with email verification on User Models [`#17`](https://github.com/GladysProject/Gladys/issues/17)
- Sync events with GitHub [`a70d489`](https://github.com/GladysProject/Gladys/commit/a70d489a4bb463b1352d7779f49064e277633995)
- Gladys version 2.1.3 [`8da796a`](https://github.com/GladysProject/Gladys/commit/8da796a0b7af7a1cb4ab67a51e711d2e064947a1)
- Sync events at bootstrap [`aaa7f89`](https://github.com/GladysProject/Gladys/commit/aaa7f89933eabc33a186da080ce92a4a38f4cc83)

#### [v2.1.1](https://github.com/GladysProject/Gladys/compare/v2.1.0...v2.1.1)
> 21 September 2015
- Gladys 2.1.1 - Fixing speak issue [`dfa8292`](https://github.com/GladysProject/Gladys/commit/dfa829265bc23dcf29080af9a87fa2b3924a460a)
- Fixing speak issues, speaking now working [`0a92d54`](https://github.com/GladysProject/Gladys/commit/0a92d54e9a479f40b7a53d96e71b2aa313c71598)

#### v2.1.0
> 16 September 2015
- Remove CDN from welcome views [`#33`](https://github.com/GladysProject/Gladys/pull/33)
- Adding gulp [`#32`](https://github.com/GladysProject/Gladys/pull/32)
- Fix bug callback undefined [`#31`](https://github.com/GladysProject/Gladys/pull/31)
- misspelled goingToSleep [`#28`](https://github.com/GladysProject/Gladys/pull/28)
- Add charset parameter to SpeakService [`#27`](https://github.com/GladysProject/Gladys/pull/27)
- pm2 / rename app to gladys [`#24`](https://github.com/GladysProject/Gladys/pull/24)
- no data userSleep [`#19`](https://github.com/GladysProject/Gladys/pull/19)
- Breadcrumb correction [`#18`](https://github.com/GladysProject/Gladys/pull/18)
- Fixes #26 , remove useless JS client on welcome page [`#26`](https://github.com/GladysProject/Gladys/issues/26)
- Gladys is not private, update package.json [`047bceb`](https://github.com/GladysProject/Gladys/commit/047bceb3490c50e953c4e3916258aada5c6cfe08)
- New version ( 2.1.0 ) [`0bdaad3`](https://github.com/GladysProject/Gladys/commit/0bdaad3ee441078da58cf73f26b3a35a17f44705)
- Added the possibility to block signup so people can&#x27;t create an account on your Gladys server ( useful for an open server ) [`b5d2f18`](https://github.com/GladysProject/Gladys/commit/b5d2f18ab5c78f99f00a3471700814a1108017cc)

