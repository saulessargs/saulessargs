##### Salīdzināt vienādu failu hash
git ls-tree HEAD -r
100644 blob 7c24348336717605361d41fc23f8684072758d9b	README.md
100644 blob 9811d61781f38f1f07a65fddf59aa57340ba1b75	module_1/990.jpg
100644 blob bf13de02485f98b495e73beded63321e7f69f58c	module_1/README.md
100644 blob 9811d61781f38f1f07a65fddf59aa57340ba1b75	module_2/990.jpg
100644 blob e69de29bb2d1d6434b8b29ae775ad8c2e48c5391	module_2/README.md


###### MD 16.p variants1
git log --since=1.weeks --pretty=oneline
983e40bf4a27ce4a0c89a62a152bc8fec5476fa3 (HEAD -> main, origin/main, origin/HEAD) CHANGELOG: Remove reference to "go-tfe" library upgrade
465832f1e32ebd551692dedc4eb870268ee97042 Update CHANGELOG.md
09ab872a6fb77d459c4633533f4eca04d5445d59 build: go get github.com/hashicorp/hcl/v2@v2.12.0
84e18f31bd2fd8645cdcd4578778f69afd1f0f8f bump mitchellh/cli from 1.1.2 to 1.1.3 (#30914)
1252f8c9c53b023d2964c4574212198fa6c254db Merge pull request #30916 from hashicorp/jbardin/speculative-apply-graph
d9af967a6e1a6c4058169feee15ad85e9ebe9cf9 build a test apply graph during plan
0b784b9b899996c2a998383bb15475bdc78c645c Merge pull request #30915 from hashicorp/update-metadata-action
955dd6b7800d943cd3511c4c22aa01bf16854d6a update CHANGELOG.md
7da52d94f2bd7a5bd4da5ce8bcb1a9d92b19569d Merge pull request #30900 from hashicorp/jbardin/replace-triggered-by
dd2decf9218166325acb69cec27c9cfa2189fc4b change action to pull v1 instead of main
39bbcf2f9cc954a8f03825f64a79d228b9b49f93 Fix for newer go version (#30889)
5f58daaf57fa8e20fc46be6883129055e54e8cc0 fix typo in struct tag (#30884)
2563bf3f966a1d21d80209e92af8403d41c3e583 feat: support local preview, post split; add deploy preview (#30814)
7d51ba51182c9f404b97769e904c0dae4b197849 Merge pull request #30862 from hashicorp/update-TF-WORKSPACE-variable
7b6dfabb74a85b06a9c79604cd1d3eea40749d39 Merge pull request #30906 from hashicorp/jbardin/races
e68ad5ec463fbfa2a9c19abc54f60efb4b779141 (origin/update-TF-WORKSPACE-variable) more edits
912e6ff6de5d79bdd5e0ea3672817be3f12d9779 Apply suggestions from PR review
a0ebb94fb598a5822fdab6c6575fae55f3a8efff Merge branch 'main' into update-TF-WORKSPACE-variable
2f7aa2fcb5c37098323bfbf4a0e16175e8b817d5 Merge pull request #30905 from hashicorp/sebasslash/rename-env-vars
0693c8dfe75c7675d820c59c91cc8bdea1334c92 enable the race detector in tests
0731213ecff25e142934d97e9f2658d3a3e64af4 sync retry goroutine return
c52e3ed37bb0be236841c0e2415dfaeeb84bb0c0 test fixture race
0fe38fba6c84f39f8d868619b5c3950b092aa370 prevent unsynchronized output changes access
f63ef2b5ef0b44fe677d02f598d6610b7c880385 (origin/sebasslash/rename-env-vars) Rename cloud env vars to use TF_CLOUD prefix
1e79682c245721ccd916faee02fe8a34bcf170ea minor fixes
d3e660d91272c239350f0cf9a01ca94c7437f775 Merge pull request #30772 from hashicorp/laura-update-pre-post-conditions
b1d9339368563b3e76e0b71fd200cafb02870853 (origin/laura-update-pre-post-conditions) Final formatting nits
eb2724d37f4d4b7c055518a7358802e419337661 Update CHANGELOG.md
d4776e8ef106aaf1ad3f8b7aa38d0d846681cb7d lang/funcs: type conversion functions can convert null values
3c7c5bbd21dc32fa650c2b3505c77315838421aa add links to function and expressions; move result types back to conditionals page (oops)
2a206c7984573d054c1dd6ea2b7eb2a733da01be fix incorrect HCL syntax for example
7a43db405c8da55f918b64b37aae59be2a8180b7 Add link to operators page and all out other types
0028a26cf81d6b9d7c036407426469597c017a02 updating to include #30891
2eb9118cd12d001ad62dd7c98ab0c9ddb48ee638 backend/remote-state/azure: defaulting the Azure Backend to use MSAL (#30891)
ba3bb5ad5dcfc63c0c72f9ed569f3bf603e191da Apply suggestions from PR review
686dbcdb8dfcf45b2063bb28960310b243847614 fix confusing sentence on lifecycle page
4d4d774aef4a7abbc77b0c951e2f124af1a2327c fix confusing sentence on resources page
ce757244f284a8270210b6dd85bea554a9fb5b7f fix confusing sentence in outputs
f660f54b87dc5b8239517560ef3626f16c907f8b Final nits from review
e8743143e33a2a8c55ebf0fc04438aeff135272b Update website/docs/language/data-sources/index.mdx
87b09b1ee173e3b92c1d08ffae6c44242600c62b Fix broken HCL in example
3a0a019521c6d8022c814dcf7f71d18975375732 round-trip replace triggers
54c1791a1b339a5e2de6d8c3b26a6b42eb953b50 add triggers reason to plan proto
868052c9e368c306878c59920eafa5e93ab6695c set replace_trigered_by reason in diff output
e2fc9a19f52282e5b876dcdbc5c8006db5c60d65 use ResourceInstanceReplaceByTriggers
e4c4dcbd14b06da76f5d8b00e59569cddf9d1c38 add ResourceInstanceReplaceByTriggers
91121aa856c226016441c197ba648729cf15c646 limit replace_triggered_by to same module instance
fb6fcf783b2b5fd2086116fd2053d9fa14334833 Fix replace_triggered_by criteria
6670b71a2ee6748c38aa4cb6892184aa48e1ded9 context test demonstrating replace_triggered_by
7598665c90707a83fb8ceb424611426d5d044593 check for replacement via replace_triggered_by
4f2195af2b666ab078d03e4197185adb77b55e25 collect references from replace_triggered_by
4d43d6f699f28d674f83e272b815c99ed4458d0b Use the EvalContext to lookup trigger changes
8b4c89bdaff4e2f45af476144bd33f923fe18934 evaluate replace_triggered_by expressions
6eb3264d1a329445912084055fd51c57f871af20 parse replace_triggered_by in resource configs
197359cc8f2da6f3306c5063b1edef1f02e596ed update hcl for IsJSONExpression
b724dc19d2e7c0638e5587611d46085637979fc9 Merge pull request #30873 from hashicorp/rt-backport-changelog
cd4b89add7cd42c25cfa5e22524d26803493659d (origin/rt-backport-changelog) Merge branch 'main' into rt-backport-changelog



##### MD 16.p variants 2, mazliet citādāks
git log --since="2022-04-18" --pretty=oneline
983e40bf4a27ce4a0c89a62a152bc8fec5476fa3 (HEAD -> main, origin/main, origin/HEAD) CHANGELOG: Remove reference to "go-tfe" library upgrade
465832f1e32ebd551692dedc4eb870268ee97042 Update CHANGELOG.md
09ab872a6fb77d459c4633533f4eca04d5445d59 build: go get github.com/hashicorp/hcl/v2@v2.12.0
84e18f31bd2fd8645cdcd4578778f69afd1f0f8f bump mitchellh/cli from 1.1.2 to 1.1.3 (#30914)
1252f8c9c53b023d2964c4574212198fa6c254db Merge pull request #30916 from hashicorp/jbardin/speculative-apply-graph
d9af967a6e1a6c4058169feee15ad85e9ebe9cf9 build a test apply graph during plan
0b784b9b899996c2a998383bb15475bdc78c645c Merge pull request #30915 from hashicorp/update-metadata-action
955dd6b7800d943cd3511c4c22aa01bf16854d6a update CHANGELOG.md
7da52d94f2bd7a5bd4da5ce8bcb1a9d92b19569d Merge pull request #30900 from hashicorp/jbardin/replace-triggered-by
dd2decf9218166325acb69cec27c9cfa2189fc4b change action to pull v1 instead of main
39bbcf2f9cc954a8f03825f64a79d228b9b49f93 Fix for newer go version (#30889)
5f58daaf57fa8e20fc46be6883129055e54e8cc0 fix typo in struct tag (#30884)
2563bf3f966a1d21d80209e92af8403d41c3e583 feat: support local preview, post split; add deploy preview (#30814)
7d51ba51182c9f404b97769e904c0dae4b197849 Merge pull request #30862 from hashicorp/update-TF-WORKSPACE-variable
7b6dfabb74a85b06a9c79604cd1d3eea40749d39 Merge pull request #30906 from hashicorp/jbardin/races
e68ad5ec463fbfa2a9c19abc54f60efb4b779141 (origin/update-TF-WORKSPACE-variable) more edits
912e6ff6de5d79bdd5e0ea3672817be3f12d9779 Apply suggestions from PR review
a0ebb94fb598a5822fdab6c6575fae55f3a8efff Merge branch 'main' into update-TF-WORKSPACE-variable
2f7aa2fcb5c37098323bfbf4a0e16175e8b817d5 Merge pull request #30905 from hashicorp/sebasslash/rename-env-vars
0693c8dfe75c7675d820c59c91cc8bdea1334c92 enable the race detector in tests
0731213ecff25e142934d97e9f2658d3a3e64af4 sync retry goroutine return
c52e3ed37bb0be236841c0e2415dfaeeb84bb0c0 test fixture race
0fe38fba6c84f39f8d868619b5c3950b092aa370 prevent unsynchronized output changes access
f63ef2b5ef0b44fe677d02f598d6610b7c880385 (origin/sebasslash/rename-env-vars) Rename cloud env vars to use TF_CLOUD prefix
1e79682c245721ccd916faee02fe8a34bcf170ea minor fixes
d3e660d91272c239350f0cf9a01ca94c7437f775 Merge pull request #30772 from hashicorp/laura-update-pre-post-conditions
b1d9339368563b3e76e0b71fd200cafb02870853 (origin/laura-update-pre-post-conditions) Final formatting nits
eb2724d37f4d4b7c055518a7358802e419337661 Update CHANGELOG.md
d4776e8ef106aaf1ad3f8b7aa38d0d846681cb7d lang/funcs: type conversion functions can convert null values
3c7c5bbd21dc32fa650c2b3505c77315838421aa add links to function and expressions; move result types back to conditionals page (oops)
2a206c7984573d054c1dd6ea2b7eb2a733da01be fix incorrect HCL syntax for example
7a43db405c8da55f918b64b37aae59be2a8180b7 Add link to operators page and all out other types
0028a26cf81d6b9d7c036407426469597c017a02 updating to include #30891
2eb9118cd12d001ad62dd7c98ab0c9ddb48ee638 backend/remote-state/azure: defaulting the Azure Backend to use MSAL (#30891)
ba3bb5ad5dcfc63c0c72f9ed569f3bf603e191da Apply suggestions from PR review
686dbcdb8dfcf45b2063bb28960310b243847614 fix confusing sentence on lifecycle page
4d4d774aef4a7abbc77b0c951e2f124af1a2327c fix confusing sentence on resources page
ce757244f284a8270210b6dd85bea554a9fb5b7f fix confusing sentence in outputs
f660f54b87dc5b8239517560ef3626f16c907f8b Final nits from review
e8743143e33a2a8c55ebf0fc04438aeff135272b Update website/docs/language/data-sources/index.mdx
87b09b1ee173e3b92c1d08ffae6c44242600c62b Fix broken HCL in example
3a0a019521c6d8022c814dcf7f71d18975375732 round-trip replace triggers
54c1791a1b339a5e2de6d8c3b26a6b42eb953b50 add triggers reason to plan proto
868052c9e368c306878c59920eafa5e93ab6695c set replace_trigered_by reason in diff output
e2fc9a19f52282e5b876dcdbc5c8006db5c60d65 use ResourceInstanceReplaceByTriggers
e4c4dcbd14b06da76f5d8b00e59569cddf9d1c38 add ResourceInstanceReplaceByTriggers
91121aa856c226016441c197ba648729cf15c646 limit replace_triggered_by to same module instance
fb6fcf783b2b5fd2086116fd2053d9fa14334833 Fix replace_triggered_by criteria
6670b71a2ee6748c38aa4cb6892184aa48e1ded9 context test demonstrating replace_triggered_by
7598665c90707a83fb8ceb424611426d5d044593 check for replacement via replace_triggered_by
4f2195af2b666ab078d03e4197185adb77b55e25 collect references from replace_triggered_by
4d43d6f699f28d674f83e272b815c99ed4458d0b Use the EvalContext to lookup trigger changes
8b4c89bdaff4e2f45af476144bd33f923fe18934 evaluate replace_triggered_by expressions
6eb3264d1a329445912084055fd51c57f871af20 parse replace_triggered_by in resource configs
197359cc8f2da6f3306c5063b1edef1f02e596ed update hcl for IsJSONExpression
b724dc19d2e7c0638e5587611d46085637979fc9 Merge pull request #30873 from hashicorp/rt-backport-changelog
cd4b89add7cd42c25cfa5e22524d26803493659d (origin/rt-backport-changelog) Merge branch 'main' into rt-backport-changelog


###### MD 17.p
git log --since="2022-04-18" --committer="Laura Pacilio" --graph
* commit e68ad5ec463fbfa2a9c19abc54f60efb4b779141 (origin/update-TF-WORKSPACE-variable)
| Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
| Date:   Wed Apr 20 18:57:50 2022 -0400
|
|     more edits
|
* commit 912e6ff6de5d79bdd5e0ea3672817be3f12d9779
  Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
  Date:   Wed Apr 20 18:54:50 2022 -0400

      Apply suggestions from PR review

* commit b1d9339368563b3e76e0b71fd200cafb02870853 (origin/laura-update-pre-post-conditions)
| Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
| Date:   Wed Apr 20 12:19:29 2022 -0400
|
|     Final formatting nits
|
* commit 3c7c5bbd21dc32fa650c2b3505c77315838421aa
| Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
| Date:   Wed Apr 20 12:06:50 2022 -0400
|
|     add links to function and expressions; move result types back to conditionals page (oops)
|
* commit 2a206c7984573d054c1dd6ea2b7eb2a733da01be
| Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
| Date:   Wed Apr 20 11:49:33 2022 -0400
|
|     fix incorrect HCL syntax for example
|
* commit 7a43db405c8da55f918b64b37aae59be2a8180b7
| Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
| Date:   Wed Apr 20 11:46:37 2022 -0400
|
|     Add link to operators page and all out other types
|
* commit ba3bb5ad5dcfc63c0c72f9ed569f3bf603e191da
| Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
| Date:   Wed Apr 20 11:30:20 2022 -0400
|
|     Apply suggestions from PR review
|
* commit 686dbcdb8dfcf45b2063bb28960310b243847614
| Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
| Date:   Wed Apr 20 11:24:23 2022 -0400
|
|     fix confusing sentence on lifecycle page
|
* commit 4d4d774aef4a7abbc77b0c951e2f124af1a2327c
| Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
| Date:   Wed Apr 20 11:23:15 2022 -0400
|
|     fix confusing sentence on resources page
|
* commit ce757244f284a8270210b6dd85bea554a9fb5b7f
| Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
| Date:   Wed Apr 20 11:22:11 2022 -0400
|
|     fix confusing sentence in outputs
|
* commit f660f54b87dc5b8239517560ef3626f16c907f8b
  Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
  Date:   Wed Apr 20 11:21:11 2022 -0400

      Final nits from review

* commit 87b09b1ee173e3b92c1d08ffae6c44242600c62b
  Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
  Date:   Wed Apr 20 11:17:16 2022 -0400

      Fix broken HCL in example

##### MD 18.p
      git log --since="2021-09-01" --until="2021-09-31" --committer="Laura Pacilio" --graph
* commit a8e5b6a4ad1747d95a6f00acde01d68f3fc5b3b8
| Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
| Date:   Thu Sep 16 17:11:31 2021 -0400
|
|     Fix alphabetical order of sidebar
|
* commit 4d1baaceabaa968c1e5009536a70341b1657b7fe
  Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
  Date:   Thu Sep 16 17:06:52 2021 -0400

      Add Machine-Readable UI to sidebar and add hyphen :-)

##### MD 19.p
git log --since="yesterday" --committer="Laura Pacilio"

#### MD 20.p

###### *
Vai varētu būt, kad tas fails ir excluded? commit 16.datumā, bet push 20-21? 
