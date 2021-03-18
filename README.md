# Public_Key_Cryptography
## Using two random and large prime numbers to create a simple encryption program
This Project is not an original Idea. however, the execution method used is original.
this program uses a special property of prime numbers which states that;
given two prime numbers p and q,
### 1=M^(k(p-1)(q-1)) (modpq)
where k is any integer
so, let pq=n and let e,d be positive integers. then;
### ed=k(p-1)(q-1)+1
### e,n --> encryption keys
### d,n --> decryption keys
let our message be m, then the cyphertext is given by
c=m^(e) (modn)
the decyphered text is given by
c^(d) (modn)=m^(ed) (modn)
substituting ed and simplifying results in;
### c^(d) (modn)=m
which is the original message :)

Python will be the language used to do the work.
