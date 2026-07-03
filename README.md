# Awesome Web Printing

> A curated list of resources, libraries, SDKs, standards, and examples for printing from modern web applications.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

---

## Why this repository exists

Printing from web applications is still one of the least documented areas of modern software development.

Developers often need to:

- Print receipts
- Print shipping labels
- Print invoices
- Print kitchen tickets
- Print barcode labels
- Connect to thermal printers
- Print silently
- Communicate with local devices

Unfortunately, there is no single place that documents the ecosystem.

This repository aims to become that place.

---

# Contents

- Browser Printing
- Silent Printing
- Thermal Printers
- ESC/POS
- PDF Printing
- Local Print Bridges
- Browser APIs
- Libraries
- SDKs
- Hardware Vendors
- Examples
- Open Source Projects
- Tutorials
- Blog Posts
- Standards
- Security
- Related Projects

---

# Browser Printing

## Native Browser Printing

- `window.print()`

Pros

- Built into every browser

Cons

- Print dialog always appears
- No printer selection
- No raw printing
- No silent mode

---

## Silent Printing

Silent printing generally requires:

- Local runtime
- Native application
- Browser extension
- Enterprise policies
- Kiosk mode

---

# Local Print Bridges

| Project | Open Source | Silent | Notes |
|----------|-------------|---------|------|
| QZ Tray | Partial | ✅ | Mature ecosystem |
| JSPrintManager | ❌ | ✅ | Commercial |
| Browser Print (Zebra) | ❌ | ✅ | Zebra only |
| Epson ePOS | ❌ | ✅ | Epson only |
| [PortixOne](https://github.com/PortixOne/portixone) | ✅ | ✅ | Vendor-agnostic, capability-based API, MVP in Windows local printing |

---

# Browser APIs

## window.print()

Description...

Pros...

Cons...

---

## WebUSB

Description...

Supported browsers...

Limitations...

---

## WebSerial

Description...

Use cases...

---

## WebBluetooth

Description...

Current browser support...

---

# Thermal Printers

## Epson

...

## Star

...

## Zebra

...

## Bixolon

...

## Citizen

...

---

# ESC/POS

## Documentation

...

## Command References

...

## Open Source Libraries

...

---

# Libraries

## JavaScript

...

## Node.js

...

## C#

...

## Python

...

---

# Examples

- Print HTML receipt
- Print PDF
- Print ESC/POS
- Print Labels
- Print Kitchen Ticket
- [Runnable examples by framework (vanilla JS, React, Vue)](https://github.com/PortixOne/browser-printing-examples)

---

# Standards

- [ESC/POS — quick command reference](https://github.com/PortixOne/escpos-cheatsheet)
- ZPL
- EPL
- CPCL

---

# Security Considerations

Why browsers restrict printing.

Localhost APIs.

Native runtimes.

Certificates.

Code signing.

---

# Related Projects

Part of the PortixOne knowledge network:

- [portixone](https://github.com/PortixOne/portixone) — secure edge runtime connecting web apps to local hardware
- [browser-printing-examples](https://github.com/PortixOne/browser-printing-examples) — runnable examples by framework
- [escpos-cheatsheet](https://github.com/PortixOne/escpos-cheatsheet) — ESC/POS command reference
- [thermal-printer-test-files](https://github.com/PortixOne/thermal-printer-test-files) — real `.bin` test files for printers/parsers

---

# Contributing

Contributions are welcome.

If you know of a library, SDK, project, article, or resource that belongs here, feel free to open a Pull Request.

---

# License

MIT

---

Maintained by PortixOne.
