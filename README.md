# Gaskony Ignition Modules

Independent, open-source modules for Inductive Automation's
[Ignition](https://inductiveautomation.com/) platform (8.3+).

> **⚠️ These modules are not actively supported.** They are published as-is, open
> source, under the licence shown against each module below. I update and improve
> them when I can, but there is no support commitment, no roadmap, and no
> guaranteed response to issues. They are open sourced so others can use, fork,
> and contribute — if you need a fix or a feature, a pull request is the fastest
> route to getting it.

### ➡️ Download portal: https://gaskony-ignition.github.io/ignition-modules-portal/

| Module | Latest | Licence | Source |
| ------ | ------ | ------- | ------ |
| Camera Driver | v3.2.1 | Apache-2.0 | [module-camera-driver](https://github.com/Gaskony-Ignition/module-camera-driver) |
| Logix PLC Emulator | v11.1.2 | Apache-2.0 | [module-plc-emulator](https://github.com/Gaskony-Ignition/module-plc-emulator) |
| Python 3 Integration | v4.6.2 | Apache-2.0 | [module-python3](https://github.com/Gaskony-Ignition/module-python3) |
| Git Integration | v2.12.6 | Beerware | [module-git-integration](https://github.com/Gaskony-Ignition/module-git-integration) |
| Script IDE | v1.25.0 | Apache-2.0 | [module-script-ide](https://github.com/Gaskony-Ignition/module-script-ide) |

Git Integration is a fork, not original work here: it was created by Enzo
Sagnelonge at [AXONE-IO](https://www.axone-io.com/) and substantially reworked by
[OperaMetrix](https://github.com/operametrix/ignition-git-module), who maintain
it. This build adds gitignore management on the gateway Versioning page and
change indicators in the Designer's Project Browser. The Beerware notice is
retained, as that licence requires.

All modules are signed and built for Ignition 8.3+ (Java 17). Download the `.modl`
from a [release](../../releases) and install via
**Gateway → Config → Modules → Install or Upgrade a Module**.

## Questions & contributions

Open an issue on the relevant module's source repository. Bear in mind these
modules are not actively supported, so issues are looked at when time allows and
may sit for a while.

**Pull requests are very welcome** and are the quickest way to get something
fixed or added. Every module here is open source under the licence shown in the
table — fork them, build on them, and contribute back if it is useful to you.
For Git Integration, changes that are not specific to this build belong upstream
at OperaMetrix.

---
*Independent project — not affiliated with, endorsed by, or supported by
Inductive Automation. "Ignition" is a trademark of Inductive Automation, LLC.
Software is provided without warranty of any kind, under each module's own
licence.*
