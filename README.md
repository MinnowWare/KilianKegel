![Visitor](https://visitor-badge.laobi.icu/badge?page_id=KilianKegel.kiliankegel)

## <img src="https://github.com/KilianKegel/pictures/blob/master/New-icon.png"  width="18" height="18"> LLVM/CLANG support for Visual Studio 2022
[**toro C Library v0.9.1 build 267**](https://github.com/KilianKegel/toro-C-Library?tab=readme-ov-file#20250322-v091-build-267) 
provides libraries for the VS2022 LLVM/CLANG tool chain.<br>
In [**Visual-ANSI-C-for-UEFI-Shell**](https://github.com/KilianKegel/Visual-ANSI-C-for-UEFI-Shell?tab=readme-ov-file#visual-ansi-c-for-uefi-shell)
all sample programs now also builds with **LLVM/CLANG**.

## License clarification
### Toro C Library binary
[**Toro C Library binary**](https://github.com/KilianKegel/toro-C-Library?tab=readme-ov-file#toro-c-library-formerly-known-as-torito-c-library) for IBM PC AT(tm) compatible x86-64 UEFI shell and Windows NT executables,<br>
C Development Environment for UEFI<br>
Copyright (c) 2017-2025, Kilian Kegel (kilian_kegel@hotmail.com), https://github.com/KilianKegel/toro-C-Library<br>
<br>
Permission to use **Toro C Library binary** for the sole purpose of creating
UEFI Shell, UEFI POST drivers and Windows NT console applications applications, which may be
distributed with or without fee, is hereby granted.

The library binary files:<br>
* [**toroC64.lib**](https://github.com/KilianKegel/toro-C-Library/blob/master/toroC64.lib), 64bit all-in-one library for UEFI Shell/DXE/SMM and Windows NT for Microsoft linker
* [**toroC64LLVMUefiShell.lib**](https://github.com/KilianKegel/toro-C-Library/blob/master/toroC64LLVMUefiShell.lib), 64bit UEFI Shell library for the LLVM linker
* [**toroC64LLVMWinNT.lib**](https://github.com/KilianKegel/toro-C-Library/blob/master/toroC64LLVMWinNT.lib), 64bit WinNT library for the LLVM linker
* [**toroC32.lib**](https://github.com/KilianKegel/toro-C-Library/blob/master/toroC32.lib), 32bit all-in-one library for UEFI Shell/DXE/PEI and Windows NT for Microsoft linker
* [**toroC32LLVMUefiShell.lib**](https://github.com/KilianKegel/toro-C-Library/blob/master/toroC32LLVMUefiShell.lib), 32bit UEFI Shell library for the LLVM linker
* [**toroC32LLVMWinNT.lib**](https://github.com/KilianKegel/toro-C-Library/blob/master/toroC32LLVMWinNT.lib), 32bit WinNT library for the LLVM linker

are **explicitely excluded from the GPL license**.<br>
This is called the **Toro C Library Runtime Exception**, similiar to the [GCC Runtime Library Exception](https://www.gnu.org/licenses/gcc-exception-3.1-faq.html).<br>


It is not allowed to sell Toro C Library as a stand alone product or
to modify it's content in any way.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH
REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND
FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL,DIRECT,INDIRECT,
OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE,
DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS
ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS
SOFTWARE.

### Toro C Library sourcecode
[Toro C Library sourcecode](https://github.com/KilianKegel/Visual-TORO-C-LIBRARY-for-UEFI?tab=readme-ov-file#torosrc)

    Copyright (c) 2017-2025, Kilian Kegel. All rights reserved.
    SPDX-License-Identifier: GNU General Public License v3.0


### TORO-UEFI-Shell – improved UEFI SHELL with original Intel ACPI Tools (ASLCOMPILER, ACPIDUMP) and many other plugins running in UEFI SHELL based on TIANOCORE/EDK2 February 2025 update [edk2-stable202502](https://github.com/tianocore/edk2/releases/tag/edk2-stable202502)
[UEFI-SHELL-binary-source-and-build-environment](https://github.com/KilianKegel/UEFI-SHELL-binary-source-and-build-environment?tab=readme-ov-file#edk2-uefi-shell--toro-uefi-shell)<br>
[ACPI Component Architecture port to UEFI](https://github.com/KilianKegel/Visual-ACPICA-for-UEFI-ShellPORTABLE?tab=readme-ov-file#visual-acpica-for-uefi-shell)<br>
![](https://github.com/KilianKegel/pictures/blob/master/TORO-UEFI-SHELL-INTRO.gif)

### Checking UEFI time drift on your platform: TSCSync
https://github.com/KilianKegel/Visual-TSCSync-for-UEFI-Shell?tab=readme-ov-file#visual-tscsync-for-uefi-shell
![](https://github.com/KilianKegel/Visual-TSCSync-for-UEFI-Shell/blob/main/TSCSyncDemo.gif)
[![Repo name](https://github-readme-stats.vercel.app/api/pin/?username=KilianKegel&repo=logbook)](https://github.com/KilianKegel/logbook)

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
[![Repo name](https://github-readme-stats.vercel.app/api/pin/?username=KilianKegel&repo=EDK2020-MinnowBoard#edk2020-minnowboard-featuring-cdepkg-c-development-environment-package)](https://github.com/KilianKegel/EDK2020-MinnowBoard#edk2020-minnowboard-featuring-cdepkg-c-development-environment-package)
[![Repo name](https://github-readme-stats.vercel.app/api/pin/?username=KilianKegel&repo=Howto-setup-a-UEFI-Development-PC)](https://github.com/KilianKegel/Howto-setup-an-UEFI-Development-PC#howto-setup-a-uefi-development-pc)
[![Repo name](https://github-readme-stats.vercel.app/api/pin/?username=KilianKegel&repo=Howto-create-a-UEFI-Shell-Boot-Drive)](https://github.com/MinnowWare/Howto-create-a-UEFI-Shell-Boot-Drive#howto-create-a-uefi-shell-boot-device)
[![Repo name](https://github-readme-stats.vercel.app/api/pin/?username=KilianKegel&repo=Howto-configure-VS2022-to-build-.EFI-executables#howto-configure-vs2022-to-build-efi-executables)](https://github.com/KilianKegel/Howto-configure-VS2022-to-build-.EFI-executables#howto-configure-vs2022-to-build-efi-executables) [![Repo name](https://github-readme-stats.vercel.app/api/pin/?username=KilianKegel&repo=git-for-gits)](https://github.com/KilianKegel/git-for-gits)
[![Repo name](https://github-readme-stats.vercel.app/api/pin/?username=KilianKegel&repo=Howto-configure-DDK-and-WDK-for-Standard-C-usage)](https://github.com/KilianKegel/Howto-configure-DDK-and-WDK-for-Standard-C-usage) 
[![Repo name](https://github-readme-stats.vercel.app/api/pin/?username=KilianKegel&repo=-obsolete-Howto-setup-a-YOCTO-Development-PC)](https://github.com/KilianKegel/-obsolete-Howto-setup-a-YOCTO-Development-PC)
[![Repo name](https://github-readme-stats.vercel.app/api/pin/?username=KilianKegel&repo=papers-bugs-miscellaneous-...-#cdepkg-blog-at--uefi--tianocore)](https://github.com/KilianKegel/papers-bugs-miscellaneous-...-#cdepkg-blog-at--uefi--tianocore)
