<ol class="breadcrumb">
  <li><a href="/">Home</a></li>
  <li class="active">Book</li>
</ol>

```Common Lisp
;; Welcome to LLTHW!
(let* ((a (list 'a 'b 'c 'd)))
  (format t "~{~A~}" a))
```

# Table of Contents

<dl class="dl-horizontal">
  <dt>Preface</dt>
  <dd>
    <ul>
      <li><a href="preface/">TANSTAAFL</a></li>
      <li><a href="introduction/">Lisp: A Future History</a></li>
      <li><a href="bootcamp/">Common Lisp Bootcamp</a></li>
      <li><a href="style-guide/">Common Lisp Style Guide</a></li>
      <li><a href="configuration/">Configuring Your Development Environment</a>
        <ul>
          <li><a href="configuration/#installing">Installing SBCL</a></li>
          <li><a href="configuration/#editor">Choosing an Editor</a></li>
          <li><a href="configuration/#command-line">Working from the Command-Line</a></li>
          <li><a href="configuration/#repl">Tour of the REPL</a></li>
        </ul>
      </li>
    </ul>
  </dd>
  <dt>PART ONE</dt>
  <dd>
    <a href="1-0-0-overview/">Grokking Lisp</a>
    <ul>
      <li><a href="1-1-0-syntax-overview/">Lisp in 5 minutes</a></li>
      <li><a href="1-2-0-input-output/">I/O</a>
        <ul>
          <li>Strings</li>
          <li>Characters</li>
          <li>Writing</li>
          <li>Printing</li>
          <li>Pretty-Printing</li>
          <li>Reading</li>
          <li>EVAL</li>
          <li>Streams</li>
          <li>Paths and Files</li>
          <li>Prompting Users</li>
        </ul>
      </li>
      <li><a href="1-3-0-lists/">Lists and List-Operations</a></li>
      <li><a href="1-4-0-math/">Numbers and Math</a></li>
      <li><a href="1-5-0-variables/">Variables, Parameters, and Constants</a></li>
      <li><a href="1-6-0-functions/">Functions and Macros</a></li>
      <li><a href="1-7-0-text-adventure/">Extra Credit: A Simple Text Adventure</a></li>
      <li><a href="1-8-0-namespaces/">Namespaces, Symbols, Packages, and Systems</a></li>
      <li><a href="1-9-0-simple-web-app/">Extra Credit: A Simple Web Application</a></li>
      <li><a href="1-10-0-conditionals/">Conditionals</a></li>
      <li><a href="1-11-0-command-line-utility/">Extra Credit: A Command-Line Utility</a></li>
      <li><a href="1-12-0-map-loop/">Mapping and Looping</a></li>
      <li><a href="1-13-0-iterate/">Extra Credit: Revisiting Loops with Iterate</a></li>
      <li><a href="1-14-0-format/">Format Strings</a></li>
      <li><a href="1-15-0-dsl/">Extra Credit: Domain Specific Languages</a></li>
      <li><a href="1-16-0-review/">Part One in Review</a></li>
    </ul>
  </dd>
  <dt>PART TWO</dt>
  <dd>
    <a href="2-0-0-overview/">The Suffusion of Blue</a>
    <ul>
      <li></li>
    </ul>
  </dd>
  <dt>PART THREE</dt>
  <dd>
    <a href="3-0-0-overview/">Lisp So(u)rcery</a>
    <ul>
      <li>Real-world Web Apps</li>
      <li>Native Mobile Applications</li>
      <li>Cross-platform Desktop Applications</li>
      <li>Drivers, Daemons, and System-Utilities</li>
      <li>Reverse Engineering</li>
      <li>Graphics Rendering</li>
      <li>OpenGL, SDL, and 3D Gaming</li>
      <li>Audio Generation/Manipulation</li>
      <li>Data Aggregation and Analysis</li>
      <li>Cryptography/Security</li>
      <li>Financial Software and Crypto-Currencies</li>
      <li>Scientific Computing</li>
      <li>Computational Physics</li>
      <li>Quantum Computing</li>
      <li>Natural Language Processing</li>
      <li>Artificial Intelligence</li>
      <li>Robotics</li>
      <li>Space Tech</li>
      <li>Neuroscience and Thought-Controlled Computing</li>
      <li>A Simple LispOS</li>
      <li>Build Your Own Lisp Machine</li>
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

#### FAQ

How long does this book take to complete?

: You should take as long as you need with each module to fully grasp the material.  It's not a race, and the only deadlines are the ones you set for yourself.

: Assuming you already have some programming experience and can do at least one module a day, you should expect to spend at least three months.

What kind of computer do I need?

: Common Lisp is available for nearly every platform. Your personal computer, whether it be a Mac, Windows, or Linux platform, will be fine.  For all the features of this website, however, you may need to update your browser to the latest version of Chrome, Firefox, or Safari.
