# pwn
$python pattern.py create 150 > payload
$ cat payload 
Aa0Aa1Aa2Aa3Aa4Aa5Aa6Aa7Aa8Aa9Ab0Ab1Ab2Ab3Ab4Ab5Ab6Ab7Ab8Ab9Ac0Ac1Ac2Ac3Ac4Ac5Ac6Ac7Ac8Ac9Ad0Ad1Ad2Ad3Ad4Ad5Ad6Ad7Ad8Ad9Ae0Ae1Ae2Ae3Ae4Ae5Ae6Ae7Ae8Ae9

$  python pattern.py offset 0x41396141
first executed
hex pattern decoded as: Aa9A
bof length: 20280
offset: Aa9A
buf type: <type 'str'>
pos 27
