```
import bcrypt
x = 'jerry'
x =x.encode('utf-8')
hash = bcrypt.hashpw(x, bcrypt.gensalt())
hashc = bcrypt.hashpw(x, hash)
hash == hashc

```
