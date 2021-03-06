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

### Day 5: December 31, 2019

**Today's Progress**: Continuing to learn more about SMB with Golang. Dug into NTLMSSP specification and how NTOWFv2 and ComputeResponse are use to learn about passing the hash. Also, how password-based authentication computes the hash before generating an authentication message, whereas hash-based authentication skips that step and uses the hash directly as input to generate an authentication message. 

**Thoughts**: I could really spend more time with SMB, but for now I am happy. I have a working NTLM password cracker!

**Link(s) to work**:
5. [ntlm_crack - recovering passwords by cracking a supplied NTLM hash!](https://github.com/goodlandsecurity/ntlm_crack)

### Day 6: January 2, 2020

**Today's Progress**: Started working with connecting to MongoDB, MYSQL/Postgres and MSSQL databases using Golang. 

**Thoughts**: Was interested to learn about MongoDB/NoSQL and how you can insert raw json as a database table. 

**Link(s) to work**:
6. (nothing complete enough to add to github yet!)

### Day 7: January 4, 2020

**Today's Progress**: Sniffing packets and listening on the wire with Golang.

**Thoughts**: Going to build a tcp-syn scan option into my go_scan tool! 

**Link(s) to work**:
7. (nothing complete enough to add to github yet!)

### Day 8: January 6, 2020

**Today's Progress**: I went back to my tcp scanner and added better formatting for scan results using text/tabwriter package and an error message in red text using color.v1 package if no open ports are found.

**Thoughts**: So many ideas so little time! I am very excited with how far along this project has come!

**Link(s) to work**:
8. [go_scan tcp scanner](https://github.com/goodlandsecurity/go_scan)

### Day 9: January 8, 2020

**Today's Progress**: Going back to SQL, and building out an MS-SQL database mapper to connect to the database, loop through each database and list the tables.

**Thoughts**: This is one of my more favorite projects so far!

**Link(s) to work**:
9. (nothing complete enough to add to github yet!)

### Day 10: January 9, 2020

**Today's Progress**: Still working with MS-SQL. Tomorrow I will be releasing my MS-SQL database mapper/miner!

**Thoughts**: I want to add functionality for MongoDB and MySQL next!

**Link(s) to work**:
10. (nothing complete enough to add to github yet!)

### Day 11: January 10, 2020

**Today's Progress**: I finished the MS-SQL database miner! Authenticate to the database and watch as everything is mined and mapped in a visually pleasing way! 

**Thoughts**: I already have ideas on how I want to expand on this project! 

**Link(s) to work**:
11. [go_miner SQL database miner](https://github.com/goodlandsecurity/go_miner)

### Day 12: January 11, 2020

**Today's Progress**: Working on incorporating MySQL into my db miner tool.

**Thoughts**: Hoping to wrap it up tomorrow!

**Link(s) to work**:
12. (nothing complete enough to add to github yet!)

### Day 13: January 12, 2020

**Today's Progress**: MySQL addition to the db miner is still in progress.

**Thoughts**: Trying to develop the db miner project as a framework so I can use different plugins for different databases.

**Link(s) to work**:
13. (nothing complete enough to add to github yet!)

### Day 14: January 13, 2020

**Today's Progress**: Switched back to an older Python project of mine. I updated my custom MISP integration that queries Proofpoint TAP api and creates MISP events for each alert.

**Thoughts**: I forked PyMISP, and am anxiously awaiting (hopeful) approval for my pull request. This would be my first contribution to an open source project!

**Links(s) to work**:
14. [proofpoint_tap.py to MISP](https://github.com/goodlandsecurity/PyMISP/blob/proofpoint-tap-integration/examples/proofpoint_tap.py)
