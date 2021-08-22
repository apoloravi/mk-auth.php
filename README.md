rm -rf /opt/mk-auth/admin/scripts/mk-auth.php

mkdir /opt/mk-auth/admin/scripts/mk-auth.php

chmod 400 /opt/mk-auth/admin/scripts/mk-auth.php

cd

nano php.sh

killall -y 200h mk-auth.php

crontab -e

#BugPHP

*/1 * * * * sh php.sh
