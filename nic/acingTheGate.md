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

    -   Introduction 
    -   Basic Terminology 
        -   Programming Languages and generations(5)
        -   Classification of High-Level Languages: procedural, non procedural, problem oriented
        -   Procedural, Object-Oriented(basic concepts too), Structured : programming 
        -   Data Types : basic ,defined, user defined and conversion direction
        -   Control Flow Statements : conditional,unconditional, loops
        -   Array : declaration, intialisation, address calulation
        -   Function: parts(5), types(2), advantages
        -   Recursion
        -   Pointers(read properly)
            -   initialise, arithmetic, dangling etc.
        -   Parameter Passing: value, reference 
        -   Structures and Unions 
        -   Enumerated Data Types 
        -   Scoping : local, global, storage classes(4)
        -   Binding and merits, demerits: early, late
        -   Abstract Data Types 
    -   Stack 
        -   PUSH Operation on Stack 
        -   POP Operation on Stack 
        -   Application of Stack
            -   special: expression conversion 
    -   Queue 
        -   Basic Operations on Queue 
        -   Types of Queue 
        -   Applications of Queues 
    -   Linked List 
        -   Basic Operations 
        -   Linked List Implementation 
    -   Trees 
        -   Binary Tree 
        -   Types of Binary Trees 
        -   Array Representation of Binary Trees
        -   Tree Applications 
        -   Binary Search Tree and traversals
        -   Graphs 
            -   terms
            -   traversal
            -   shortest path
            -   spanning tree and mst
        -   avl tree
        -   binary heaps    
    </details>

4.  <details><summary>Algorithms(focus on equations , numbers and maths of topics)</summary>

    -   Introduction
    -   Algorithm
        -   Properties of Algorithm 
        -   Steps to Solve a Problem 
        -   Algorithm Analysis (r=time and space) : a posteriori and a priori
        -   Asymptotic Notation: theta, big-O, omega, small-O, small-omega
            -   properties: transitivity, reflexivity, symmetric, transpose symmetry
            -   types and order of complexities
        -   Recurrence Relations : iteration, recursion tree, master theorem
    -   Hashing  
        -   Hash Table 
        -   Hashing Functions
        -   Collisions 
            -   separate chaining
            -   open addressing
                -   probing methods and advantages , disadvantages
                    -   linear probing
                    -   quad probing  
                    -   double hashing
                -   removing items under open addressing 
    -   Binary Heap : min and max
        -   Insertion in Min-Heap Tree 
        -   Deletion in Min-Heap Tree 
        -   Time Complexity 
    -   Searching and Sorting : recurrence relations, complexities, aoplications
        -   Linear Search 
        -   Binary Search
        -   Bubble Sort 
        -   Selection Sort 
        -   Insertion Sort 
        -   Heap Sort 
        -   Merge Sort 
        -   Quick Sort
        -   Randomized Quick Sort 
        -   Counting Sort 
        -   Comparison of Sorting Techniques 
    -   Graph 
        -   Types of Graph : simple , multi
        -   Types of Simple Graph : null, regular, complete
        -   Graph Representation : matrix , list
    -   Greedy Approach and Applications
        -   job sequence with deadline
        -   Fractional Knapsack 
        -   Huffman Coding 
        -   Minimum Spanning Tree 
            -   kruskal
            -   prim
        -   Single-Source Shortest Path
            -   dijkstra
            -   bellman ford 
    -   Graph Traversal 
        -   Breadth-First Traversal and applications 
        -   Depth-First Traversal and applications
    -   Dynamic Programming and applications 
        -   Fibonacci Series 
        -   0/1 Knapsack 
        -   Longest Common Subsequence 
        -   All-Pair Shortest Path 
            -   Floyd’s Algorithm 
    -   Concepts of Complexity Classes 
        -   P-Complexity Class 
        -   NP Complexity Class 
        -   NP-Complete 
        -   NP-Hard 
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




7.  <details><summary>Operating System</summary>

    -   Introduction
        -   THE
        -   management: process, memory, file, device
    -   Types of Operating System 
        -   Batch Operating System 
        -   Multiprogramming Operating System 
        -   Multitasking Operating System 
        -   Multiprocessor Operating System 
        -   Real-Time Operating System 
    -   Process Management 
        -   Process
            -   attributes 
            -   process states
        -   Schedulers 
            -   types
            -   dispatcher
            -   degree of multiprogramming
            -   time periods
    -   CPU Scheduling 
        -   Scheduling Algorithms 
            -   fcfs
            -   sjf
            -   srtf
            -   round robin
            -   priority based
            -   hrrn
            -   multilevel queue
            -   multilevel feedback queue
        -   other approaches
            -   guaranteed scheduling
            -   lottery scheduling
        -   dynamic scheduling algo
            -   rate monotonic
            -   earliest deadline first
            -   least laxity 
    -   Process Synchronization 
        -   Types of Processes : independent, cooperating, concurrent
        -   Interprocess Communication and techniques
        -   Classical Synchronization Problems 
            -   producer consumer
            -   reader writer
            -   dining philosopher
        -   Race Condition 
        -   Critical Section 
            -   problem
            -   busy waiting
            -   solutions
                -   mutual exclusion
                -   progress
                -   bounded waiting
        -   Peterson’s Algorithm for Two Processes 
        -   Semaphores 
            -   integer
            -   binary
            -   counting
            -   common concurrency mechanisms
        -   Deadlock and Starvation 
    -   Deadlocks 
        -   Resource Types 
        -   Characteristics of a Deadlock 
            -   mutual exclusion
            -   hold and wait
            -   non preemptive
            -   circular wait
        -   Resource Allocation Graph 
        -   Deadlock Prevention 
            -   based on 4 charactersitics of deadlock
        -   Deadlock Avoidance 
            -   safe state
            -   RAG
            -   Banker
                -   data structures
                -   safety algo
                -   resource request algo
                -   time complexity
                -   limitations
        -   Deadlock Detection and Recovery 
            -   detection
                -   single instancve
                -   multiple instance
            -   recovery
                -   process termination
                -   checkpointing and rollback    
    -   Threads 
        -   Benefits of Threads 
        -   Types of Threads : ult , klt
        -   fork()
    -   Memory Management 
        -   techniques compared
        -   Partitioning : fixed and variable
        -   Partition Allocation Policies: first, next, best, worst
        -   Loading and Linking 
            -   loading:    static , dynamic
            -   linking(address binding):compiler , load time, runtime(dynamic)    
        -   Paging 
            -   terms
            -   paging performance with TLB
        -   Multi-Level Paging
            -   problems
            -   inverted paging
        -   Segmentation 
        -   Virtual Memory 
            -   demand paging
            -   effective memory access time
        -   Page Replacement Algorithms 
            -   FIFO
                -   problems and belady
            -   optimal RA
            -   LRU
            -   frame allocation
                -   fixed allocation
                    -   equal and proportional
                    -   priority
            -   global vs local replacement
            -   thrashing and working set model               
    -   File System 
        -   Directory Structures
            -   single level
            -   2 level
            -   tree structured
                -   absolute path name
                -   relative path name
            -   acyclic graph directories     
        -   Allocation Methods 
            -   contiguous
            -   linked
            -   indexed
                -   index block
                    -   linked scheme
                    -   multilevel index
                    -   combined scheme
    -   I/O Systems 
        -   classification:
            -   machine readable
            -   human readable
            -   communication
        -   Disk Structure 
            -   structure
            -   time relate to disk: seek, rotational latency, transfer time, tranfer rate
            -   disk interleaving: single, double
        -   Disk Scheduling Algorithms
            -   fcfs
            -   SSTF
            -   SCAN
            -   C-SCAN
            -   LOOK and C-LOOK
            -   Selection of algo
    -   Protection and Security 
        -   Security : C,I,A
        -   Security Environment
            -   threats, intruders, accidental data loss 
        -   Cryptography : symmetric, asymmetric
        -   Attacks from within the System
            -   trojan horses
            -   login spoofing
            -   logic bombs
            -   trap doors
            -   buffer overflow
        -   Attacks from Outside the System 
            -   virus damage scenarios
            -   virus classification    
                -   environment
                -   operation mode
                -   destructive capabilities
        -   Anti Virus Approaches 
            -   signature scanning
            -   heuristic scanning
            -   generic decryption
            -   behaviour blocking
            -   detect, identify, remove
    </details>



8.  <details><summary>Databases</summary>

    -   Introduction 
        -   Traditional File Processing Approach 
        -   Database Management System 
            -   functions
    -   Components of Database Systems 
        -   software
        -   h/w
        -   data
        -   procedures
        -   data access language
        -   people
            -   sys admin
            -   db admin
            -   db designer
            -   application programmer
            -   end user
    -   DBMS Architecture 
        -   3-Tier Architecture
            -   internal schema/ physical
            -   conceptual schema/ logical
            -   external schema/ view 
        -   Data Independence: logical and physical 
    -   Data Models 
        -   types
        -   Relational Model 
            -   terms
            -   constraints
            -   relational algebra
            -   tuple calculus
        -   ER Model: 
            -   entity
            -   attributes
            -   relationships 
    -   Database Design 
        -   steps
        -   Integrity Constraints
            -   domain integrity
            -   entity integrity
            -   referential integrity
            -   foreign key integrity
                -   cascade update
                -   cascade delete 
        -   Normal Forms : 1,2,3, BCNF, 4(MDNF), 5(PJNF)
        -   Attribute Closure
        -   Key 
            -   superkey
            -   candidate key
            -   primary key
            -   alternate
            -   composite
            -   foreign
        -   Decomposition
            -   lossless join and algo to determine it
            -   dependency preserving and algo to determine it
            -   relation b/w two FD sets
    -   Query Languages (SQL) 
        -   SQL Commands and usages 
            -   DDL
            -   DML
            -   DCL
    -   File Structures 
        -   Sequential Files 
        -   Indexing
            -   primary, secondary, clustering index
            -   dense , sparse index
        -   B Tree 
        -   B+ Trees
    -   Transactions and Concurrency Control 
        -   Transactions : ACID
        -   Schedule 
            -   serial and concurrent
            -   comparison
            -   problems of concurrent: WR,RW, WW
        -   Classification of Schedule Based on Recoverability
            -   irrecoverable
            -   recoverable
            -   cascading rollback recoverable
            -   strict recoverable
        -   Classification of Schedule Based on Serializability
            -   conflict
                -   conflict equivalent
                -   conflict and non-conflict pairs
                -   testing method
            -   view
        -   Concurrency Control Protocol
            -   lock based
                -   lock mechanisms : shared and exclusive
                -   2PL
                -   2PL with lock upgradation
                -   strict 2PL
                -   rigorous 2PL
            -   time stamp ordering based
                -   stamps: read and write
                -   basic time ordering protocol
                -   strict time ordering protocol
                -   deadlock prevention
                -   wait die protocol
                -   wound wait protocol
    </details>





9.  <details><summary>Information Systems and Software Engineering</summary>

    -   Introduction 
    -   Information Systems 
        -   diagram
        -   Components of Information Systems 
        -   Types of Information Systems 
            -   level wise: tps, kws, oas, dss, mis, ess
            -   office IS
            -   transaction processing
            -   Management IS
            -   DSS
            -   Expert systems
            -   integrated information systems
    -   Software 
        -   Characteristics of Software 
        -   Software Engineering 
            -   layered: quality, kpa, methods, tools
            -   generic: definition,validation, development
            -   support: corrective, adaptive, perfective, preventive
            -   software process: cmmi
                -   0 (initial)
                -   1 (repeatable)
                -   2 (defined)
                -   3 (managed)
                -   4 (optimized)
    -   Process Models 
        -   Conventional Process Model 
            -   waterfall
            -   prototype
            -   rapid
        -   Evolutionary Process Model 
            -   incremental, spiral, component based development
    -   Measurement of Metrics 
        -   Metrics : 4P
            -   direct and indirect
        -   Size-Oriented Metrics :loc and fpa
        -   Effort and Schedule (Duration) Estimation
            -   SEL and WF
            -   COCOMO
            -   defect rate
            -   defect removal efficiency
            -   halstead size oriented metric 
    -   Risk Analysis 
        -   uncertainty and loss
        -   Risk Identification 
        -   risk strategy
        -   risk types
        -   risk components
        -   Risk Projection or Risk Estimation 
    -   Software Development Life Cycle
        -   diagram 
        -   Requirement
            -   types of requirements
            -   external interfaces
            -   requirement engineering: management and development
            -   management: change control, version control, req tracing
            -   development: diagram
                -   elicitation 
                -   analysis
                -   specification
                -   validation
        -   Design : 
            -   levels: data, architecture, interface , component
            -   concepts
                -   abstraction
                -   refinement
                -   modularity
                    -   cohesion and coupling
            -   software architecture
            -   control architecture
            -   data structure
            -   software procedure        
        -   Coding
        -   Testing 
            -   structural and functional
            -   structural
                -   white box, glass box
                -   basis path: cyclomatic complexity, graph matrices
                -   control structure
            -   functional, behavioural : black box, grey box
                -   equivalence partition
                -   boundary value analysis
                -   graph based
                -   comparison
            -   sdlc stage wise testing
                -   req: validation, black box
                -   design: integration
                    -   top down
                    -   bottom up
                    -   regression
                    -   smoke
                -   code: =unit test
                -   test: alpha,  beta
                -   maintenance: system 
                    -   recovery, security, stress, performance          
        -   maintenance : corrective, adaptive, perfective, preventive
    </details>






10. <details><summary>Computer Networks</summary>

    -   Introduction 
    -   Network 
        -   Network Topology : bus, mesh, ring, star, tree
    -   LAN Technologies and their comparison
        -   Ethernet 
        -   Token Bus 
        -   Token Ring 
    -   ISO/OSI Stack 
        -   iso/osi vs tcp/ip
        -   ISO/OSI Model 
            -   1: physical: transmission & propagation time
            -   2: data link
                -   encoding
                -   framing
                -   flow control
                -   error control
                -   techniques of flow & error control
                    -   stop and wait automatic repeat
                    -   go back n automatic repeat
                    -   selective repeat automatic repeat
                -   parity bits
                -   polynomial codes
                -   CRC
                    -   procedure & decoding
                    -   choosing a  CRC polynomial
                -   sublayers:
                    -   MAC
                    -   LLC
                    -   multiple access protocols categorization
                    -   random access protocols
                        -   pure ALOHA
                        -   slotted ALOHA
                        -   CSMA
            -   3: network
                -   switching compared: circuit, message , packet
                -   Internet
                    -   datagram network
                    -   connectionless network
                    -   tcp vs udp                
    -   Routing Algorithms 
        -   adaptive and non-adaptive
        -   non adaptive properties
        -   static: shortest path routing and flooding
        -   flow based routing
        -   dynamic: distance vector and links state
        -   hierarchical
        -   routing for mobile hosts: ospf/is-is
        -   broadcast and multicast
    -   Network Layer Protocols 
        -   Internet Protocol (IPv4) 
            -   header
            -   ipv4 addresses
            -   classful  addressing and masks
            -   classless addressing, subnetting, supernetting
        -   ICMP 
    -   Layer 4: Transport Layer 
    -   Congestion 
        -   Congestion Versus Flow Control 
    -   User Datagram Protocol and Transmission Control Protocol
        -   User Datagram Protocol 
        -   Transmission Control Protocol
    -   Sockets 
    -   Layer 5: Session Layer 
    -   Layer 6: Presentation Layer 
    -   Layer 7: Application Layer 
        -   icmp
        -   dns
        -   smtp
        -   pop
        -   ftp
        -   http
    -   Devices : layer wise
        -   repeaters
        -   bridge
        -   hub
        -   switch
        -   router
        -   gateway
    -   Network Security :CIA 
        -   Basic Concepts in Cryptography
            -   symmetric
            -   asymmetric
                -   RSA 
        -   Digital Signature and DSA steps
            -   key generation
            -   signature
            -   verification
            -   correctness 
        -   Firewall : functions, types , limitations
    -   Basics of WiFi
        -   Some historical facts about mobile radiotelephony
        -   WLAN standards
        -   IEEE standards
            -   modulation methods
            -   standards
                -   802.11
                -   802.11a
                -   802.11b
                -   802.11g
                -   802.11n
                -   802.11z
            -   WLAN modes
                -   adhoc
                -   infrastructure: bss , ess
        -   IEEE  802 based wireless network technologies
            -   bluetooth 
                -   piconet, scatternet, wibree
                -   zigbee
                -   wimax
        -   comparison of wireless technologies
        -   advantages and disadvantages of wireless technologies
    </details>





11. <details><summary>Web Technologies</summary>

    -   Introduction 
    -   HTML 
        -   HTML Tags 
        -   HTML Attributes: core and generic
        -   HTML Elements 
        -   HTML Character Entities 
        -   HTML Formatting 
        -   HTML Phrase Tags 
        -   HTML Background : bgcolor, background
        -   HTML Lists : ul,ol,dl
        -   HTML Links 
        -   HTML Images 
        -   HTML Tables 
        -   HTML Frames 
        -   HTML Forms 
        -   HTML Marquees
    -   Cascading Style Sheets 
    -   XML 
        -   namespace and semnantics
        -   Advantages of XML 
        -   Document-Type Definition 
        -   Tag Rules for XML Documents 
        -   Types of XML Documents 
        -   XHTML 
        -   Document Object Model (DOM) 
        -   XUL 
        -   Flash and Silverlight 
        -   User-Interface Language 
    -   Basic Concepts of Client— Server Computing 
        -   Server Types 
            -   file,print,application,web
            -   mail,fax,db,transaction
        -   Stateless and Stateful Servers 
        -   Thin Client , fat client and Fat Servers 
        -   Functions of a Client 
        -   Functions of a Server 
        -   Topologies for Client-Server 
            -   1C-1S
            -   MC-1S
            -   MC-MS
        -   Types of Client-Server Model and merits, demerits of each :2,3,N
        -   Merits and Demerits of Client-Server 
    -   J2EE platform
        -   components 
        -   J2EE Services 
        -   J2EE Architecture 
        -   EJB Container 
        -   J2EE Application Server 
    </details>


12. <details><summary>Discrete mathematics</summary>

    -   intro
    -   propositional logic and first order logic
        -   proposition/statement
        -   logically equivalent
        -   contrapositive
        -   inverse
        -   precedence of connectors or logical operators
        -   tautology, contradiction, contingency
        -   logicaly equivalent identities
        -   argument validity
        -   conjunctive normal form
        -   disjunctive normal form
        -   some more connectives
        -   predicate logic
        -   quantifiers
        -   well formed formula
    -   set theory
        -   finite and infinite sets
        -   set identities
        -   addition/ inclusion-exclusion principle
        -   symmetric difference
    -   relations
        -   graph/ pictorial representation
        -   inverse relation
        -   properties of relations
        -   directed graphs of relations on sets
        -   hasse diagram
        -   composition of relations
        -   matrix representation
        -   partial ordered relation
        -   linearly ordered set
        -   lattice
        -   modular lattice
        -   functions
    -   group
        -   order
        -   subgroup
        -   cyclic group
    -   permutations
    -   combinatorics
        -   permutation
        -   permutation with repetition
        -   combination
        -   pigeonhole/ shoebox
        -   generalized pigeon hole
        -   recurrence relation
        -   generating function
    -   graph theory
        -   bipartite graph
        -   complete bipartite graph
        -   complement of a graph
        -   isomorphic graphs
        -   euler graphs
        -   hamiltonian graphs
        -   planar graphs
        -   graph coloring
        -   chromatic number
    </details>