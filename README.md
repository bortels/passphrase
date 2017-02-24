Generate a secure passphrase

wordlist is EFF short wordlist #1 from https://www.eff.org/dice modified
to remove dice codes.

Code stolen liberally from https://docs.python.org/3/library/secrets.html

passphrase generated in this manner should:
    have > 80 bits of entropy
    be memorizable with reasonable effort
    be unambiguous when spoken
    contain no odd or "problem" words
