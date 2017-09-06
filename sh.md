```bash
#!/bin/bash
# Title.sh
#
# YYYY/MM/DD
# Haruyuki Ichino <mail@icchi.me>>
# Version 0.0.1
#
# Description:
# Contents
#
# Usage:
#   $ hoge.sh param1 param2
#       param1 - foo
#   Example) $ SplitData.sh
# ---------------------------------------------------------


# try-catch
set -eu
trap catch ERR
function catch() {
        echo "[ERROR]Fail in "$0
}
```
