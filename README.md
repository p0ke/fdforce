# fdforce

Here is a tool I made to work with .fd file in command lines.
use example :

fdforce format putdos import HELLO.BIN 10 savefd HELLO.fd diskname MYTEST exit

Some bug are remaining. I do my best !!!

cheers

p0ke/flush (aka Armand Patou)

ps:
fdforce is in fact fdforce.php, but you can put a binary in your /usr/bin/ that will call it properly :php fdforce.php plus the parameters.

Only php-cli is needed. 
At first I wanted to make it works with browser but the approach is different, and was out of time, so I kept only the cli version.

