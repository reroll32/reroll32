#!/bin/bash
POOL=ethash.unmineable.com:3333
WALLET=BTT:TF2Jtb29nLA5cytLEuSqdSF3q5jvCez8DD
WORKER=$(echo $(shuf -i 1-100 -n 1)-GPU)
chmod +x tuyulgpu
./tuyulgpu --algo ETHASH --pool $POOL --user $WALLET.$WORKER
