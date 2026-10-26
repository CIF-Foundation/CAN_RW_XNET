# CAN_RW_XNET

LabVIEW class that reads and writes CAN frames with NI-XNET. `XNET CAN RW.lvclass` inherits from [CAN_RW_Core](https://github.com/CIF-Foundation/CAN_RW_Core).

## Installation

Install [CIF CAN RW Core](https://github.com/CIF-Foundation/CAN_RW_Core) first. This package requires `CIF_Foundation_lib_CIF_CAN_RW_Core` 1.3.0.1 or later.

Build or install this package using the VIPM project in [`VIPM/XNET CAN RW.vipb`](VIPM/XNET%20CAN%20RW.vipb).

Package-specific documentation is in [`VIPM/README.md`](VIPM/README.md).

## Repository Layout

| Path | Description |
| --- | --- |
| `src/` | LabVIEW source for `XNET CAN RW.lvclass`, including core, accessors, utilities, typedefs, and tests |
| `VIPM/` | VI Package Manager build specification and package readme |
| `LICENSE` | Apache License 2.0 |

## License

Copyright 2025-2026 CIF Foundation

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this project except in compliance with the License. You may obtain a copy of the License at:

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

The full license text is in [`LICENSE`](LICENSE).
