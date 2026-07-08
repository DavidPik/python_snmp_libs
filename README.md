# Python Library Injector for Home Assistant

This HACS-compatible custom component injects Python libraries into Home Assistant Core
so that custom integrations depending on pysnmp, pyasn1, or pyasn1-modules can work
inside Home Assistant OS.

## Included libraries

- pysnmp-lextudio
- pyasn1
- pyasn1-modules

## Installation

1. Upload this repository to GitHub.
2. Add it to HACS as a custom repository (Integration).
3. Install the component.
4. Restart Home Assistant.

## Usage

Custom integrations can import these libraries normally:

```python
import pysnmp
import pyasn1
import pyasn1_modules
