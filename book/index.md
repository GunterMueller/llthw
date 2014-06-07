<ol class="breadcrumb">
  <li><a href="/">Home</a></li>
  <li class="active">Book</li>
</ol>

```Common Lisp
;; Welcome to LLTHW!
(let* ((a (list 'a 'b 'c 'd)))
  (format t "~{~A~}" a))
```

# Contents at a Glance

<dl class="dl-horizontal">
  <dt>Preface</dt>
  <dd>
    <ul>
      <li><a href="preface/">TANSTAAFL</a></li>
      <li><a href="introduction/">Lisp: A Future History</a></li>
      <li><a href="bootcamp/">Common Lisp Bootcamp</a></li>
      <li><a href="style-guide/">Common Lisp Style Guide</a></li>
      <li><a href="configuration/">Configuring Your Development Environment</a></li>
    </ul>
  </dd>
  <dt>PART ONE</dt>
  <dd>
    <a href="1-0-0-overview/">Grokking Lisp</a>
    <ul>
      <li><a href="1-01-0-syntax-overview/">Lisp in 5 minutes</a></li>
      <li><a href="1-02-0-input-output/">Printing, Strings and Streams</a></li>
      <li><a href="1-03-0-getting-input-from-users">Extra Credit: Getting Input from Users</a></li>
      <li><a href="1-04-0-lists/">Lists and List-Operations</a></li>
      <li><a href="1-05-0-/">Extra Credit: Look-up Lists and Trees</a></li>
      <li><a href="1-06-0-math/">Numbers and Math</a></li>
      <li><a href="1-07-0-arrays/">Extra Credit: Arrays and Vectors</a></li>
      <li><a href="1-08-0-variables/">Variables, Parameters, and Constants</a></li>
      <li><a href="1-09-0-/">Extra Credit: Closures</a></li>
      <li><a href="1-10-0-functions/">Functions and Macros</a></li>
      <li><a href="1-11-0-text-adventure/">Extra Credit: A Simple Text Adventure</a></li>
      <li><a href="1-12-0-namespaces/">Namespaces, Symbols, Packages, and Systems</a></li>
      <li><a href="1-13-0-simple-web-app/">Extra Credit: A Simple Web Application</a></li>
      <li><a href="1-14-0-conditionals/">Conditionals</a></li>
      <li><a href="1-15-0-command-line-utility/">Extra Credit: A Command-Line Utility</a></li>
      <li><a href="1-16-0-map-loop/">Mapping and Looping</a></li>
      <li><a href="1-17-0-iterate/">Extra Credit: Revisiting Loops with Iterate</a></li>
      <li><a href="1-18-0-format/">Format Strings</a></li>
      <li><a href="1-19-0-dsl/">Extra Credit: Domain Specific Languages</a></li>
      <li><a href="1-20-0-review/">Part One in Review</a></li>
    </ul>
  </dd>
  <dt>PART TWO</dt>
  <dd>
    <a href="2-0-0-overview/">The Suffusion of Blue</a>
    <ul>
      <li><a href="2-01-0-/">Programming Paradigms</a></li>
      <li><a href="2-02-0-/">Extra Credit: Regular Expressions</a></li>
      <li><a href="2-03-0-/">Objects and Control Structures</a></li>
      <li><a href="2-04-0-/">Extra Credit: The Meta-Object Protocol</a></li>
      <li><a href="2-05-0-/">Extended Types</a></li>
      <li><a href="2-06-0-/">Extra Credit: Threading, Memoization, and Parallel Processing</a></li>
      <li><a href="2-07-0-/">Logic and Advanced Math</a></li>
      <li><a href="2-08-0-/">Extra Credit: Number Theory</a></li>
      <li><a href="2-09-0-/">Binary Streams, Octet-Vectors, and Bit-Vectors</a></li>
      <li><a href="2-10-0-/">Extra Credit: An Improved Text Adventure Engine</a></li>
      <li><a href="2-11-0-/">Conditions and Error Handling</a></li>
      <li><a href="2-12-0-/">Extra Credit: Write a 2D Game</a></li>
      <li><a href="2-13-0-/">The Compiler</a></li>
      <li><a href="2-14-0-/">Extra Credit: Write a Tree-Shaker</a></li>
      <li><a href="2-15-0-/">Documentation and Inspection</a></li>
      <li><a href="2-16-0-/">Extra Credit: Foreign Libraries in Lisp</a></li>
      <li><a href="2-17-0-/">Debugging and Unit Testing</a></li>
      <li><a href="2-18-0-/">Extra Credit: Write a Foreign Function Interface</a></li>
      <li><a href="2-19-0-/">Essential Lisp Libraries</a></li>
      <li><a href="2-20-0-/">Extra Credit: Packaging Lisp Libraries</a></li>
      <li><a href="2-21-0-/">Detailed Syntax Review</a></li>
    </ul>
  </dd>
  <dt>PART THREE</dt>
  <dd>
    <a href="3-0-0-overview/">Lisp So(u)rcery</a>
    <ul>
      <li><a href="3-01-0-web-apps/">Real-world Web Apps</a></li>
      <li><a href="3-02-0-mobile/">Native Mobile Applications</a></li>
      <li><a href="3-03-0-gui/">Cross-platform Desktop Applications</a></li>
      <li><a href="3-04-0-system-utils/">Drivers, Daemons, and System-Utilities</a></li>
      <li><a href="3-05-0-reverse-engineering/">Reverse Engineering</a></li>
      <li><a href="3-06-0-graphics/">Graphics Rendering</a></li>
      <li><a href="3-07-0-gaming/">OpenGL, SDL, and 3D Game Development</a></li>
      <li><a href="3-08-0-audio/">Audio Generation and Manipulation</a></li>
      <li><a href="3-09-0-data/">Data Aggregation and Analysis</a></li>
      <li><a href="3-10-0-cryptosec/">Cryptography and Security</a></li>
      <li><a href="3-11-0-fintech/">Financial Software and Crypto-Currencies</a></li>
      <li><a href="3-12-0-scientific-computing/">Scientific Computing</a></li>
      <li><a href="3-13-0-computational-physics/">Computational Physics</a></li>
      <li><a href="3-14-0-quantum-computing/">Quantum Computing</a></li>
      <li><a href="3-15-0-nlp/">Natural Language Processing</a></li>
      <li><a href="3-16-0-ai/">Artificial Intelligence</a></li>
      <li><a href="3-17-0-robotics/">Robotics</a></li>
      <li><a href="3-18-0-space-tech/">Space Tech</a></li>
      <li><a href="3-19-0-neurotech/">Neuroscience and Thought-Controlled Computing</a></li>
      <li><a href="3-20-0-lispos/">A Simple LispOS</a></li>
      <li><a href="3-21-0-lisp-machine/">Build Your Own Lisp Machine</a></li>
      <li><a href="3-22-0-gov-mil/">Government and Military Grade Systems</a></li>
    </ul>
  </dd>
</dl>

* PART ONE: Grokking Lisp
    * [Syntax Overview in 5 minutes](1-1-0-syntax-overview/)
    * [I/O](1-2-0-input-output/)
        * [Strings](1-2-01-strings/)
        * [Characters](1-2-02-chars/)
        * [Writing](1-2-03-writing/)
        * [Printing](1-2-04-printing/)
        * [Pretty-Printing](1-2-05-pprint/)
        * [Reading](1-2-06-read/)
        * [EVAL](1-2-07-eval/)
        * [Working with Streams](1-2-08-streams/)
        * [Paths and Files](1-2-09-paths-files/)
        * [Prompting Users](1-2-10-prompts/)
    * [Lists and List-Operations](1-3-0-lists/)
        * Consing and Cons-Cells
        * Quoting Lists
        * Association Lists
        * Property Lists
        * Trees
    * [Numbers & Math]()
        * Numeric Types
        * Built-in Mathematical Functions
        * Arrays
        * Vectors
    * [Variables, Parameters, and Constants]()
        * Global Variables
        * Local Variables
    * [Functions and Macros]()
        * LAMBDA: Anonymous Functions
        * Global Functions
        * Local Functions
        * Recursive Functions
        * Defining Macros
    * [Extra Credit: A Simple Text Adventure]()
    * [Namespaces, Symbols, Packages, and Systems]()
        * Function and Variable Namespaces
        * Symbol Names
        * Defining Packages
        * ASDF and Systems
        * The Quicklisp Package Manager
    * [Extra Credit: Write a Simple Web Application]()
        * Sockets
        * Introducing Hunchentoot
        * Serving Static Files
        * Coding HTML5, CSS3, and JavaScript in Lisp
    * [Conditionals]()
        * IF, WHEN, UNLESS
        * COND
        * Predicates
    * [Extra Credit: Write a Command-Line Utility]()
        * Introducing CLON: The Command-Line Options Nuker
        * Loading Quicklisp in Lisp Scripts
        * Defining Your Application's Synopsis
        * Defining Your Application's Event Loop
        * Dumping Binaries
    * [Mapping and Looping]()
        * `DO` and `DO*`
        * `DOTIMES`
        * `DOLIST`
        * `MAP`
        * `MAPC` and `MAPL`
        * Other Mapping Functions
        * The `LOOP` Macro
    * [Extra Credit: Revisiting LOOPS with ITERATE]()
    * [Formatted Strings]()
        * The FORMAT Macro
        * Conditionals
        * Iteration
        * Numbers
        * Unprintable Objects
    * [Extra Credit: Write a Domain-Specific Language]()
    * [Part One in Review]()
* PART TWO: The Suffusion of Blue
    * [Programming Paradigms]()
        * The Multi-Paradigm Approach
        * Procedural Programming
        * Imperative Programming
        * Object-Oriented Programming
        * Functional Programming
        * Novel Paradigms
    * [Extra Credit: Threading, Memoization, and Parallel Processing]()
    * [Logic and Advanced Math]()
        * Logic Functions
        * Arrays
        * Vectors
        * Integer Functions
        * Floats
    * [Extra Credit: Using Regular Expressions in Lisp]()
    * [Objects and Control Structures]()
        * Blocks
        * Tagbodys
        * GO
        * PROG, PROGN
        * Structs
        * CLOS
    * [Extended Data-Types]()
        * Hash-Tables
        * Sequences
        * Sets
        * Type Definition
        * CLOS for Type Definition
    * [Extra Credit: An Improved Text Adventure Engine]()
    * [Conditions and Error Handling]()
    * [Extra Credit: Write a 2D Game]()
    * [The Compiler]()
        * Declaring Types
        * Controlling Compile-Time
        * Compiler Optimizations
    * [Documentation and Object Inspection]()
    * [Extra Credit: Using Foreign Libraries in Lisp]()
    * [Debugging Your Code]()
    * [Extra Credit: Write a Foreign Function Interface]()
    * [Essential Lisp Libraries]()
    * [Detailed Syntax Review]()
        * S-Expressions
        * Atoms
        * Lists
        * Quotes
        * Backtick Syntax
        * CLOS and the Meta-Object Protocol
* PART THREE: Lisp So(u)rcery
    * [Real-world Web Apps]()
    * [Native Mobile Applications]()
    * [Cross-platform Desktop Applications]()
    * [Drivers, Daemons, and System-Utilities]()
    * [Reverse Engineering]()
    * [Graphics Rendering]()
    * [OpenGL, SDL, and 3D Gaming]()
    * [Audio Generation/Manipulation]()
    * [Data Aggregation and Analysis]()
    * [Cryptography/Security]()
    * [Financial Software and Crypto-Currencies]()
    * [Scientific Computing]()
    * [Computational Physics]()
    * [Quantum Computing]()
    * [Natural Language Processing]()
    * [Artificial Intelligence]()
    * [Robotics]()
    * [Space Tech]()
    * [Neuroscience and Thought-Controlled Computing]()
    * [A Simple LispOS]()
    * [Build Your Own Lisp Machine]()

# FAQ

How long does this book take to complete?

: You should take as long as you need with each module to fully grasp the material.  It's not a race, and the only deadlines are the ones you set for yourself.

: Assuming you already have some programming experience and can do at least one module a day, you should expect to spend at least three months.

What kind of computer do I need?

: Common Lisp is available for nearly every platform. Your personal computer, whether it be a Mac, Windows, or Linux platform, will be fine.  For all the features of this website, however, you may need to update your browser to the latest version of Chrome, Firefox, or Safari.
