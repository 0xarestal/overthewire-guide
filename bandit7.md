# Bandit 7

The password for the next level is stored somewhere on the server and has all of the following properties:

owned by user bandit7
owned by group bandit6
33 bytes in size

the command to get the password is

```
find / -type f -user bandit7 -group bandit6 -size 33c 2>/dev/null
```

you will get a file named bandit7.password
lets head onto the next level!
