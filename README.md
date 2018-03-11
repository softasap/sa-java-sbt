sa-java-sbt
===========

[![Build Status](https://travis-ci.org/softasap/sa-java-sbt.svg?branch=master)](https://travis-ci.org/softasap/sa-java-sbt)

The interactive build tool
Define your tasks in Scala. Run them in parallel from sbt's interactive shell. 

Example of usage (all parameters are optional)

Simple

```YAML
  roles:
    - {
        role: "sa-java-sbt",
        sbt_version: "1.1.1"
      }
```

Advanced:

```YAML
  roles:
    - {
        role: "sa-java-sbt",
        sbt_version: "1.1.1",

        sbt_lib_root_path: "/usr/share/sbt",
        sbt_lib_path: "{{sbt_lib_root_path}}/{{sbt_version}}",

        bin_dir: "/usr/bin",
        sbt_bin_link: "{{bin_dir}}/sbt"

      }
```

Copyright and license
---------------------

Code is dual licensed under the [BSD 3 clause] (https://opensource.org/licenses/BSD-3-Clause) and the [MIT License] (http://opensource.org/licenses/MIT). Choose the one that suits you best.

Reach us:

Subscribe for roles updates at [FB] (https://www.facebook.com/SoftAsap/)

Join gitter discussion channel at [Gitter](https://gitter.im/softasap)

Discover other roles at  http://www.softasap.com/roles/registry_generated.html

visit our blog at http://www.softasap.com/blog/archive.html
