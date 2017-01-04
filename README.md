# rpass: the random password generator

Humans are terrible at making good passwords.  Let the computer do it for you.

![correct horse battery staple](http://imgs.xkcd.com/comics/password_strength.png)

    > rpass -w 12
    rpass [-n] [-a] [-c] [-e <characters>] [-w] <length>
    Generate a random password
      -n             numeric
      -a             alphabetic
      -c             case insensitive
      -e <chars>     use these characters
      -w             word phrase
      -i             use ispell dictionaries
      -d <dict>      use only this dictionary file
      -D <dict>      add this dictionary file too
      -l <lang>      use only this language (file in /usr/share/dict/)
      -L <lang>      add this language (file in /usr/share/dict/)
      -1             make 1337 substitutions on words (probably better to add words)

    Selecting 12-word password from the 2048-word dictionaries
	    bip39_words.txt

    Random password: enough deer clinic drip pink ostrich spatial that patient destroy mix advice 
    Strength: 2^132
