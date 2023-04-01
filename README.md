## Changelog for nixpkgs:
Branch: master
Commits: [nixos/nixpkgs@a4dd572d...d154f809](https://github.com/nixos/nixpkgs/compare/a4dd572de1b524c9d2187b815c85dd20a09b6f4a...d154f809e9c3c47fee72186aa3ff6479403435d4)

* [`2924c3dc`](https://github.com/NixOS/nixpkgs/commit/2924c3dcab29c51d22750089e1985838dc838685) ejson2env: update script and strip
* [`7cee18ee`](https://github.com/NixOS/nixpkgs/commit/7cee18eef3538478cffd8da3779215e9315aaab4) services.dendrite: change ExecStartPre to a list
* [`bf41254a`](https://github.com/NixOS/nixpkgs/commit/bf41254a8add0d7255505afa3ff8068e0baf4127) nixos/qemu-vm: allow use without a disk image
* [`246d09fe`](https://github.com/NixOS/nixpkgs/commit/246d09fea28c85de7a2f6223fad6927429c3697b) qemu-vm: use nixos module patterns for filesystems
* [`a440e955`](https://github.com/NixOS/nixpkgs/commit/a440e955e049da9458837c43c8bd08202ef16229) python3: allow enabling framework on darwin
* [`614f0d0e`](https://github.com/NixOS/nixpkgs/commit/614f0d0edbd75eabe92d64ca722cf7ba4bbd8f37) libsForQt5.prison: enable PrisonScanner functionality
* [`85574ba2`](https://github.com/NixOS/nixpkgs/commit/85574ba216e0225b79db33dd2d07685e85eab10e) ctpv: init at v1.0
* [`e8844941`](https://github.com/NixOS/nixpkgs/commit/e88449419a9b9b69dec6ed3586a5cb09e7a55d24) postgresqlPackages.temporal_tables: 1.2.0 -> 2021-02-20
* [`3341300c`](https://github.com/NixOS/nixpkgs/commit/3341300ca71af9f8242a5e9e08ebe4dffb3dd5fc) pdisk: Fix duplicated id parameter in patch URL
* [`18b4f3c9`](https://github.com/NixOS/nixpkgs/commit/18b4f3c939a6a16a8ea8489b9e3e7408ab31ffe2) sq: 0.20.0 -> 0.24.0
* [`d7c81d6c`](https://github.com/NixOS/nixpkgs/commit/d7c81d6c7314d04beaa44b020bf3308864c2f9bf) rav1e: 0.6.1 -> 0.6.3
* [`991a22a7`](https://github.com/NixOS/nixpkgs/commit/991a22a7d0aa93784370407fb2657f20f52c6dd3) licenses: Remove unnecessary archive.org link for APSL-1.0
* [`34bb2681`](https://github.com/NixOS/nixpkgs/commit/34bb2681f5daa536f2ef9a9777644823d24e66f7) pdfstudio: remove libgccjit dependency
* [`9722f822`](https://github.com/NixOS/nixpkgs/commit/9722f8221842b409606f7d0af80fe2592f374071) shairport-sync: 3.3.9 -> 4.1.1
* [`6d154c8b`](https://github.com/NixOS/nixpkgs/commit/6d154c8b251fc3dc9f1d8a403372030be8882567) looking-glass-client: B5.0.1 -> B6
* [`9fa5c1f0`](https://github.com/NixOS/nixpkgs/commit/9fa5c1f0a85f83dfa928528a33a28f063ae3858d) looking-glass-client: add j-brn to maintainers
* [`0710a736`](https://github.com/NixOS/nixpkgs/commit/0710a736c55c4cdbd17743c1e6ff0dfd8bd3009f) python310Packages.systemd: 234 -> 235, adopt, run tests
* [`d2823723`](https://github.com/NixOS/nixpkgs/commit/d2823723cc77bc8d530dc441b1253473ac03521c) slack: add conditional-flag "--enable-features=WebRTCPipeWireCapturer" for screensharing under wayland
* [`30081adc`](https://github.com/NixOS/nixpkgs/commit/30081adcd56e046701a7209fd58f1695a442d660) nixos/docker: add "local" as valid logDriver option
* [`11fa1795`](https://github.com/NixOS/nixpkgs/commit/11fa179533f0b4328647072092acd838f5313757) nixos/postfix: restrict inet_protocols to ipv4 when ipv6 is disabled
* [`c44b8049`](https://github.com/NixOS/nixpkgs/commit/c44b804901fee5b71690b2fe932979422400d47a) lens: move default.nix to linux.nix
* [`e4af93b2`](https://github.com/NixOS/nixpkgs/commit/e4af93b2200ab4bc1a6c2de0754d93aab4e1d196) lens: add aarch64-darwin support
* [`0de0ab5f`](https://github.com/NixOS/nixpkgs/commit/0de0ab5f9d88b27de4b771040a09f1dc77a772e8) gitea-actions-runner: init at unstable
* [`c8ed3c29`](https://github.com/NixOS/nixpkgs/commit/c8ed3c29621a1e8dd63a7d7e8b436f2e89cf3172) linuxPackages: bump default 5.15 -> 6.1
* [`fa7fbe56`](https://github.com/NixOS/nixpkgs/commit/fa7fbe565ded463f2864f128e8d467d0fd53bdff) nixos/paperless: apply nixpkgs-fmt
* [`e961b3bf`](https://github.com/NixOS/nixpkgs/commit/e961b3bf8d28e0007069e8cd01a31af986601dc0) dolibarr: 16.0.3 -> 16.0.4
* [`919f2b2b`](https://github.com/NixOS/nixpkgs/commit/919f2b2b6292436570613e7f7166eb992b12255f) nixos/borgmatic: Allow defining multiple configurations
* [`3c6be4ce`](https://github.com/NixOS/nixpkgs/commit/3c6be4cec71023f4b88407b343c752a210afde45) arcanPackages.arcan: cosmetic rewrite
* [`3cb73a65`](https://github.com/NixOS/nixpkgs/commit/3cb73a653bd2e643c3effc78a29e5ba06ac3011a) arcanPackages.prio: cosmetic rewrite
* [`d39b1260`](https://github.com/NixOS/nixpkgs/commit/d39b1260365d040a0fef49082eb7cd3e622c3cce) arcanPackages.cat9: unstable-2018-09-13 -> unstable-2023-02-11
* [`fbac91e0`](https://github.com/NixOS/nixpkgs/commit/fbac91e0bab383d405b3150d98cc1c6ded2a5c74) arcanPackages.durden: unstable-2022-10-16 -> unstable-2023-01-19
* [`f60c5a80`](https://github.com/NixOS/nixpkgs/commit/f60c5a80b0d6074e86d7cee7f93e9955cf248587) arcanPackages.pipeworld: unstable-2022-04-03 -> unstable-2023-02-05
* [`d9f8b180`](https://github.com/NixOS/nixpkgs/commit/d9f8b18044c63c0649491486db1c1dce0153f3f7) vscode: Explicitly disable integration tests
* [`8db2dbb6`](https://github.com/NixOS/nixpkgs/commit/8db2dbb6cb20d9f8d1974f4986fe34858b8a77ec) ceres-solver: Add and propagate metis dependency
* [`a65374c4`](https://github.com/NixOS/nixpkgs/commit/a65374c436140880a6cd457138f33473a849e65d) scilab-bin: refactor
* [`5e86cc98`](https://github.com/NixOS/nixpkgs/commit/5e86cc98d713ff8cf57cc0ae876922ca570aca44) discord: disableBreakingUpdates: create settings.json when missing
* [`e68c7797`](https://github.com/NixOS/nixpkgs/commit/e68c7797ab08abfd0edc5bdab5e710d428792b42) dune_3: 3.6.2 -> 3.7.0
* [`1c3dea1a`](https://github.com/NixOS/nixpkgs/commit/1c3dea1aebc827c935933bd34e3212adab0465ac) fead: init at 0.1.3
* [`5479767f`](https://github.com/NixOS/nixpkgs/commit/5479767f2cc2ef1baa5b20c3ff476e5431d462fa) libaosd: mark broken on darwin
* [`900e57fa`](https://github.com/NixOS/nixpkgs/commit/900e57fab288551efc8739fe486fd5337ea2455e) qscintilla: fix darwin builds
* [`0a2cc62b`](https://github.com/NixOS/nixpkgs/commit/0a2cc62b54781b66e58b239a7655a44d96642564) qownnotes: fix darwin build
* [`94514596`](https://github.com/NixOS/nixpkgs/commit/94514596ea56c507cbee40dc180385a7add8c034) quasselDaemon,libsForQt5.qca-qt5: fix darwin build
* [`fe2d070d`](https://github.com/NixOS/nixpkgs/commit/fe2d070d7e81724f87d99e18801cf1439d2e27e1) all-cabal-hashes: 2023-02-13T17:53:53Z -> 2023-02-19T09:15:19Z
* [`cc9672e5`](https://github.com/NixOS/nixpkgs/commit/cc9672e57c14ef38ada91bd3e29f36a948a94c34) haskellPackages: regenerate package set based on current config
* [`d1b90447`](https://github.com/NixOS/nixpkgs/commit/d1b904479ada49377a933a1744d39305e5afc49f) haskellPackages.h-raylib, haskellPackages.bytepatch: unmark broken
* [`e7054c7d`](https://github.com/NixOS/nixpkgs/commit/e7054c7d32f34771fe19508bef475ce9781d7443) haskellPackages.tdlib: patch for aeson >= 2.0 compat
* [`98be10b1`](https://github.com/NixOS/nixpkgs/commit/98be10b1999fedba13c8cde7779bb990fb75d03f) git-annex: update sha256 for 10.20230214
* [`a5821740`](https://github.com/NixOS/nixpkgs/commit/a5821740f82f136fa3f7e9bf88bcfe6ac8e1a62a) haskell.packages.*.[cC]abal*: use process 1.6.17.0 for GHC < 9.2.5
* [`16078721`](https://github.com/NixOS/nixpkgs/commit/16078721aae76dee5b82f643eb211fa7b9aa0796) release-haskell.nix: don't try building known to fail js backends
* [`b7e41b82`](https://github.com/NixOS/nixpkgs/commit/b7e41b825ea3b2f897112c7f0810508b0e8b9d5e) maintainers/haskell: generate core-pkgs hackage2nix configuration
* [`b5b5a192`](https://github.com/NixOS/nixpkgs/commit/b5b5a192108e201f19a3923564a86f93bf15035e) haskellPackages.espial: Jailbreak to avoid upper bound on bytestring
* [`51cde6c8`](https://github.com/NixOS/nixpkgs/commit/51cde6c87d0672c03a69460bd5800406c2a6455f) haskellPackages.espial: Add dalpd as the maintainer
* [`dbe67812`](https://github.com/NixOS/nixpkgs/commit/dbe678126b8296ce444087f0ea0efa66d109b003) haskellPackages.patat: Add dalpd as the maintainer
* [`bda7e527`](https://github.com/NixOS/nixpkgs/commit/bda7e527de5efa69743b0854710116ed14b2d33f) hedgedoc: 1.9.6 -> 1.9.7, remove inactive maintainer
* [`0debf145`](https://github.com/NixOS/nixpkgs/commit/0debf1453d66decb3e2e89d957e492f8fc791e94) maintainers/scripts/haskell/hydra-report: Add comments with error causes to broken list
* [`30e6c20c`](https://github.com/NixOS/nixpkgs/commit/30e6c20c2df566548af4d576e3b2e18a11633e3f) matrix-synapse.plugins.matrix-synapse-mjolnir-antispam: mark broken on darwin, update homepage, don't propagate matrix-synapse
* [`bbc8fd76`](https://github.com/NixOS/nixpkgs/commit/bbc8fd76c93fec20db36787bee0c88ded9802697) matrix-synapse.plugins.matrix-synapse-ldap3: 0.1.5 -> 0.2.2
* [`935a4e00`](https://github.com/NixOS/nixpkgs/commit/935a4e0039c5fc970a05fff8454c4f1d93f33756) matrix-synapse.plugins.matrix-synapse-pam: complete meta, add import check
* [`653dc22f`](https://github.com/NixOS/nixpkgs/commit/653dc22fa1eec8f8142bdaf3c072c260ff7f2dc9) haskell.packages.ghc94.ormolu: fix eval by bumping version
* [`9bff8435`](https://github.com/NixOS/nixpkgs/commit/9bff8435da488dd4e43bccc485c0b2bb03aff1d2) xemu: cosmetic rewrite
* [`49e647d1`](https://github.com/NixOS/nixpkgs/commit/49e647d1bdd7dadb3fbd07152ea7e7cfe13ba2f6) govulncheck: unstable-2022-09-02 -> unstable-2023-02-17
* [`320cb598`](https://github.com/NixOS/nixpkgs/commit/320cb5981592aad6544b6c1820132d0804aa868d) xemu: refactor installPhase
* [`31b278f6`](https://github.com/NixOS/nixpkgs/commit/31b278f6ade7f3a5a4ea9482a859839864edacdd) xemu: add meta attributes
* [`4c296f58`](https://github.com/NixOS/nixpkgs/commit/4c296f58dff81cabe74ab6ac82e5edfef4e25916) ldb: copy cross fix from tevent
* [`a9c47ffc`](https://github.com/NixOS/nixpkgs/commit/a9c47ffc867d75fd58d2a6028e287aa6c6bfd1d5) winetricks: 20220411 -> 20230212
* [`8e89e1cd`](https://github.com/NixOS/nixpkgs/commit/8e89e1cd8bca8cbb86c1aa5c7ca0a58418d1bf6e) displaycal: init at 3.9.10
* [`3794c04d`](https://github.com/NixOS/nixpkgs/commit/3794c04d798c39755f36718b650172c1ae7ff6f9) nixos/manual: fix manpage links
* [`0236dcb5`](https://github.com/NixOS/nixpkgs/commit/0236dcb59fb7b58f0ba5fee3ff15cc88ba903d61) nixos-render-docs: don't use markdown-it RendererProtocol
* [`6f253fc7`](https://github.com/NixOS/nixpkgs/commit/6f253fc70b5f21fde4a61f873650778478cdcc30) nixos-render-docs: drop options, env parameters
* [`068916ae`](https://github.com/NixOS/nixpkgs/commit/068916ae8fccebf137ffe68b511bff26f1069ef8) nixos-render-docs: keep revision in renderer, not converter
* [`5b8be28e`](https://github.com/NixOS/nixpkgs/commit/5b8be28e66a31ba4683d0fc337f67a46d5db8f9a) nixos-render-docs: don't render options during manual parsing
* [`2ab8e742`](https://github.com/NixOS/nixpkgs/commit/2ab8e742a541659baa0470e3be8fc7e01ff51175) nixos-render-docs: move recursive manual parsing to base class
* [`a7c25bb0`](https://github.com/NixOS/nixpkgs/commit/a7c25bb01f2373eb1f113272731e1659bc91de95) nixos-render-docs: add Freezable class
* [`7b0824c0`](https://github.com/NixOS/nixpkgs/commit/7b0824c0031dd65e1abd6d88ca537a90d4dfbe23) nixos-render-docs: check heading presence during parsing
* [`ba201144`](https://github.com/NixOS/nixpkgs/commit/ba201144605ed4ba83d165a37c3660ef2b49b193) nixos-render-docs: check heading continuity
* [`163b6673`](https://github.com/NixOS/nixpkgs/commit/163b667352e19411473fdf8603f0883c1b106d58) nixos-render-docs: require headings to have ids
* [`768794d6`](https://github.com/NixOS/nixpkgs/commit/768794d6c11b5e37f954405a3f03d63ef45897f6) nixos-render-docs: check book structure
* [`23dc31a9`](https://github.com/NixOS/nixpkgs/commit/23dc31a9755cf34a2040fe574798c09d1c857df0) nixos-render-docs: allow for options in include blocks
* [`7a74ce51`](https://github.com/NixOS/nixpkgs/commit/7a74ce51a1643aa6e83c912203bb6c3a987376b9) nixos-render-docs: add toc generator
* [`82e62614`](https://github.com/NixOS/nixpkgs/commit/82e62614e9171981a3972940b8e96e02c7e55f83) nixos-render-docs: add html renderer
* [`d520d55d`](https://github.com/NixOS/nixpkgs/commit/d520d55dee017fff8b3d0682260e12a27035378e) nixos-render-docs: add options html renderer
* [`feaa97e5`](https://github.com/NixOS/nixpkgs/commit/feaa97e5dcbb889404442ebe952357ef927d17ca) nixos-render-docs: render directly from file to file
* [`36f04733`](https://github.com/NixOS/nixpkgs/commit/36f04733ddc40beb54659f290aaf369d380f312b) nixos-render-docs: add manual html converter
* [`54f4992e`](https://github.com/NixOS/nixpkgs/commit/54f4992e80df3b8007dd8235c9f8d6ec77eef16f) nixos/manual: render html with nixos-render-doc if !allowDocBook
* [`5de1cdfc`](https://github.com/NixOS/nixpkgs/commit/5de1cdfcfc02a345bbe4b31871de404860dcb991) pulumiPackages.pulumi-command: init at 0.7.1
* [`5199f94e`](https://github.com/NixOS/nixpkgs/commit/5199f94e6583d787a1ddcdc6501dec83056cb710) python310Packages.pulumi-command: init at 0.7.1
* [`a4f63a6e`](https://github.com/NixOS/nixpkgs/commit/a4f63a6e772af8a4062800ea616d4c8b6148dc51) nixos/no-x-libs: hide qt5's self
* [`3733933e`](https://github.com/NixOS/nixpkgs/commit/3733933e489987dbca2b4e54f3058cd87ea0258f) ArchiSteamFarm: 5.4.1.11 -> 5.4.2.13
* [`d9e8d5d8`](https://github.com/NixOS/nixpkgs/commit/d9e8d5d8c199c8c88729583bfd4b483ad18f4aee) etesync-dav: fix broken dependancies
* [`884edcc2`](https://github.com/NixOS/nixpkgs/commit/884edcc23a1e7fc6de1186463d76e32e4a7dd667) grafana-dash-n-grab: init at 0.3.1
* [`92b71b5b`](https://github.com/NixOS/nixpkgs/commit/92b71b5be970528ad5ad0d4c57abcba1da4c8b94) maintainers: add wraithm
* [`6f12b6e1`](https://github.com/NixOS/nixpkgs/commit/6f12b6e1295f687f3f63501640b54e158421b48a) matrix-synapse.plugins.matrix-http-rendezvous-synapse: init at 0.1.12
* [`540fb7a2`](https://github.com/NixOS/nixpkgs/commit/540fb7a27074eec677266b218e8bbe9a385cbfa5) kubo-migrator: fix broken migrations
* [`9c878608`](https://github.com/NixOS/nixpkgs/commit/9c87860827088ab5bcde8718bde99c40a4c533b6) kubo-migrator: add migration from 12 to 13
* [`912441ef`](https://github.com/NixOS/nixpkgs/commit/912441ef4fff147ef9cb629e584ed89e57be482e) mathematica: 13.2.0 -> 13.2.1
* [`053c4dea`](https://github.com/NixOS/nixpkgs/commit/053c4dea8ff06c757c58f1393fbc4140a81b1513) clash-verge: init at 1.2.3
* [`9dafd18b`](https://github.com/NixOS/nixpkgs/commit/9dafd18b8059dd80023e28a8d042604273edd660) graalvm19-ce: init at 22.3.1
* [`fd18361c`](https://github.com/NixOS/nixpkgs/commit/fd18361c85b13c4e70922c92cab5468da9d6c109) maintainers.nix: add myself
* [`166ec8a5`](https://github.com/NixOS/nixpkgs/commit/166ec8a5ec7c14b1f3633883701bc0e25b77194c) python310Packages.execnb: init at 0.1.4
* [`460911e6`](https://github.com/NixOS/nixpkgs/commit/460911e6e72d06b189fe0f1889c1a94b15b4af0c) python310Packages.fastdownload: init at 0.0.6
* [`cdd01b98`](https://github.com/NixOS/nixpkgs/commit/cdd01b988d3df152931137c401906ec6b87248e0) python310Packages.nbdev: init at 2.3.11
* [`e9be4207`](https://github.com/NixOS/nixpkgs/commit/e9be42072d493a2696579ed21eb187da6fb52b25) python310Packages.fastai: init at 2.7.10
* [`9b540a87`](https://github.com/NixOS/nixpkgs/commit/9b540a871dc3491f3d68af98f88c14266d8a5a98) haskellPackages.swisstable: "reflect" AVX2 requirement in platforms
* [`0f74c643`](https://github.com/NixOS/nixpkgs/commit/0f74c643227974d445a942973efc4ca7f1f7ca3e) span-lite: init at 0.10.3
* [`d6942e22`](https://github.com/NixOS/nixpkgs/commit/d6942e22f1944802b85cc40515b27cfcc9ae22a1) openloco: init at 23.02
* [`e52a73d1`](https://github.com/NixOS/nixpkgs/commit/e52a73d184eafbd7406e4b3540a766ad35751c35) obs-hyperion: 1.0.1 -> 1.0.2
* [`6dc3f22a`](https://github.com/NixOS/nixpkgs/commit/6dc3f22ae7ef5f3c001e211ff335fabb1a7e3219) snappy: unbreak build
* [`1df0e06d`](https://github.com/NixOS/nixpkgs/commit/1df0e06d540ac88153860df4874bd2294f9d92b0) haskell-tensorflow: unbreak build
* [`7f658519`](https://github.com/NixOS/nixpkgs/commit/7f65851908ad5ab883778f32e70d236319d07c71) Revert "haskellPackages.heystone: fix darwin dylibs"
* [`857636b0`](https://github.com/NixOS/nixpkgs/commit/857636b0327ad7e092ec6cbd71a7735c885cbebd) teleport: 11.3.4 -> 12.0.2
* [`ec1a40dc`](https://github.com/NixOS/nixpkgs/commit/ec1a40dc2a90ebd57caed707283301c21f3ef2fd) sketchybar: 2.13.2 -> 2.14.1
* [`f78d225b`](https://github.com/NixOS/nixpkgs/commit/f78d225b92a6ccb817ed8ffe8833f72240c8a401) python3Packages.soundfile: 0.11.0 -> 0.12.1
* [`5210ddc7`](https://github.com/NixOS/nixpkgs/commit/5210ddc7017ea62d987bc646e9106793d6e1ae57) nixos/systemd-initrd: allow overriding initrdBin with extraBin
* [`ebdfdae1`](https://github.com/NixOS/nixpkgs/commit/ebdfdae156da6d3a94b3e5119f792e33334d6edb) nixos/paperless: download NLTK data
* [`7be1ecb2`](https://github.com/NixOS/nixpkgs/commit/7be1ecb2dca7eb5e9119f406bdb8aacaff4dcd0d) paperless-ngx: update homepage URL
* [`51894cc9`](https://github.com/NixOS/nixpkgs/commit/51894cc90010b2f9a85ea506c417424748513090) haskellPackages: regenerate package set based on current config
* [`40c2af49`](https://github.com/NixOS/nixpkgs/commit/40c2af4957c26bb13fb4a352309fba07df5c2f4b) gitlab-runner: 15.8.2 -> 15.9.0
* [`e867e3e4`](https://github.com/NixOS/nixpkgs/commit/e867e3e4f52736dfd46308b4875290c9b5d98520) maintainers: adding aaronarinder
* [`64a2ee45`](https://github.com/NixOS/nixpkgs/commit/64a2ee45ea50ecf50761e02d5c6badac6ea501d6) rover: 0.5.1 -> 0.11.0
* [`db8170d3`](https://github.com/NixOS/nixpkgs/commit/db8170d30796d3492971f01d41a939117bd39ab3) rover: adding aaronarinder as maintainer
* [`056e7c94`](https://github.com/NixOS/nixpkgs/commit/056e7c94f7186782e795bb648f70267022042a38) vieb: 9.5.1 -> 9.6.0
* [`c8a52f45`](https://github.com/NixOS/nixpkgs/commit/c8a52f451c4695b97eea53cab0ad64020f2483c1) minizinc: 2.6.4 -> 2.7.0
* [`ccc71550`](https://github.com/NixOS/nixpkgs/commit/ccc715503b8832d8494f022ca89fd668911821e8) virtiofsd: 1.5.0 -> 1.5.1
* [`06581ee7`](https://github.com/NixOS/nixpkgs/commit/06581ee7c74ae0fd62ff7d8d654942b79b463878) slint-lsp: 0.3.4 -> 0.3.5
* [`83d121fc`](https://github.com/NixOS/nixpkgs/commit/83d121fc5a4fc92c2512f42f21379b5ecc1fa4e0) slint-lsp: fix build on darwin
* [`02b0106d`](https://github.com/NixOS/nixpkgs/commit/02b0106dd68129d2f89d02b659c5af3d5206e46d) dufs: 0.31.0 -> 0.32.0
* [`163e6c07`](https://github.com/NixOS/nixpkgs/commit/163e6c07fdff1251f5135a21d8e2814cab274b65) python3Packages.soundfile: Fix build on aarch64-linux
* [`55f85c55`](https://github.com/NixOS/nixpkgs/commit/55f85c555d3b8e90cb4dc6549ed3333529b9ca94) bottles: 50.2 -> 51.5
* [`9ace1d89`](https://github.com/NixOS/nixpkgs/commit/9ace1d895c246d5a6fa9a405897d40f64b5167cd) haskell.compiler.ghc94*: backport Cabal bugfix for Paths_ modules
* [`8b2f23ff`](https://github.com/NixOS/nixpkgs/commit/8b2f23ff26880188b5a53414eb39205b9e378ddc) Add @⁠MrFreezeex as maintainer
* [`2a42048c`](https://github.com/NixOS/nixpkgs/commit/2a42048c897ade9bc234ac782e09ba4b14ad61e5) nushell: 0.75.0 -> 0.76.0
* [`3e22f9a4`](https://github.com/NixOS/nixpkgs/commit/3e22f9a497d0535916acc387cf284f1738cd3efa) python310Packages.python-openstackclient: 6.0.0 -> 6.1.0
* [`f933f5f5`](https://github.com/NixOS/nixpkgs/commit/f933f5f50ce591fa73b36b91f2bb96d9f82d0811) foxotron: 2022-11-02 -> 2023-02-23
* [`626a0ff9`](https://github.com/NixOS/nixpkgs/commit/626a0ff9fa580762fbf3cb93c914bf2f7e5a7d0a) gmic: fix linking against shared lib with cmake
* [`20121a61`](https://github.com/NixOS/nixpkgs/commit/20121a61171ea9f8be7f6fe1ecb81c01e46d5e03) portfolio: 0.61.0 -> 0.61.3
* [`28f9a2e3`](https://github.com/NixOS/nixpkgs/commit/28f9a2e3b61af0e361f4b491625ea16a139b3c21) opustags: 1.6.0 -> 1.7.0
* [`32898461`](https://github.com/NixOS/nixpkgs/commit/328984611ba69e569d9a0ba879b3e76ba932f971) sdrangel: 7.9.0 -> 7.10.0
* [`60ee2eaf`](https://github.com/NixOS/nixpkgs/commit/60ee2eaf54dece4ecc15f73b18569b623359af47) diamond: 2.1.1 -> 2.1.3
* [`47782b16`](https://github.com/NixOS/nixpkgs/commit/47782b16c5024cf775230ae0a659fab20b2a6efe) protonmail-bridge: 2.3.0 -> 3.0.18
* [`0ecf6ced`](https://github.com/NixOS/nixpkgs/commit/0ecf6ced8f1cb3827958c176412ffc595efb1b95) snappymail: 2.26.0 -> 2.26.3
* [`677e62b9`](https://github.com/NixOS/nixpkgs/commit/677e62b9b166a495ca28b1ff2fa24c66440a627d) semodule-utils: 3.4 -> 3.5
* [`434c3ea4`](https://github.com/NixOS/nixpkgs/commit/434c3ea46cf53cc6004c94ea738d5459185b7170) magma: init 2.7.1; migrate to cudaPackages
* [`5d419ff3`](https://github.com/NixOS/nixpkgs/commit/5d419ff33d70c52192b22b019d6c5ba53fe866cf) opcr-policy: 0.1.47 -> 0.1.50
* [`510e2ccd`](https://github.com/NixOS/nixpkgs/commit/510e2ccd97f7fe392ebfc80212d4e78fcfdd06d1) cudnn: init 8.8.0; rewrite to assist maintainability
* [`522098e3`](https://github.com/NixOS/nixpkgs/commit/522098e3b54712d5800ae272994c2114a427d090) wasmtime: 5.0.0 -> 6.0.0
* [`d8d0cc1a`](https://github.com/NixOS/nixpkgs/commit/d8d0cc1a782dc27d7fb0e2c9d4a0f02c087993e7) bundlewrap: 4.16.0 -> 4.17.0
* [`355861a4`](https://github.com/NixOS/nixpkgs/commit/355861a4479962ad6b23e8fe3cd5006b204deb90) quickmu: fix for spice-client-glib-usb-acl-helper
* [`fb15c693`](https://github.com/NixOS/nixpkgs/commit/fb15c693c331adbc548abf19fbe4eabfdef5adf1) widevine-cdm: merge with vivaldi-widevine
* [`66d83340`](https://github.com/NixOS/nixpkgs/commit/66d833402d02b09031a97ec4460702468f53e3b7) widevine-cdm: 4.10.2449.0 -> 4.10.2557.0
* [`d1aca2c1`](https://github.com/NixOS/nixpkgs/commit/d1aca2c12567eb801d470945ab0b468c9c45f569) lighthouse: 3.4.0 -> 3.5.0
* [`89bf849a`](https://github.com/NixOS/nixpkgs/commit/89bf849a27917ec745af3a79a3b58b835fddaad5) pkgsMusl: disable for i686-linux
* [`19c7b80b`](https://github.com/NixOS/nixpkgs/commit/19c7b80ba03f505d16db1450c9a3cfde4971d695) mediawiki: 1.39.1 -> 1.39.2
* [`239fd0fb`](https://github.com/NixOS/nixpkgs/commit/239fd0fbf52fcd4e61cfe03a79c61a8e77fa2048) sslsplit: fix build with openssl_3
* [`2085adc3`](https://github.com/NixOS/nixpkgs/commit/2085adc322a27d352bd2d2f4801c5a6bc0b0cf54) benthos: 4.11.0 -> 4.12.1
* [`a2842d7e`](https://github.com/NixOS/nixpkgs/commit/a2842d7eb7c567f35b0aba9fe2056077c8710397) qcad: 3.27.8.7 -> 3.27.9.2
* [`da816da5`](https://github.com/NixOS/nixpkgs/commit/da816da53fd87c0e373c32b96ba511bb38b0157d) jotta-cli: 0.14.60923 -> 0.15.75988
* [`bad5dc61`](https://github.com/NixOS/nixpkgs/commit/bad5dc61f3a18578607c54368c88ec885eebb4e4) xjadeo: 0.8.11 -> 0.8.12
* [`4d334eb4`](https://github.com/NixOS/nixpkgs/commit/4d334eb4e51786431c2ec906e530d38ecaa86b3d) linux: 4.14.306 -> 4.14.307
* [`99e80162`](https://github.com/NixOS/nixpkgs/commit/99e8016209350461bf8863f098dc367e667933d2) linux: 4.19.273 -> 4.19.274
* [`90d7fb05`](https://github.com/NixOS/nixpkgs/commit/90d7fb0502a5a7e6a485d828d88b591d4da38dd5) linux: 5.10.169 -> 5.10.170
* [`9b723ed0`](https://github.com/NixOS/nixpkgs/commit/9b723ed0cfccba4e042004adb8df258036ce000f) linux: 5.15.95 -> 5.15.96
* [`bb82baf1`](https://github.com/NixOS/nixpkgs/commit/bb82baf13c2e9297f88c6a24de59aa84908db157) linux: 5.4.232 -> 5.4.233
* [`bbec187a`](https://github.com/NixOS/nixpkgs/commit/bbec187ad195d911546b6c4e4be315f5bc4f81f0) linux: 6.1.13 -> 6.1.14
* [`62ff5149`](https://github.com/NixOS/nixpkgs/commit/62ff5149a10567d08c81ca898fe3f5d564a1c288) linux: 6.2 -> 6.2.1
* [`8397fc5e`](https://github.com/NixOS/nixpkgs/commit/8397fc5ed4d2efef82d85f263402c81c7036194d) linux-rt_5_15: 5.15.94-rt59 -> 5.15.95-rt60
* [`62b5c4ba`](https://github.com/NixOS/nixpkgs/commit/62b5c4ba75838b94bd60a461109be0fba9cbf775) linux/hardened/patches/4.14: 4.14.305-hardened1 -> 4.14.307-hardened1
* [`bac3918b`](https://github.com/NixOS/nixpkgs/commit/bac3918ba6d1bd6c34984d9a4dc1aef9ccbfead4) linux/hardened/patches/4.19: 4.19.272-hardened1 -> 4.19.274-hardened1
* [`e3b330c1`](https://github.com/NixOS/nixpkgs/commit/e3b330c1f3ef71f74165b334ee611bc835890fb5) linux/hardened/patches/5.10: 5.10.168-hardened1 -> 5.10.170-hardened1
* [`699d7016`](https://github.com/NixOS/nixpkgs/commit/699d70160683ed55e87a52c44f88f17adac0a879) linux/hardened/patches/5.15: 5.15.94-hardened1 -> 5.15.96-hardened1
* [`71039ab2`](https://github.com/NixOS/nixpkgs/commit/71039ab2cfd64e936a4088f6c5746ad0e5b73860) linux/hardened/patches/5.4: 5.4.231-hardened1 -> 5.4.233-hardened1
* [`47ae0917`](https://github.com/NixOS/nixpkgs/commit/47ae09178b5d5369ac42b40d3f43cdf605075ac2) linux/hardened/patches/6.1: 6.1.12-hardened1 -> 6.1.14-hardened1
* [`c27db2a9`](https://github.com/NixOS/nixpkgs/commit/c27db2a9d6ed1bb77addd3e2ff40d7510db48a2f) i2pd: 2.46.0 -> 2.46.1
* [`bb62d57a`](https://github.com/NixOS/nixpkgs/commit/bb62d57a851706efd5a69149acd5fe64c76b1de1) haskellPackages.cabal2nix-unstable: 2023-02-15 -> 2023-02-25
* [`68e85028`](https://github.com/NixOS/nixpkgs/commit/68e85028e5918ff22786e8aa5dfd58aa15a3c9ae) nodenv: 1.4.0 -> 1.4.1
* [`7d530fdb`](https://github.com/NixOS/nixpkgs/commit/7d530fdb9957f83882a0d1a78b76fd5be70199df) nextcloud-notify_push: 0.5.0 -> 0.6.0
* [`c4bd0e0f`](https://github.com/NixOS/nixpkgs/commit/c4bd0e0f56d187799f1f6921635dd432a1041d51) thedesk: 24.0.8 -> 24.0.10
* [`030638a3`](https://github.com/NixOS/nixpkgs/commit/030638a3620c9bf9fc3565096d1666ca93e5c724) benthos: add changelog to meta
* [`3436e4b1`](https://github.com/NixOS/nixpkgs/commit/3436e4b1eeab4a7d90b5b83198bca19a1fd9b1f8) benthos: equalize
* [`4fa61c7d`](https://github.com/NixOS/nixpkgs/commit/4fa61c7d7921785895f25dbda2d3a5404bf0b053) pyradio: 0.9.0 -> 0.9.1
* [`95ca5f57`](https://github.com/NixOS/nixpkgs/commit/95ca5f576c7258b0e011e48458548c215f4c503f) bcftools: 1.16 -> 1.17
* [`f3f74ac6`](https://github.com/NixOS/nixpkgs/commit/f3f74ac6c7c622311585b9669fe58af4aea32d15) wireless-regdb: 2022.08.12 -> 2023.02.13
* [`c4744988`](https://github.com/NixOS/nixpkgs/commit/c4744988ff31f378881b0d3859db3d5cabc6ca4a) glew: fix cmake's FindGLEW.cmake by adding more cmake target properties
* [`30e1b25e`](https://github.com/NixOS/nixpkgs/commit/30e1b25efef9f2b9b0ec0fc6053915929189c241) pcm: 202211 -> 202302
* [`2235d00b`](https://github.com/NixOS/nixpkgs/commit/2235d00b44cc4cac653167f4b4f0f2bba5862ed0) aws-sso-cli: 1.9.6 -> 1.9.9
* [`1d8d2e40`](https://github.com/NixOS/nixpkgs/commit/1d8d2e408c53c3361c5c5e8dffeca8842bc789ed) asdf-vm: 0.11.1 -> 0.11.2
* [`90aebced`](https://github.com/NixOS/nixpkgs/commit/90aebced348d679f034c6cfefc13e66197573f7d) go-task: 3.20.0 -> 3.21.0
* [`15f1369b`](https://github.com/NixOS/nixpkgs/commit/15f1369b95d04a90fcb4ac1e5e59f2d2dfe154db) Revert "nixos/systemd-coredump: guard static gid for systemd-coredump behind state version"
* [`ee6517a9`](https://github.com/NixOS/nixpkgs/commit/ee6517a915424f7d7a07f6d1fddf8fd2f5b04a2c) Revert "nixos/polkit: guard static gid for polkituser behind state version"
* [`724569db`](https://github.com/NixOS/nixpkgs/commit/724569db28ffb82d8f8063162bbbd4bf4d6deb86) fortune: 3.14.1 -> 3.16.0
* [`32422ca1`](https://github.com/NixOS/nixpkgs/commit/32422ca13d14ebe54bb5e3889b74009af18400bc) deno: 1.30.3 -> 1.31.1
* [`515b3009`](https://github.com/NixOS/nixpkgs/commit/515b3009c1c4865f0bdf49e12ab1cf8b8a02238b) scryer-prolog: replace patch with environment variable, clean up
* [`d3630d1d`](https://github.com/NixOS/nixpkgs/commit/d3630d1d70456ad12972d0ca3ae4154af0ba08f0) go-mockery: 2.20.0 -> 2.20.2
* [`fc547a8f`](https://github.com/NixOS/nixpkgs/commit/fc547a8f8d9689113c28d0fcbc64321e0877e96a) go-graft: 0.2.17 -> 0.2.18
* [`3a0b1aff`](https://github.com/NixOS/nixpkgs/commit/3a0b1aff7a8e98c7e8fccd99f0bd431c39dff300) trashy: remove patch, clean up
* [`013d612e`](https://github.com/NixOS/nixpkgs/commit/013d612e59d0b3fa3602101cc374500f375e466c) book-summary: switch to fetchCrate to remove patch
* [`1747570c`](https://github.com/NixOS/nixpkgs/commit/1747570c5808c4ef0e53f7ff6b5ef245d881b5c2) micronaut: 3.8.4 -> 3.8.5
* [`9a8272bd`](https://github.com/NixOS/nixpkgs/commit/9a8272bd0120b39e4a3825ae0a4a0332aab098c8) nixos/tests/txredisapi: stop using python38
* [`265f5b47`](https://github.com/NixOS/nixpkgs/commit/265f5b47391825f2b05a175cc571bb2710d80893) python310Packages.fastavro: 1.7.1 -> 1.7.2
* [`f3e9abfb`](https://github.com/NixOS/nixpkgs/commit/f3e9abfb9e81dd30455010586b039e8251a672e4) cppcheck: 2.10 -> 2.10.1
* [`5c470aa9`](https://github.com/NixOS/nixpkgs/commit/5c470aa92b3a469b91a92414abe723752bf2966b) minio: 2023-02-17T17-52-43Z -> 2023-02-22T18-23-45Z
* [`b783f87f`](https://github.com/NixOS/nixpkgs/commit/b783f87fc2aca6e291fc3adc50988d8b9679dd8e) ameba: 1.4.1 -> 1.4.2
* [`0309bd6a`](https://github.com/NixOS/nixpkgs/commit/0309bd6a4c5d10e7ba1be385806a09689f6e9f14) typos: 1.13.10 -> 1.13.12
* [`828e8214`](https://github.com/NixOS/nixpkgs/commit/828e8214f4d8e8eb2cb72d2eed4cc46b77532107) prometheus-haproxy-exporter: 0.14.0 -> 0.15.0
* [`953997c5`](https://github.com/NixOS/nixpkgs/commit/953997c5c24a7431c2ddeca96a1d6011657bb532) ddccontrol-db: 20230124 -> 20230223
* [`eaa2576c`](https://github.com/NixOS/nixpkgs/commit/eaa2576cf7dcefd1328194cc8d75c28fedcd4398) helmsman: 3.16.1 -> 3.16.4
* [`25915c63`](https://github.com/NixOS/nixpkgs/commit/25915c636a47c8a0b17359e314309df9614c040e) avalanchego: 1.9.8 -> 1.9.9
* [`d5b65a22`](https://github.com/NixOS/nixpkgs/commit/d5b65a225349cdea9b4edecbfaa546f01f6d2149) mark: 8.7 -> 8.8
* [`a5d69be8`](https://github.com/NixOS/nixpkgs/commit/a5d69be8104375c3a8a73fa828f64dc59bd03071) denaro: 2023.2.0 -> 2023.2.2
* [`42222b99`](https://github.com/NixOS/nixpkgs/commit/42222b99947c326ed5d63439b72e5d6da7a2f8d5) naabu: 2.1.1 -> 2.1.2
* [`41ff17b1`](https://github.com/NixOS/nixpkgs/commit/41ff17b16124b450a4864ac7ec0ab36f757aafa3) naabu: add changelog to meta
* [`742cdb45`](https://github.com/NixOS/nixpkgs/commit/742cdb455fc2dc36c85d9485b071220695b096b9) maintainers: add pinkcreeper100
* [`eec584d6`](https://github.com/NixOS/nixpkgs/commit/eec584d627fe0ab5675ebecfc5b6d68d7570d02c) findex: init at v0.7.1
* [`fd3e2b49`](https://github.com/NixOS/nixpkgs/commit/fd3e2b49f4a3138a1c3e2dd854578f64b9c772cd) gmic-qt: fix build with 3.2.1
* [`79cd7639`](https://github.com/NixOS/nixpkgs/commit/79cd76390cbaafbcbebf1e55b30d6a064e950908) python310Packages.meshtastic: add setuptools
* [`2faf6b3a`](https://github.com/NixOS/nixpkgs/commit/2faf6b3aa7d85706772a9560056d41cc7f0d7985) xorg.xf86videoamdgpu: 21.0.0 -> 23.0.0
* [`82964d16`](https://github.com/NixOS/nixpkgs/commit/82964d16945b77a3db503ff6db6c693ca6c20476) nixos/x11: default to the modesetting driver
* [`2a251817`](https://github.com/NixOS/nixpkgs/commit/2a251817f423a786fc7c0695c326b8e8012a0086) swaynotificationcenter: 0.7.3 -> 0.8.0
* [`0dc54aae`](https://github.com/NixOS/nixpkgs/commit/0dc54aaeb31443d1e4e1c4fc08b9ab0a2385e2cc) python310Packages.cnvkit: 0.9.9 -> 0.9.10
* [`ce1b8a70`](https://github.com/NixOS/nixpkgs/commit/ce1b8a7055a9180962e706bd1f0ff337937d3d71) wrangler_1: 1.20.0 -> 1.21.0
* [`44622373`](https://github.com/NixOS/nixpkgs/commit/44622373661e1f8bfeb728497e381f09f278d615) polkadot: 0.9.37 -> 0.9.38
* [`7b2d3277`](https://github.com/NixOS/nixpkgs/commit/7b2d32770ba8eede033ba00c0a492ba318ed28a6) nghttp3: 0.8.0 -> 0.9.0
* [`eec6c7a4`](https://github.com/NixOS/nixpkgs/commit/eec6c7a41c38e3196c78ea3c3539f250051d6752) linkerd_edge: 23.2.2 -> 23.2.3
* [`da3ecb18`](https://github.com/NixOS/nixpkgs/commit/da3ecb18d8f7f977e5352e1987dcf6840c7ae77c) python310Packages.django-cacheops: 6.1 -> 6.2
* [`e9c3f417`](https://github.com/NixOS/nixpkgs/commit/e9c3f417dd0f687979237c10eb7945ea2ab390ed) ubports-click: init at 22-02-2023
* [`a451a763`](https://github.com/NixOS/nixpkgs/commit/a451a7634d792734760c94afc8c5e3a9c154d820) vassal: 3.6.11 -> 3.6.12
* [`59462da9`](https://github.com/NixOS/nixpkgs/commit/59462da91769ff9d089a753a26ba77387349441d) nixos/lib/make-disk-image: expose memSize parameter
* [`0ec0b1ad`](https://github.com/NixOS/nixpkgs/commit/0ec0b1ad0d329f8a7c2e334f13293950c05b2822) treesheets: unstable-2023-02-14 -> unstable-2023-02-25
* [`bf935617`](https://github.com/NixOS/nixpkgs/commit/bf935617bf5af00664556c51420ca70bfc1e1418) kube-bench: 0.6.11 -> 0.6.12
* [`6ef0c6ab`](https://github.com/NixOS/nixpkgs/commit/6ef0c6ab9b763ec542cf7839483f3355f5f2b6d3) kube-bench: update fetcher
* [`8342c954`](https://github.com/NixOS/nixpkgs/commit/8342c954d189d428c1af052e1b1a775636165b0f) python310Packages.peaqevcore: 12.1.6 -> 12.2.0
* [`03640372`](https://github.com/NixOS/nixpkgs/commit/0364037265361de2e14e60cc126c776fc473b333) python3Packages.python-mpv-jsonipc: 1.1.14 -> 1.2.0
* [`c9793345`](https://github.com/NixOS/nixpkgs/commit/c9793345ddbc488c2229e3e3926b402bb11eea3c) jellyfin-mpv-shim: 2.4.2 -> 2.5.0
* [`91a05709`](https://github.com/NixOS/nixpkgs/commit/91a05709b6827bd57858107643e07049b1a806f1) grpc-gateway: 2.15.0 -> 2.15.1
* [`8af02a19`](https://github.com/NixOS/nixpkgs/commit/8af02a19970a0e25c73e275c9574662f63a18f89) python310Packages.django-cacheops: add changelog to meta
* [`af995c12`](https://github.com/NixOS/nixpkgs/commit/af995c12889486ddf4f00fb437cdd394a02cfda9) cloudflare-warp: 2022.8.936 -> 2023.1.133, add Cloudflare Zero Trust enrollment desktop file
* [`cbe45180`](https://github.com/NixOS/nixpkgs/commit/cbe45180d16129b1a591d204d0b6f01246c009bc) python310Packages.django-cacheops: disabled on unsupported Python releases
* [`ce7409ca`](https://github.com/NixOS/nixpkgs/commit/ce7409ca5648db0920ccfbabe8801b910f1bab9e) tpm2-tools: 5.4 -> 5.5
* [`b1fea486`](https://github.com/NixOS/nixpkgs/commit/b1fea486af1d2f641c386b274d923c383cad0f66) python310Packages.cnvkit: add changelog to meta
* [`f780ed4c`](https://github.com/NixOS/nixpkgs/commit/f780ed4c6844b7adc72c1d491a1f17211864d90d) python310Packages.cnvkit: normalize pname
* [`9eb255c5`](https://github.com/NixOS/nixpkgs/commit/9eb255c553de98a006d10226d30a646289a21c45) python310Packages.cnvkit: disable on unsupported Python releases
* [`76a4e078`](https://github.com/NixOS/nixpkgs/commit/76a4e078baef402607979fc97769e4b11c54c216) coursier: 2.1.0-M7 -> 2.1.0-RC6
* [`2e8740b3`](https://github.com/NixOS/nixpkgs/commit/2e8740b3a9637502680003457328ae3a871e23e4) armcord: 3.1.4 -> 3.1.6
* [`8c693ec9`](https://github.com/NixOS/nixpkgs/commit/8c693ec9acedb2983168be2e5e3e9b8e2a621ca7) python310Packages.azure-mgmt-containerservice: 21.1.0 -> 21.2.0
* [`a0521c92`](https://github.com/NixOS/nixpkgs/commit/a0521c92c0ab2d1ee6a74df6e94499184f314172) lighthouse: fix build on aarch64-darwin
* [`2bfa93e0`](https://github.com/NixOS/nixpkgs/commit/2bfa93e01c1574343236b8d0052ad5e2964a363c) treewide: python{ => .pythonForBuild}.interpreter
* [`eefba3de`](https://github.com/NixOS/nixpkgs/commit/eefba3de1d613465354457953bf571a670aaf558) rocblas: 5.4.2 -> 5.4.3
* [`0137d780`](https://github.com/NixOS/nixpkgs/commit/0137d7803f3b563e2983f29195ae815f613f957c) mqtt-benchmark: init at 0.2.0
* [`da79c193`](https://github.com/NixOS/nixpkgs/commit/da79c1937d8687f9b870bf3ff413ee90fc71be17) python310Packages.zigpy: 0.53.1 -> 0.53.2
* [`2d597fcc`](https://github.com/NixOS/nixpkgs/commit/2d597fccc12cfea2733196bbb0c612feb53791ff) python310Packages.mne-python: 1.3.0 -> 1.3.1
* [`bf16d007`](https://github.com/NixOS/nixpkgs/commit/bf16d007b8e967fa81fc21dbbeb7e6bf8726cd06) firefox-devedition-bin-unwrapped: 111.0b3 -> 111.0b5
* [`cf689615`](https://github.com/NixOS/nixpkgs/commit/cf68961533a453f2761178646af9ae87393c7426) rnr: 0.4.1 -> 0.4.2
* [`8d8c53c6`](https://github.com/NixOS/nixpkgs/commit/8d8c53c68923e235b53ff9e1995a490dded43798) python310Packages.deal: 4.23.7 -> 4.24.0
* [`99beb76d`](https://github.com/NixOS/nixpkgs/commit/99beb76ded0d6e76840b591cc12e1fa5f90848fc) python310Packages.gsd: 2.7.0 -> 2.8.0
* [`426ebe81`](https://github.com/NixOS/nixpkgs/commit/426ebe81e275d22dbd073b155bce1264c441a729) luarocks-nix: unstable-2022-10-12 -> unstable-2023-02-26
* [`56e5d60a`](https://github.com/NixOS/nixpkgs/commit/56e5d60a2488c043912f7dd4cbfffec974d8d6ca) go-dork: init at 1.0.2
* [`b4efe4c1`](https://github.com/NixOS/nixpkgs/commit/b4efe4c1d6fe96ec0e3cd8ee6bc0a688c3f786aa) furnace: 0.6pre3 -> 0.6pre4-hotfix
* [`bc8ef804`](https://github.com/NixOS/nixpkgs/commit/bc8ef8049b09401902652ce201d3bb1608eac161) librem: enableParallelBuilding=true
* [`141b35de`](https://github.com/NixOS/nixpkgs/commit/141b35de2d9239df42bd226508c7108f7632c39b) libre: enableParallelBuilding=true
* [`7e0e0528`](https://github.com/NixOS/nixpkgs/commit/7e0e0528176c9f4a4a4418ffc05f6f62ef733d6f) baresip: enableParallelBuilding=true
* [`526fa7ee`](https://github.com/NixOS/nixpkgs/commit/526fa7eefbb8325bc10f853a6b4e9f10429d84fe) python310Packages.pyoverkiz: 1.7.4 -> 1.7.6
* [`00dd8da1`](https://github.com/NixOS/nixpkgs/commit/00dd8da110160c7b7675e11c977d40f285656f7c) python310Packages.yalexs-ble: 2.0.3 -> 2.0.4
* [`2d6461ed`](https://github.com/NixOS/nixpkgs/commit/2d6461ed31f758d9f1896f06201da77e2ac59513) python310Packages.caldav: 1.1.3 -> 1.2.0
* [`58d79831`](https://github.com/NixOS/nixpkgs/commit/58d79831bfe54cf05d79516350898e026f3cda8b) python310Packages.caldav: add changelog to meta
* [`79aed270`](https://github.com/NixOS/nixpkgs/commit/79aed27012741dc9fab4c37189970b78d4b7b8c4) python310Packages.caldav: disable on unsupported Python releases
* [`86961ce9`](https://github.com/NixOS/nixpkgs/commit/86961ce993d7d323b2f237d948912bab34e6c684) _1password-gui: stable 8.9.14 -> 8.10.0, beta 8.10.0-20 -> 8.10.1-19
* [`6a4a0394`](https://github.com/NixOS/nixpkgs/commit/6a4a0394253df972617a4545340d9d5a7ec89bb9) boxxy: 0.3.4 -> 0.3.5
* [`fb7c2cdb`](https://github.com/NixOS/nixpkgs/commit/fb7c2cdb519dcffb3cd3b29b8179a306afaecd74) hplip: fix patch download link
* [`017522f6`](https://github.com/NixOS/nixpkgs/commit/017522f61adeea787e5f5d93c85b6d09eb639946) nextcloud{24,25}Packages: update
* [`9c421e59`](https://github.com/NixOS/nixpkgs/commit/9c421e593450e326ad08c2ceaccee608dcba9447) flyctl: 0.465 -> 0.470
* [`3dbe3e35`](https://github.com/NixOS/nixpkgs/commit/3dbe3e3507363226fd23e51647df984793acad5b) pv-migrate: 1.0.1 -> 1.1.0
* [`4af3342a`](https://github.com/NixOS/nixpkgs/commit/4af3342a93d39ab6bdb20814295cbeaf3f54d0b1) speedtest-rs: init at 0.1.4
* [`62c63224`](https://github.com/NixOS/nixpkgs/commit/62c632241bf12a1256c150cedf06fba040e8822b) luaPackages: update
* [`625157f8`](https://github.com/NixOS/nixpkgs/commit/625157f81dba706add1d4cc4db0363266eb76ac4) urbit: 1.20 -> 1.21
* [`69da0d24`](https://github.com/NixOS/nixpkgs/commit/69da0d24d9d393f980df0b2c117d2074f24d7612) colord: fix cross-compilation
* [`01c57a99`](https://github.com/NixOS/nixpkgs/commit/01c57a994afc663879be7c5c039e12221c1d1648) trivy: 0.37.2 -> 0.37.3
* [`3da83ed1`](https://github.com/NixOS/nixpkgs/commit/3da83ed15ad6d145e2104985c942dd1c21ac7a69) weston: fix cross-compilation
* [`519958c9`](https://github.com/NixOS/nixpkgs/commit/519958c94bbe5dd9a9b34f529e0a8e56afc40df1) nixos/lib/make-multi-disk-zfs-image: expose memSize parameter
* [`6d71c7c3`](https://github.com/NixOS/nixpkgs/commit/6d71c7c3e256786796e2f728978dbd05588df84a) python310Packages.datasets: 2.9.0 -> 2.10.0
* [`841c416f`](https://github.com/NixOS/nixpkgs/commit/841c416f0aab6e7433d5ef599d4e00eabaa6d64c) datree: 1.8.24 -> 1.8.27
* [`266609b0`](https://github.com/NixOS/nixpkgs/commit/266609b0e275a24699df5def4d42f739cb2db01c) arkade: 0.8.62 -> 0.9.0
* [`17c86704`](https://github.com/NixOS/nixpkgs/commit/17c86704733b93dd1251e77d53f4d0569550a8ff) psst: add wmclass to desktop file
* [`eb30f33d`](https://github.com/NixOS/nixpkgs/commit/eb30f33d0a89739e8739f0c4f13cd9a7e5f1e748) wtfis: 0.5.1 -> 0.6.1
* [`f66033d2`](https://github.com/NixOS/nixpkgs/commit/f66033d2903f8180deadcb8dfea5c234d5ca42f9) python310Packages.atlassian-python-api: 3.33.0 -> 3.34.0
* [`616b8466`](https://github.com/NixOS/nixpkgs/commit/616b8466344ef48e3377aa0a3100127ce496c324) python310Packages.google-cloud-pubsub: 2.14.1 -> 2.15.0
* [`59a2869c`](https://github.com/NixOS/nixpkgs/commit/59a2869c5ef9c947e0faf24162a55e6ba0b2717f) python310Packages.dkimpy: 1.0.5 -> 1.1.0
* [`f44d0c89`](https://github.com/NixOS/nixpkgs/commit/f44d0c895a5063f309d50dbaf7477841e30f64df) framac: 25.0 (Manganese) → 26.1 (Iron)
* [`78eda516`](https://github.com/NixOS/nixpkgs/commit/78eda5168cf3f3ebe88ed27bb680ee6479a777d4) commitizen: 2.42.0 -> 2.42.1
* [`496cb1e3`](https://github.com/NixOS/nixpkgs/commit/496cb1e30fb98d430754650c88ef7a46e8dcc4b8) mmdoc: 0.13.0 -> 0.14.0; fix darwin build
* [`924cc033`](https://github.com/NixOS/nixpkgs/commit/924cc0331c34273df859b91cce653fc4b91739e7) zfxtop: init at 0.2.1
* [`b958bc9b`](https://github.com/NixOS/nixpkgs/commit/b958bc9bdb6d0a00222848d7b87f1dd7f17152bf) python310Packages.ffmpeg-progress-yield: 0.7.0 -> 0.7.1
* [`765fff92`](https://github.com/NixOS/nixpkgs/commit/765fff9297774662a9bf6026395da900dfc32024) terraform-providers.lxd: 1.9.0 → 1.9.1
* [`89990aea`](https://github.com/NixOS/nixpkgs/commit/89990aeae85ac18c5b6ae416e4b111a56bb5747b) python310Packages.ffmpeg-progress-yield: add changelog to meta
* [`35260272`](https://github.com/NixOS/nixpkgs/commit/35260272d4f4b023754b12ca6335899ce4586e7d) python310Packages.ffmpeg-progress-yield: disable on unsupported Python releases
* [`9f153970`](https://github.com/NixOS/nixpkgs/commit/9f1539702dd9603a5f4074e43aeb7696d8d94a4e) rich-cli: fix dependency versions
* [`fca0501c`](https://github.com/NixOS/nixpkgs/commit/fca0501c76e38f4ef375f1581770598144803e2e) crystfel: 0.10.1 → 0.10.2
* [`d2306aa5`](https://github.com/NixOS/nixpkgs/commit/d2306aa5ec33dec45019c1a5a57db39813a7381d) wireguard-go: 0.0.20220316 -> 0.0.20230223
* [`04aa4172`](https://github.com/NixOS/nixpkgs/commit/04aa417225803b968d7ad7b5a1db97f9b5149b71) ombi: 4.22.5 -> 4.35.10
* [`081f28c0`](https://github.com/NixOS/nixpkgs/commit/081f28c0a0c433593ad3e53896ca257367866727) ntfy-sh: 2.0.1 -> 2.1.0
* [`f1698cbb`](https://github.com/NixOS/nixpkgs/commit/f1698cbb38f9c5c4c13284e1e48d808868089618) texlab: 5.2.0 -> 5.3.0
* [`ec666e51`](https://github.com/NixOS/nixpkgs/commit/ec666e514bf720f5a9c57db1ef69de2eec91496c) uid_wrapper: 1.2.9 -> 1.3.0
* [`51d6b4cc`](https://github.com/NixOS/nixpkgs/commit/51d6b4cc2798e6989ff893ee43159cc02392faec) dbx: add changelog to meta
* [`faa5ecad`](https://github.com/NixOS/nixpkgs/commit/faa5ecad9da89e42fe7f8376e29326a5892c7953) dbx: 0.7.6 -> 0.8.8
* [`369ab08b`](https://github.com/NixOS/nixpkgs/commit/369ab08b5726ea3718ec12c45292dbf227b37fc5) python311Packages.karton-dashboard: move to pythonRelaxDepsHook
* [`3d7cef76`](https://github.com/NixOS/nixpkgs/commit/3d7cef76e34eef5710bf60e03e8d868a8991e8fa) python310Packages.numpyro: add changelog to meta
* [`42b339db`](https://github.com/NixOS/nixpkgs/commit/42b339db0652305b048ece607fa08701a97b5b46) python310Packages.bellows: 0.34.8 -> 0.34.9
* [`7af9e1fe`](https://github.com/NixOS/nixpkgs/commit/7af9e1fe8a186145fe53dc7a87cdc51ad80aa300) python310Packages.holidays: 0.18 -> 0.20
* [`9166649c`](https://github.com/NixOS/nixpkgs/commit/9166649c3ee430bd9a5d20c2b62ec311ac6a4f68) khoj: add changelog to meta
* [`ea232651`](https://github.com/NixOS/nixpkgs/commit/ea232651a19af707aab973c7219293f705539bd5) v2ray-domain-list-community: 20230202101858 -> 20230227064844
* [`6bc91075`](https://github.com/NixOS/nixpkgs/commit/6bc91075667952f7206d2742ffe711d0bfb4e52e) zotero: 6.0.20 -> 6.0.22
* [`9c1c08a5`](https://github.com/NixOS/nixpkgs/commit/9c1c08a57e2d565195340e5b810e3300b63522c9) khoj: 0.2.6 -> 0.3.0
* [`1a24bd86`](https://github.com/NixOS/nixpkgs/commit/1a24bd868c3726c3118157fc906344bf070ea3c0) kaniko: add jk as maintainer
* [`d2ca40be`](https://github.com/NixOS/nixpkgs/commit/d2ca40be87deebcbc3c337686ccd890af53227e2) python310Packages.shap: add changelog to meta
* [`1c5e5f4d`](https://github.com/NixOS/nixpkgs/commit/1c5e5f4dffd8b4084cd6f45df28c7aaed1ce9be3) python310Packages.shap: mark as broken
* [`c7132173`](https://github.com/NixOS/nixpkgs/commit/c7132173806cfc92fa0f2bcbf965a1af3a259dea) nixos/k3s: add environmentFile as an option
* [`edcfe3f6`](https://github.com/NixOS/nixpkgs/commit/edcfe3f6b979a10feb6485b81ad592d3ac4fba45) python310Packages.mocket: add changelog to meta
* [`65f898d6`](https://github.com/NixOS/nixpkgs/commit/65f898d6e4195214230707b00fb34c30b910ee70) python310Packages.geoip2: add changelog to meta
* [`8eee919c`](https://github.com/NixOS/nixpkgs/commit/8eee919c90f19fadf4b14693525078845a48ddec) python310Packages.mocket: 3.10.9 -> 3.11.0
* [`c62d5ef3`](https://github.com/NixOS/nixpkgs/commit/c62d5ef31f0b7f9edf2ad18b5b2c35f740d12465) crun: 1.8 -> 1.8.1
* [`930b1c06`](https://github.com/NixOS/nixpkgs/commit/930b1c06b14c906fae4f529c6978e53250dce09c) ocamlPackages.base64: 3.5.0 → 3.5.1 ([nixos/nixpkgs⁠#218580](https://togithub.com/nixos/nixpkgs/issues/218580))
* [`c246d9af`](https://github.com/NixOS/nixpkgs/commit/c246d9af83c959eb642998794d5791bd0a8e4522) python311Packages.django-cacheops: re-add six
* [`4ec20c70`](https://github.com/NixOS/nixpkgs/commit/4ec20c70d8229219f6c0744e9547192f8ec47a07) python310Packages.flask-appbuilder: add changelog to meta
* [`605b230a`](https://github.com/NixOS/nixpkgs/commit/605b230af97bba3c294077ada2be263fe055008c) python310Packages.apispec: add optional-dependencies
* [`43508688`](https://github.com/NixOS/nixpkgs/commit/435086885c953ce70e8f3bfd1eb833da21998388) electron-bin: rename from electron
* [`9d3aa1d2`](https://github.com/NixOS/nixpkgs/commit/9d3aa1d2e9ef2eca6ea02880b3f5fa65faa84a2a) python310Packages.flask-sqlalchemy: 3.0.2 -> 3.0.3
* [`94a9f076`](https://github.com/NixOS/nixpkgs/commit/94a9f07625497bb1d1a2bf36d820bddbe2cc1a16) python310Packages.flask-appbuilder: 4.1.3 -> 4.2.1, mark as broken
* [`45c20570`](https://github.com/NixOS/nixpkgs/commit/45c2057059a8db33627c6e2c7e6720758454de19) python310Packages.oci: update homepage and add changelog
* [`fc14705f`](https://github.com/NixOS/nixpkgs/commit/fc14705f97f6f42de392b3a61e5d4a6f9614d6e2) python310Packages.oci: 2.92.0 -> 2.93.0
* [`18a5e5af`](https://github.com/NixOS/nixpkgs/commit/18a5e5afdda6c97be90b47fca0b4144e27b48531) docopts: support darwin
* [`d63e9527`](https://github.com/NixOS/nixpkgs/commit/d63e95274a156b1cfabd220b9f1557f72e213628) python310Packages.suds-jurko: remove
* [`4fa6026e`](https://github.com/NixOS/nixpkgs/commit/4fa6026eaab69736d7bbcabc78ef41dbaed17e25) copyq: set meta.mainProgram
* [`28a70c10`](https://github.com/NixOS/nixpkgs/commit/28a70c103bfb9543d572f16aba86a7e48f557d32) python310Packages.transip: remove
* [`ea31ef91`](https://github.com/NixOS/nixpkgs/commit/ea31ef91afc7997264ceeb8736fea6e5429d677a) nixos/headscale: update oidc options
* [`c6f109bb`](https://github.com/NixOS/nixpkgs/commit/c6f109bb59c88483f77be5074e388d357d34c067) lexicon: add changelog to meta
* [`a2a49666`](https://github.com/NixOS/nixpkgs/commit/a2a496663876e4660cd20d6862fc75a7848d2aeb) lexicon: 3.9.4 -> 3.11.7
* [`79de2ae2`](https://github.com/NixOS/nixpkgs/commit/79de2ae2ce7655d194ff37b44e638566a3ed0bba) cargo-llvm-lines: 0.4.24 -> 0.4.25
* [`fab5be18`](https://github.com/NixOS/nixpkgs/commit/fab5be185cd4f9834090c10b505d53424028a369) python311Packages.pyairvisual: drop asynctest
* [`b8aa3ead`](https://github.com/NixOS/nixpkgs/commit/b8aa3ead714b36b0eefc9290776fd1035c3122d9) trufflehog: 3.28.0 -> 3.28.1
* [`529946c4`](https://github.com/NixOS/nixpkgs/commit/529946c468c3f34c050fd5805abe42d5792160c9) python310Packages.peaqevcore: 12.2.0 -> 12.2.1
* [`6034f0bd`](https://github.com/NixOS/nixpkgs/commit/6034f0bda34f45d2634b597696719107d9a924fb) python310Packages.env-canada: 0.5.28 -> 0.5.29
* [`05751ed2`](https://github.com/NixOS/nixpkgs/commit/05751ed28f4e62cb7d88324ffc8b88ec2f679adf) python310Packages.pyvista: 0.38.2 -> 0.38.3
* [`64b341c9`](https://github.com/NixOS/nixpkgs/commit/64b341c997ceedd314bd16692b20ac5d1e0e636c) ferretdb: 0.9.1->0.9.2
* [`869e91ec`](https://github.com/NixOS/nixpkgs/commit/869e91ec782d5192b1d472981a0c19a305af43a1) awscli2: 2.10.1 -> 2.10.3
* [`897b8d4e`](https://github.com/NixOS/nixpkgs/commit/897b8d4eb4ea3a353aacc8e683138aac1adc7391) firefox-devedition-bin-unwrapped: 111.0b5 -> 111.0b6
* [`c8a11278`](https://github.com/NixOS/nixpkgs/commit/c8a1127856af899aea3dd3ef5e8f804acb105fb3) cppcheck: disable tests on aarch64-linux
* [`e02836f0`](https://github.com/NixOS/nixpkgs/commit/e02836f017315568845726168b5c5d2abe2eaf55) python310Packages.ml-collections: 0.1.0 -> 0.1.1
* [`d0f30dbf`](https://github.com/NixOS/nixpkgs/commit/d0f30dbfc8ea09645ac6f008776b8501f9af3d81) zine: 0.11.0 -> 0.11.1
* [`2378d1a2`](https://github.com/NixOS/nixpkgs/commit/2378d1a21466f58e85a0394fef54bfa5a93e7711) nixos/klipper: fix assert message to match actual assertion
* [`ff7dfcba`](https://github.com/NixOS/nixpkgs/commit/ff7dfcba57fd60c53c333285012f78fd48da6920) nixos/opensearch: fix opensearch startup
* [`922fbae5`](https://github.com/NixOS/nixpkgs/commit/922fbae50c3d738d33a963ab0b07afeb9e03a294) python serialio: connunication -> communication
* [`55f6bccb`](https://github.com/NixOS/nixpkgs/commit/55f6bccb51cfc625c2498c18b64be742ea07f294) apfs-fuse: 2020-09-28 -> 2023-01-04
* [`f4849d6b`](https://github.com/NixOS/nixpkgs/commit/f4849d6b5fef32658542360c4a9ad15964dcc6d6) python310Packages.rich-argparse-plus: init at 0.3.1.4
* [`b4c4419b`](https://github.com/NixOS/nixpkgs/commit/b4c4419b05700f5a0af8a9d603f293404d75854e) libwacom-surface: init at 2.4.0
* [`03924558`](https://github.com/NixOS/nixpkgs/commit/039245588c2871c3d62783010dbdd252ae430284) zoom-us: 5.13.7.683 -> 5.13.10.1208
* [`2cbded08`](https://github.com/NixOS/nixpkgs/commit/2cbded08a287aab6721479772604fd2146606290) wezterm: add vulkan-loader to library path ([nixos/nixpkgs⁠#218410](https://togithub.com/nixos/nixpkgs/issues/218410))
* [`592fe49f`](https://github.com/NixOS/nixpkgs/commit/592fe49fc7fc4b92e26a0bb85def2d3a2e7d8ccf) haproxy: 2.7.2 -> 2.7.3
* [`50800cbe`](https://github.com/NixOS/nixpkgs/commit/50800cbe94a065e3f152e7901d294d66f64985ff) blightmud: 5.0.0 -> 5.1.0
* [`43e79015`](https://github.com/NixOS/nixpkgs/commit/43e79015bf52e90bfe2983e0f1c54e781557d79f) nixos/tests/haproxy: stop using nixos/profiles/minimal
* [`b8442a65`](https://github.com/NixOS/nixpkgs/commit/b8442a653abcfa0806b2eb213a078db95a9fd8a5) haskellPackages.haskell-gi: move temporary upgrade into overlay
* [`7b6e7dd7`](https://github.com/NixOS/nixpkgs/commit/7b6e7dd796f8fe17f673b7434e9366f2f7dbd67e) electron-bin: move print-hashes.sh script
* [`c973f19a`](https://github.com/NixOS/nixpkgs/commit/c973f19acde96069266c31b251d4ef799030b3c4) SDL2_mixer: 2.0.4 -> 2.6.3
* [`8a5af8e2`](https://github.com/NixOS/nixpkgs/commit/8a5af8e2b8b4f776945488b4b9d51d43de9303e5) haskellPackages.cabal2nix-unstable: 2023-02-25 -> 2023-02-27
* [`477440f9`](https://github.com/NixOS/nixpkgs/commit/477440f9d79294108d0437dbc9a3d354a42897d8) ali: init at 0.7.5
* [`cc7b8d0e`](https://github.com/NixOS/nixpkgs/commit/cc7b8d0e92fae1df8ac03e89ebce0fda01f5e93e) gogs: 0.12.10 -> 0.13.0
* [`bac11af0`](https://github.com/NixOS/nixpkgs/commit/bac11af0da17f85d3cec38cc1f9584542fe28913) yaralyzer: init at 0.9.0
* [`7b7e2a21`](https://github.com/NixOS/nixpkgs/commit/7b7e2a217eba414f04ba3fde67e651908e4164e6) python310Packages.hg-evolve: 10.5.3 -> 11.0.0
* [`61770c9a`](https://github.com/NixOS/nixpkgs/commit/61770c9a168a5532b9973d28ceb917d296c22498) python310Packages.azure-storage-blob: 12.14.1 -> 12.15.0
* [`a12ccf90`](https://github.com/NixOS/nixpkgs/commit/a12ccf900be540e6c2216f50628b377cd074e9b8) python3.pkgs.wordcloud: 1.8.1 -> unstable-2023-01-04
* [`d928451e`](https://github.com/NixOS/nixpkgs/commit/d928451e6d9d5ff6dd0d117e3fadc620d4609b3a) python3Packages.django-compression-middleware: init at 0.4.2
* [`3ee30ec4`](https://github.com/NixOS/nixpkgs/commit/3ee30ec4027738cf0ed5e0921657651f18702197) paperless-ngx: 1.12.2 -> 1.13.0
* [`aaecc6a7`](https://github.com/NixOS/nixpkgs/commit/aaecc6a7c7a879201d58cb39b333314dce4a17d2) nixVersions.nix_2_13: 2.13.2 -> 2.13.3
* [`056b679c`](https://github.com/NixOS/nixpkgs/commit/056b679c35b66515f3305921500a989b3951f1ff) nix-fallback-paths.nix: Update to 2.13.3
* [`36ea8625`](https://github.com/NixOS/nixpkgs/commit/36ea86257bfbbc1d7f52f5676082e2f4c33e9b19) nixVersions.nix_2_12: 2.12.0 -> 2.12.1
* [`2d0a4d55`](https://github.com/NixOS/nixpkgs/commit/2d0a4d55c7c582992dceff56b069577de006ee8f) onlyoffice-bin: add gcc lib to runtimeInputs
* [`d729a80b`](https://github.com/NixOS/nixpkgs/commit/d729a80b14e4a5e2d9e3a85c43f7dac1eb7abcbf) cargo-dist: 0.0.2 -> 0.0.3
* [`e59f35e7`](https://github.com/NixOS/nixpkgs/commit/e59f35e7f67bf7cb75b9e1c8a9d0bdebd1306d50) guglielmo: don't use librtlsdr alias
* [`cf3243a2`](https://github.com/NixOS/nixpkgs/commit/cf3243a24380e1ba6c6b03b20b864e3046669922) sdrpp: don't use librtlsdr alias
* [`cb1ee0a7`](https://github.com/NixOS/nixpkgs/commit/cb1ee0a78a2f7e7247809fa3b7aa9e8ba6a8049a) rng-tools: don't use librtlsdr alias
* [`8435101b`](https://github.com/NixOS/nixpkgs/commit/8435101b6402b57bd29695d9fffa6afef3734fc8) cloudflared: 2023.2.1 -> 2023.2.2
* [`645253e6`](https://github.com/NixOS/nixpkgs/commit/645253e62fdcabe9247f38d8033bf086f86b0715) firefox: fix desktop file and icon for variants
* [`3698eb68`](https://github.com/NixOS/nixpkgs/commit/3698eb68a7f6a5975faa0d5eb98fb1087c20d540) python3Packages.pymorphy3: init at 1.2.0
* [`702dd8ea`](https://github.com/NixOS/nixpkgs/commit/702dd8ea613cf9b11882962c92ef3e3298eb1f0e) nodenv: support more platforms
* [`5035ccd5`](https://github.com/NixOS/nixpkgs/commit/5035ccd56f849c774f2caad8758111887818e526) python310Packages.sparse: 0.13.0 -> 0.14.0
* [`28f16257`](https://github.com/NixOS/nixpkgs/commit/28f162579b0a002ed9faa9329e9b68853424b7da) rocclr: 5.4.2 -> 5.4.3
* [`3e439e7c`](https://github.com/NixOS/nixpkgs/commit/3e439e7cc4bd14893db755d37404305d323d8a0a) netcdf: add bzip2/libzip/zstd dependencies (and allow for szip support; disabled by default because it's nonfree)
* [`8dbf4797`](https://github.com/NixOS/nixpkgs/commit/8dbf47975942793c7fd9646a038c684dbb05ddce) netcdf: enable parallel building
* [`981839f2`](https://github.com/NixOS/nixpkgs/commit/981839f265b5b73dcd12fa9f5fdf78269d27e971) netcdf: install plugins into lib/hdf5-plugins
* [`6123056e`](https://github.com/NixOS/nixpkgs/commit/6123056e1840d9d56d7d8723ecd30eeb3df11675) netcdf-cxx4: during tests, use netcdf's installed plugins
* [`de8e79c9`](https://github.com/NixOS/nixpkgs/commit/de8e79c9ba13bc023278cf0d35990738108b9b8a) Revert "netcdfcxx4: disable tests"
* [`509f32d9`](https://github.com/NixOS/nixpkgs/commit/509f32d9c9262cb76f06d21a811b1bb2f3399ef6) python3Packages.dnspython: fix tests (again) ([nixos/nixpkgs⁠#218662](https://togithub.com/nixos/nixpkgs/issues/218662))
* [`1119b007`](https://github.com/NixOS/nixpkgs/commit/1119b007101afa65b2e7a6f3eae28d357388e830) python310Packages.wasmer*: Fix build with maturin 0.14
* [`2af041ab`](https://github.com/NixOS/nixpkgs/commit/2af041ab44ce4b8c10b015ff3674c0852d193a75) nixos/gitlab-runner: do not pull in Docker if gitlab-runner-clear-docker-cache is disabled
* [`3b4775c0`](https://github.com/NixOS/nixpkgs/commit/3b4775c00ec583dc6cd2aece8ae7438e0d8607f7) fb303: 2023.02.13.00 -> 2023.02.20.00
* [`137ed8a0`](https://github.com/NixOS/nixpkgs/commit/137ed8a032ca50e1b3b3b29b21026cc872ff9d5d) ansi: cleanup
* [`dc17f0ae`](https://github.com/NixOS/nixpkgs/commit/dc17f0ae4eaab11f4f7d07d4578a15de3159743b) ttfb: cleanup
* [`8f7e647c`](https://github.com/NixOS/nixpkgs/commit/8f7e647c3032cf7536c2df117655b08b035f6bfe) linux: enable VIRTIO_MMIO_CMDLINE_DEVICES
* [`3a6f8a58`](https://github.com/NixOS/nixpkgs/commit/3a6f8a5871df0972fbd1566b2226d531acb9dbaf) linuxPackages.nvidia_x11_vulkan_beta: 515.47.06 -> 525.47.11
* [`fe4e3211`](https://github.com/NixOS/nixpkgs/commit/fe4e3211889a553f9d4ee4f93b8e481626913302) protonup-qt: 2.7.4 -> 2.7.7
* [`e825a158`](https://github.com/NixOS/nixpkgs/commit/e825a158dc79ce22987688ef714a674eff48f27b) orc: fix build with gcc12 on aarch64-linux
* [`41317262`](https://github.com/NixOS/nixpkgs/commit/4131726270412e87ea7666c5a6a175d7fa0bbd62) deltachat-desktop: 1.34.4 -> 1.34.5
* [`8e149942`](https://github.com/NixOS/nixpkgs/commit/8e149942c7740a146e0fb4e361f245f574b01d36) octosuite: init at 3.1.0
* [`7f17cacb`](https://github.com/NixOS/nixpkgs/commit/7f17cacb6ade23cee05f055b4dea5276c8b86da0) wolf-shaper: 1.0.0 -> 1.0.1
* [`a3a34145`](https://github.com/NixOS/nixpkgs/commit/a3a34145d3183aa9ed55e1b35f5a6ba604ce221a) otel-cli: 0.1.0 -> 0.2.0
* [`ae6dc252`](https://github.com/NixOS/nixpkgs/commit/ae6dc2525ddcb25706f17fe7db1cc089c04b8267) konstraint: 0.25.0 -> 0.25.1
* [`f2a1f0cf`](https://github.com/NixOS/nixpkgs/commit/f2a1f0cf82b515f5da2583334288aea59b2d4ff8) maintainers: add developer-guy
* [`000960c3`](https://github.com/NixOS/nixpkgs/commit/000960c351145a43cbcbe2ef792fe3a115046059) cosign: add developer-guy to the maintainers
* [`344355f7`](https://github.com/NixOS/nixpkgs/commit/344355f7553dd6658e616843ddf29800ffb45e6e) kubeone: 1.5.6 -> 1.6.0
* [`2c106c1e`](https://github.com/NixOS/nixpkgs/commit/2c106c1e7c0794927c3b889de51e3c2cdd9130ba) google-chrome: Support GTK 4 ([nixos/nixpkgs⁠#218572](https://togithub.com/nixos/nixpkgs/issues/218572))
* [`a46074d1`](https://github.com/NixOS/nixpkgs/commit/a46074d1acc319fc8ad0f269af0db751a1bd56ad) trufflehog: 3.28.1 -> 3.28.2
* [`36fccf2f`](https://github.com/NixOS/nixpkgs/commit/36fccf2fdb240c8fe71c7ec0752572e227c85140) mir: 2.12.0 -> 2.12.1
* [`8f32beea`](https://github.com/NixOS/nixpkgs/commit/8f32beea227a1cfb2908e3a5d04f265cfe6a43ac) uxplay: 1.63 -> 1.63.2
* [`5e98938f`](https://github.com/NixOS/nixpkgs/commit/5e98938f2bf3642d0fe6ef2245c9614993374087) python310Packages.tld: 0.12.7 -> 0.13
* [`70335751`](https://github.com/NixOS/nixpkgs/commit/70335751e46c5201d4b613099aeb8456a33c087b) vte: restrict condition for using clangStdenv
* [`77bbdaa9`](https://github.com/NixOS/nixpkgs/commit/77bbdaa9be377676cadd55febcb2cafe76f7b853) cudatext-qt: 1.185.0 -> 1.186.0
* [`d15787c4`](https://github.com/NixOS/nixpkgs/commit/d15787c4dcbd3845270231b3e324dcf6be46d5f7) python310Packages.roonapi: 0.1.3 -> 0.1.4
* [`ce83a0c1`](https://github.com/NixOS/nixpkgs/commit/ce83a0c11c149cacaf708cd44e69487293ccf671) medfile: build with hdf5 1.14
* [`435580f0`](https://github.com/NixOS/nixpkgs/commit/435580f08f6a45d6ddcc8119c849a15f2a28f8fc) lib.maintainers.rrbutani.matrix: add
* [`b9b555ff`](https://github.com/NixOS/nixpkgs/commit/b9b555ff62797b1b73be449d8ceb716e7a468209) spicedb-zed: 0.9.1 -> 0.10.0
* [`a6bc7c0b`](https://github.com/NixOS/nixpkgs/commit/a6bc7c0bbaf4f0168c33dc74bb5ad0fe02b19496) python310Packages.msoffcrypto-tool: 5.0.0 -> 5.0.1
* [`254fbb6a`](https://github.com/NixOS/nixpkgs/commit/254fbb6a378b6dd3b0d7a7b8a0d9dd070c3a6f60) python310Packages.msoffcrypto-tool: add changelog to meta
* [`d654c44d`](https://github.com/NixOS/nixpkgs/commit/d654c44d2f967247c219950158e7fc3cc36658e0) drawio-headless: add --auto-display to prevent races
* [`dd50092f`](https://github.com/NixOS/nixpkgs/commit/dd50092fdaedcfe8e1fffe64ceddf461752d512a) croc: 9.6.2 -> 9.6.3, disable extra test on darwin, cleanup
* [`fd802ced`](https://github.com/NixOS/nixpkgs/commit/fd802ced97642e511dd2fc5805703cbb38ebc8a9) python310Packages.notifications-python-client: 7.0.0 -> 8.0.0
* [`60f5299a`](https://github.com/NixOS/nixpkgs/commit/60f5299a00fa6e5fffc248bdfc2d19a566e8fc07) kubo: 0.17.0 -> 0.18.0
* [`b034792b`](https://github.com/NixOS/nixpkgs/commit/b034792be3fb8631e75abc0893a897e50e462cf2) kubo: 0.18.0 -> 0.18.1
* [`b8b74bb8`](https://github.com/NixOS/nixpkgs/commit/b8b74bb84ef99cd9e01b3dbe849f69fc6167d273) standardnotes: 3.148.0 -> 3.150.0
* [`ae671e1b`](https://github.com/NixOS/nixpkgs/commit/ae671e1b918e8ce7e7cf1372f5a91bcbd3d44d58) Revert "nixos/release: disable nfs3.simple"
* [`ce07d44c`](https://github.com/NixOS/nixpkgs/commit/ce07d44ca9d6824125f4a30a96a42555b61de205) Revert "nixos/release: disable nfs3.simple"
* [`359a46e7`](https://github.com/NixOS/nixpkgs/commit/359a46e751124454a1a03ad1cdcb1efef745abd8) llvm*: Remove `outputSpecified` workaround where possible
* [`61295f7a`](https://github.com/NixOS/nixpkgs/commit/61295f7a0e394af834e5fcb785b4eb0ea3b09919) poetry2nix: fix override bootstrapped-pip
* [`02fa99fd`](https://github.com/NixOS/nixpkgs/commit/02fa99fd08645c921d970d397502c6338eae9dbc) lua_5_3_compat, lua_5_4_compat: set LUA_COMPAT_5_x as LUA_COMPAT_ALL was removed
* [`660e32a9`](https://github.com/NixOS/nixpkgs/commit/660e32a9ffb0cc797b9dd2dd6e26b9bd43deb3d7) kdiff3: 1.9.6 -> 1.10.0
* [`58609f1d`](https://github.com/NixOS/nixpkgs/commit/58609f1dc5183df1c37a34be40f219f7ccacc705) deepin.deepin-movie-reborn: init at 5.10.17
* [`5f7abf8e`](https://github.com/NixOS/nixpkgs/commit/5f7abf8e23396056ffce1a54e6089baa9981b067) mpop: 1.4.17 -> 1.4.18
* [`5191e540`](https://github.com/NixOS/nixpkgs/commit/5191e540accd5b899a4e1faa9966dfd689bc8c6b) deepin.dde-device-formatter: init at unstable-2022-09-05
* [`d6531973`](https://github.com/NixOS/nixpkgs/commit/d65319733c25e218c86f22faa61dd17468d039aa) powerstat: 0.03.00 -> 0.03.01
* [`358fa30b`](https://github.com/NixOS/nixpkgs/commit/358fa30bafddf8ba394fb68b76d196ecc4f9ae42) oguri: reduce supported platforms
* [`79414696`](https://github.com/NixOS/nixpkgs/commit/79414696e027f4448dd74654ec37c4a1ff5d964c) pantheon.granite7: 7.1.0 -> 7.2.0
* [`4659cef5`](https://github.com/NixOS/nixpkgs/commit/4659cef5b9aadbe0c77d43925d6dfd60527bd217) terraform-providers.google: 4.54.0 → 4.55.0
* [`568bece2`](https://github.com/NixOS/nixpkgs/commit/568bece2c567fd2c36c4f1946ebb7c7a29e79d76) terraform-providers.google-beta: 4.54.0 → 4.55.0
* [`5c48a036`](https://github.com/NixOS/nixpkgs/commit/5c48a036021ae46de26ec8cc0949fbd5b664a351) terraform-providers.launchdarkly: 2.9.5 → 2.10.0
* [`72541551`](https://github.com/NixOS/nixpkgs/commit/725415519f4c20426659e1591536a2cd9af7de12) terraform-providers.minio: 1.11.0 → 1.12.0
* [`c97c4ccd`](https://github.com/NixOS/nixpkgs/commit/c97c4ccd378a9c7bdcec749d2b46da0ec99f2ebc) terraform-providers.newrelic: 3.14.0 → 3.15.0
* [`ea7312d1`](https://github.com/NixOS/nixpkgs/commit/ea7312d1efcbb7d852637d79bf7e7efe425b4e30) terraform-providers.sumologic: 2.20.0 → 2.21.0
* [`872ba191`](https://github.com/NixOS/nixpkgs/commit/872ba19121a7a56a4c8b82d1cb2a0e92e02a8a05) terraform-providers.spotinst: 1.100.0 → 1.101.0
* [`37eea1f9`](https://github.com/NixOS/nixpkgs/commit/37eea1f95048ffd9e2c2f14dc18fa3fe5e279075) terraform-providers.ucloud: 1.34.0 → 1.34.1
* [`44ac1cbe`](https://github.com/NixOS/nixpkgs/commit/44ac1cbea8621d6e18a2b0cbfa3d773ba04f3268) terraform-providers.tencentcloud: 1.79.11 → 1.79.12
* [`1da5b4be`](https://github.com/NixOS/nixpkgs/commit/1da5b4be764c0803c5c2f794c8ef4984e30832c3) python310Packages.scmrepo: 0.1.12 -> 0.1.13
* [`0e1d56a3`](https://github.com/NixOS/nixpkgs/commit/0e1d56a397cc47fc2bcfa8a2fcee83b4a6d4f678) reaper: add curl and libxml2 ld_library_path deps
* [`4bc6ce1d`](https://github.com/NixOS/nixpkgs/commit/4bc6ce1da0d9bc378c3528dfed1c862545886793) ooniprobe-cli: 3.16.7 -> 3.17.0
* [`3a2f536e`](https://github.com/NixOS/nixpkgs/commit/3a2f536e742e51f9b49055e3f82a5ac665a2eded) python311Packages.sip_4: disable
* [`375f5b6f`](https://github.com/NixOS/nixpkgs/commit/375f5b6f80d6f824f4dcbdee55df413174ff6ed9) openvpn3: 18_beta -> 19_beta
* [`5261692e`](https://github.com/NixOS/nixpkgs/commit/5261692e980d4d39d743b6be5bf2ccbbe919c209) python310Packages.bx-py-utils: 75 -> 76
* [`5d12e405`](https://github.com/NixOS/nixpkgs/commit/5d12e405f6ed8f061673f5ce609b5e74fb135f34) python310Packages.inkex: build independently
* [`6d945d28`](https://github.com/NixOS/nixpkgs/commit/6d945d280326d15b1850c0df3219d8d40d1735f9) python310Packages.svg2tikz: unstable-2021-01-12 -> 1.2.0
* [`059ba12e`](https://github.com/NixOS/nixpkgs/commit/059ba12eddaca35bbf8dc6dac2c803476f689034) tgt: 1.0.85 -> 1.0.86
* [`eafa5eba`](https://github.com/NixOS/nixpkgs/commit/eafa5eba29feec42459b2e6fc7e00d3ca0a6ffb4) python310Packages.aioopenssl: init at 0.6.0
* [`6025563b`](https://github.com/NixOS/nixpkgs/commit/6025563be6c1cf39bd3124649dc0c9f7302d2762) python310Packages.aiosasl: init at 0.5.0
* [`d7189365`](https://github.com/NixOS/nixpkgs/commit/d71893657dea77da27e2885c0542f018fe98b475) python310Packages.aioxmpp: init at 0.13.3
* [`9e56d6ec`](https://github.com/NixOS/nixpkgs/commit/9e56d6ec92c8fb4192f1392aa5c4101ad77f2070) moodle-dl: 2.1.2.5 -> 2.2.2.4
* [`59cb9060`](https://github.com/NixOS/nixpkgs/commit/59cb90605d1ee9ed0f5207d3ef0dec810c5eaf2e) python310Packages.udatetime: 0.0.16 -> 0.0.17
* [`0c960d8d`](https://github.com/NixOS/nixpkgs/commit/0c960d8de4c94bc2577294b9fdff0a3341c8099e) ctlptl: 0.8.16 -> 0.8.17
* [`d051e0ad`](https://github.com/NixOS/nixpkgs/commit/d051e0ad48a33e70afb1abfcf96f30933a44eed3) librelp: 1.10.0 -> 1.11.0
* [`8041ca78`](https://github.com/NixOS/nixpkgs/commit/8041ca7884a6ba3c6265b96eeb02974ca491765e) your-editor: 1503 -> 1504
* [`6f82f79a`](https://github.com/NixOS/nixpkgs/commit/6f82f79acd671832fe70416687b6bb908074a4c4) dua: 2.19.1 -> 2.19.2
* [`36405d17`](https://github.com/NixOS/nixpkgs/commit/36405d170ac00549cf0f5139a3f5adbc1c5cffa0) freefilesync: 12.0 -> 12.1
* [`b41bc9a0`](https://github.com/NixOS/nixpkgs/commit/b41bc9a0e0b564ebc095d9819afa523d0b241262) python310Packages.adblock: fix build
* [`d286464e`](https://github.com/NixOS/nixpkgs/commit/d286464ec3ea208f1bd1b92b9bd7f11eb99ae61f) fioctl: 0.31 -> 0.32.0
* [`d531f0a0`](https://github.com/NixOS/nixpkgs/commit/d531f0a0d632de6d43bbd6c5edc97e5464e52923) vscode-extensions.streetsidesoftware.code-spell-checker: 2.17.1 -> 2.18.0
* [`6c4c6f73`](https://github.com/NixOS/nixpkgs/commit/6c4c6f731252e4530d1c0ca900bb445251b8dc3b) jira_cli: mark as broken
* [`c884849a`](https://github.com/NixOS/nixpkgs/commit/c884849a3c6407bfff3383c54499595781fea73a) openmm: use gcc11Stdenv everywhere
* [`14533fe0`](https://github.com/NixOS/nixpkgs/commit/14533fe0ae2c95751711a568fb6f7c840c6ae950) python310Packages.cart: add changelog to meta
* [`31b4cd4b`](https://github.com/NixOS/nixpkgs/commit/31b4cd4bcad55c702f47a28019d4f5032e3200d2) python310Packages.cart: 1.2.1 -> 1.2.2
* [`2d42003f`](https://github.com/NixOS/nixpkgs/commit/2d42003f5ff81da8a496a72363067e465d33411e) python310Packages.ne…
