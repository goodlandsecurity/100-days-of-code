# 100 Days Of Code - Log

### Day 1: December 27, 2019 

**Today's Progress**: I've learned about the flag package in Golang, and how to incorporate it into my tcp scanner tool rather than rely on arguments.

**Thoughts**: I've only been learning Golang for a few short weeks, but I am very please with how it is coming along!

**Link(s) to work**:
1. [Golang flag package](https://github.com/goodlandsecurity/go_scan/commit/6b5246a508cf8c6653ca1b1f0d93bbfecd499bd3)

### Day 2: December 28, 2019 

**Today's Progress**: Maps! Golang's equivalent to Python's dictionaries. 

**Thoughts**: It was really straight forward, however I struggled with understanding how to declare a global map in one package that could be accessed from main package. It turns out you need to capitalize your global variables, or you're going to have a bad time!  

**Link(s) to work**:
2. [Calling a global map to get a key's value from main (line 75)](https://github.com/goodlandsecurity/go_scan/commit/4f659d3da13952fbcb084987b863621a45c2dcff)

### Day 3: December 29, 2019 

**Today's Progress**: Today I learned about DNS clients, processing answers from a MSG struct and retrieving/querying A and CNAME records. 

**Thoughts**: I am really enjoying Golang!

**Link(s) to work**:
3. [subfinder - enumerating subdomains!](https://github.com/goodlandsecurity/subfinder)

### Day 4: December 30, 2019

**Today's Progress**: The step from DNS to SMB is intense. Learning about using mixed encoding of struct fields, forcing ASN.1 encoding and understanding metadata and referential fields.

**Thoughts**: This got complicated really fast. I will definitely need to spend more time on this! 

**Link(s) to work**:
4. (nothing complete enough to add to github yet!) 

### Day 5: December 30, 2019

**Today's Progress**: Continuing to learn more about SMB with Golang. Dug into NTLMSSP specification and how NTOWFv2 and ComputeResponse are use to learn about passing the hash. Also, how password-based authentication computes the hash before generating an authentication message, whereas hash-based authentication skips that step and uses the hash directly as input to generate an authentication message. 

**Thoughts**: I could really spend more time with SMB, but for now I am happy. I have a working NTLM password cracker!

**Link(s) to work**:
5. [ntlm_crack - recovering passwords by cracking a supplied NTLM hash!](https://github.com/goodlandsecurity/ntlm_crack)
