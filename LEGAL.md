# Legal notes for Embryo FPGA Route

Embryo FPGA Route is a modified version of **nextpnr** (https://github.com/YosysHQ/nextpnr), copyright its authors.
License: **ISC (bundled parts keep their own licenses)**. The original license files are kept unchanged: COPYING.

First lines of those files when we forked (2026-11-16):
- `COPYING`: Copyright (C) 2018-2020 Claire Xenia Wolf <claire@yosyshq.com> / Copyright (C) 2018-2020 gatecat <gatecat@ds0.me> / Copyright (C) 2018-2020 Dan Gisselquist <dan@symbioticeda.com>

## When we offer it to people
- Keep the copyright notice, license text and disclaimer in source and in the documentation of anything we hand out.
- CHECK before release: the FPGA chip databases it uses (e.g. himbaechel/uarch/xilinx/meta) have their own licenses.
- Running it on our own servers for people (inside the apps) is not handing out the program; we still keep our source public.
- Chips and layouts people make with it belong to them; the tool's license does not cover what it produces.
- No warranty beyond what the license says.
