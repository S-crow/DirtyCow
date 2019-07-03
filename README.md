# DirtyCow

                        .=     ,        =.
                _  _   /'/    )\,/,/(_   \ \
                 `//-.|  (  ,\\)\//\)\/_  ) |
                 //___\   `\\\/\\/\/\\///'  /
              ,-"~`-._ `"--'_   `"""`  _ \`'"~-,_
              \       `-.  '_`.      .'_` \ ,-"~`/
               `.__.-'`/   (-\        /-) |-.__,'
                 ||   |     \O)  /^\ (O/  |
                 `\\  |         /   `\    /
                   \\  \       /      `\ /
                    `\\ `-.  /' .---.--.\
                      `\\/`~(, '()      ('
                       /(O) \\   _,.-.,_)
                      //  \\ `\'`      /
                     / |  ||   `""""~"`
                   /'  |__||
                         `o
           
           
           
DirtyCow (CVE-2016-5195) is a privilege escalation vulnerability in the Linux Kernel  
This exploit is for both 32 and 64-bit 

# Usage Example For 32 Bit

* $ gcc dc32.c -o cowroot -pthread
* $ ./cowroot
* $ echo 0 > /proc/sys/vm/dirty_writeback_centisecs

# Usage Example For 64 Bit

* $ gcc dc64.c -o cowroot -pthread
* $ ./cowroot
* $ echo 0 > /proc/sys/vm/dirty_writeback_centisecs
