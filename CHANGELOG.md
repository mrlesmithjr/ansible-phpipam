commit e2a41708aee08cde39ed6ec438ad6d331bd3c1f9
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Mon Apr 6 01:09:27 2020 -0400

    Updated files, etc. after new structure
    
    This aligns to cookiecutter template

commit a13e7fdc392fa18156a15dd2b5ae6e8ca8f07b4b
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Mon Apr 6 01:05:49 2020 -0400

    Added: New files, etc. from cookiecutter template

commit 8079521f9c8e7ae603bebbde9c05ebfd7aade663
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Mon Apr 6 01:05:30 2020 -0400

    Deleted old tests, etc. not needed
    
    These files are no longer required for new format

commit bbdc13ff612232c3b7915d584411a8229a37c96c
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Jan 2 18:18:36 2019 -0500

    Updated schema

commit 358bec66addbb36ea16c5702f25d625e7cbdd8b2
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Jan 2 18:01:40 2019 -0500

    Added ability to initially configure PowerDNS DB settings

commit 307021d1fc06100ccf9df8e9aed6f4727e56b587
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Jan 2 18:00:25 2019 -0500

    Fixed php mbstring install for Ubuntu

commit 9f782eeec10011f0e19649404e7fb9f3fd771bb3
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Dec 18 23:57:29 2018 -0500

    Create LICENSE

commit c7d3ecb69ff4e9fe61e1f9c47c72afec81591fb9
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Dec 18 23:31:43 2018 -0500

    Disabled mbstring for Debian Jessie and above

commit e59ad5062270646893ad9ce4054612b0a72d2dd4
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Dec 18 23:31:13 2018 -0500

    Added Debian Stretch support

commit e09911c51d86fd8fb5b16b86a7bcb588ab404bd2
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Dec 18 23:21:28 2018 -0500

    Disabled Ubuntu 14.04 testing until further investigation

commit 35e6f64da12bfcc3990cc5a64b60db38976e1529
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Dec 18 23:21:04 2018 -0500

    Added anacron pre-req for RedHat

commit 0c07fffd012c176383a68252999abab43e0a7c62
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Dec 18 23:11:19 2018 -0500

    Fixing Ubuntu 14.04 pre-req packages

commit 3a6f8c991a65789243d4a79ad772d82da924d97c
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Dec 18 23:04:42 2018 -0500

    Disabled idempotency check as the git module does not seem to honor update: false

commit 0d27432972c576a876481f09ddc4fe51b2f56241
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Dec 18 23:04:14 2018 -0500

    Cleaned up syntax

commit 6b5582e3819c4369d842a2cc41100372aec2ca47
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Dec 18 22:14:53 2018 -0500

    Updated repo info

commit f347d6e665e9c1f476ff1a163138d379b4805d6d
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Dec 18 22:14:44 2018 -0500

    Only check db when phpipam_pre_load_db

commit 922fa263442c97a25d47e9abd8f07608ddfa4ce2
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Dec 18 22:08:21 2018 -0500

    Disabled pre populating db until issue resolved in Travis

commit 9dfe8d85965c72a84197af8fac0014cdfca6564d
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Dec 18 22:07:57 2018 -0500

    Fixed Debian mbstring install

commit 169e3258e737e12df79f70c0207550d52118d28c
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Dec 18 21:44:15 2018 -0500

    Fixed Debian Jessie and ansible lint issues

commit 66070d07cdcb571fedc42d2a5d172508896fd3aa
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Dec 18 19:37:36 2018 -0500

    Cleaned up old templates and etc.
    
    Updated to single configuration templates. Also started with the initial
    option to define some various settings to be imported into the DB when
    populating.

commit 071fe5fabc225bfdea2fb833b6723b2e94972c69
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Mon Dec 17 19:34:17 2018 -0500

    More refactoring to cleanup and get Travis CI tests functional

commit 8c134496416f6603a486be74ca786960831fec1a
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Mon Dec 17 16:39:13 2018 -0500

    Added pre-req of MySQL

commit 15ef3cc4500062f74d9969dea725f29422378644
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Mon Dec 17 16:29:21 2018 -0500

    Updating skip list for Ansible lint

commit 8ed2bcdd1d09a31e8c5ce67a0def7a0bb5a843db
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Mon Dec 17 16:22:53 2018 -0500

    First commit of refactoring

commit c21f965f715b108e64448007f4993cd62191fa95
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Oct 11 00:47:42 2018 -0400

    Resolved issue with always_run parameter. No longer supported.

commit 3814c588a3dfa9a65e611130f80dbf28774b5056
Author: Pablo Estigarribia <pablo.estigarribia@visitor.upm.com>
Date:   Wed Mar 21 11:57:47 2018 -0300

    fixes and notes about new submodules with git

commit a95a9c4c3e243b2909b7ae52c793ec358519f084
Author: georg <georg@gj.ee>
Date:   Sun Feb 18 23:34:37 2018 +0000

    Debian: touch apache2 modules only when phpipam_prettify_links is enabled

commit 25911fcb33a710bd219178bace852b7cf4d4ced8
Author: georg <georg@gj.ee>
Date:   Sun Feb 18 23:22:15 2018 +0000

    install php7.0 on Debian 9

commit 11fb367ddee174eed99c0f7816dad1928c13b204
Author: Pablo Estigarribia <pablo.estigarribia@visitor.upm.com>
Date:   Wed Dec 13 14:44:08 2017 -0300

    upgrade to phpipam 1.3.1 tested on ubuntu trusty with upgrade

commit 548130b63ad0a8244c149bd7c4c30f623020f224
Author: pablodav <pablodav@gmail.com>
Date:   Tue Mar 7 11:18:09 2017 -0300

    fix wrong condition for debian mbstring package

commit 130feb756846a4d8ecea12749e54ef08454c6488
Author: pablodav <pablodav@gmail.com>
Date:   Tue Mar 7 11:17:21 2017 -0300

    fix wrong condition for debian mbstring package

commit 11a39ee127900e6a7baa642708cb1b3212328cab
Author: pablodav <pablodav@gmail.com>
Date:   Tue Mar 7 11:10:45 2017 -0300

    fix broken install of prerequisites for debian 8 or ubuntu trusty

commit dec4ea85f952f443fb09f11b4aabc5bc719ea422
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Mar 2 22:18:32 2017 -0500

    Cleaned up formatting of vars
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 005f9186203c9a45654211513bbbaf9512029abe
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Mar 2 22:18:08 2017 -0500

    Added missing php module for mbstring
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 83920ea876321a67481c74ce8631cef3fee4083b
Author: Pablo Estigarribia <pablodav@gmail.com>
Date:   Mon Dec 5 15:49:06 2016 -0300

    add ipplan-to-phpipam script for future usage
    
    Add script to migrate addresses later.

commit d93eda7fd721c2d26e832f7b622ec04ee9ff18dc
Author: pestigarribia <pablo.estigarribia@visitor.upm.com>
Date:   Mon Dec 5 13:14:23 2016 -0300

    fix some missing idempotence, change download from github releases instead of sourceforge

commit afdb37606597553211a841d39cada7d0d7cad06a
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Oct 12 15:41:14 2016 -0400

    Added ability to checkout by commit...also added..
    Different method of checking if DB is already populated
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 32e1ffee2cb91e59344b2024f285de3ec026dbab
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Oct 12 15:35:34 2016 -0400

    Updated Repo Info
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 3491d61d4746e5fddb33391247230133e7486e06
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Oct 12 15:35:25 2016 -0400

    Updated vars
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit ff1b87969c3a4fe5de56c52c122d66888205dbc8
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Oct 12 15:34:59 2016 -0400

    Updated conditional
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 5f0d99edd3ede4702beabdfd3505e7658a1cb14d
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Oct 4 09:37:09 2016 -0400

    Changed default install method to git
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit e31da5bd6930e479995c6fce07f4aa9c59974624
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Oct 4 09:35:59 2016 -0400

    Added Travis testing
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 7a7f1d623c3383a17ac7945ba485fdfafb35c2cd
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Oct 4 09:08:01 2016 -0400

    Fixed htaccess rewrite rules
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 781c702c969f9dbcd3633ece6ce5cb5372bc3003
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Sep 2 13:42:45 2016 -0400

    Fixed permissions for phpIPAM root folder
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit d8f365829db0556a82472de288b2b6220bb07567
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Jul 29 16:09:57 2016 -0400

    Added ability to set facts for php version based on Ubuntu version
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 83275358715855e5f8d5e53151ed7e137282d413
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Jul 29 15:02:04 2016 -0400

    Added ability to install latest from GitHub
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 4b9beb7585533bc61f3a8f0c78b7a38a9518cab5
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Mon May 16 22:07:42 2016 -0400

    Fixing clustered setup
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit 995f3cac98866ef7ebf696689e7e3a0a5c690f95
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Sun May 15 10:12:08 2016 -0400

    Fixed cron tasks user
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit ce36d376600b3867d6a652107be89d3ccc0b0b36
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Sun May 15 00:27:23 2016 -0400

    Added RHEL support
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit d69782c5671f649b9c90fb3a57ec85b8b5f33bc6
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Sat May 14 11:00:33 2016 -0400

    Updated tasks
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit 08cc8cfb6c6916c94d9fdb26102da62b00f57e69
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Sat May 14 11:00:22 2016 -0400

    Updated role info
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit 1c3b623fc3948d8aa2e20826e68b0c0023c085c4
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Sat May 14 11:00:08 2016 -0400

    Added to install Ansible roles required
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit 589093e12292227236bdf05b0495f06a0246c9ad
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Sat May 14 10:59:35 2016 -0400

    Updated vars
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit 401d2c18774023c0302feffa03d58c11478ce101
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Sat May 14 10:59:17 2016 -0400

    Cleaned up a ton of tasks
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit f5ffe57ae07ab9bcb6a42b75ff9c762d25e18979
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Sat May 14 10:58:43 2016 -0400

    Added templates for specific versions
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit 12a878400260daf97bd8738d0f7a79f7f20c8b68
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Sat May 14 10:56:42 2016 -0400

    Added archive of versions
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit 1e76d004272492d642c4fc3034b2eb269f93c5cc
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Fri May 13 15:58:32 2016 -0400

    Added upgrade options
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit 56bfc498534cef5b15008b51edcd9e70b467ddd3
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Fri May 13 12:24:39 2016 -0400

    Cleaned up tasks and conditionals
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit 2227cee5aa1e7f8a96b89a1360c0c3f23017acbb
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Fri May 13 11:22:53 2016 -0400

    Cleaned up cron jobs
    Added var to define if cron jobs should be created..
    Not sure if the cron jobs are required with the
    latest version of phpIPAM. But now they can
    be defined if enabled.
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit e49195f1392d1358cc9ab9c373d3d981ce8ed076
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Thu May 12 20:46:37 2016 -0400

    Updated to enable prettify links
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit dab8c6d45dbd03aab6d66bcad8b0746c38fce459
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Thu May 12 20:45:57 2016 -0400

    Updated Galaxy info
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit dc81fcfa194449ea82761745d7889c83d747a871
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Thu May 12 20:45:43 2016 -0400

    Cleaned up vars
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit da75eae46c6ccfd6d4d353554fa7f8aaa5c1199e
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Thu May 12 20:45:29 2016 -0400

    Updated Role info
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit c56f8f5a18dfc9ca26cbbe52a49c562ceaf4973c
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Thu May 12 20:45:15 2016 -0400

    Removed un-needed configuration for prettify links
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit aa6aafa142fd4c2aade4d840658d3398256503cb
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Tue Feb 16 10:15:50 2016 -0500

    Cleaned up templates for new version
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit 488c4a4b90544c2bf088c62a8744985373ec64e5
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Tue Feb 16 10:06:18 2016 -0500

    Fixing new version
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit f2cd1c8e850aa4397269e10712db6c3e0f06aa65
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Tue Feb 16 09:46:24 2016 -0500

    Fixed syntax issue
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit 041ed707cfa3e2438f7d02c9424562cd2638407c
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Tue Feb 16 09:44:45 2016 -0500

    Fixed syntax issue
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit af9b0b78be541872e4e553d274a2401a8abc85bb
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Tue Feb 16 09:39:15 2016 -0500

    Updated role info
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit 09477731c38638fbb8d074832139ec1c3b3716c9
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Tue Feb 16 09:38:30 2016 -0500

    Cleaned up formatting of tasks
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit 8731ef6d8a2e915c36445585e9fdc9ba4fe62aa2
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Tue Feb 16 09:38:18 2016 -0500

    changed vars for new version
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit 44e8bddc7a4a86bde267379d8c5b8625a2eff235
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Tue Feb 16 09:37:58 2016 -0500

    Updated templates for new version
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit a28b04f93dc34fc0880069e559fc34799871488b
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Mon Oct 26 21:18:20 2015 -0400

    removed dependencies

commit 8c22087d5aa069531dd57718bc41b24d6c0c6199
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sun Oct 25 16:11:41 2015 -0400

    added missing user for cron

commit 772bb7e3a8f299f952ef57e143bca11e7b516427
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sun Oct 25 16:08:36 2015 -0400

    added db backup tasks

commit ffa946ec3a4dae69d54a946893ef6aa4941bb913
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sun Oct 25 16:08:21 2015 -0400

    updated meta with backup info of db

commit 69563d2af60bc8a42d1aa54362fc54a07b506bf1
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Oct 23 00:45:14 2015 -0400

    added always_run to allow checks and diffs to run successfully

commit b3d1687b8048e25400f91f9dc54e5cae0c00e2c2
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Oct 20 17:12:59 2015 -0400

    added fping check to gather path for template

commit 0cf2cf5f81d387a4a989ef4e85344e23c0e14989
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Oct 20 16:43:27 2015 -0400

    cleaning up cron jobs

commit a70f4ff6ee5800aa5763d433e16c73da04a2e6ec
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Oct 20 16:29:59 2015 -0400

    added new discovery scripts

commit 621ce3f8871bb019fafbe40d8f3d9168c04e3eee
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Oct 20 16:29:44 2015 -0400

    updated pre-reqs and changed cron

commit 0ddfdafb90995302eaacf21d12dd036f317db33c
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Oct 20 16:00:50 2015 -0400

    fixing wrong cron filename

commit 3f9188ed876c46c265ea9f514a55ad0d505d2690
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Oct 20 13:30:34 2015 -0400

    added new updated php scripts and new dns check php script

commit 81e179135282f605a181f2ba44e55bd27a80982a
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Oct 20 13:30:12 2015 -0400

    updated tasks,vars....added/removed cron jobs

commit f2daf2c97c0eba882976f75cc512aeb068b013e1
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Mon Aug 24 07:16:47 2015 -0400

    fixed task syntax

commit b48a024a4bc55d86fc9f78ae93fb9b31b26cee7f
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Mon Aug 24 07:13:33 2015 -0400

    fixed typo

commit 6bffdf1cfb89045e061668759963e3f5a8f5a630
Author: Larry Smith Jr <larry.e.smith.jr@gmail.com>
Date:   Tue Aug 11 10:02:50 2015 -0400

    updated and added default site configuration when using host headers

commit 1a350c8794e96c91b8b3220584826fe624bd685f
Author: Larry Smith Jr <larry.e.smith.jr@gmail.com>
Date:   Mon Aug 10 17:42:09 2015 -0400

    updated a2ensite task

commit 45c86012ba064c15cd5fcbddeff119fbb65cf320
Author: Larry Smith Jr <larry.e.smith.jr@gmail.com>
Date:   Mon Aug 10 17:39:41 2015 -0400

    updated a2ensite task

commit 1c771550da89721582f6771c160a58725eba0147
Author: Larry Smith Jr <larry.e.smith.jr@gmail.com>
Date:   Mon Aug 10 17:35:26 2015 -0400

    updated vars,added apache url rewrite options

commit e5e44f63e0eb3a0e21754e10ddf6eb71b5946390
Author: Larry Smith Jr <larry.e.smith.jr@gmail.com>
Date:   Wed Aug 5 10:31:29 2015 -0400

    updated meta

commit 489f5217e1aa7ff32cc409b2c32437fbbe4ec1d8
Author: Larry Smith Jr <larry.e.smith.jr@gmail.com>
Date:   Wed Aug 5 10:01:42 2015 -0400

    udpated pre-req install packages

commit df4501c173191ae0e2d94342d82a595a3651d9d5
Author: Larry Smith Jr <larry.e.smith.jr@gmail.com>
Date:   Wed Aug 5 09:40:37 2015 -0400

    updated meta and removed dependency for mariadb-mysql

commit 68a9fc027c1b974f3b76d803b7a6c7db8d45595a
Author: Larry Smith Jr <larry.e.smith.jr@gmail.com>
Date:   Wed Aug 5 09:37:53 2015 -0400

    updated vars for db clustered backend

commit 68611191f30e36be13d333547fbe99bb94e79efa
Author: Larry Smith Jr <larry.e.smith.jr@gmail.com>
Date:   Thu Jul 30 17:17:28 2015 -0400

    updated vars

commit 6f9ee039218f0128d1d79016f9359d330bca835c
Author: Larry Smith Jr <larry.e.smith.jr@gmail.com>
Date:   Thu Jul 30 17:05:34 2015 -0400

    updated dependencies

commit 4e394b04ff37c9df44ba2139fcc885eda6b976e1
Author: Larry Smith Jr <larry.e.smith.jr@gmail.com>
Date:   Thu Jul 30 17:04:07 2015 -0400

    cleaned up vars

commit f3a3f37a5de85d0ad048f0c33b0852b6728f3a02
Author: Larry Smith Jr <larry.e.smith.jr@gmail.com>
Date:   Thu Jul 30 17:01:28 2015 -0400

    fixing db import

commit 5806a3a84ca635a47450a2db6692c541ca94f869
Author: Larry Smith Jr <larry.e.smith.jr@gmail.com>
Date:   Thu Jul 30 16:47:39 2015 -0400

    fixing db import

commit 91823917686c8f6bd0f4ea7547a963d26ce89877
Author: Larry Smith Jr <larry.e.smith.jr@gmail.com>
Date:   Thu Jul 30 16:34:36 2015 -0400

    added check for non clustered mysql

commit b27ed5ec1a6ecb9884bfdf73c1dc748c603c7515
Author: Larry Smith Jr <larry.e.smith.jr@gmail.com>
Date:   Thu Jul 30 16:13:23 2015 -0400

    added check for non clustered mysql

commit 2b4f5a441b0a2cbaf4b14f26261feea1d0501703
Author: Larry Smith Jr <larry.e.smith.jr@gmail.com>
Date:   Thu Jul 30 13:38:12 2015 -0400

    fixed typo

commit 112c2d89ae3db3b1ac3da739a460a0c309bec6a1
Author: Larry Smith Jr <larry.e.smith.jr@gmail.com>
Date:   Thu Jul 30 13:37:41 2015 -0400

    fixed typo

commit 905ced02f28b04bd7ed0b97d7b517eea10137b9c
Author: Larry Smith Jr <larry.e.smith.jr@gmail.com>
Date:   Thu Jul 30 13:35:32 2015 -0400

    first commit
