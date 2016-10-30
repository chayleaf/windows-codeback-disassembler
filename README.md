**Current version: 1.05**

What is WCB ?

Windows CodeBack (WCB) is a disassembler designed exclusively for Microsoft
Windows applications. It can disassemble New Executable format files (such as
.EXEs, .DLLs, .DRVs, etc.), Linear Executables (.386s and .VXDs) and can
extract LE files bounded into W3 files (such as WIN386.EXE). The current
version does not include support for conventional DOS .EXE files, OS/2 2.x LX,
and Win32 PE files, but you can disassemble OS/2 NE files too.

After you start it, WCB gathers and shows information about the program's
entry point, main procedure, device descriptor block. Shows by name all Windows
API functions that an application calls and all the virtual device driver calls
that a VxD makes. Labels the exported functions in a program and the control
procedures and services in a VxD. Identifies by name and labels the WinMain and
LibMain functions. Uses CodeView symbols, such as those shipped with the
debugging version of Windows.

Hardware and Software Requirements

In order to run WCB you will need at least a 386 based machine with DOS 3.0 or
above installed on the system, an XMS memory manager such as HIMEM.SYS (the XMS
version it provides must be 2.0 or higher.) And it is not bad if you have a
plenty of free hard disk space (from giant applications such as WinWord WCB may
create a 20-30 MB list file!).
