# CV: Boris Podchezertsev

## 2020 1C

**Links**: <https://1c.ru/eng/title.htm>

**Position**: Programmer.

**Programming languages**: Java.

**Specialization**: internal tools, refactoring.

**OS**: Windows.

## 2019 Faberlic

**Links**: <https://faberlic.com>

**Position**: Programmer.

**Programming languages**: Java.

**Specialization**: microservices, prototyping.

**OS**: Windows.

## 2017-2019

**Position**: Freelancer

## 2015-2017 Servionica

**Links**: <https://servionica.ru>

**Position**: Chief engineer-designer.

**Programming languages**: Java, Python, Object Pascal(Delphi, Lazarus).

**Specialization**: MQ, telephony, prototyping.

**OS**: Linux, Windows.

## 2012-2015 RusTeleSys

**Links**: <http://rustelesys.com> <http://rustelesys.ru>
 
**Specialization**: License plate recognition.

**Position**: Invited to this startup as chief architect and software developer.

**Programming languages**: Java, C++, Object Pascal(Delphi, Lazarus).

**OS**: Linux, Windows, Android

**CPU**: x86, ARM

**Key features**: multithreading, interprocess communications, networking, OpenCV, postgresql, sqlite.

**Migrations**:
- Delphi -> FPC/Lazarus, Java.
- Windows -> Linux, Android.
- dll -> separate processes.
- x86 -> ARM.

Total **refactoring** all systems from bottom to up for stability and upscale:
- Global code cleanup.
- Tight coupling -> modules, facade extraction.
- Threads -> managed workers and queues.
- Data protocols unification XML, binary (see <https://github.com/speaking-fish/doc-sf-ssp>).
- Create multiply software variants and external API's based on unified facades.
- Unite network nodes with rabbitmq.

**Large clients**:

* ASKT <http://ackt.ru>:

1. AFIMALL underground parking (2700 parking places) in "Moscow-city" (Moscow International Business Center) <http://afimall.ru/en/page/about>
2. Kievsky & Paveletsky railway terminal's parkings in Moscow
3. Kazan Ice Palace "Tatneft-Arena" parking (800 parking place) <http://tatneftarena.ru/arena/o-ledovom-dvortse.html>

* Russia state structures of some regions

## 2005-2011 Tops Business Integrator

**Links**: <http://www.topsbi.ru>

**Specialization**: Software development

**Position**: Chief software developer and architect.

**Programming languages**: Java, JavaScript.

**OS**: Windows, Linux.

**Large projects**:

### RosGosStrakh <http://www.rgs.ru>: RGS-AUTO: Car insurance system, desktop GUI

*Java, Oracle(+lite), Sybase, Swing, replication*

**Some tasks totally implemented by me**:
- Client software migration from Oracle-lite to Sybase.
- New GUI subsystems using functional-reactive programming.
- Renovation of insurance reserves calculation subsystem.

**Refactoring**:
- GUI hell -> MVC, functional-reactive.
- Fixes and speedup for multithreading jobs.
- Fixes all database transaction/locking.
- Total memory leaks fixes.
- Lazy calculations.
- Migration to generics.

### MosEnergo <http://www.mosenergo.ru>: WEB-GIS.

*Java, JavaScript, web, RIA, GIS, oracle, COM, using renderer (no tiled interface was supported in that time) from <http://www.resident.ru> (Yandex.Maps ex-provider).*

The project is mainly made by me.

### Alfa-Insurance <http://www.alfastrah.ru>: WEB-client for Unicus insurance system <http://www.systematic.ru/unicus.html>

Java, web, oracle

Fully made by me part: DB-layer (Jook-like).

## 2003-2005 BSS/BFT

**Links**: <http://www.bssys.com>, <http://www.bftcom.com>

**Specialization**: Budget and financial software.

**Position**: Chief software developer.

Invited to develop a new report generator to replace the old.

The project is fully implemented and introduced me:

Report generator for MS Excel: Java, Delphi 5-7, VBA, firebird.

- Logical data structure representation based on existing or new data sources, data source union, data operations: application server (Java) + GUI client (Delphi)
- Micro-sripting language for data operations on server (data sources operations) and client (data source operations and functional-reactive forms)
- Markup language for templates in Excel.
- Tables/trees/matrices with grouping.
- User extensions via Excel VBA.

Description sample <https://github.com/speaking-fish/archive/blob/master/reporter/reporter.ru.txt>

## 2000-2003 Quorum

**Specialization**: Banking software.

**Links**: <http://www.quorum.ru>

**Position**: Chief core developer.

**Programming languages**: Java, Delphi 1-5, borland Pascal 7, Assembler, C++.

**Key features**: heavy WinAPI, DLL, COM, 16/32bit, oracle, multithreading, communications, reverse engineering.

**Large projects**:

### Automated banking system "Quorum"

**Large refactoring (70% mine)**:

Renovation of unstable terminal version of ABS Quorum. (multithreading, locks, networking).

**Fully made by me**:

- Renovation of unstable DLL-links of ABS Quorum.
- Link with control cash machine & service tools.
- Total code cleanup for ABS Quorum. (mem cleanup, mem check, null pointers, access violations, multithreading, locks, total static initialization/finalization fixes, 16-bit issues fixes, compatibility fixes, code simplification, Assembler removal/fixes, etc.)
- Experimental GUI-Wrapper for ABS Quorum text mode interface.

### Experimental project "Stealth"

**Links**: <http://bankir.ru/dom/threads/31222-%D0%9A%D0%B2%D0%BE%D1%80%D1%83%D0%BC-Next-%28%D0%BE%D0%BD-%D0%B6%D0%B5-Stelth-%D0%BE%D0%BD-%D0%B6%D0%B5-%29?s=96b5c3058568130d00e68c576e431c81>, <http://bankir.ru/dom/threads/66278-Next>

Application server + GUI-client: Delphi GUI client (GUI without business logic) <-> non-GUI Java client (business logic) <-> Java server (business logic).

## 1999 Altey Laboratories

**Links**: <http://www.altey.ru>

**Specialization**: Clinical Laboratory Automation.

**Programming languages**: Delphi 3-5.

**Key features**: WinAPI, COM, DCOM, SQL, BDE, Interbase, Firebird, DBF, communications, multithreading.

**OS**: Windows 95-98, NT 3-4.

**Position**: software developer and system administrator.

Support and setup of harware and sofware.

Integrations with customer's hardware and software.

User support.

**Participation in projects**:

* Development of interchange software modules for Moscow polyclinic #129. Setup hardware. User support.

* Software and hardware works in some medical organizations: Moscow Medicina Clinic <http://en.medicina.ru>, Moscow polyclinic #220, etc.

## 1998-1999 Commercial bank «FINROS» Financial Initiative

**Links**: <http://www.banki.ru/banks/memory/bank/?id=174589>

**Specialization**: Commercial bank.

**Position**: Chief software developer.

**Programming languages**: Delphi 1-3, Clipper 6, shell.

**Key features**: RxLib, Quick Report, DBF, Paradox.

**OS**: Windows 95-98, DOS.

Support Clipper-based software.

**New projects**:
* Internal storage support system. Delphi.
* Utilities for financial document convertations, parsing, union, generation, printing etc.

## 1996-1998 Prais Telecom

**Links**: <http://web.archive.org/web/20011221163510/http://www.aha.ru/~kat> <http://www.aboutphone.info/lib/WireLesson2.html>

**Specialization**: Telecommunication systems development.

**Position**: Chief PC developer.
 
**Programming languages**: Delphi 1-2, Assembler, Watcom C/C++, Watcom Optima.

**Key features**: communications, multithreading, embedded, WinAPI, RxLib, Paradox.

**OS**: Windows 3-95, DOS, embedded

**Projects**:
* TSC-1. Tech service system for telephone exchange system "LOB". Further development.
* Tarification server and client for telephone exchange system "LOB". Development.
* TSC-1-32bit. Migration to Win32.
* TSC-2. Renovation of TSC-1-32bit for unify protocols, configurations, routing.
* Further development of embedded software for new experimental telephone exchange system (Watcom C).

## 1992-1995 MSMU (Moscow State Mining University), Department of Surveying and Geology

**Links**: <http://msmu.misis.ru/index.php/ru>

**Specialization**: Automation geological and surveying works.

**Position**: Chief developer.

**Programming languages**: Pascal (TP6, BP7), Assembler (TASM2), Clipper('87, 5).

**Key features**: frameworks, hardware programming (video adapters, printers, plotters), Turbo Vision, Fast Vision, Assembler, vector graphic, Clipper 5, DBF.

**Projects**:
* GeoDB-1. Clipper. Team development.

*Fully implemented by me:*
* GeoDB-1 – Modules for build and display/plot profiles and plans for mining. Pascal, Turbo Vision, plotters, printers.
* Framework: Vector GUI: Pascal.
* GeoDB-1.5 – Modules for build and display/plot plans for mining. Pascal, Turbo Vision, plotters, printers.
* Framework: Fast Vision - fastest graphic framework based on Turbo Vision. Pascal, Assembler.
* GeoDB-2 - Profiles and plans for mining. Pascal, Fast Vision.
* GeoDB-2 – Module subsidence monitoring of the Earth's surface. Pascal, Fast Vision.

## 1987-1991 Moscow Instrument-building Technical College, Department of Computer Science

**Links**: <http://mpt.ru>

**Profession**: technician-mathematician-programmer.

**Programming languages**: Pascal (Turbo Pascal 2-6, Borland Pascal 7), Assembler (Turbo Assembler 1-2), Clipper’87, DBF, C, GWBasic, DOS batch files.

**Key features**: OOP, interrupt handling, TSR, background tasks, low-level hardware access, drivers, graphics, expression parsing, symbolic math, shell scripts, Turbo Vision. 
 
**OS**: DOS 2-5, desqview.
