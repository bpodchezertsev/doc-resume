# CV: Boris Podchezertsev

LinkedIn profile: https://www.linkedin.com/in/boris-podchezertsev/

# Main goals
- As a Team Leader: Improve the team's performance today and in the future.
- As a Business Analyst: Design features as combinations of reusable, long-term parts.
- As a System Architect: Design the most safe, reusable, and efficient long-term solutions.
- As a Software Developer: Implement safe, reusable, and efficient long-term solutions with the smallest possible code and useful features per code size.

# How I work
- Deeply analyze the code/problem to find ways to fix not only current issues but also future improvements, and create recommendations for that.
- Make it harder to create future bugs by organizing the code in predictive ways.
- Don't stop at exploring common areas, but try to develop something with unique features.

# Explanation of the main goals
In many of my works, I focus on the productivity of our teams.
- For our development teams, I have created reusable helpers, libraries, and frameworks to avoid routine operations and isolate complex decisions.
- For the development and testing teams, I create APIs and tools for debugging, data collection and output, analysis, and monitoring.
- For the support teams, I create useful APIs and tools.

# Explanation of how I work
- I analyze huge amounts of code to find possible solutions and improvements from simple bugs to major design flaws.
- In my job, I actively take further direction from our and other teams and try to test and implement solutions to address these directions,
  avoiding bureaucracy to help teams work without headaches.
- In all my jobs, I get the most difficult tasks, creating many tasks for bugs and design flaws that I find.

When planning tasks, I prefer to introduce long-term features into projects.
For example, when I fix a bug, of course I look for the same bug in the whole system and fix it or create subtasks,
but for fixing the main bug, I fix the bug to avoid similar problems in the future,
this includes isolating the code in helper classes to avoid future copy and paste (I prefer DDD style),
and documenting well with cross-references to the same aspects.

# Development style
- Declarative design, DDD, functional design
- Create many helper functions and small independent libraries to avoid routine operations
- Generalized algorithms as much as possible
- Extensive use of metadata, collecting metadata from various sources, code generation
- Document code well, tools, create guides, use diagrams for better visualization
- Create APIs and tools for debugging, data collection and derivations, analysis and monitoring

# Types of projects
- frameworks
- libraries
- rich UI
- backend
- web-client
- CLI
- script engines
- embedded
- hardware (e.g., testbeds, CNC)

# Largest projects with all my own design and implementation that I've done by type:
- Largest project I made: Universal report generator: ~1M lines Java, Delphi, VBA. (Also my largest multilanguage scripting engines and metadata-based operations.)
- Largest refactoring (+migrations +extensions) I made: Licence plate recognition systems: ~500K lines of FPC/Lazarus/Delphi, Java, C++.
- Largest metadata collectors & code generators I made: Iiko/Syrve restaurant software: ~100K lines of Java
- Largest embedded I made: Telephony hardware: ~10K lines of C++

# My latest pet-projects in progress
- An umbrella software project for all my experimental performance, compatibility, reusability, flexibility libraries, utilities and snippets. Goal is multi-language interoperability (currently Java and Rust, outdated parts in C++, Python), performance, DDD and code generation.
- A hardware project of development principal new multipurpose omnidirectional drone family (I use CADs and Python for 3D-modelling and principal modelling).
- Literature project of hard sci-fi novell in the nearest future.

# Also

## Hardware
- Improvements, fixes, overview of various hardware testbeds, hardware drivers and other hardware interfaces.
- Installation and maintenance of hardware.

## DIY
- Milling machines, OpenSCAD modeling.
- Design, modeling, calculations and creation of drones.
- Modeling, creation/construction, installation of furniture, kitchens, built-in furniture.
- Repair: replacement of electrical wiring, ventilation; dismantling, leveling, pouring, sealing of floors, etc.

## Driving
Category B. Since 2005, no accidents due to my fault. 10 years of driving experience in a minivan with a manual transmission.


# History

## 2024 Dukascopy

**About**: Dukascopy is a Swiss banking and trading company.

**Position**: Senior Java Developer, Systems Analyst. Contract work.

**Comment**: My first job at a trader. My second job at a bank.

**Work on**: Java Swing UI, libraries, algorithms, optimizations, refactoring, parsing, CI/CD.

**Done entirely by me**:
- Stable DDD typesafe APIs.
- Libraries that cover all existing cases, fixing bugs, which will help remove or compact a large legacy codebase.
- Improving debugging productivity by implementing various error detection methods, object tracing, external debugging APIs.
- Synchronizing the codebase between modules.
- Functional style in algorithm handling and UI handling.
- Common stable APIs for various internal data structures to allow the use of generic algorithms.
- Well-documented code, including not only text but also diagrams and not only comments but also guidelines.


## 2021 - 2023 Iiko/Syrve

**About**: Iiko is one of the leading restaurant software platforms in Russia and the most complex.
Syrve is a brand used outside of Russia.

**Position**: Senior Software Developer, Systems Analyst, Subsystem Architect, Subsystems Owner. (Java, C#, JSP, Javascript, PHP)

**Outdoor activity with colleagues**: Travelling by car in Armenia.

**Work on**: Backend, GUI, JSP, Tomcat, Spring, Hibernate, MSSQL/Postgres, MQ, CLI, data models, code generation, metrics, CI/CD.

**Done entirely by me**:
- Data model builder from source code, code generators with generation gap.
- General helper functions for support engineers working with both hot and cold databases.
- Performance related decorators for time- or memory-critical code.
- Memory optimization, destructive data transformations, local metadata fixes.
- Metrics collection, debugging helpers creation.


## 2020 iFellow

**About**: IFellow is an outstaffing company in Russia.

**Position**: Senior Software Developer, Systems Analyst. (Java, Jelly, JSP, Javascript)

**Comment**: My first job in an outstaffing company.

**Work on**: Backend, JSP, Tomcat, Spring, MSSQL, MQ, ERwin, reporting tools.

**Done entirely by me**: New report generator to replace imperative reports generated by Jelly scripts with simple functional substitutions.


## 2020 1C

**About**: 1C is the most popular (and most hated) accounting platform in Russia.

**Position**: Senior Software Developer, Systems Analyst. (Java, Javascript)

**Work on**: Maven plugin, Eclipse EMF (XCore, ECore), code generation, refactoring

**Done entirely by me**: I fixed the code generation system to be more predictable and configurable, replacing the spaghetti code with imperative computations with configurable DAG-based computations.
I also added traceable configurations, made it easier to point to file subsystems, etc.


## 2019 Faberlic

**About**: Faberlic is one of the leading direct marketing companies in Russia.
In these years, Faberlic has been working on migrating from its own software to other platforms.

**Position**: Senior Software Developer

**Work on**: Microservices, Docker, Spring, Oracle/Postgres, tools, CI/CD. (Java, Javascript, PHP)

**Done entirely by me**:
- Library with a single configuration point to easily wrap many Oracle PLSQL stored procedures into microservices to avoid manual creation of microservices.
- Universal unit tests to check the completeness of the implementation of some functions for unknown data objects based on the collected metadata.
- Debugging tools, synchronization tools, convert code between languages, etc.


## 2015-2017 Servionica

**About**: Servionica is a part of the ITECO group of companies, one of the leading system integrators in Russia.

**Position**: Senior Software Developer, Team Leader, Systems Analyst, business trips. Contract work. (Java, Delphi/Lazarus, Python)

**Work on**: Backend, GUI, Swing UI, Postgres, telephony, MQ, utilities.

**Done entirely by me**: UI based on metadata.


## 2012 - 2015 RusTeleSys

**About**: At that time, RusTeleSys had the most powerful license plate recognition system in Russia.

**Position**: Lead Architect, Senior Software Developer, Project owner. (Delphi/Lazarus/FPC, C++, Java, scripts)

**Comment**: I like working with such a degree of freedom, I like working practically with hardware.
I like sharing my experience with the team. I like teaching colleagues to do something new.

**Work on**: Backend, GUI, Swing UI, OpenCV, Postgres, sandboxing, interprocess communication, network communication, porting, migrations.

**Done entirely by me**:
- I completely redesigned and cleaned all systems, implemented sandboxing and increased the uptime of our software to 99.9%.
- Make the system run on different OS and CPU in different programming languages with different API variations.
- Create tools/libraries/apps for debugging, logging, performance monitoring, integration, etc.


## 2005 - 2011 TopS BI

**About**: TopS BI was one of the largest independent software integrators in Russia at that time.

**Position**: Lead Developer, Team Leader, System Architect, System Analyst, Subsystem Owner (Java, JSP, Javascript)

**Work on**: Backend, Swing UI, modules for various application servers, JSP, Java Web Start, Oracle/Oracle Lite/Sybase/MSSQL, database administration tools, CI/CD.

**Done entirely by me**:
- Fixing all multithreading or system issues in all projects.
- Design and implementation of new GUI subsystems using my functional-reactive library.
- Updating the insurance reserve calculation subsystem.
- Migration of client software from Oracle to Sybase.
- Design and implementation of dynamic object overlay for the map rendering system.
- Design and implementation of custom type-safe ORM APIs.
- Database administration tools.


## 2003 - 2005 BSS/BFT

**About**: This years BFT is one of the leading integrators of budget financial processes in Russia, presenting its own systems and automated workflows.

**Position**: Lead Software Developer, Team Leader, System Architect, System Analyst, Project Owner. (Java, Delphi, VBA)

**Comment**: I was invited to develop a new report generator to replace the old one. I am designing and implementing my largest in-house project here: ~1 million lines of java, delphi, VBA. (Also my largest multilingual functional script engines)

**Work on**: Backend, GUI, Excel VBA, Oracle/MSSQL/Firebird, parsing, functional script engines, workflow.

**Done entirely by me**: Universal report generator:
- Logical representation of data structure based on existing or new data sources, data source merging, data operations: application server (Java) + GUI client (Delphi)
- Microscript language for data operations on the server (data source operations) and client (data source operations and functional-reactive forms)
- Markup language for Excel templates.
- Tables/trees/matrices with grouping, variable ranges.
- Custom extensions via Excel VBA.


## 1999 - 2003 Quorum

**About**: Quorum was one of the leading providers of banking software in Russia at that time. And one of the outsourcing companies.
In those years, the company is trying to move to modern technologies by creating various experimental banking platforms, workflows and tools.

**Position**: Software Developer, Team Leader, Systems Analyst, Systems Architect, Hardware Interface Integrator, Subsystems Owner. (Object Pascal/Delphi, Assembler, Java)

**Comment**: My first encounter with Java.

**Work on**: Backend, GUI, WinAPI(16/32), DOS, DLL, COM, Btrieve/Pervasive/Oracle, multithreading, communication, CLI, parsers, scripting engines, IDEs, hardware interfaces, database administration tools.

**Done entirely by me**:
- Tools: incremental build and deployment, project management, code generators, hardware interfaces and management consoles.
- Complete ABS Quorum code cleanup
- Complete repair of two buggy ABS Quorum interface variants (remote terminal and GUI)


## 1999 Altey Laboratories

**About**: Altey Laboratories was one of the leading independent Russian integrators of software systems for medical laboratories in those years.

**Position**: Software Developer, Local Project Coordinator, Hardware Installer and Support Engineer, Subsystems Owner. (Delphi)

**Work on**: Backend, COM, DCOM, WinAPI, SQL, Interbase/Firebird, communications, multithreading.

**Mostly done by me**:
- Development of software exchange modules for the laboratory of Polyclinic No. 129 in Moscow. Hardware setup. User support.
- Hardware and software support and setup, hardware interfaces and management tools, user support.


## 1998 - 1999 Commercial bank «FINROS» Financial Initiative

**About**: At that time, FINROS was the largest owner of exchange offices in Moscow.

**Position**: Software developer, Business analyst, Project owner. (Delphi/Object Pascal, Clipper)

**Comment**: My first job at a bank.

**Work on**: Support of our own banking software.

**Done entirely by me**:
- Various text processing tools, etc.
- Internal warehouse support and reporting system.
- New OOP UI for Clipper + applications.


## 1996 - 1998 Prais Telecom

**About**: Prais Telecom is one of the independent manufacturers of telecommunications equipment, developed entirely in Russia in those years.

**Position**: Software developer, Embedded Software Developer, Business Analyst, Systems analyst, System Architect, Project owner, Support Engineer. (Delphi/Object Pascal, C++, Optima, embedded systems, assembler)

**Work on**: GUI, hardware interfaces, embedded, communications, multithreading, WinAPI (16/32).

**Done entirely by me**:
- Client-server billing system.
- New systems of service and technical support based on metadata with centralized routing and scripting.


## 1995 Avrora-Region

**About**: Avrora-Region was an advertising company in Moscow.

**Position**: Software Developer. Business Analyst. Project Owner. Contract work. (Delphi)

**Done entirely by me**: Applications and reports.


## 1995 Corvus

**About**: Corvus was a small banking software developer in Moscow working for banks in Kazakhstan.

**Position**: Software Developer, Support Engineer. (Clipper, Pascal)

**Work on**: Text processing, reporting tools.

**Done entirely by me**: Parsers, database utilities.


## 1992 - 1995 Moscow State Mining University (MSMU), Department of Surveying and Geology

**Position**: Lead Software Developer, System Architect, Business Analyst, Hardware Specialist, Student, Mine Surveyor, Business trips to mines. (Object Pascal, Assembler, Clipper).

**Outdoor activity with colleagues**: Surveying underground quarries with a mapping group.

**Work on**: Surveying management software, hardware interfaces.

**Done entirely by me**:
- The fastest (at that time) UI framework with native support for EGA/VGA, plotters, printers, keyboards + surveying applications.
- Vector UI framework with native support for plotter output + surveying applications.


## 1987 - 1991 Moscow Instrument-building Technical College, Department of Computer Science

**About**: Moscow Instrument-building Technical College was a small, but the most computerized per student higher education facility in Russia in that years.

**Profession**: Computer science, applied mathematics, analog devices, hardware interfaces.

**Programming languages**: Pascal, Assembler, Clipper, C++, scripts, BASIC.

**Work on**: OOP, interrupt handling, multitasking, hardware access, drivers, graphics, parsing, symbolic mathematics, closures, scripts, UI, CLI, TSR, electronics, analog devices.

