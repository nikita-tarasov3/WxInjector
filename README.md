<h1 align="center">
  <br>
    <img src="./.github/icon.png" width="200">
  <br>
    WxInjector
  <br>
</h1>

<p align="center">
  <a href="https://dotnet.microsoft.com">
    <img src="https://img.shields.io/badge/Powered%20By-.NET-blue?logo=microsoft&style=for-the-badge">
  </a>
  <a href="https://visualstudio.microsoft.com">
    <img src="https://img.shields.io/badge/Made%20With-Visual%20Studio-blue?logo=visual-studio&style=for-the-badge">
  </a>
</p>

This program injects DLLs into any processes with three special methods and special flags. This program is useful for hackers, developers and cheaters alike. This injector is powered by [Bleak](https://github.com/Akaion/Bleak), which is by now deprecated but it still works without any flaws!

**Features**

* Supports WoW64 and x64 injection
* Supports ejection from process
* Has a variety of injection methods
* Has a variety of injection flags
* Has a metro interface and it is well-designed (based on my opinion)
* Can see if process or DLL is 64-bit or 32-bit
* Created entirely in .NET

**Injection Methods**

* CreateThread
* HijackThread
* ManualMap

**Injection Flags**

* HideDllFromPeb
* RandomizeDllHeaders (No Ejection Support)
* RandomizeDllName

## Screenshots

![](./.github/screenshots/0.png)
![](./.github/screenshots/1.png)
