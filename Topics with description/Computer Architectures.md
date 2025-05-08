# Computer Architectures

---

## I. Logical Architecture

1. **Data Files & Manipulations**  
   - Definition, memory, logical and physical memory, Registers vs. Memory, addressing modes, indexed addressing

2. **Sequential Instruction Execution**  
   - Arithmetical instructions, load and store, conditional and unconditional jumps

3. **Instruction Types & State Transitions**  
   - Types of instructions and operands, architectural types, regular architectures, state space and state transitions

---

## II. Classes of Computers and Performance Metrics

4. **Performance Metric & Instruction Set Architecture**  
   - Classes of Computers, Instruction Set Architecture (ISA), CPU clocking, CPU time, instruction count and CPI, MIPS

5. **Power & Energy**  
   - Power trends, Power Wall, reducing power, dynamic energy and power, static power

---

## III. Classical Microarchitectures (Physical Architecture)

6. **ALU I**  
   - Parts of the ALU, data paths, single-bit adder, n-bit sequential and parallel adder, adder with carry

7. **ALU II**  
   - BCD encoding, floating-point properties, formats, IEEE 754, rounding, exceptions, algebraic operations

8. **Control Unit**  
   - Implementation and operation of hard-wired CU

9. **Interrupt System**  
   - Definition, causes, exceptions, differences between interrupts and exceptions

---

## IV. Memory

10. **Memory Hierarchy & DRAM**  
    - Principle of locality, memory hierarchy, DRAM technology, memory width effects, interleaving

11. **Cache Write Policies**  
    - Write-through, write-back, write allocation, write-around, differences

12. **Associative & Multilevel Caches**  
    - Associative cache types, direct-mapped vs. fully associative, multilevel cache advantages

---

## V. Modern Microarchitectures (Physical Architecture)

13. **Architecture Classification**  
    - Flynn’s classification, modern classification methods

14. **Data Dependencies**  
    - Definition, types, influence on performance

15. **Control Dependencies**  
    - Definition, influence on performance, branch types, static/dynamic prediction, speculative execution

16. **Sequential Consistency**  
    - Instruction and interrupt consistency, reorder buffer (ROB), reservation stations

17. **Parallel Instruction Execution**  
    - Prefetching, instruction overlap, pipelining, bottlenecks and mitigation

18. **Pipeline-Based Execution**  
    - Pipeline basics, logical and physical pipeline characteristics

19. **Superscalar Architectures**  
    - Operation principles, Harvard architecture, CISC vs. RISC, ILP, branch prediction

20. **Instruction Fetch & Branch Prediction**  
    - Local prediction, correlating predictor, tournament predictor, branch target prediction

21. **3rd Gen Superscalar**  
    - Three-operand instructions, SIMD, vector multimedia, VLIW architectures

---

## VI. New Era in Processor Development

22. **Thread-Level Parallelism**  
    - Single-core limitations, performance vs. complexity, forms of multithreading, SMT vs. single-threaded

23. **Process-Level Parallelism**  
    - Motivation, rating, limits, Amdahl’s law, shared/distributed memory

---

## VII. Intel Core 2 Family

24. **Intel vs. AMD I**  
    - IC tech competition, transistor growth rate, Intel tech development

25. **Intel vs. AMD II**  
    - Performance race, shift reasons, ARM's rise and impact

26. **Core Family Roadmap**  
    - Pentium 4 cancellation, tick-tock model, key developments

27. **Desktop/Laptop/HED CPUs**  
    - Core counts, performance, system topology

28. **Server CPUs**  
    - Core counts, memory bandwidth, UMA and NUMA

29. **Thermal Management**  
    - Dissipation focus, reduction methods, thermal reserves

30. **ISA Extensions**  
    - x86 extensions, SIMD details

31. **Memory Subsystem Evolution**  
    - Channel attachment, bandwidth, direct/indirect interfaces

32. **Cache Architecture Evolution**  
    - L2–L4 levels, per-core/shared, unified/split caches

---

## VIII. AMD Zen Family

33. **Zen Roadmap**  
    - Zen to Zen+, core complexes, Zeppelin, Threadripper, Epyc, Infinity Fabric

34. **Ryzen Line**  
    - Pure Power, Precision Boost, XFR, StoreMI, control triangle

35. **In-Package Integration**  
    - MCMs, homogeneous/heterogeneous dies, horizontal/vertical integration, power limits

36. **Zen Family Introduction & Success**  
    - Launch, modularity, multi-chip benefits, alternatives

37. **Zen 2 Development**  
    - Processor types, chipset selections, implementation

38. **Zen Overview**  
    - With/without GPU, packaging, Pro models

---

## IX. Mobile Revolution & ARM CPUs

39. **Mobile Revolution**  
    - History, use cases, low power/connectivity needs, Intel/AMD mobile CPUs

40. **ARM CPU Families**  
    - ARM’s business model, product lines, mobile dominance

41. **ARM ISA Development**  
    - Base ISA, version history, extension focuses

42. **ARMv7 ISA**  
    - Purpose, significance, Cortex profiles, secondary registers

43. **ARMv7 big.LITTLE Architectures**  
    - Evolution, operation principle

44. **ARMv7–v9 CPU Evolution**  
    - 32-bit to 64-bit, big.LITTLE development, ARMv8.2/v9 advancements
