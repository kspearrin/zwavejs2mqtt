### Changelog

All notable changes to this project will be documented in this file. Dates are displayed in UTC.

Generated by [`auto-changelog`](https://github.com/CookPete/auto-changelog).

#### [v1.1.1](https://github.com/robertsLando/Zwave2Mqtt/compare/v1.1.1...v1.1.1)

> 15 May 2019

- [chore] fixed missing pkg script on release [`9133fba`](https://github.com/robertsLando/Zwave2Mqtt/commit/9133fbaba0d8540c71083dcdf9f0d184eba708c4)
- [chore] `-s` option not allowed [`972e9c3`](https://github.com/robertsLando/Zwave2Mqtt/commit/972e9c39cc5c5cdc6b422785a031a3191dde3113)
- [chore] secure token read in release [`fb1a44b`](https://github.com/robertsLando/Zwave2Mqtt/commit/fb1a44b0d8f4e0ae4d4ba8affde0a1ea7e321d3c)

#### [1.1.0](https://github.com/robertsLando/Zwave2Mqtt/compare/1.0.1...1.1.0)

> 4 May 2019

- Bumped version 1.1.0 [`9cc3740`](https://github.com/robertsLando/Zwave2Mqtt/commit/9cc3740740b57f1e896139b5ffdb25be7576ad58)

#### [1.0.1](https://github.com/robertsLando/Zwave2Mqtt/compare/1.0.0...1.0.1)

> 4 May 2019

- - Protocol support in host url [`474e0aa`](https://github.com/robertsLando/Zwave2Mqtt/commit/474e0aa9a87d067c52824554e4363949dfa4bdb2)
- - Added 'verifyChanges' flag on gateway values [`1fd4ef0`](https://github.com/robertsLando/Zwave2Mqtt/commit/1fd4ef03f410ed162610ef4afc8515b6c8577b05)
- - Moved all config files in store folder [`bfb07ff`](https://github.com/robertsLando/Zwave2Mqtt/commit/bfb07ff57f27daa2e35267cf16907bea8be3b135)
- Fixed Readme [`ab5eb19`](https://github.com/robertsLando/Zwave2Mqtt/commit/ab5eb19be8b2a0f745a6f23761d8f9ff492f2239)
- Removed  double closing tag [`0decf00`](https://github.com/robertsLando/Zwave2Mqtt/commit/0decf00634e3918cdfaa0be9061947926c64dc3a)
- Docker support :tada: [`dfc2c37`](https://github.com/robertsLando/Zwave2Mqtt/commit/dfc2c3713cf5677006eff5469c54cf6b61bba3c5)
- - Option to allow self signed certs on mqtt clients [`d6a9362`](https://github.com/robertsLando/Zwave2Mqtt/commit/d6a93623647550d88ac89805f503b89ad69c4ca2)
- Fixed es-lint errors on www [`59bde82`](https://github.com/robertsLando/Zwave2Mqtt/commit/59bde82bd05a7260c8a1147e3b188c06530c6480)
- Update is_polled flag on valueids #18 [`29bba97`](https://github.com/robertsLando/Zwave2Mqtt/commit/29bba9716a3ddc05ae793a50e4a45a3b081d5c8f)
- Updated to openzwave-shared@1.4.8 [`0690bfd`](https://github.com/robertsLando/Zwave2Mqtt/commit/0690bfdea9c8d41b02b393bed84c57c62ed0cf1b)
- Fixed config xml import/export [`51038c7`](https://github.com/robertsLando/Zwave2Mqtt/commit/51038c7edf3fac0d5ab1a5ad7662ff4abacc1903)
- Added alpine build [`c451ca9`](https://github.com/robertsLando/Zwave2Mqtt/commit/c451ca95c8dfb38cb94cc3862843c1dfb9fc62e0)
- Updated Readme [`f000af1`](https://github.com/robertsLando/Zwave2Mqtt/commit/f000af17a455cd78ef8985d3f8e051904457401e)
- Updated github links after ownership transfer to Openzwave org [`91f54d9`](https://github.com/robertsLando/Zwave2Mqtt/commit/91f54d9715ae436920fdfbe8054432f27f4125b9)
- Added docker badges to readme [`667adae`](https://github.com/robertsLando/Zwave2Mqtt/commit/667adae2e1e8db4233e54c08d911e28454f77500)
- Bumped version 1.0.1 [`2f9da87`](https://github.com/robertsLando/Zwave2Mqtt/commit/2f9da876ff148aa5be5dece76a1cac0115dd0c54)
- Fixed typo in README [`30a5723`](https://github.com/robertsLando/Zwave2Mqtt/commit/30a5723b5bd96e307a40187b4b700421e3279383)
- Updated pkg link in README [`24e2f96`](https://github.com/robertsLando/Zwave2Mqtt/commit/24e2f96bcd883e94cf1958ff427d5a31bdd1a989)
- Updated package script to ignore duplicates .node files [`abdcc57`](https://github.com/robertsLando/Zwave2Mqtt/commit/abdcc57f484396304e77329f7bc1b95d3db333f9)
- Update script pkg [`2925390`](https://github.com/robertsLando/Zwave2Mqtt/commit/2925390dfac6d2d9f7b5e759835c4f031cbc49c3)
- Updated README with mqtt protocol help [`e3c63cc`](https://github.com/robertsLando/Zwave2Mqtt/commit/e3c63ccb10365667320561f17b699585e25d68ac)
- Better log of 404 errors [`e8029dc`](https://github.com/robertsLando/Zwave2Mqtt/commit/e8029dc38c6cbab98b6ea60259217584db6586e9)
- Remove unused require [`e048033`](https://github.com/robertsLando/Zwave2Mqtt/commit/e048033c7b08f7272ed426a82576f2b2e6cfd43b)
- Remove unused require [`2195d53`](https://github.com/robertsLando/Zwave2Mqtt/commit/2195d53146ae96d86892a1343f7532a4d411b393)

#### [1.0.0](https://github.com/robertsLando/Zwave2Mqtt/compare/v1.0.0-beta.1...1.0.0)

> 19 March 2019

- Added callback to close #17 [`#17`](https://github.com/robertsLando/Zwave2Mqtt/issues/17)
- Detect sleeping devices using `nodeAviable` event [`#11`](https://github.com/robertsLando/Zwave2Mqtt/issues/11)
- Added 'int' missing type on valueId.vue. Should fix #10 [`#10`](https://github.com/robertsLando/Zwave2Mqtt/issues/10)
- Fix #15: topic conflicts with named topics and multi-instance devices [`#15`](https://github.com/robertsLando/Zwave2Mqtt/issues/15)
- - Drawer expand/collapse fix #8 [`#8`](https://github.com/robertsLando/Zwave2Mqtt/issues/8) [`#7`](https://github.com/robertsLando/Zwave2Mqtt/issues/7)
- Don't send error if SerialPort.list fails (Fixes #6) [`#6`](https://github.com/robertsLando/Zwave2Mqtt/issues/6)
- - Added support for lot more controller commands [`82a59a9`](https://github.com/robertsLando/Zwave2Mqtt/commit/82a59a9d1c98c5072ea80752a6c9d0ed36957522)
- - Custom config path option in zwave settings [`1840bef`](https://github.com/robertsLando/Zwave2Mqtt/commit/1840bef82ae786fd2adf6becb99619950cb5e356)
- Updated gateway logic. Now values table is always visible [`95bd0aa`](https://github.com/robertsLando/Zwave2Mqtt/commit/95bd0aaaeb0e2146ab82b7d9f57c3e85c14594e2)
- - Convert value based on valueID type [`499ea83`](https://github.com/robertsLando/Zwave2Mqtt/commit/499ea83a286b5d8e09fed1cec9d5519ae1bbca61)
- Updated README.md [`312ddd1`](https://github.com/robertsLando/Zwave2Mqtt/commit/312ddd1860afad0814c6d885f1e6fe65318be9ee)
- Working on better support of broadcast commands [`1b52539`](https://github.com/robertsLando/Zwave2Mqtt/commit/1b525399a48a020ab580f3edb83abcb76a3a6fa9)
- Update groups on nodes added after scan complete event [`9811c67`](https://github.com/robertsLando/Zwave2Mqtt/commit/9811c674eb5ca7321941d2a4a11bc66ac8413af6)
- - Added Test network and test node functions [`259b295`](https://github.com/robertsLando/Zwave2Mqtt/commit/259b2953dc5d0ebeff4beeb58862b3f2e125d5cb)
- Fixed duplicated messages when restarting client #17 [`f88f607`](https://github.com/robertsLando/Zwave2Mqtt/commit/f88f60773025ceb9d5891fa3a7c35906c44d9387)
- - Parse value on Valueadded event (and little bug fix) [`1637b3a`](https://github.com/robertsLando/Zwave2Mqtt/commit/1637b3af46e75cd778a6b15b6a0d5deeda8202e9)
- Updated README [`2d25ac5`](https://github.com/robertsLando/Zwave2Mqtt/commit/2d25ac5ea9be155a1c3df616ac6d741ae5adbd6d)
- Show snackbar error if socket is disconnected when try to call api [`150981f`](https://github.com/robertsLando/Zwave2Mqtt/commit/150981facee262606ad5e1fefc14d5b0c1244361)
- Set disconnect timeout to 2 sec #17 [`c5057c6`](https://github.com/robertsLando/Zwave2Mqtt/commit/c5057c601d5b653f967bb0bf67a6217decae46a6)
- Send NIF frame when scan is completed to ndoes that are not ready [`ed6acb0`](https://github.com/robertsLando/Zwave2Mqtt/commit/ed6acb0929dde014d821fbcca32916e1677ae384)
- Added AssumeAwake option to zwave settings [`88698bd`](https://github.com/robertsLando/Zwave2Mqtt/commit/88698bdc1d7f77c7d8d256b829b69c85f1b2b58c)
- Added functions to controller for inclusion/exclusion [`c8c3ae2`](https://github.com/robertsLando/Zwave2Mqtt/commit/c8c3ae28a6fec0b35fee85900a74e54d0fa5d1b7)
- Removed NIF on scan complete and added event nodeAvailable [`bdc29ec`](https://github.com/robertsLando/Zwave2Mqtt/commit/bdc29ecb218476819556154393fc662432b73861)
- Eval operation even if no topic specified [`66272ad`](https://github.com/robertsLando/Zwave2Mqtt/commit/66272ad2664706480ebd7766693b784d71b776a7)
- Make dialogs peristent to prevent Vue error [`fde4211`](https://github.com/robertsLando/Zwave2Mqtt/commit/fde421176379400013ea1c920fb4e8cce8b46308)
- Updated README [`7b7a742`](https://github.com/robertsLando/Zwave2Mqtt/commit/7b7a7423f7ed60ff6199b4c3f6bbc157d50a1ea2)
- Updated readme with last pkg version [`0554eac`](https://github.com/robertsLando/Zwave2Mqtt/commit/0554eac8d86d602bff28ae8b3ba83786cb6a96a0)
- Fix error 'undefined' config.values (#5) [`24e9631`](https://github.com/robertsLando/Zwave2Mqtt/commit/24e963184dca9be1bce56323aaa6b52565da7a40)
- Removed date string from prefix on logs in UI [`a79c526`](https://github.com/robertsLando/Zwave2Mqtt/commit/a79c526f9fe3abe43a3759b8ef37ee170e8d3fe3)
- Removed blank lines [`8ae8438`](https://github.com/robertsLando/Zwave2Mqtt/commit/8ae84389261ef6ab461135ef9948e253f421001f)

#### v1.0.0-beta.1

> 30 January 2019

- Initial commit [`ed66c7a`](https://github.com/robertsLando/Zwave2Mqtt/commit/ed66c7a638c09b588c86332c32342ee9235dcf41)
- First working implementation of publish/subscribe [`834ae97`](https://github.com/robertsLando/Zwave2Mqtt/commit/834ae979cd0bc38b82766c3c5590630bdb4be20b)
- Control panel and socket management [`b7ec431`](https://github.com/robertsLando/Zwave2Mqtt/commit/b7ec4311d5e7db291636f4cd804ebd88921dec9d)
- Setting up main structure [`9d0c799`](https://github.com/robertsLando/Zwave2Mqtt/commit/9d0c79981e47d1999160b821632c9c9ff5924801)
- - Check if value is polled before enable polling [`808d342`](https://github.com/robertsLando/Zwave2Mqtt/commit/808d3427fd23493cc6cd87ba583567352411f150)
- - Updated icons [`1ea90bf`](https://github.com/robertsLando/Zwave2Mqtt/commit/1ea90bf1f760bb54d8506ec1e30e8bd1241cb477)
- Broadcast improvments and api calls via mqtt [`0e2647c`](https://github.com/robertsLando/Zwave2Mqtt/commit/0e2647cdb49823a6ce4afe3258cbc6f2eb96e75d)
- Scene support (need work) [`6d87d5f`](https://github.com/robertsLando/Zwave2Mqtt/commit/6d87d5f30d7eebcb3373f38db47c3864f2353365)
- - Custom scene management with values timeout [`ea9fca5`](https://github.com/robertsLando/Zwave2Mqtt/commit/ea9fca5a24c88898c83e03da308c57dec1948561)
- - Better logging with debug module [`869d3dc`](https://github.com/robertsLando/Zwave2Mqtt/commit/869d3dcbe4378fac27da86851926148d638bc56c)
- - Import/Export scenes [`dc7a4fe`](https://github.com/robertsLando/Zwave2Mqtt/commit/dc7a4fe6018184a6748855e5d8334883e02c1962)
- Fixed scenes management and started refactoring code [`07e3838`](https://github.com/robertsLando/Zwave2Mqtt/commit/07e383817e1506baf42e51adf35db2e42891a61d)
- Updated README [`12af1ac`](https://github.com/robertsLando/Zwave2Mqtt/commit/12af1ac6811ff2030c89048654b52aca4f3d2994)
- Removed unused routes and starting pkg support [`2683e19`](https://github.com/robertsLando/Zwave2Mqtt/commit/2683e196c81702591c266dd21cbc32b7c29a3afe)
- Updated README [`ad297e0`](https://github.com/robertsLando/Zwave2Mqtt/commit/ad297e0597042a348b6bd1a9275e3b0c5eea7fb5)
- Initial commit [`db5c17d`](https://github.com/robertsLando/Zwave2Mqtt/commit/db5c17d542f717211172b3cc7011bdf5f5837fc0)
- Inited readme [`2807782`](https://github.com/robertsLando/Zwave2Mqtt/commit/2807782131900ee23f9f7ecd562126edcae4c625)
- - Debug tab [`4392976`](https://github.com/robertsLando/Zwave2Mqtt/commit/4392976ac13b4ffadce2058398f5a6af40850e4c)
- - Fix bug on start when no configuration is present [`4081147`](https://github.com/robertsLando/Zwave2Mqtt/commit/40811470c521836064d945837a97c14e68616daf)
- Fixed some typos in Readme and added some emojy [`937ea43`](https://github.com/robertsLando/Zwave2Mqtt/commit/937ea43f80d5dcd93ed57cf33dea3545cd0e6f3d)
- - Fixed bug value not set correctly in payload [`20ced2e`](https://github.com/robertsLando/Zwave2Mqtt/commit/20ced2e6b8fa746d1f6aed3f12c287e782841580)
- Updated README [`00cea67`](https://github.com/robertsLando/Zwave2Mqtt/commit/00cea672d8705aa131011781546a3fe9700c760a)
- Handle value update [`948b39a`](https://github.com/robertsLando/Zwave2Mqtt/commit/948b39a1d781de7a84376eb650a5261dc4d4659c)
- Updated readme [`176aede`](https://github.com/robertsLando/Zwave2Mqtt/commit/176aede2219546b7bdbf21280323d57fd2c8308b)
- Better log colors and enabled debug by default [`20592b0`](https://github.com/robertsLando/Zwave2Mqtt/commit/20592b09181841fc36b2251647cebb62a57e4f1b)
- Updated webpack-dev-server and openzwave-shared packages [`0b56981`](https://github.com/robertsLando/Zwave2Mqtt/commit/0b56981bf30856db759a92ff106f67b4c252f1df)
- Updated README [`5ec5425`](https://github.com/robertsLando/Zwave2Mqtt/commit/5ec54253e4042d61f2a901140b1deffd5648948b)
- Updated Readme with new server dev start [`50ff268`](https://github.com/robertsLando/Zwave2Mqtt/commit/50ff2680948cb34460c49c4e5bae9a7c80d6cdaa)
- Added TODOs and fixed some typos [`8fdb485`](https://github.com/robertsLando/Zwave2Mqtt/commit/8fdb4859b203810f89463a2ac2e62ea2114c5fa3)
- Fixed markdown for TODOs [`f94313b`](https://github.com/robertsLando/Zwave2Mqtt/commit/f94313bf075b92460bb0011d2229f2cdfe806d56)
- Add debug on Gateway [`01d5afc`](https://github.com/robertsLando/Zwave2Mqtt/commit/01d5afce785305f3b9b553bdc89feed6fffa03b0)
- Updated README.md [`a75e280`](https://github.com/robertsLando/Zwave2Mqtt/commit/a75e280b88e7551395d68c5b87b33cb1fa0a18a4)
- Fixed typo in README [`b09ad26`](https://github.com/robertsLando/Zwave2Mqtt/commit/b09ad260d47a963c5be43258ecf40f33bfba9be5)
- Added TODOs section [`6e36951`](https://github.com/robertsLando/Zwave2Mqtt/commit/6e36951d239f73c7a55854eaaf2cc14ca1f37656)
- Updated wget link for pkg version [`8f20706`](https://github.com/robertsLando/Zwave2Mqtt/commit/8f20706cfee7d2f6cb7b7d00b44a3e5ac0d48c9d)
- Ignore pkg folder [`58076c6`](https://github.com/robertsLando/Zwave2Mqtt/commit/58076c66875ea0ea4d3d6ec7d1c199cb86ec393a)
- Ignore store folder [`2532ad3`](https://github.com/robertsLando/Zwave2Mqtt/commit/2532ad3e21f4dff6bab1ce3ec1190e478af06d59)
- Added developing note [`2d1579c`](https://github.com/robertsLando/Zwave2Mqtt/commit/2d1579c628eda49a0a29d8ff8a6d068687fd3b50)