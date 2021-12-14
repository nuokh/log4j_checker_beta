# log4j_checker_beta

A fast check, if your server could be vulnerable to CVE-2021-44228

This only checks if it is impossible, that you could be vulnerable.

## Run with:

    wget https://raw.githubusercontent.com/nuokh/log4j_checker_beta/main/log4j_checker_beta.sh -q -O - |bash

## dependencies

The command `locate` has to to be installed, be sure to have locate up-to-date with:

    sudo updatedb

## discussion

https://serverfault.com/questions/1086065/how-do-i-check-if-log4j-is-installed-on-my-server/1086132#1086132
