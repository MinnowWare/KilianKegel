#### keywords
"ANSI C for UEFI", "ISO C for UEFI", "Standard C for UEFI", "UEFI LIBC", "EFI LIBC", "UEFI application", "UEFI driver"

![Visitor](https://visitor-badge.laobi.icu/badge?page_id=KilianKegel.kiliankegel)

# UEFI C Library

The content on this page is all about the development of <img src="https://github.com/KilianKegel/pictures/blob/master/uefi-logo.png"  width="20" height="20"> UEFI  applications
and drivers using Microsoft <img src="https://github.com/KilianKegel/pictures/blob/master/vs-icon.svg"  width="20" height="20"> Visual Studio 2022 for x86 platforms.

The [**♉toro C Library**](https://github.com/KilianKegel/toro-C-Library) introduced here is written without any dependancy of other source code.<br>
It is a new, indepenant implementation of the [**ANSI C89 / ISO C90+C95 Standard C Library**](https://nvlpubs.nist.gov/nistpubs/Legacy/FIPS/fipspub160.pdf).<br>
([Only floating point print/scan-support is currently missing](https://github.com/KilianKegel/toro-C-Library?tab=readme-ov-file#known-bugs) — Instead [**MATH.H**](https://github.com/KilianKegel/Visual-TORO-C-LIBRARY-for-UEFI?tab=readme-ov-file#20250309-v090-build-243) functions are available !!!)


<img src="https://github.com/KilianKegel/pictures/blob/master/torouefishell.png"  width="256" height="144"><br>


## Flagship Projects
| Flagship Project | Content|
|--------------|--------------------|
|[**ANSI C for UEFI Shell**](https://github.com/KilianKegel/Visual-ANSI-C-for-UEFI-Shell)| getting started with simple programs <img src="https://github.com/KilianKegel/pictures/blob/master/New-icon.png"  width="18" height="18"> LLVM/CLANG support<br><img src="https://github.com/KilianKegel/Visual-ANSI-C-for-UEFI-Shell/blob/master/CfgMgr.png"  width="256" height="144"><br>
|
|[**ACPICA**](https://github.com/KilianKegel/Visual-ACPICA-for-UEFI-ShellPORTABLE?tab=readme-ov-file#visual-acpica-for-uefi-shell)| [**Intel ACPI COMPONENT ARCHITECTURE**](https://www.intel.com/content/www/us/en/developer/topic-technology/open/acpica/overview.html)<br><img src="https://github.com/KilianKegel/Visual-ACPICA-for-UEFI-ShellPORTABLE/blob/main/LOGO.PNG"  width="291" height="45"><br>Original Intel reference implementation running in UEFI Shell:<br>- AslCompiler.EFI<BR>- AcpiBin.EFI<BR>- AcpiDump.EFI<BR>|
|[**UEFI-SHELL**](https://github.com/KilianKegel/UEFI-SHELL)| Build original UEFI SHELL from latest available [**EDK2 drop**](https://github.com/tianocore/edk2/tags)<br><img src="https://github.com/KilianKegel/pictures/blob/master/torouefishell.png"  width="256" height="144"><br>1. integrate Tianocore EDK2 build tools into project (*portable build*)<br>2. introduce ♉toro-UEFI-SHELL with *plugins* and other improvements build with VS2022.   |
|[**TSCSync**](https://github.com/KilianKegel/Visual-TSCSync-for-UEFI-Shell)| TimeStampCounter-Synchronizer<br><img src="https://github.com/KilianKegel/Visual-TSCSync-for-UEFI-Shell/blob/main/TSCSyncDemo.gif"  width="256" height="144"><br>1. Introduce **TUI** TextUserInterface, a menu driven UEFI application — that looks not so bad...<br>2. Introduction of multi chart <img src="https://github.com/KilianKegel/pictures/blob/master/Microsoft_Office_Excel_(2019%E2%80%93present).svg.png"  width="20" height="20"> Excel .XLSX file generation using open source [**libxlsxwriter**](https://github.com/jmcnamara/libxlsxwriter)<br>3. Introduce reliable speed measurement to enable TSC for timer and wallclock usage [**AcpiClkWait()**](https://github.com/KilianKegel/Visual-TSCSync-for-UEFI-Shell/blob/main/TSCSync/AcpiClkWait.c#L51) vs. [**InternalAcpiDelay()**](https://github.com/tianocore/edk2/blob/master/PcAtChipsetPkg/Library/AcpiTimerLib/AcpiTimerLib.c#L150)|
|[**toro C Library**<br>source code](https://github.com/KilianKegel/Visual-TORO-C-LIBRARY-for-UEFI)| The Stuff That Dreams Are Made Of |

### <!--<img src="https://github.com/KilianKegel/pictures/blob/master/refresh-icon.png"  width="48" height="48">-->HOWTO

[![Repo name](https://github-readme-stats.vercel.app/api/pin/?username=KilianKegel&repo=Howto-setup-a-UEFI-Development-PC)](https://github.com/KilianKegel/Howto-setup-an-UEFI-Development-PC#howto-setup-a-uefi-development-pc)
[![Repo name](https://github-readme-stats.vercel.app/api/pin/?username=KilianKegel&repo=Howto-create-a-UEFI-Shell-Boot-Drive)](https://github.com/MinnowWare/Howto-create-a-UEFI-Shell-Boot-Drive#howto-create-a-uefi-shell-boot-device)

[![Repo name](https://github-readme-stats.vercel.app/api/pin/?username=KilianKegel&repo=Howto-configure-VS2022-to-build-.EFI-executables#howto-configure-vs2022-to-build-efi-executables)](https://github.com/KilianKegel/Howto-configure-VS2022-to-build-.EFI-executables#howto-configure-vs2022-to-build-efi-executables) [![Repo name](https://github-readme-stats.vercel.app/api/pin/?username=KilianKegel&repo=git-for-gits)](https://github.com/KilianKegel/git-for-gits)

[![Repo name](https://github-readme-stats.vercel.app/api/pin/?username=KilianKegel&repo=Howto-configure-DDK-and-WDK-for-Standard-C-usage)](https://github.com/KilianKegel/Howto-configure-DDK-and-WDK-for-Standard-C-usage) 
[![Repo name](https://github-readme-stats.vercel.app/api/pin/?username=KilianKegel&repo=Howto-setup-a-YOCTO-Development-PC)](https://github.com/KilianKegel/Howto-setup-a-YOCTO-Development-PC)


## License clarification
### License [**toro C Library** *binary*](https://github.com/KilianKegel/toro-C-Library)
[**toro C Library** binary](https://github.com/KilianKegel/toro-C-Library) is free to use like the [**GLIBC runtime library**](https://www.gnu.org/licenses/gcc-exception-3.1-faq.html)

**I decided to allow developers to use [**toro C Library** binary](https://github.com/KilianKegel/toro-C-Library) to compile any program, regardless of its [license](https://github.com/KilianKegel/toro-C-Library/blob/master/LICENSE.md)**.

### License [**toro C Library** *source code*](https://github.com/KilianKegel/toro-C-Library)
```
    Copyright (c) 2017-2025, Kilian Kegel. All rights reserved.
    SPDX-License-Identifier: GNU General Public License v3.0
```

[![Repo name](https://github-readme-stats.vercel.app/api/pin/?username=KilianKegel&repo=toro-C-Library#toro-c-library-formerly-known-as-torito-c-library)](https://github.com/KilianKegel/toro-C-Library#toro-c-library-formerly-known-as-torito-c-library)
[![Repo name](https://github-readme-stats.vercel.app/api/pin/?username=KilianKegel&repo=Visual-TORO-C-LIBRARY-for-UEFI)](https://github.com/KilianKegel/Visual-TORO-C-LIBRARY-for-UEFI)
[![Repo name](https://github-readme-stats.vercel.app/api/pin/?username=KilianKegel&repo=Visual-TSCSync-for-UEFI-Shell#visual-tscsync-for-uefi-shell)](https://github.com/KilianKegel/Visual-TSCSync-for-UEFI-Shell#visual-tscsync-for-uefi-shell)
[![Repo name](https://github-readme-stats.vercel.app/api/pin/?username=KilianKegel&repo=UEFI-SHELL-binary-source-and-build-environment#edk2-uefi-shell--visual-uefi-shell)](https://github.com/KilianKegel/UEFI-SHELL-binary-source-and-build-environment#edk2-uefi-shell--visual-uefi-shell)
[![Repo name](https://github-readme-stats.vercel.app/api/pin/?username=KilianKegel&repo=Visual-ANSI-C-for-UEFI-Shell#visual-ansi-c-for-uefi-shell)](https://github.com/KilianKegel/Visual-ANSI-C-for-UEFI-Shell#visual-ansi-c-for-uefi-shell)
[![Repo name](https://github-readme-stats.vercel.app/api/pin/?username=KilianKegel&repo=Visual-DOS-Tools-for-UEFI-Shell)](https://github.com/KilianKegel/Visual-DOS-Tools-for-UEFI-Shell)
[![Repo name](https://github-readme-stats.vercel.app/api/pin/?username=KilianKegel&repo=Visual-ACPICA-for-UEFI-Shell)](https://github.com/KilianKegel/Visual-ACPICA-for-UEFI-Shell)
[![Repo name](https://github-readme-stats.vercel.app/api/pin/?username=KilianKegel&repo=Visual-LIBWIN32-for-UEFI)](https://github.com/KilianKegel/Visual-LIBWIN32-for-UEFI)
[![Repo name](https://github-readme-stats.vercel.app/api/pin/?username=KilianKegel&repo=Visual-HWTools-for-UEFI-Shell)](https://github.com/KilianKegel/Visual-HWTools-for-UEFI-Shell)
[![Repo name](https://github-readme-stats.vercel.app/api/pin/?username=KilianKegel&repo=Visual-LIBXLSXWRITER-for-UEFI-Shell)](https://github.com/KilianKegel/Visual-LIBXLSXWRITER-for-UEFI-Shell)
[![Repo name](https://github-readme-stats.vercel.app/api/pin/?username=KilianKegel&repo=CdePkg#CdePkg)](https://github.com/KilianKegel/CdePkg#CdePkg)
[![Repo name](https://github-readme-stats.vercel.app/api/pin/?username=KilianKegel&repo=CdePkgValidation#cdepkgvalidation)](https://github.com/KilianKegel/CdePkgValidation#cdepkgvalidation)
[![Repo name](https://github-readme-stats.vercel.app/api/pin/?username=KilianKegel&repo=-obsolete-EDK2020-MinnowBoard#edk2020-minnowboard-featuring-cdepkg-c-development-environment-package)](https://github.com/KilianKegel/-obsolete-EDK2020-MinnowBoard#edk2020-minnowboard-featuring-cdepkg-c-development-environment-package)
[![Repo name](https://github-readme-stats.vercel.app/api/pin/?username=KilianKegel&repo=Howto-setup-a-UEFI-Development-PC)](https://github.com/KilianKegel/Howto-setup-an-UEFI-Development-PC#howto-setup-a-uefi-development-pc)
[![Repo name](https://github-readme-stats.vercel.app/api/pin/?username=KilianKegel&repo=Howto-create-a-UEFI-Shell-Boot-Drive)](https://github.com/MinnowWare/Howto-create-a-UEFI-Shell-Boot-Drive#howto-create-a-uefi-shell-boot-device)
[![Repo name](https://github-readme-stats.vercel.app/api/pin/?username=KilianKegel&repo=Howto-configure-VS2022-to-build-.EFI-executables#howto-configure-vs2022-to-build-efi-executables)](https://github.com/KilianKegel/Howto-configure-VS2022-to-build-.EFI-executables#howto-configure-vs2022-to-build-efi-executables) [![Repo name](https://github-readme-stats.vercel.app/api/pin/?username=KilianKegel&repo=git-for-gits)](https://github.com/KilianKegel/git-for-gits)
[![Repo name](https://github-readme-stats.vercel.app/api/pin/?username=KilianKegel&repo=Howto-configure-DDK-and-WDK-for-Standard-C-usage)](https://github.com/KilianKegel/Howto-configure-DDK-and-WDK-for-Standard-C-usage) 
[![Repo name](https://github-readme-stats.vercel.app/api/pin/?username=KilianKegel&repo=-obsolete-Howto-setup-a-YOCTO-Development-PC)](https://github.com/KilianKegel/-obsolete-Howto-setup-a-YOCTO-Development-PC)
[![Repo name](https://github-readme-stats.vercel.app/api/pin/?username=KilianKegel&repo=papers-bugs-miscellaneous-...-#cdepkg-blog-at--uefi--tianocore)](https://github.com/KilianKegel/papers-bugs-miscellaneous-...-#cdepkg-blog-at--uefi--tianocore)
