# Rocket Surgery

A discussion of next generation technologies, especially with regard to software and formal methods.

Canonical Locations for this repo are, in order:

1. Keybase.io [team page](keybase://team-page/rocket_surgery), [git sync url](keybase://team/rocket_surgery/rocket-surgery)
2. [GitLab](https://gitlab.com/egrieco/rocket-surgery)
3. [GitHub](https://github.com/egrieco/rocket-surgery)

## Why Does Anyone Care?

Formal methods allow us to create High Assurance (essentially "bug-free") software assuming certain conditions are met. We'll save the list of conditions for a future update.

While these methods take more time and skill up front, they allow software to run for far longer periods between failures or security compromises. Potentially forever in a theoretical sense if the hardware could ever be reliable enough to allow that. This is a far cry from today's systems that must be rebooted frequently and patched daily in an effort to stave off attacks.

Some good intro materials for the general public and executives:

* Hacker-Proof Code Confirmed [Quanta Magazine](https://www.quantamagazine.org/formal-verification-creates-hacker-proof-code-20160920/) [Reprint in Wired](https://www.wired.com/2016/09/computer-scientists-close-perfect-hack-proof-code/)
* [DARPA High Assurance Cyber Military Systems (HACMS) MH-6 Little Bird helicopter](https://www.youtube.com/watch?v=VxB-U51__Ss)

## Examples of Formally Verified Software

* [seL4](https://sel4.systems/): A high-assurance, high-performance operating system microkernel.
* [CertiKOS](https://deepspec.org/entry/Project/CertiKOS): A novel and practical programming infrastructure for constructing large-scale certified system software.
* [Ironsides](https://ironsides.martincarlisle.com/): An authoritative/recursive DNS server pair that is provably invulnerable to many of the problems that plague other servers.
* [Muen](https://www.muen.sk/): An x86/64 Separation Kernel for High Assurance.

## Program Analysis & Verification

### KLEE

* [KLEE](https://klee.github.io/)
* [GitHub - klee/klee: KLEE Symbolic Execution Engine](https://github.com/klee/klee)

### SMACK

* [SMACK Software Verifier and Verification Toolchain](http://smackers.github.io/)
* [smackers · GitHub](https://github.com/smackers)
* [smack/projects.md at master · smackers/smack · GitHub](https://github.com/smackers/smack/blob/master/docs/projects.md)
* [GitHub - alastairreid/smack-play: Experiments in using Smack verification tool with C and Rust](https://github.com/alastairreid/smack-play)
* [GitHub - smackers/democratizing-software-verification-workshop-2019](https://github.com/smackers/democratizing-software-verification-workshop-2019)

### SeaHorn

* [SeaHorn | A Verification Framework](https://seahorn.github.io/)
* [SeaHorn · GitHub](https://github.com/seahorn)

## Dependent Types

* [LiquidHaskell](http://goto.ucsd.edu:8090/index.html) ([awesome repo](https://github.com/ucsd-progsys/liquidhaskell.git))
* [Idris](https://www.idris-lang.org/) ([awesome repo](https://github.com/joaomilho/awesome-idris))
* [Dafny](https://github.com/dafny-lang/dafny) is a verification-aware programming language

## Theorem Provers

* [Coq](https://github.com/coq/coq.git)
* [Alloy](https://www.csail.mit.edu/research/alloy)
* [Z3](https://github.com/Z3Prover/z3)

### TLA+

* [TLA+](https://lamport.azurewebsites.net/tla/tla.html)
* [Using TLA+ for fun and profit in the development of Elasticsearch - Yannick Welsch - YouTube](https://www.youtube.com/watch?v=qYDcbcOVurc)
* [Introduction :: Learn TLA+](https://learntla.com/introduction/)
* [TLA+ model checking made symbolic – the morning paper](https://blog.acolyer.org/2019/11/29/tla-model-checking-made-symbolic/)
* [Using TLA+ to Model Cascading Failures - Marianne Bellotti - Medium](https://medium.com/@bellmar/using-tla-to-model-cascading-failures-5d1ebc5e4c4f)
* [Using TLA+ to understand Xen vchan - Thomas Leonard's blog](https://roscidus.com/blog/blog/2019/01/01/using-tla-plus-to-understand-xen-vchan/)
* [Practical TLA+ Now Available • Hillel Wayne](https://www.hillelwayne.com/post/practical-tla/)

### Isabelle

* [Isabelle](https://isabelle.in.tum.de/)
* [Martin Kleppmann - Correctness proofs of distributed systems with Isabelle | Code Mesh LDN 19 - YouTube](https://www.youtube.com/watch?v=NfdP6wwjsGk)
* [What are the strengths and weaknesses of the Isabelle proof assistant compared to Coq? - Stack Overflow](https://stackoverflow.com/questions/30152139/what-are-the-strengths-and-weaknesses-of-the-isabelle-proof-assistant-compared-t)
* [Solving a puzzle using the Isabelle proof assistant · GitHub](https://gist.github.com/jmoy/59c0ef25196716f1a0f4fd0efae6e099)

## Full Program Synthesis

* ["Type-Driven Program Synthesis" by Nadia Polikarpova](https://www.youtube.com/watch?v=HnOix9TFy1A)
* [Commandline Commander: Synquid](http://comcom.csail.mit.edu/comcom/#Synquid) (appears to have been taken offline)

## Program Self-Repair

* [DARPA Seeks to Create Software Systems That Could Last 100 Years](https://www.darpa.mil/news-events/2015-04-08)
* [Automated Program Repair | December 2019 | Communications of the ACM](https://cacm.acm.org/magazines/2019/12/241055-automated-program-repair/fulltext)

## Quorum and N-Version Computing

* [The Origin of Quorum Systems](http://vukolic.com/QuorumsOrigin.pdf)
* [Distributed Storage Systems: Data Replication using Quorums](https://blough.ece.gatech.edu/6102/quorums.pdf)
* [The load, capacity, and availability of quorum systems](https://blog.acolyer.org/2016/10/03/the-load-capacity-and-availability-of-quorum-systems/)
* [Enter the Hydra: Towards Principled Bug Bounties and Exploit-Resistant Smart Contracts](https://www.youtube.com/watch?v=0sdby0R5L8s&t=7m24s) - [Blockchain Protocol Analysis and Security Engineering 2018 | Cyber Initiative](https://cyber.stanford.edu/bpase18) - Good overview of N-Version computing starting at 7:24.

## Further Reading and Resources

* [Hillel Wayne](https://hillelwayne.com/) - Lots of blog posts about TLA+ and Formal Methods

### Related Awesome Repos

* [awesome-provable: A curated set of links to formal methods involving provable code.](https://github.com/awesomo4000/awesome-provable)
* [awesome-static-analysis: Static analysis tools for all programming languages, build tools, config files and more.](https://github.com/analysis-tools-dev/static-analysis)
* [awesome-dynamic-analysis: Dynamic analysis tools for all programming languages, build tools, config files and more.](https://github.com/analysis-tools-dev/dynamic-analysis)
* [Awesome-Fuzzing: A curated list of fuzzing resources ( Books, courses - free and paid, videos, tools, tutorials and vulnerable applications to practice on ) for learning Fuzzing and initial phases of Exploit Development like root cause analysis.](https://github.com/secfigo/Awesome-Fuzzing)
* [awesome-program-synthesis: An curated list of papers on program synthesis.](https://github.com/praveenkulkarni1996/awesome-program-synthesis)
