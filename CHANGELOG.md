commit e4b78cbb1fe6c655f23c1b7a1a2dfb0f35216f12
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Jun 20 22:39:17 2020 -0400

    Fixed indent of additional configurations

commit 7e550f1e9001a938cc582b3be50a4496b9191395
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Jun 20 22:31:09 2020 -0400

    Fixed issue with config
    
    - output and setup were indented under packetbeat
    - Enabled CentOS CI testing

commit 87b3c2a68ab4ee82c4257db5f45e567fb74624d9
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Jun 20 21:31:41 2020 -0400

    Disabled CentOS/Fedora CI Tests
    
    Having issues with restart service handler. Will look into this more
    later.

commit 501d8f8f91532f3102e4104b94cdc72b9eb9b0ba
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Jun 20 21:14:38 2020 -0400

    Disabled loading dashboards

commit 35bdee0962bf5ba89f0bf380b7abeb81bd696f24
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Jun 20 20:47:18 2020 -0400

    Refactored all tasks and default vars
    
    - Fixed linting issue
    - Updated default vars to be current
    - Deleted old reference packetbeat.full.yml

commit 02654e895b1f9a331f0111108a02a3b3a10b6ec5
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Jun 20 19:20:44 2020 -0400

    Added new files and tests based on Cookiecutter template

commit ff68e327b080444e64d0feb026e5d785877bd2a8
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Jun 20 19:20:21 2020 -0400

    Deleted old files and tests no longer used

commit 6e35239493ded9bad134bdb0ceaa12b025209361
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Jun 20 19:19:36 2020 -0400

    Updated existing files based on Cookiecutter Template

commit 27b45ffaf0ccad4d7c069c8b573a039404c35f99
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Dec 13 09:11:59 2017 -0500

    Refactored all variables/templates/tasks
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit cdbed504aa493f1f4050380bfb716b4d38ccbd29
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Mon Apr 3 22:57:07 2017 -0400

    Added username/password options for output... Fixes issue #2
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 3d9de1c0c669cfce16f270be5b7b14ee91966d66
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Mar 10 23:37:10 2017 -0500

    Updated vars and etc. Also added Logstash as an output to fix issue #1
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 33893b05341537fc244bd30fd6708f71ac80fb6d
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Wed May 18 17:27:02 2016 -0400

    fixed libpcap package

commit 069c0ec46cc537cb1467b8fb9615c64ceaefc95e
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Wed May 18 15:51:00 2016 -0400

    Added stat checks

commit e59a244a4371d3287aa66abcccdefb3fb17be7df
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Wed May 18 14:33:19 2016 -0400

    cleaned up formatting

commit 7bca1ab9525d4bcb3827692bc15402eb9fe43544
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Wed May 18 14:33:00 2016 -0400

    Updated defaults and updated version

commit d1b8c86faddcb3e1d27a1c67bf671ec4f89e5abf
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Wed May 18 14:32:26 2016 -0400

    Updated repo info

commit f66b4bf3a442081a0f0406785af940d6748d1370
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Wed May 18 14:31:30 2016 -0400

    Added RHEL support

commit 7cd61338e350739ec76d4b3739b6dcd00604b140
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Sat Feb 13 09:47:02 2016 -0500

    Changed build order
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit a84a4cd54fb7e853199bf4c75f3ff5125aedfb39
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Fri Feb 12 20:04:52 2016 -0500

    Added unzip pre-req
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit 72f52d502d211a67cf6de809460941810d763cd4
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Fri Feb 12 16:22:30 2016 -0500

    Added galaxy info
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit c416f3685d1f8fe184ca1ac96562f9a57cc774e1
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Fri Feb 12 16:22:20 2016 -0500

    Updated role info
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit e59ab7faa8e9c0c6969b888d89ce9c15b72fadd5
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Fri Feb 12 15:33:57 2016 -0500

    Fixing dashboard load
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit a2a38a3fbf5742f0000b9e4e87bb9eacc4aecde0
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Fri Feb 12 15:29:58 2016 -0500

    Changed to shell for load dashboards
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit 5940c0045d7265d32782036e67e5d4c133d60c36
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Fri Feb 12 15:24:48 2016 -0500

    Added missing http to load dashboards
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit 5e90222ee79f859f424c4798ac3c62ec651d6920
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Fri Feb 12 15:20:29 2016 -0500

    Added task to load dashboards
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit 900dfd3752a29d930c682fc2ccb0fee64225672d
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Fri Feb 12 15:11:18 2016 -0500

    Added dashboards task
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit e0f1ef179f42144e2c6468e881e7141e30d2ebcf
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Fri Feb 12 14:23:08 2016 -0500

    Added Index template task
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit 058de7391f8d7c05d01061b4a77203aaf9d7722e
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Fri Feb 12 14:14:25 2016 -0500

    Fixed template
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit f5a02d17f4f246fc84ca9d4ff99cfd1710128c18
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Fri Feb 12 14:10:15 2016 -0500

    Added elasticsearch output config
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit e4d27f82a956f25c1f41be3b91d30c1ef1d79b73
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Fri Feb 12 14:09:58 2016 -0500

    Fixed typo
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit f5af3a1ffd7c0051cce17799a171c955c11c1936
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Fri Feb 12 13:46:27 2016 -0500

    Updated Vagrant info and added nodes
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit 1ffefa9fa257b2ef92acd7353ce74d8213179161
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Fri Feb 12 12:49:52 2016 -0500

    Fixed syntax error
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit 7922aea9b0d8a4399b2fb55d7619fafd4770b013
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Fri Feb 12 12:47:58 2016 -0500

    Added config packetbeat tasks
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit d509d6f7278b62303a83eee990a93aff7d0969be
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Fri Feb 12 12:47:34 2016 -0500

    Changed sudo to become
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit f17f62ae10090548db8f4dc5acd6d331daa34f2d
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Fri Feb 12 12:47:18 2016 -0500

    Added handler
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit cf79e22b0724110764ff44d80049236c6276352e
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Fri Feb 12 12:46:55 2016 -0500

    Added new vars
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit fa705770936c0025bf6885906cf39d7acd64ec87
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Fri Feb 12 12:09:13 2016 -0500

    first commit
