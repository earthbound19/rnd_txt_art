# rnd_txt_art
Public Domain random text art ▅▉▜▅▅▏▜▅▉▜■▉ collection

See [randomNsetChars.sh](https://github.com/earthbound19/_ebDev/blob/master/scripts/randomNsetChars.sh) and [randomNsetCharsAlt.sh](https://github.com/earthbound19/_ebDev/blob/master/scripts/randomNsetCharsAlt.sh). Most or all of this collection might be output from it.

Example command that invokes `randomNsetChars.sh` 20 times to generate noise of ~200
randomly chosen block characters (where the script by default chooses a subset of block
chars to produce noise of a potentially different character every run), printed to the terminal,
with sleep periods in between to avoid overheating a laptop:

for n in `seq 20`; do randomNsetChars.sh 200; sleep 15; done

To pipe it all to incrementing numbered documents without pauses; each document contains
a different character of noise:

for n in `seq 20`; do n=`printf "%04d" $n`; randomNsetChars.sh 800 > $n.txt; done




Sample output from 1 run that prints 800 characters (but broken into lines that
GitHub may display better) :

▏▌▝▖▅▍▎▋█▃▍▃▃█▘▘▂▀▔▛▛▂▂▀▖▖▖▌▂▎▀▂▓▘▏▋▔▘▘▀▃▔▖▘▎▓▂▌▘▋▌▅▀▘▎▅▘▂▎▘▛▘▃▘▓▃▏▔▓▏▍▍
▘▋▂▛▂▃▋█▎▖▂▏▋▔▖▎▎▘▔▂▂▀▘▘▂▍▃▘▘▛▝▘▎▛█▃▘▖▛▝▖▍▎▏▖▂▃▋▘▏▂▘▂▂▋▝▂▛▖▀▎▘▂▃▀▃▂▔▘▃▌▏
▀▎▓▔█▋▃▖▃▂▘▝▔▍▀▃▛▔▃▃▃▃▛▏▌▅▂▂▃▂█▌▔▂▝▏▂█▌▃▃▘▃▘▂▀▀▘▖▛▀▘▌▋▏▋▝▃▍▅▃▎▂▘▍▌▛▋▔▖▅▌
▅▅▍▌▋▀▎▂▅▘▍▎▝▔▋▏▃▌▓▃▌▎▂▍▀▀▓▔▋▃▋▂▋▃▛▖▅▘▘▋▍▘▛▂▏▀▂▀▋▂▃▌▅▛▋▌▋▏▘▂▛▃▓▘▖▀▓▔▎▘▍▖
▎▘▂▖▂▖▓▏▂▋▍▂▋▅▓▂▘▖▔▖▃▓▋▃▖▂▛▏█▘▖▝▏▘▝▔▝▌▓▖▍▝▔▔▋▍▏▎▔▘▀▖▘▌▃▂▝▓▛▃▘▀▋▂▌▋▔█▝▃▛▀
▔▌▅▀▔▖▖▓▂▘▅▍▏▋▃▓▓▓▔▃▃▅▃▘▏▂▂▀▃▔▖▛▋▋▎▝▖▅▋▀▖▖▅▛▀▏▍▓▍▎▖▘▎▖▂▏▋▏▋▃▏▘▏▏▖▏▅▛▏▋▀▘
▖▋▃▃▍▃▍▎▂▛▔▘▂▘▎▅▃▅▝▖▓▖▋▅▃▌▘▅▅▔▋▂▋█▋▂▖▘▃▖▛▎▃▖▘▝▖▛▎▂▀▍▍▔▂▂▖▝▍▛▝▏▔▂█▂▋▓██▂▖
▛▂▋▋▃▖▅█▀▖█▘▀▛▋▃▘▅▔▍▖▃▖▏▂▘▘█▂▛▘▀▘▍▋▖▃▔▍▂▖▋▂▃▛▂▔▖▌▌▃▂▖▔▏▌▘▔▘█▂▖▌▋▃▋▎▃▃▀▖▏
▖▃▌▂▂▂█▃▘▅▓▂▀▓▏▍▔▘▖▖▘▀▛▃█▋▓▝▓▖▋▖▂▘▂▔▂▛▓▍▅▅▓▛▂▖▝▌▖█▘▖▋▌▃▖▂▝▔▛▃▘▔▝▂▘▍▌▖▂▘▔
▌▖▖▌▍▖▘▝▂▖▖▔▏▅▃▛▍▂▅▂▓▓▌▋▝▔▏▂▅▛▃▘█▖▖▌▌▓▔▏▔▋▃▍▔▏▃▓▏▃▎▅▋▋▏▘▃▃▃▓▂▌▌▀▀▎▅▃▝▋▃▋
▂▀▓▌▝▌▋▝▋▃▖▍▂▋▌▘▂▌▔▖▋▅▖▂▂▅▓▘▋▀▂▂▓▌▏▛▀█▋▔▖▘▂▓▌▀▖▏▂▀▂▃▛▝▘▋▘▃▎▖▅▂▝█▖▀▎▃▖▘▌▃