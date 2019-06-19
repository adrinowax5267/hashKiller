# hashKiller

installing steps

pip install -r hashKiller.txt


#usg

usage: hashKiller.py [-h] [-A <option>] [-H <hash>]

optional arguments:
  -h, --help            show this help message and exit
  -A <option>, --option <option>
                        Choose hash' option between ['md5', 'sha1', 'sha256',
                        'sha384', 'sha512', 'rmd160', 'lm', 'ntlm', 'mysql',
                        'cisco', 'juniper', 'gost', 'whirlpool', 'ldap_md5',
                        'ldap_sha1']
  -H <hash>, --hash <hash>
                        Specify a hash to crack

Example:--->  python2 hashKiller.py --option md5 --hash 967ab7737cccb696be5fd243d32796b0
