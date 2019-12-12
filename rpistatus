#!/bin/bash
for n in {1..20}; do printf "rpi%02d : " "$n"; ping -c1 "rpi$n" > /dev/null 2>&1; if [ $? -eq 0 ]; then echo "alive"; else echo "dead"; fi; done

