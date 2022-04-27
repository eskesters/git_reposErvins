##Hash salidzināšana
eskesters@PXITC001282 MINGW64 ~/git_repos (main)
$ git cat-file -p 12e06d344079095e005afb3e4428234e7d633125
100644 blob d904713c52c9356e7bb2af5455b3d6cbd14d723d    bilde_devop.jpg
100644 blob e69de29bb2d1d6434b8b29ae775ad8c2e48c5391    readme.md

eskesters@PXITC001282 MINGW64 ~/git_repos (main)
$ git cat-file -p 149fe5e8fc522fc5ee776347ee9f74edad9be252
100644 blob d904713c52c9356e7bb2af5455b3d6cbd14d723d    bilde_devop.jpg
100644 blob 52b07c4cf19a2df0e4ff1c1fbcd77c16df83d375    readme.md

##16.jautajums:
eskesters@PXITC001282 MINGW64 ~/git_repos/terraform (main)
$ git log --after="2022-04-11" --until="2022-04-17"
commit 173e21a0e27dfec9615ac2cfc694dd5cc6365177
Merge: 3a7263990 1943af51a
Author: Brandon Croft <brandon.croft@gmail.com>
Date:   Fri Apr 15 14:40:01 2022 -0600

    Merge pull request #30878 from hashicorp/brandonc/periods_env_creds

    fix(creds): allow periods in TF_TOKEN_... credentials vars

commit 1943af51a22c1453f032df5b5653e9382296ab06
Author: Brandon Croft <brandon.croft@gmail.com>
Date:   Fri Apr 15 11:19:46 2022 -0600

    fix(creds): allow periods in TF_TOKEN_... credentials vars

commit 3a7263990d283e5166e847389ea9d1929d9c8880
Author: Martin Atkins <mart@degeneration.co.uk>
Date:   Fri Apr 15 08:41:49 2022 -0700

    Update CHANGELOG.md

commit dc9940332537d56b4d620cab536f574983618333
Author: Brandon Croft <brandon.croft@gmail.com>
:
commit 173e21a0e27dfec9615ac2cfc694dd5cc6365177
Merge: 3a7263990 1943af51a
Author: Brandon Croft <brandon.croft@gmail.com>
Date:   Fri Apr 15 14:40:01 2022 -0600

    Merge pull request #30878 from hashicorp/brandonc/periods_env_creds

    fix(creds): allow periods in TF_TOKEN_... credentials vars

commit 1943af51a22c1453f032df5b5653e9382296ab06
Author: Brandon Croft <brandon.croft@gmail.com>
Date:   Fri Apr 15 11:19:46 2022 -0600

    fix(creds): allow periods in TF_TOKEN_... credentials vars

commit 3a7263990d283e5166e847389ea9d1929d9c8880
Author: Martin Atkins <mart@degeneration.co.uk>
Date:   Fri Apr 15 08:41:49 2022 -0700

    Update CHANGELOG.md

commit dc9940332537d56b4d620cab536f574983618333
Author: Brandon Croft <brandon.croft@gmail.com>
:

##17.jautajums
eskesters@PXITC001282 MINGW64 ~/git_repos/terraform (main)
$ git log --author="Laura Pacilio"
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
##18.jautajums
eskesters@PXITC001282 MINGW64 ~/git_repos/terraform (main)
$ git log --author="Laura Pacilio" --since="2021-09-01" --before="2021-09-30"
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
:

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
##19jautājums
eskesters@PXITC001282 MINGW64 ~/git_repos/terraform (main)
git log --author="Laura Pacilio" --since="2022-04-21" --before="2022-04-22"

