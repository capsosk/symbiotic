## What is Symbiotic?
Symbiotic is a tool for analysis of sequential computer programs written in the programming language C. It can check all common safety properties like assertion violations, invalid pointer dereference, double free, memory leaks, etc. Symbiotic combines light-weight static analysis, compile-time code instrumentation, program slicing, and symbolic execution
[[1](http://is.muni.cz/repo/984069/sse.pdf),
 [2](http://www.fi.muni.cz/~xstrejc/publications/tacas2016symbiotic_preprint.pdf),
 [3](https://link.springer.com/chapter/10.1007/978-3-030-45237-7_31)].
We use [LLVM](<https://llvm.org>) as internal program representation. Symbiotic is highly modular and all of its components can be used separately.


## SV-COMP 2021
Symbiotic won the gold medal in MemSafety and SoftwareSystems categories and took the 4th place in the meta category Overall in [SV-COMP 2021](https://sv-comp.sosy-lab.org/2021/results/results-verified/).

## SV-COMP 2020
Symbiotic won the silver medal in MemSafety category, the gold medal in SoftwareSystems category, 2nd place in FalsificationOverall meta category (finding bugs) and 4th place in the meta category Overall in [SV-COMP 2020](https://sv-comp.sosy-lab.org/2020/results/results-verified/).

## SV-COMP 2019
Symbiotic won the gold medal in MemSafety category and 4th place in the meta category Overall and FalsificationOverall of SV-COMP 2019. Complete results can be found at the [official SV-COMP 2019 site](https://sv-comp.sosy-lab.org/2019/results/results-verified/).

## SV-COMP 2018
Symbiotic won the gold medal in MemSafety category, Bronze medal in the FalsificationOverall meta category and took 4th place in the Overall category of SV-COMP 2018. Complete results can be found [official SV-COMP 2018 site](http://sv-comp.sosy-lab.org/2018/results/results-verified/).

## SV-COMP 2017
We participated in SV-COMP 2017 and we won the bronze medal in MemSafety category. Complete results can be found [official SV-COMP 2017 site](http://sv-comp.sosy-lab.org/2017/results/results-verified/).

## SV-COMP 2016
We participated in SV-COMP 2016 with this particular release: <https://github.com/staticafi/symbiotic/releases/tag/3.0.1> and we won the bronze medal in Arrays category. Complete results can be found [official SV-COMP 2016 site](http://sv-comp.sosy-lab.org/2016/results/results-verified/).


### Symbiotic Components

Components of Symbiotic can be found at <https://github.com/staticafi> with the only exception of the slicer, that can be found at <https://github.com/mchalupa/dg> (it will be moved to _staticafi_ in the future though). All parts of Symbiotic are open-source projects and are licensed under various open-source licenses (GPL, MIT license, University of Illinois Open Source license)

## Contact

For more information send an e-mail to <statica@fi.muni.cz>. We'll be happy to answer your questions :)

------------------------------------------------
[1] Slabý, Jiří and Strejček, Jan and Trtík, Marek. _Checking Properties Described by State Machines: On Synergy of Instrumentation, Slicing, and Symbolic Execution_. [link](http://is.muni.cz/repo/984069/sse.pdf)

[2] Chalupa, Jonáš, Slaby, Strejček, Vitovská. _Symbiotic 3: New Slicer and Error-Witness Generation_. [link](http://www.fi.muni.cz/~xstrejc/publications/tacas2016symbiotic_preprint.pdf)

[3] Chalupa, Jašek, Tomovič, Hruška, Šoková, Ayaziová, Strejček. _Symbiotic 7: Integration of Predator and More_. [link](https://link.springer.com/chapter/10.1007/978-3-030-45237-7_31)
