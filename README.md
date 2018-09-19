# Lab04Test

# Personal Computers

A personal computer (PC) is a multi-purpose computer whose size, capabilities, and price make it feasible for individual use.[1] PCs are intended to be operated directly by an end user, rather than by a computer expert or technician. Computer time-sharing models that were typically used with larger, more expensive minicomputer and mainframe systems, to enable them be used by many people at the same time, are not used with PCs.

Early computer owners in the 1960s, invariably institutional or corporate, had to write their own programs to do any useful work with the machines. In the 2010s, personal computer users have access to a wide range of commercial software, free-of-charge software ("freeware") and free and open-source software, which are provided in ready-to-run form. Software for personal computers is typically developed and distributed independently from the hardware or OS manufacturers.[2] Many personal computer users no longer need to write their own programs to make any use of a personal computer, although end-user programming is still feasible. This contrasts with mobile systems, where software is often only available through a manufacturer-supported channel,[3] and end-user program development may be discouraged by lack of support by the manufacturer.[4]

Since the early 1990s, Microsoft operating systems and Intel hardware have dominated much of the personal computer market, first with MS-DOS and then with Windows. Alternatives to Microsoft's Windows operating systems occupy a minority share of the industry. These include Apple's macOS and free and open-source Unix-like operating systems such as Linux. Advanced Micro Devices (AMD) provides the main alternative to Intel's processors.

## Terminology

"PC" is an initialism for "personal computer". The IBM Personal Computer incorporated the designation in its model name, but IBM has not used this brand for many years. It is sometimes useful, especially in a marketing context, to distinguish personal computers of the "IBM Personal Computer" family from personal computers made by other manufacturers. For example, "PC" is used in contrast with "Mac", an Apple Macintosh computer.[5][6][7][8] This sense of the word is used in the "Get a Mac" advertisement campaign that ran between 2006 and 2009, as well as its rival, I'm a PC campaign, that appeared in 2008. Since none of these Apple products were mainframes or time-sharing systems, they were all "personal computers" and not "PC" (brand) computers

## Hardware

Computer hardware is a comprehensive term for all physical parts of a computer, as distinguished from the data it contains or operates on, and the software that provides instructions for the hardware to accomplish tasks. The boundary between hardware and software has become blurred, with the existence of firmware that is software "built into" the hardware. For example, a 2010-era LCD display screen contains a small computer inside. Mass-market consumer computers use highly standardized components and so are simple for an end user to assemble into a working system. Most 2010s-era computers only require users to plug in the power supply, monitor, and other cables. A typical desktop computer consists of a computer case (or "tower"), a metal chassis that holds the power supply, motherboard, hard disk drive, and often an optical disc drive. Most towers have empty space where users can add additional components. External devices such as a computer monitor or visual display unit, keyboard, and a pointing device (mouse) are usually found in a personal computer.

## Software

Computer software is any kind of computer program, procedure, or documentation that performs some task on a computer system.[56] The term includes application software such as word processors that perform productive tasks for users, system software such as operating systems that interface with computer hardware to provide the necessary services for application software, and middleware that controls and co-ordinates distributed systems.

Software applications are common for word processing, Internet browsing, Internet faxing, e-mail and other digital messaging, multimedia playback, playing of computer game, and computer programming. The user may have significant knowledge of the operating environment and application programs, but is not necessarily interested in programming nor even able to write programs for the computer. Therefore, most software written primarily for personal computers tends to be designed with simplicity of use, or "user-friendliness" in mind. However, the software industry continuously provide a wide range of new products for use in personal computers, targeted at both the expert and the non-expert user.

### Operating System

An operating system (OS) manages computer resources and provides programmers with an interface used to access those resources. An operating system processes system data and user input, and responds by allocating and managing tasks and internal system resources as a service to users and programs of the system. An operating system performs basic tasks such as controlling and allocating memory, prioritizing system requests, controlling input and output devices, facilitating computer networking, and managing files.

Common contemporary desktop operating systems are Microsoft Windows, macOS, Linux, Solaris and FreeBSD. Windows, macOS, and Linux all have server and personal variants. With the exception of Microsoft Windows, the designs of each of them were inspired by or directly inherited from the Unix operating system, which was developed at Bell Labs beginning in the late 1960s and spawned the development of numerous free and proprietary operating systems.

# Central Processing Unit

A central processing unit (CPU) is the electronic circuitry within a computer that carries out the instructions of a computer program by performing the basic arithmetic, logical, control and input/output (I/O) operations specified by the instructions. The computer industry has used the term "central processing unit" at least since the early 1960s.[1] Traditionally, the term "CPU" refers to a processor, more specifically to its processing unit and control unit (CU), distinguishing these core elements of a computer from external components such as main memory and I/O circuitry.[2]

## History

Early computers such as the ENIAC had to be physically rewired to perform different tasks, which caused these machines to be called "fixed-program computers".[5] Since the term "CPU" is generally defined as a device for software (computer program) execution, the earliest devices that could rightly be called CPUs came with the advent of the stored-program computer.

The idea of a stored-program computer had been already present in the design of J. Presper Eckert and John William Mauchly's ENIAC, but was initially omitted so that it could be finished sooner.[6] On June 30, 1945, before ENIAC was made, mathematician John von Neumann distributed the paper entitled First Draft of a Report on the EDVAC. It was the outline of a stored-program computer that would eventually be completed in August 1949.[7] EDVAC was designed to perform a certain number of instructions (or operations) of various types. Significantly, the programs written for EDVAC were to be stored in high-speed computer memory rather than specified by the physical wiring of the computer.[8] This overcame a severe limitation of ENIAC, which was the considerable time and effort required to reconfigure the computer to perform a new task. With von Neumann's design, the program that EDVAC ran could be changed simply by changing the contents of the memory. EDVAC, however, was not the first stored-program computer; the Manchester Baby, a small-scale experimental stored-program computer, ran its first program on 21 June 1948[9] and the Manchester Mark 1 ran its first program during the night of 16–17 June 1949.[10]

## Operation

The fundamental operation of most CPUs, regardless of the physical form they take, is to execute a sequence of stored instructions that is called a program. The instructions to be executed are kept in some kind of computer memory. Nearly all CPUs follow the fetch, decode and execute steps in their operation, which are collectively known as the instruction cycle.

After the execution of an instruction, the entire process repeats, with the next instruction cycle normally fetching the next-in-sequence instruction because of the incremented value in the program counter. If a jump instruction was executed, the program counter will be modified to contain the address of the instruction that was jumped to and program execution continues normally. In more complex CPUs, multiple instructions can be fetched, decoded and executed simultaneously. This section describes what is generally referred to as the "classic RISC pipeline", which is quite common among the simple CPUs used in many electronic devices (often called microcontroller). It largely ignores the important role of CPU cache, and therefore the access stage of the pipeline.

Some instructions manipulate the program counter rather than producing result data directly; such instructions are generally called "jumps" and facilitate program behavior like loops, conditional program execution (through the use of a conditional jump), and existence of functions.[c] In some processors, some other instructions change the state of bits in a "flags" register. These flags can be used to influence how a program behaves, since they often indicate the outcome of various operations. For example, in such processors a "compare" instruction evaluates two values and sets or clears bits in the flags register to indicate which one is greater or whether they are equal; one of these flags could then be used by a later jump instruction to determine program flow.

### Fetch

The first step, fetch, involves retrieving an instruction (which is represented by a number or sequence of numbers) from program memory. The instruction's location (address) in program memory is determined by a program counter (PC), which stores a number that identifies the address of the next instruction to be fetched. After an instruction is fetched, the PC is incremented by the length of the instruction so that it will contain the address of the next instruction in the sequence.[d] Often, the instruction to be fetched must be retrieved from relatively slow memory, causing the CPU to stall while waiting for the instruction to be returned. This issue is largely addressed in modern processors by caches and pipeline architectures (see below).

### Decode

The instruction that the CPU fetches from memory determines what the CPU will do. In the decode step, performed by the circuitry known as the instruction decoder, the instruction is converted into signals that control other parts of the CPU.

### Execute

After the fetch and decode steps, the execute step is performed. Depending on the CPU architecture, this may consist of a single action or a sequence of actions. During each action, various parts of the CPU are electrically connected so they can perform all or part of the desired operation and then the action is completed, typically in response to a clock pulse. Very often the results are written to an internal CPU register for quick access by subsequent instructions. In other cases results may be written to slower, but less expensive and higher capacity main memory.

# Graphics Processing Unit

A graphics processing unit (GPU) is a specialized electronic circuit designed to rapidly manipulate and alter memory to accelerate the creation of images in a frame buffer intended for output to a display device. GPUs are used in embedded systems, mobile phones, personal computers, workstations, and game consoles. Modern GPUs are very efficient at manipulating computer graphics and image processing, and their highly parallel structure makes them more efficient than general-purpose CPUs for algorithms where the processing of large blocks of data is done in parallel. In a personal computer, a GPU can be present on a video card, or it can be embedded on the motherboard or—in certain CPUs—on the CPU die.[1]

## History

### 2000 to 2010

Nvidia was first to produce a chip capable of programmable shading, the GeForce 3 (code named NV20). Each pixel could now be processed by a short "program" that could include additional image textures as inputs, and each geometric vertex could likewise be processed by a short program before it was projected onto the screen. Used in the Xbox console, it competed with the PlayStation 2 (which used a custom vector DSP for hardware accelerated vertex processing; commonly referred to VU0/VU1). The earliest incarnations of shader execution engines used in Xbox were not general purpose and could not execute arbitrary pixel code. Vertices and pixels were processed by different units which had their own resources with pixel shaders having much tighter constraints (being as they are executed at much higher frequencies than with vertices). Pixel shading engines were actually more akin to a highly customizable function block and didn't really "run" a program. Many of these disparities between vertex and pixel shading wouldn't be addressed until much later with the Unified Shader Model.

### 2010 to present

In 2010, Nvidia began a partnership with Audi to power their cars' dashboards. These Tegra GPUs were powering the cars' dashboard, offering increased functionality to cars' navigation and entertainment systems.[44] Advancements in GPU technology in cars has helped push self-driving technology.[45] AMD's Radeon HD 6000 Series cards were released in 2010 and in 2011, AMD released their 6000M Series discrete GPUs to be used in mobile devices.[46] The Kepler line of graphics cards by Nvidia came out in 2012 and were used in the Nvidia's 600 and 700 series cards. A new feature in this new GPU microarchitecture included GPU boost, a technology adjusts the clock-speed of a video card to increase or decrease it according to its power draw.[47] The Kepler microarchitecture was manufactured on the 28 nm process.

## Computational Functions

Modern GPUs use most of their transistors to do calculations related to 3D computer graphics. In addition to the 3D hardware, today's GPUs include basic 2D acceleration and framebuffer capabilities (usually with a VGA compatibility mode). Newer cards like AMD/ATI HD5000-HD7000 even lack 2D acceleration; it has to be emulated by 3D hardware. GPUs were initially used to accelerate the memory-intensive work of texture mapping and rendering polygons, later adding units to accelerate geometric calculations such as the rotation and translation of vertices into different coordinate systems. Recent developments in GPUs include support for programmable shaders which can manipulate vertices and textures with many of the same operations supported by CPUs, oversampling and interpolation techniques to reduce aliasing, and very high-precision color spaces. Because most of these computations involve matrix and vector operations, engineers and scientists have increasingly studied the use of GPUs for non-graphical calculations; they are especially suited to other embarrassingly parallel problems.

## Sales

In 2013, 438.3 million GPUs were shipped globally and the forecast for 2014 was 414.2 million.
