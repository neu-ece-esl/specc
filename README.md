# SpecC

Source: [Wikipedia.org](http://en.wikipedia.org/wiki/SpecC):

**SpecC** is a System Description Language(SDL), or System-level Design Language(SLDL), and is an extension of the [ANSI C](http://en.wikipedia.org/wiki/ANSI_C "ANSI C") [programming language](http://en.wikipedia.org/wiki/Programming_language "Programming language"). It is used to aid the design and specification of digital [embedded systems](http://en.wikipedia.org/wiki/Embedded_system "Embedded system"), providing improved productivity whilst retaining the ability to change a design at functional and specification level, unlike [HDLs](http://en.wikipedia.org/wiki/Hardware_description_language "Hardware description language") like[Verilog](http://en.wikipedia.org/wiki/Verilog "Verilog") and [VHDL](http://en.wikipedia.org/wiki/VHDL "VHDL"). An architectural model can be created which allows other tools to directly map the design onto [silicon](http://en.wikipedia.org/wiki/Silicon "Silicon") or [FPGA](http://en.wikipedia.org/wiki/FPGA "FPGA"). The main aim is for the reuse, exchange and integration of IP at various levels of abstraction.

The language and design methodology were created by Rainer Dömer and Daniel Gajski at the Centre for Embedded Computer Systems at [University of California, Irvine](http://en.wikipedia.org/wiki/University_of_California,_Irvine "University of California, Irvine") in 2001.

The tutorial [part 1](http://www.cecs.uci.edu/%7Edoemer/publications/ESC_02_1.pdf ) and [part 2](http://www.cecs.uci.edu/%7Ecad/publications/conferences/2000-04/esc02.349.pdf ) show a basic introduction to SpecC SLDL and the design methodology. The design methodology is implemented in System-on-Chip Environment (SCE), see the [overview](http://www.hindawi.com/getarticle.aspx?doi=10.1155/2008/647953).

![System-on-Chip Environment (SCE)](http://www.cecs.uci.edu/~cad/sce.png)

Similar projects and design methodologies include [SystemC](http://en.wikipedia.org/wiki/SystemC), an SDL based on [C++](http://en.wikipedia.org/wiki/C%2B%2B "C++"). Although this rival language has seen much more widespread industry usage (although SpecC is popular in [Japan](http://en.wikipedia.org/wiki/Japan "Japan")), SpecC retains simplicity whilst also providing the vital features of any SDL, such as [concurrency](http://en.wikipedia.org/wiki/Concurrency "Concurrency") (SpecC provides pipelined and parallel flows), [synchronisation](http://en.wikipedia.org/wiki/Synchronisation "Synchronisation"), [state transitions](http://en.wikipedia.org/wiki/State_transition "State transition") (not available in [Verilog](http://en.wikipedia.org/wiki/Verilog "Verilog")), and [composite](http://en.wikipedia.org/wiki/Composite_image "Composite image") [data types](http://en.wikipedia.org/wiki/Data_types "Data types").

For more information about SpecC usage and development, see our [Wiki](https://github.com/neu-ece-esl/specc/wiki).
