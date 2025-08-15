# Specific Checks

Heartbleed oneliner: echo QUIT | openssl s_client -connect target:443 2>&1 | grep 'server extension "heartbeat" (id=15)'