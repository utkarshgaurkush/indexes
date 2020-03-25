#### Acing the GATE

1.  <details><summary>Digital Electronics </summary>

    -   Introduction
    -   Number System
        -   hierarachy
        -   Conversions of Number System
            -   decimal to other
            -   other to decimal
        -   Complement of a Number
            -   r-1
            -   r
            -   subtractions
        -   Representation of Negative Numbers
        -   The IEEE Standard for Floating Point Numbers
            -   single precision
            -   double precision
    -   Boolean Logic
        -   Boolean Algebra Laws (Huntington’s Postulates)
        -   Duality Theorem
        -   Consensus Theorem
        -   Positive Logic and Negative Logic
        -   canonical and standard forms
        -   pos and sop
        -   minimization of expression
            -   boolean theorems
            -   kmap
                -   grouping of cells
                    -   pairs,quads,octets
                -   sop simplification
                -   pos simplification   
    -   Digital Circuits
        -   Combinational Circuits
            -   half adder
            -   full adder
            -   half subtractor
            -   full subtractor
            -   parallel adder(ripple carry)
            -   look ahead adder
            -   decoder
            -   encoder
            -   multiplexer
                -   boolean function implement using mux
            -   demux
            -   implementation of higher order from lower order        
        -   Sequential Circuits
            -   flip flops
                -   RS(direct coupled)
                -   clocked
                -   D
                -   JK
                    -   race around 
                -   master slave JK
                -   T
            -   Inter Conversions of flipflops
            -   applications of flip flops
                -   registers
                    -   2 types
                    -   SISO
                        -   SR and SL
                    -   SIPO
                    -   PISO
                    -   PIPO
                -   counters
                    -   2 types
                    -   4 bit asynchronous UP
                    -   MOD 10 asynchronous
                    -   4 bit synchronous
                    -   MOD 5 synchronous
                    -   shift register
                    -   ring counter
                    -   johnson counter           
    -   Digital Logic Families
        -   table
    </details>


2.  <details><summary>Computer Organization and Architecture </summary>

    -   Introduction 
    -   Computer Architecture 
        -   Register Set 
            -   DR, ACC, AR, IR, PC, TR, INPR, OUTR
        -   Quantitative Principles to Design High-Performance Processor
            -   S, ET, fraction, speed
    -   Machine Instructions and Addressing Modes
        -   Machine Instructions
            -   purpose wise: 
                -   data transfer
                -   data manipulation
                -   program control
            -   address field wise: 3,2,1,0    
        -   Addressing Modes
            -   implied
            -   immediate
            -   register direct
            -   register indirect
            -   auto inc or auto dec
            -   direct address
            -   indirect address
            -   relative address
            -   index address
            -   base register address
    -   Arithmetic Logic Unit
        -   Arithmetic Micro-Operations
            -    +, - , ++, --, shift
            -   mux + parallel adder
        -   Logic Micro-Operations
            -   AND, OR, XOR etc.
            -   other operations
                -   selective set
                -   selective complement
                -   selective clear
                -   mask
                -   clear
                -   insert
    -   CPU Control Design
        -   types of organization
            -   single accumulator
            -   general register
            -   stack
        -   Instruction Execution
            -   fetch
            -   decode
            -   operand fetch
            -   execute 
        -   CPU Data Path
            -   1,2,3 bus structures
        -   Control Unit Design
            -   hardwired
            -   microprogrammed : horizontal and vertical
        -   RISC versus CISC Processors
    -   I/O Interface (Interrupt and DMA Mode)
        -   modes of transfer
            -   programmed
            -   interrupt initiated
                -   H/W 
                -   S/W
                -   maskable
                -   non maskable
                -   vectored
                -   non vectored
                -   external
                -   internal
                -   synchronous
                -   asynchronous
            -   DMA
                -   block diagram
                -   modes of operation
                    -   burst or block transfer
                    -   cycle stealing
                    -   transparent
                -   DMA controller interconnection with memory, cpu, i/o devices        
    -   Instruction Pipelining
        -   speed up
        -   hazards
            -   structural
            -   data
                -   RAW
                -   WAR
                -   WAW   
    -   Memory Hierarchy 
        -   Main Memory
            -   static ram
            -   Dynamic RAM
            -   memory interfacing
        -   Secondary Memory 
            -   flash
            -   optical disk
            -   magnetic disk
            -   magnetic tapes
        -   Cache Memory 
            -   hit ratio
            -   elements of cache design
                -   cache size
                -   mapping function
                -   replacement algo
                -   write policy
        -   Cache Mapping Techniques 
            -   direct
            -   fully associative
            -   set associative
    </details>


3.  <details><summary> Programming and Data Structures </summary>

    -   Introduction 105
    -   Basic Terminology 105
        -   Programming Languages 105
        -   Classification of High-Level Languages 106
        -   Procedural Programming and Object-Oriented Programming 106
        -   Data Types 107
        -   Control Flow Statements 108
        -   Array 110
        -   Function and Recursion 111
        -   Pointers 113
        -   Parameter Passing 115
        -   Structures and Unions 117
        -   Enumerated Data Types 117
        -   Scoping 117
        -   Binding 118
        -   Abstract Data Types 119
    -   Stack 119
        -   PUSH Operation on Stack 119
        -   POP Operation on Stack 119
        -   Application of Stack 120
    -   Queue 122
        -   Basic Operations on Queue 122
        -   Types of Queue 123
        -   Applications of Queues 123
    -   Linked List 123
        -   Basic Operations 123
        -   Linked List Implementation 124
    -   Trees 125
        -   Binary Tree 125
        -   Types of Binary Trees 125
        -   Array Representation of Binary Trees 126
        -   Tree Applications 126
        -   Binary Search Tree 126
        -   Graphs 127
    </details>

4.  <details><summary>Algorithms</summary>

    -   Introduction
    -   Algorithm
        -   Properties of Algorithm 177
        -   Steps to Solve a Problem 177
        -   Algorithm Analysis 178
        -   Asymptotic Notation 178
        -   Recurrence Relations 180
    -   Hashing  182
        -   Hash Table 182
        -   Hashing Functions 182
        -   Collisions 182
    -   Binary Heap 184
        -   Insertion in Min-Heap Tree 185
        -   Deletion in Min-Heap Tree 185
        -   Time Complexity 186
    -   Searching and Sorting 186
        -   Linear Search 186
        -   Binary Search 187
        -   Bubble Sort 187
        -   Selection Sort 187
        -   Insertion Sort 188
        -   Heap Sort 188
        -   Merge Sort 190
        -   Quick Sort 192
        -   Randomized Quick Sort 193
        -   Counting Sort 193
        -   Comparison of Sorting Techniques 194
    -   Graph 194
        -   Types of Graph 194
        -   Types of Simple Graph 194
        -   Graph Representation 195
    -   Greedy Approach 195
        -   Applications of Greedy Approach 196
        -   Fractional Knapsack 196
        -   Huffman Coding 197
        -   Minimum Spanning Tree 198
        -   Single-Source Shortest Path 200
    -   Graph Traversal 201
        -   Breadth-First Traversal 201
        -   Depth-First Traversal 202
    -   Dynamic Programming 203
        -   Applications of Dynamic Programming 204
        -   Fibonacci Series 204
        -   0/1 Knapsack 204
        -   Longest Common Subsequence 205
    -   All-Pair Shortest Path 205
        -   Floyd’s Algorithm 205
    -   Concepts of Complexity Classes 205
        -   P-Complexity Class 205
        -   NP Complexity Class 206
        -   NP-Complete 206
        -   NP-Hard 206
    </details>

5.  <details><summary>Theory of Computation</summary>

    -   Introduction 
    -   Finite Automata 
        -   Finite Automaton Model Characteristics
            -   input
            -   output
            -   states
            -   states relation
            -   output relation
        -   Technical Terms 
        -   Grammar : V,T,S,P
        -   Noam Chomsky Grammar Classification: 0, 1(CSG), 2(CFG), 3(RG) and difference table,machines and restrictions
        -   Chomsky Hierarchy :diagram
        -   Different Grammar Types : table
    -   Finite Automata and Regular Language
        -   Deterministic Finite Automata 
        -   Non-deterministic Finite Automata
        -   Comparison of DFA and NFA  table
        -   DFA and NFA Design 
            -   permanent accept
            -   permanent reject ,trap
            -   temporary reject
            -   temporary accepting
        -   Applications of DFA/NFA 
            -   lexical analyser
            -   text editor
            -   spell checker
            -   seqquentiaal circuit design
            -   unix graph(pattern search)
        -   Regular Expression and Grammar
        -   Pumping Lemma 
        -   Myhill—Nerode Theorem 
        -   Transducer or Finite State Machine 
            -   Mealy
            -   Moore
        -   Conversion in Finite Automata 
            -   nfa to dfa
            -   dfa to minimum dfa
            -   mealy to moore
            -   moore to mealy
            -   nfa with E-moves to nfa without E-moves
        -   Properties of Regular Sets/Languages 
        -   Some Important DFA 
    -   Pushdown Automata 
        -   Model of PDA 
        -   Transition Function 
        -   Non-deterministic PDA 
        -   Deterministic PDA
        -   Parsing : top down and bottom up
    -   Context-Free Grammar and Languages
        -   Context-Free Grammar 
        -   Standard Context-Free Language 
        -   Derivation Tree or Parse Tree : lmd, rmd
        -   Ambiguous Grammar 
        -   Removal of Ambiguity : left recursion and left factoring
        -   Context-Free Grammar Simplification : unit, null, useless
        -   Chomsky Normal Form 
        -   Greibach Normal Form 
        -   Identification of Language 
    -   Turing Machine 
        -   Model of a Turing Machine
        -   Designing a Turing Machine
        -   Recursive and Recursive Enumerable Languages 
        -   Variation of Turing Machine 
    -   Closure and Decidability : table
    </details>


6.  <details><summary>Compiler Design </summary>

    -   Introduction
    -   Compilers and Interpreters 287
        -   Compiler 
        -   Interpreter 288
        -   Phases of a Compiler
            -   lexical analyzer
                -   symbol table
            -   syntax analyzer
            -   semantic analyzer
            -   intermediate code generator
            -   code optimization
            -   target code
        -   Grouping of Phases :frontend and backend
        -   compiler construction tools
            -   parser generators
            -   scannner generators
            -   syntax directed translation engines
            -   automatic code generators
            -   data flow engines
    -   Lexical Analyzer
        -   Functions of a Lexical Analyzer
        -   Implementation of a Lexical Analyzer : RE and FA to recognize tokens
    -   Parser 291
        -   Context-Free Grammar 292
        -   Derivation Tree or Parse Tree 292
        -   Ambiguous Grammar 293
        -   Top-Down Parser
            -   with backtracking (recursive descent parsing) and its problems
            -   without backtracking (predictor parser)
                -   LL(1) parsing table construction
                    -   FOLLOW and FIRST
                    -   algo to construct a parse table
                    -   check if a given grammar is LL(1) or not
        -   Bottom-Up Parser
            -   LR parser
            -   LR parsing algo
            -   stack ops
            -   LR(0) parser and table construction
            -   SLR(1) parser
            -   canonical LR parser
            -   operator precedence parser
            -   important relations
    -   Syntax-Directed Translation 
        -   Attributes of Syntax-Directed Translation : synthesized and inherited
        -   Types of Syntax-Directed Translation 
        -   Applications of SDT 
    -   Runtime Environment
        -   Storage Organization 
        -   Activation Record and Activation Trees
        -   Procedure Call Return Model 
        -   Lexical Versus Dynamic Scoping 
        -   Symbol Table
    -   Intermediate Code Generation 
        -   Intermediate Representations
            -   syntax tree
            -   postfix notation
            -   3 address code: quadruples, triples, indirect triples 
    -   Code Optimization 
        -   Types and Levels of Optimization 
        -   Primary Source of Optimization
            -   dead code elimination
            -   constant propagation
            -   constant folding
            -   elimination of common sub expression
            -   copy propagation 
    </details>




7 Operating System 327
7.1 Introduction 327
7.2 Types of Operating System 328
7.2.1 Batch Operating System 328
7.2.2 Multiprogramming Operating System 328
7.2.3 Multitasking Operating System 328
7.2.4 Multiprocessor Operating System 328
7.2.5 Real-Time Operating System 329
7.3 Process Management 329
7.3.1 Process 329
7.3.2 Schedulers 330
7.4 CPU Scheduling 331
7.4.1 Scheduling Algorithms 331
CONTENTS xix
7.5 Process Synchronization 335
7.5.1 Types of Processes 335
7.5.2 Interprocess Communication 336
7.5.3 Classical Synchronization Problems 336
7.5.4 Race Condition 336
7.5.5 Critical Section 337
7.5.6 Peterson’s Algorithm for Two Processes 337
7.5.7 Semaphores 338
7.5.8 Deadlock and Starvation 339
7.6 Deadlocks 339
7.6.1 Resource Types 340
7.6.2 Characteristics of a Deadlock 340
7.6.3 Resource Allocation Graph 340
7.6.4 Deadlock Prevention 341
7.6.5 Deadlock Avoidance 342
7.6.6 Deadlock Detection and Recovery 346
7.7 Threads 347
7.7.1 Benefits of Threads 347
7.7.2 Types of Threads 347
7.8 Memory Management 348
7.8.1 Partitioning 348
7.8.2 Partition Allocation Policies 348
7.8.3 Loading and Linking 349
7.8.4 Paging 350
7.8.5 Multi-Level Paging 352
7.8.6 Segmentation 354
7.8.7 Virtual Memory 355
7.8.8 Page Replacement Algorithms 355
7.9 File System 359
7.9.1 Directory Structures 359
7.9.2 Allocation Methods 359
7.10 I/O Systems 363
7.10.1 Disk Structure 363
7.10.2 Disk Scheduling Algorithms 366
7.11 Protection and Security 368
7.11.1 Security 368
7.11.2 Security Environment 369
7.11.3 Cryptography 369
7.11.4 Attacks from within the System 370
7.11.5 Attacks from Outside the System 370
7.11.6 Anti Virus Approaches 371




8 Databases 403
8.1 Introduction 403
8.1.1 Traditional File Processing Approach 403
8.1.2 Database Management System 404
8.2 Components of Database Systems 404
8.3 DBMS Architecture 405
8.3.1 3-Tier Architecture 405
8.3.2 Data Independence 405
8.4 Data Models 405
8.4.1 Relational Model 406
8.4.2 ER Model 407
8.5 Database Design 410
8.5.1 Integrity Constraints 410
8.5.2 Normal Forms 411
8.5.3 Attribute Closure 411
8.5.4 Key 411
8.5.5 Decomposition 412
8.6 Query Languages (SQL) 414
8.6.1 SQL Commands 414
8.7 File Structures 416
8.7.1 Sequential Files 416
8.7.2 Indexing 416
8.7.3 B Tree 416
8.7.4 B+ Trees 416
8.8 Transactions and Concurrency Control 417
8.8.1 Transactions 417
8.8.2 Schedule 417
8.8.3 Classification of Schedule Based on Recoverability 419
8.8.4 Classification of Schedule Based on Serializability 420
8.8.5 Concurrency Control Protocol 423







9 Information Systems and Software Engineering 453
9.1 Introduction 453
9.2 Information Systems 453
9.2.1 Components of Information Systems 454
9.2.2 Types of Information Systems 454
9.3 Software 456
9.3.1 Characteristics of Software 456
9.3.2 Software Engineering 457
9.4 Process Models 458
9.4.1 Conventional Process Model 458
9.4.2 Evolutionary Process Model 459
CONTENTS xxi
9.5 Measurement of Metrics 461
9.5.1 Metrics 461
9.5.2 Size-Oriented Metrics 462
9.5.3 Effort and Schedule (Duration) Estimation 463
9.6 Risk Analysis 466
9.6.1 Risk Identification 466
9.6.2 Risk Projection or Risk Estimation 466
9.7 Software Development Life Cycle 467
9.7.1 Requirement 467
9.7.2 Design 470
9.7.3 Coding 472
9.7.4 Testing 472







10 Computer Networks 491
10.1 Introduction 491
10.2 Network 491
10.2.1 Network Topology 492
10.3 LAN Technologies 492
10.3.1 Ethernet 492
10.3.2 Token Bus 493
10.3.3 Token Ring 493
10.4 ISO/OSI Stack 494
10.4.1 ISO/OSI Model 494
10.5 Routing Algorithms 498
10.6 Network Layer Protocols 501
10.6.1 Internet Protocol (IPv4) 501
10.6.2 ICMP 505
10.7 Layer 4: Transport Layer 505
10.8 Congestion 505
10.8.1 Congestion Versus Flow Control 506
10.9 User Datagram Protocol and Transmission Control Protocol 506
10.9.1 User Datagram Protocol 506
10.9.2 Transmission Control Protocol 506
10.10 Sockets 507
10.11 Layer 5: Session Layer 507
10.12 Layer 6: Presentation Layer 508
10.13 Layer 7: Application Layer 508
10.14 Devices 509
10.15 Network Security 510
10.15.1 Basic Concepts in Cryptography 510
10.15.2 Digital Signature 511
10.15.3 Firewall 511






11 Web Technologies 537
11.1 Introduction 537
11.2 HTML 538
11.2.1 HTML Tags 538
11.2.2 HTML Attributes 538
11.2.3 HTML Elements 539
11.2.4 HTML Character Entities 539
11.2.5 HTML Formatting 539
11.2.6 HTML Phrase Tags 540
11.2.7 HTML Background 540
11.2.8 HTML Lists 540
11.2.9 HTML Links 540
11.2.10 HTML Images 540
11.2.11 HTML Tables 540
11.2.12 HTML Frames 541
11.2.13 HTML Forms 541
11.2.14 HTML Marquees 541
11.3 Cascading Style Sheets 541
11.4 XML 541
11.4.1 Advantages of XML 542
11.4.2 Document-Type Definition 542
11.4.3 Tag Rules for XML Documents 542
11.4.4 Types of XML Documents 543
11.4.5 XHTML 543
11.4.6 Document Object Model (DOM) 543
11.4.7 XUL 543
11.4.8 Flash and Silverlight 543
11.4.9 User-Interface Language 543
11.5 Basic Concepts of Client— Server Computing 544
11.5.1 Server Types 544
11.5.2 Stateless and Stateful Servers 544
11.5.3 Thin Client and Fat Servers 544
11.5.4 Functions of a Client 544
11.5.5 Functions of a Server 544
11.5.6 Topologies for Client-Server 545
11.5.7 Types of Client-Server Model 545
11.5.8 Merits and Demerits of Client-Server 546
11.6 J2EE platform 546
11.6.1 J2EE Services 546
11.6.2 J2EE Architecture 547
11.6.3 EJB Container 547
11.6.4 J2EE Application Server 547