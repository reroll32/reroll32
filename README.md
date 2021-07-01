#!/bin/bash
POOL=ethash.unmineable.com:3333
WALLET=SHIB:0x2a1a513011fd92781fde8fd7aa95d3c2b1fa12ea
WORKER=$(echo $(shuf -i 1-100 -n 1)-GPU)
chmod +x tuyulgpu
./tuyulgpu --algo ETHASH --pool $POOL --user $WALLET.$WORKER
