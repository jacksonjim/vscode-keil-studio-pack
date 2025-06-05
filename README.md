# Arm Keil Studio Pack for Visual Studio Code

## Overview

The Arm® Keil® Studio Pack installs recommended extensions for embedded and IoT software development on
Arm-based microcontrollers. See the **Details** tab in Visual Studio Code for a full list, or refer to
[Extensions available in the pack](#extensions-available-in-the-pack).

Key extensions include **Arm CMSIS Solution** and **Arm CMSIS Debugger**. Together, they support CMSIS solutions
(csolution projects), hardware execution, and debugging. Each extension can be used independently.

## Use Cases

**CMSIS-Packs and csolution projects**: Build embedded and IoT applications using CMSIS-standard components. For
  supported hardware, see [Boards](https://www.keil.arm.com/boards/) and [Devices](https://www.keil.arm.com/devices/).
  For [CMSIS-Packs](https://www.keil.arm.com/packs/), visit [open-cmsis-pack.org](https://www.open-cmsis-pack.org/index.html).
  CMake). Advanced configuration in VS Code may be required.

## Related

- [Arm CMSIS Solution extension user's guide](https://mdk-packs.github.io/vscode-cmsis-solution-docs/index.html).
- [Arm Keil Studio getting started guide](https://developer.arm.com/documentation/109350/latest/What-is-MDK-/A-family-of-tools).
- [Example projects](https://github.com/Arm-Examples) help you setting up the tools and validating their operation.
- [Available CMSIS-Packs](https://keil.arm.com/packs).

## Extensions available in the pack

The extensions available are:

- [Arm CMSIS Solution](https://marketplace.visualstudio.com/items?itemName=Arm.cmsis-csolution): Supports development
  using CMSIS solutions (csolution projects).
- [Arm CMSIS Debugger](https://marketplace.visualstudio.com/items?itemName=Arm.vscode-cmsis-debugger): An extension
  pack that creates the debug platform for Arm-based IoT solutions.
- [Arm Tools Environment Manager](https://marketplace.visualstudio.com/items?itemName=Arm.environment-manager):
  Installs development tools specified in a manifest (e.g., Arm Compiler, CMSIS-Toolbox, CMake, Ninja).
- [clangd](https://marketplace.visualstudio.com/items?itemName=llvm-vs-code-extensions.vscode-clangd): Adds intelligent
code features such as completion, diagnostics, and navigation.
> 📝 **Note:**  
> This is an open-source third-party extension.

### Bundled with Arm CMSIS Debugger

- [CDT GDB Debug Adapter Extension](https://marketplace.visualstudio.com/items?itemName=eclipse-cdt.cdt-gdb-vscode):
  Supports debugging using gdb and any other debugger that supports the
  [MI protocol](https://sourceware.org/gdb/current/onlinedocs/gdb.html/GDB_002fMI.html).
- [Memory Inspector](https://marketplace.visualstudio.com/items?itemName=eclipse-cdt.memory-inspector): Analyzes and
  monitors system memory during development.
- [Peripheral Inspector](https://marketplace.visualstudio.com/items?itemName=eclipse-cdt.peripheral-inspector):
  Displays register-level peripheral information using CMSIS-SVD files.
- [Serial Monitor](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-serial-monitor): An extension
  that provides a serial monitor to view output from as well as send messages to serial ports.

> 📝 **Note:**  
> These are third-party extensions. Some of them are open-source.

### Bundled with Arm CMSIS Solution

- [YAML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml): Enables YAML syntax support.

> 📝 **Note:**  
> This is a third-party extension.

## Feedback

Submit feedback via our [support page](https://www.keil.arm.com/support/#:~:text=Keil%20Studio%20for%20VS%20Code).

## Telemetry

This pack collects usage data in accordance with
[VS Code telemetry settings](https://code.visualstudio.com/docs/getstarted/telemetry#_disable-telemetry-reporting).
You can adjust telemetry behavior in the VS Code settings menu.

## License agreement

Use of this extension indicates acceptance of the
[End User License Agreement](https://www.keil.arm.com/license-agreement-extensions/).
