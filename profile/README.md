![https://plasma-umass.org/plasma-globe.png](https://plasma-umass.org/plasma-globe.png)

# PLASMA (Programming Languages and Systems at Massachusetts)

- [Emery Berger](https://github.com/emeryberger): PLASMA lab advisor
  * YouTube: [![views](https://img.shields.io/youtube/channel/views/UCIPi_mHiQ6FoMgMej51s-lA?style=social)](https://www.youtube.com/@EmeryBerger)
  * [emeryberger.com](https://emeryberger.com), [Medium blog](https://emeryberger.medium.com)

## Current PhD Students

- [Kyla Levin](https://khlevin.github.io/KylaHLevin/)
- [Juan Altmayer Pizzorno](https://jaltmayerpizzorno.github.io/)
- [Sam Stern](https://samstern.me/)
- [Nicolas van Kempen](https://nvankempen.com/)

## PLASMA projects

- [**Scalene**](https://github.com/plasma-umass/scalene): A state-of-the-art CPU+GPU+memory profiler for Python, with AI-powered optimization suggestions
  [![PyPI Latest Release](https://img.shields.io/pypi/v/scalene.svg)](https://pypi.org/project/scalene/)
  [![Anaconda-Server Badge](https://anaconda.org/conda-forge/scalene/badges/version.svg)](https://conda.anaconda.org/conda-forge/scalene)
  [![Downloads](https://pepy.tech/badge/scalene)](https://pepy.tech/project/scalene)
  [![Downloads](https://pepy.tech/badge/scalene/month)](https://pepy.tech/project/scalene)
  [![GitHub stars](https://img.shields.io/github/stars/plasma-umass/scalene?style=social&label=Star&maxAge=2592000)](https://GitHub.com/plasma-umass/scalene/)
- [**Coz**](https://github.com/plasma-umass/coz): A _causal profiler_ that tells you where to optimize your code (C/C++/Rust/Swift/Java)
  [![GitHub stars](https://img.shields.io/github/stars/plasma-umass/coz?style=social&label=Star&maxAge=2592000)](https://GitHub.com/plasma-umass/coz/)
  [![Rust crate downloads](https://img.shields.io/crates/d/coz)](https://img.shields.io/crates/d/coz) <small>_(just counting Rust crate downloads)_</small>
- [**CSrankings**](https://csrankings.org): Ranks the world's CS departments
  [![GitHub stars](https://img.shields.io/github/stars/emeryberger/CSrankings?style=social&label=Star&maxAge=2592000)](https://GitHub.com/emeryberger/CSrankings)
- [**Slipcover**](https://github.com/plasma-umass/slipcover): Nearly zero-overhead code coverage analysis for Python
  [![PyPI Latest Release](https://img.shields.io/pypi/v/slipcover.svg)](https://pypi.org/project/slipcover/)
  [![Downloads](https://pepy.tech/badge/slipcover)](https://pepy.tech/project/slipcover)
  [![GitHub stars](https://img.shields.io/github/stars/plasma-umass/slipcover?style=social&label=Star&maxAge=2592000)](https://GitHub.com/plasma-umass/slipcover/)
- [**ChatDBG**](https://github.com/plasma-umass/ChatDBG): AI-assisted debugging in `lldb`, `gdb`, and `pdb`. Uses AI to answer 'why'
  [![PyPI Latest Release](https://img.shields.io/pypi/v/ChatDBG.svg)](https://pypi.org/project/ChatDBG/)
  [![Downloads](https://pepy.tech/badge/ChatDBG)](https://pepy.tech/project/ChatDBG)
  [![Downloads](https://pepy.tech/badge/ChatDBG/month)](https://pepy.tech/project/ChatDBG)
  [![GitHub stars](https://img.shields.io/github/stars/plasma-umass/ChatDBG?style=social&label=Star&maxAge=2592000)](https://GitHub.com/plasma-umass/ChatDBG/)
- [**Commentator**](https://github.com/plasma-umass/commentator): Automatically comments Python code, adding docstrings and type annotations
  [![PyPI Latest Release](https://img.shields.io/pypi/v/python-commentator.svg)](https://pypi.org/project/python-commentator/)
  [![Downloads](https://pepy.tech/badge/python-commentator)](https://pepy.tech/project/python-commentator)
  [![Downloads](https://pepy.tech/badge/python-commentator/month)](https://pepy.tech/project/python-commentator)
  [![GitHub stars](https://img.shields.io/github/stars/plasma-umass/commentator?style=social&label=Star&maxAge=2592000)](https://GitHub.com/plasma-umass/commentator/)
- [**CWhy**](https://github.com/plasma-umass/CWhy): ("See why") Explains and suggests fixes for C/C++/Rust compiler error messages.
  [![PyPI Latest Release](https://img.shields.io/pypi/v/CWhy.svg)](https://pypi.org/project/CWhy/)
  [![Downloads](https://pepy.tech/badge/CWhy)](https://pepy.tech/project/CWhy)
  [![Downloads](https://pepy.tech/badge/CWhy/month)](https://pepy.tech/project/CWhy)
  [![GitHub stars](https://img.shields.io/github/stars/plasma-umass/CWhy?style=social&label=Star&maxAge=2592000)](https://GitHub.com/plasma-umass/CWhy/)
- [**SQLwrite**](https://github.com/plasma-umass/sqlwrite): SQLite3 with natural language to SQL, recommends indexes to optimize queries
  [![GitHub stars](https://img.shields.io/github/stars/plasma-umass/sqlwrite?style=social&label=Star&maxAge=2592000)](https://GitHub.com/plasma-umass/sqlwrite/)

## Selected PLASMA publications

See [this DBLP entry](https://dblp.org/pid/98/4487.html) for a complete list of PLASMA papers co-authored by Emery Berger.

- [**Triangulating Python Performance with Scalene**](https://www.usenix.org/system/files/osdi23-berger.pdf) (OSDI 2023, Best Paper Award)
  Introduces Scalene, a profiler that highlights Python performance issues. [[software](https://github.com/plasma-umass/scalene)]
- [**Coz: Finding Code that Counts with Causal Profiling**](http://sigops.org/sosp/sosp15/current/2015-Monterey/090-curtsinger-online.pdf) (Best Paper Award SOSP 2015, CACM Research Highlight)
  Introduces causal profiling and the Coz profiler. [[software](https://github.com/plasma-umass/coz)]
- [**Mesh: Compacting Memory Management for C/C++ Applications**](https://people.cs.umass.edu/~mcgregor/papers/19-pldi.pdf) (PLDI 2019)
  A drop-in replacement for `malloc` that eliminates fragmentation. [[software](https://github.com/plasma-umass/mesh)]
- [**BLeak: Automatically Debugging Memory Leaks in Web Applications**](https://jvilk.com/assets/pdf/bleak.pdf) (PLDI 2018, CACM Research Highlight)
  Detects memory leaks in web applications automatically. [[software](https://github.com/plasma-umass/BLeak)]
   [_incorporated into Android Studio_](https://cs.android.com/android-studio/platform/tools/adt/idea/+/mirror-goog-studio-main:bleak/src/com/android/tools/idea/bleak/Bleak.kt)
- [**Stabilizer: Statistically Sound Performance Evaluation**](https://people.cs.umass.edu/~emery/pubs/stabilizer-asplos13.pdf) (ASPLOS 2013)
  Randomizes everything to see if performance changes are real.
  [_incorporated into WebAssembly benchmarking infrastructure_](https://mastodon.world/@cfallin/109833747279454645)
- [**Reconsidering Custom Memory Allocation**](https://people.cs.umass.edu/~emery/pubs/berger-oopsla2002.pdf) (OOPSLA 2012, Most Influential Paper)
  Shows which kinds of custom memory allocators are useful for improving performance (TL;DR - not many).
- [**Hoard: A Scalable Memory Allocator for Multithreaded Applications**](https://people.cs.umass.edu/~emery/pubs/berger-asplos2000.pdf) (ASPLOS 2000, ASPLOS Most Influential Paper)
  The first scalable `malloc`. [[software](https://github.com/emeryberger/Hoard)] [_incorporated into the Mac OS X allocator_](https://opensource.apple.com/source/libmalloc/libmalloc-116.50.8/src/magazine_malloc.c.auto.html)
 
### PhD Alumni

- [Dan Barowy](https://www.cs.williams.edu/~dbarowy/), Williams College
- [Charlie Curtsinger](https://curtsinger.cs.grinnell.edu/), Grinnell College
- [Matthew Hertz](https://cse.buffalo.edu/~mhertz/), University of Buffalo
- [Tongping Liu](https://www.linkedin.com/in/tongping-liu-b6b64415/), ByteDance
- [Gene Novark](https://www.linkedin.com/in/gene-novark-183a4b20/), "Quantitative Hedge Fund"
- [John Vilk](https://jvilk.com/), Stripe
- [Ting Yang](https://www.linkedin.com/in/tingyang/), Meta (co-advised with Eliot Moss)

### MS Alumni

- [Justin Aquadro](https://www.linkedin.com/in/justin-aquadro-4547561a/), MachineMetrics
- [Breanna Devore-McDonald](https://www.linkedin.com/in/bdevorem/), Untether AI
- [Yi Feng](https://www.linkedin.com/in/yi-feng-0b10241bb/), Google
- [Nitin Gupta](https://www.linkedin.com/in/nitingupta910/), Netflix
- [Vitaly Lvin](https://www.linkedin.com/in/vitaliyl/), Google
- [Bobby Powers](https://www.linkedin.com/in/bobby-powers-0639b81a/), Stripe

