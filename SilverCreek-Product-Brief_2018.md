### <span style="color:rgb(107,194,140)">Executive Overview</span>
Whether your job is to find SNMP compliance problems or to fix them, the SilverCreek SNMP test suite is your most valuable ally. SilverCreek is a
software product for design, quality assurance, and test engineers to find and fix bugs in their SNMP agent implementations. The SilverCreek SNMP
software is so easy to use that anyone who can navigate a graphical user interface can quickly run a battery of individual, comprehensive tests.

The tests are designed to detect and diagnose implementation errors in private and standard MIBs as well as SNMPv1, v2c, and v3 stacks and
implementations. Yet SilverCreek is so powerful, extensible, and flexible, power users can create the ideal solution for virtually any testing environment.

SilverCreek is the Authoritative SNMP Test Suite -- designed to test implementations of the Simple Network Management Protocol (SNMP agents)
and standard and private MIBs (Management Information Bases). SilverCreek incorporates thousands of small, single function tests written in the Tcl
scripting language to exercise one or a small number of parameters. The syntactic tests verify protocol compliance, error and exception handling,
and boundary condition behavior. The functionality tests (semantic tests) verify performance, trap/alert/event/notification handling, counter accuracy,
security, and many other implementation specific areas.

SilverCreek's SNMP engine is written in C++. The testing interface is written in the interpretive Tcl/Tk scripting language. Users may modify or extend
test scripts without programming. Using the SilverCreek management information base (MIB) browser is just as easy. Clicking on any leaf automatically
launches the SNMP Command Tool, which allows users to view the contents of the agent’s object identifier (OID) tree and issue GETs and SETs.
Because the MIB browser combines SNMP GET and NEXT requests on modified object identifiers, it discovers MIB branches in a manner that is
more efficient, more thorough, and more accurate than the average MIB walk. Combined with the MIB Lookup Tool and support for private MIBs, the SilverCreek MIB Browser boosts productivity to new levels.

The SilverCreek SNMP Test Suite was developed and refined by InterWorking Labs, Inc. with the help of the Advisory Board comprised of key SNMP
technology experts from the IETF. Attending the IETF meetings, commenting on drafts in progress, and evaluating interoperability issues with other
participants assures the best understanding of the standards documents which translates into meaningful tests. This results in the most accurate,
credible, and comprehensive test suites possible.
#### SilverCreek SNMP Tests
* Set up in less than five minutes - Windows or Linux
* Customize tests via Wizards, Script Generators, and more
* Automate operation with unambiguous test results
* Integrate with other test harnesses and test tools
* Cover conformance, compliance, vulnerability, robustness, stress, and performance testing
* Investigate failures and quickly resolve them with powerful diagnostic and analysis tools
### <span style="color:rgb(107,194,140)">Test Coverage:</span>
* Conformance/compliance tests for SNMPv1, v2c, v3, all private and standard MIBs
* Syntactic tests
* Semantic (functionality) tests
* Vulnerability (robustness) tests
* Functionality Tests:
    * RMON I and RMON II
    * SNMPv3 USM-MIB (RFC-3414)
    * SNMPv3 VACM-MIB (RFC-3415)
    * SNMPv3 Apps (RFC-3413)
    * SNMPv3 MPD-MIB (RFC-3412)
    * MIB-II Tests (RFC 1213/2011/2012/2013/2196)
    * IPv6 IP MIB Tests (RFC 4293)
    * IPv6 ipForward MIB Tests (RFC 4292)
    * IPv6 TCP-MIB Tests (RFC 4022)
    * IPv6 UDP-MIB Tests (RFC 4113)
    * DOCSIS Tests
    (Data Over Cable Service Interface Specification)
    (Includes Diffie-Helman SNMPv3 key ignition and keyChange
    * Inform Response Handling Tests
    * Coexistence SNMP-COMMUNITY-MIB (rfc3584) Tests
    * Host-RESROUCE-MIB (RFC2790) Tests
    * DIFFERV-MIB (RFC3289) Tests
    * IP-TUNNEL-MIB (RFC4087)Tests
    * MIBILE-IPV6-MIB (RFC4295) Tests
    * IPSec-SPD (RFC4807) Tests
    * SNMP Manager Tests
* Load tests (by simulating multiple managers)
* Performance measurement tests
* Tests reference source of authority in RFCs

### <span style="color:rgb(107,194,140)">A Rich Toolset</span>
For probing, sniffing, and inspecting individual objects, components or subsystems of your product's SNMP implementation, the toolset includes:
#### MIB Tools 
* A MIB browser that actively probes the agent for the true value of objects
* A MIB compiler that allows you to add, compile, and automatically test your private MIB, or any IETF MIB
    * Add and compile any MIB (private or standard)
    * Automatically compile and load multiple MIBs (all at once)
    * Add and compile an agent-capabilitiy MIB
    * Select one or more branches of MIBs for testing
* A MIB Lookup Tool for quick and convenient access to information about a MIB object. Provides basic
* information such as descriptor name, OID, syntax, access, status, and index.
* A MIB Scope Tool to isolate a portion of the agent's objects to focus testing on a specific set of
* objects
* MIB Compare Tool
* MIB Walker
* MIB Table Inspector
* MIB Dictionary
* Validate MIBs by 6 Severity Levels
#### Traps, Alerts, Informs
* A Trap Monitor to visually examine the contents of all traps
* A Trap Tester that works with the Trap Monitor to verify syntax, ordering, and correct indexing of the incoming event.
#### Utilities
* A Command Line Interface that allows command line SNMP requests outside of the
* SilverCreek application
* A Command Tool for issuing SNMP SET, GET, and GET-NEXT commands
* An ODBC (Open Data Base Connection) tool, a powerful way to process test results
* and generate reports.
* A Command Script Wizard to build complicated SNMP commands, generate and
* store requests as scripts and reload them.
* Polling Tool
* Memory Leak Tool
* Performance Measuring Tool
#### Diagnostic Tools
* A Packet Monitor that demonstrates the flow of traffic to an and from the agent under test in three output types: octet, pseudo-ASN.1, and/or
summary. This facilitates debugging as all the low level traffic may be examined and analyzed.
* The Diffie-Hellman (DH) key ignition and key change test module validates support for DH key agreement (as specified in the Data Over Cable
Service Interface Specification).
* SilverCreek Console
* Summary (summarized form of packets sent)
    * Watch (pseudo ASN.1)
    * Debug (octet dump)
* Packet Recorder and Decoder:
    * Capture packets
    * Decode any SNMP HEX data to human readable form
#### SilverCreek is available on:
* Windows (x86, x64)
* Fedora (Linux) (x86, x64)
### <span style="color:rgb(107,194,140)">Extend, Customize, Diagnose, Analyze</span>
* All tests written in the Tcl scripting language for extensibility and customization
* The test engine is written in fast and efficient, compiled C++
* Packet recorder and decoder for packet capture and analysis
* Add, compile and test multiple private or standard MIBs, automatically
* Save and reload configuration files
* Select data to include in output results and save in multiple formats
* SNMPv3 USM manager for managing USM and VACM table relations
* Comprehensive set of MIB tools and utilities for analysis and diagnostics
#### Testing Options/Customizations:
* Customize tests (for ultimate flexibility)
* Access source code, APIs, library definitions
* Customize your MIB definitions (e.g. Redefine the range of an integer)
* Check system reboot
* Ignore lexicographic errors
* Insert a delay between test packets sent (for slow agents)
* Test according to MIN-ACCESS
* Ignore writeable objects in SET tests (treat them as read-only)
* Repetitively execute selected tests
* Pause testing and resume later
* Disable 'SET' tests
* Disable 'GET-BULK' tests
#### Creating Your Own Tests
* For Creating Tests:
    * Classic SNMP requests API (optimized for testing)
    * Light weight SNMP requests API
    * Scotty/TNM API with support for IPv6 and SNMPv3
    * Synchronous and Asynchronous API
* Automation Wizard:
    * Build a script to drive the GUI to automatically run test suites
#### Integration:
* Full support of Tcl language
* Any Tcl extensions can be added to the SilverCreek environment
* SilverCreek libraries can be added to any standard Tcl environment
* SilverCreek may be integrated with other products (e.g. to control the Spirent packet generator)

***Image goes here***

### <span style="color:rgb(107,194,140)">Architecture</span>
* Consistent Architecture and Operation of Tools
* SNMP engine written in compiled C++ (for fast engine operation)
* Testing interface written in Tcl, an interpreter (for easy test customization)
* SilverCreek uses small, single function tests written in the Tcl scripting language to exercise one or a small number of parameters.
* Syntactic tests verify protocol compliance, error and exception handling, and boundary condition behavior.
* Functionality tests (semantic tests) verify performance, trap /alert /event /notification handling, counter accuracy, security, and many other
implementation specific areas

***Image goes here***

#### Support for Windows and Linux Agent Setup
* Save agent setup to file
* Share agent setup file with other users
* Agent capabilities
* Advanced Agent Setup - customize interactive parameters
#### Documentation
* Online Help (user manual)
* Task-based Training Videos
* CookBook of Tcl Scripts (for Controlling and Automating SilverCreek)
* SilverCreek Developer's Guide (for Creating Your Own Tests)
* SilverCreek Test Handbook (details of each test)
#### Test Output
* POSIX Standard Result Codes
* Text file (human readable and machine parsable via keywords)
* CSV delimited output can be imported into a spreadsheet (e.g. Excel)
* XML support (parsing by an XML parser)
* Web page (display results in a web browser)
* Journal
* Log of test session (machine parsable via 3 digit code)
* ODBC support (store results and SQL query your database)
* HTML
#### Authentication, Encryption and Key Exchange Algorithms
* Diffie Hellman
* DES
* AES 128, 192, 256
* Triple DES
* MD5 and SHA Authentication
* SHA224, SHA256, SHA384, and SHA512 Authentication
### <span style="color:rgb(107,194,140)">Summary</span>
The SilverCreek SNMP Test Suite is used by thousands of design, quality assurance, and test engineers o find and fix bugs in their SNMP agent
implementations. SilverCreek is the only authoritative SNMP tester backed up by an Advisory Board of SNMP experts who can arbitrate disputes, clarify
the intent of the RFCs, and provide you with the assurances you need for clear and unambiguous test results.