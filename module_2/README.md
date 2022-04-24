Github redz atšķirību starp šiem failiem.

1 parent 54b8016 commit 4105eb01f7f69a8c7e656bd861b765440ddd47d8

1 parent 4105eb0 commit 32f41f507bbcc2d627005a495d349b040fe0e434
______________________________________________________________________________________________________

16. Pārbaudīt kādas izmaiņas tika veiktas iepriekšējās nedēļas laikā. Atrast
vismaz divus veidus kā to izdarīt.
___________________________________
$ git log --since="2022-04-18" --before="2022-04-24"
$ git log --since=Apr-18 --until=Apr-24
$ git log --after="2022-04-18" --until="2022-04-24"

___________________________________

17. Atrast commit kurus veica autors - “Laura Pacilio”
___________________________________
$ git log --author laurapacilio
commit e68ad5ec463fbfa2a9c19abc54f60efb4b779141 (origin/update-TF-WORKSPACE-variable)
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 18:57:50 2022 -0400

    more edits

commit 912e6ff6de5d79bdd5e0ea3672817be3f12d9779
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 18:54:50 2022 -0400

    Apply suggestions from PR review

commit a0ebb94fb598a5822fdab6c6575fae55f3a8efff
Merge: 201c9168f 2f7aa2fcb
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 18:40:26 2022 -0400

    Merge branch 'main' into update-TF-WORKSPACE-variable

commit d3e660d91272c239350f0cf9a01ca94c7437f775
Merge: eb2724d37 b1d933936
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 12:25:43 2022 -0400

    Merge pull request #30772 from hashicorp/laura-update-pre-post-conditions

    [WIP] Preconditions and Postconditions Content Updates

commit b1d9339368563b3e76e0b71fd200cafb02870853 (origin/laura-update-pre-post-conditions)
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 12:19:29 2022 -0400

    Final formatting nits

commit 3c7c5bbd21dc32fa650c2b3505c77315838421aa
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 12:06:50 2022 -0400

    add links to function and expressions; move result types back to conditionals page (oops)

commit 2a206c7984573d054c1dd6ea2b7eb2a733da01be
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 11:49:33 2022 -0400

    fix incorrect HCL syntax for example

commit 7a43db405c8da55f918b64b37aae59be2a8180b7
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 11:46:37 2022 -0400

    Add link to operators page and all out other types

commit ba3bb5ad5dcfc63c0c72f9ed569f3bf603e191da
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 11:30:20 2022 -0400

    Apply suggestions from PR review

commit 686dbcdb8dfcf45b2063bb28960310b243847614
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 11:24:23 2022 -0400

    fix confusing sentence on lifecycle page

commit 4d4d774aef4a7abbc77b0c951e2f124af1a2327c
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 11:23:15 2022 -0400

    fix confusing sentence on resources page

commit ce757244f284a8270210b6dd85bea554a9fb5b7f
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 11:22:11 2022 -0400

    fix confusing sentence in outputs

commit f660f54b87dc5b8239517560ef3626f16c907f8b
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 11:21:11 2022 -0400

    Final nits from review

commit e8743143e33a2a8c55ebf0fc04438aeff135272b
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 11:17:45 2022 -0400

    Update website/docs/language/data-sources/index.mdx

    Co-authored-by: Alisdair McDiarmid <alisdair@users.noreply.github.com>

commit 87b09b1ee173e3b92c1d08ffae6c44242600c62b
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 11:17:16 2022 -0400

    Fix broken HCL in example
________________________________


18. Atrast vai Laura ir veikusi commit pagājušā gada septembrī?
Jā
________________________________
$ git log --since="2021-09-01" --before="2021-09-30"
commit 8f09e27597c9e792d7d9acea158429f10269572d
Merge: 5386d6c5b c8e2be76d
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Sep 20 17:24:31 2021 -0400

    Merge pull request #29567 from drasko95/patch-1

    Fix a documentation typo
commit dfbef12a6ca4ba95531bef09ac6c7edc3cc2868b
Merge: 1bd5987a8 a8e5b6a4a
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Sep 16 17:30:37 2021 -0400

    Merge pull request #29598 from hashicorp/laura-add-mrui-to-sidebar

    Add Machine-Readable UI to sidebar

commit a8e5b6a4ad1747d95a6f00acde01d68f3fc5b3b8
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Sep 16 17:11:31 2021 -0400

    Fix alphabetical order of sidebar

commit 4d1baaceabaa968c1e5009536a70341b1657b7fe
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Sep 16 17:06:52 2021 -0400

    Add Machine-Readable UI to sidebar and add hyphen :-)

commit dcf2d3c1efa2165cfe953794bcfcb8d074d2ed9b
Merge: 8ed9a270e f238e9395
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Sep 13 10:39:02 2021 -0400

    Merge pull request #29494 from magnetikonline/docs-s3-backend-dynamodb-partition-key

    S3 backend documentation update - DynamoDB uses Partition keys, not primary keys - redux

commit 43f960b19736cf6f7d6413a85b3d33f88a1e5a6c
Merge: 48768a003 a303a03f2
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Sep 9 15:09:31 2021 -0400

    Merge pull request #28579 from ChadBailey/patch-2

    Added clarity: remote-exec connection requirement

commit 48768a0037c27dad8fd09de6383455ada77b9275
Merge: 64a95fc29 49b31d005
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Sep 9 14:54:17 2021 -0400

    Merge pull request #29451 from kmadof/patch-1

    Added required paramter `resource_group_name` for MSI
commit a819d7db3ad489e91aff0f295f9d0d44b34ecc81
Merge: 1cd6c9fae b60f201ee
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Sep 9 11:06:58 2021 -0400

    Merge pull request #29502 from hashicorp/alisdair/json-format-version

    json-output: Release format version 1.0

commit 3c518880d39b5d7abf118440241e3e26f4184a72
Merge: 1e1d47d16 e3b6c6403
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Sep 3 12:11:34 2021 -0400

    Merge pull request #29509 from drewmullen/d-module-source-revision-option

    documentation: commit sha can be passed to ref

commit 1e1d47d16d343e5bd917c24ce24d8675431435dd
Merge: 4f10de2ac fa4c590f5
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Sep 3 10:19:30 2021 -0400

    Merge pull request #28345 from yvespp/destroy_provisioners_doc

    document that destroy provisioners don't run with create_before_destroy

commit 73a3bb27029054a0c14f2aef8081900bf821c809
Merge: 05f21cdff b8a0929a5
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Sep 2 14:47:38 2021 -0400

    Merge pull request #28334 from paultyng/patch-1

    Add null to type conversion docs
________________________________

19. Vai Laura ir veikusi commit vakar?
Nē
________________________________
$ git log --since="2022-04-23"
- - - - - - - 
$ git log --author laurapacilio
commit e68ad5ec463fbfa2a9c19abc54f60efb4b779141 (origin/update-TF-WORKSPACE-variable)
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 18:57:50 2022 -0400

    more edits
_______________________________
