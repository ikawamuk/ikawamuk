# ikawamuk


## Project Experience
### Web server software refer to nginx
- Period:2026/4 ~ 2026/6
- Technologies:C++
- Description:
	- Summary:A collaborative project (team of 2) to develop a high-performance HTTP/1.1 web server using C++98 and event-driven I/O.
	- Objective and Approaches:
		- Designed and implemented a robust HTTP request parser using a state machine to handle fragmented or large payloads efficiently.
		- Utilized I/O multiplexing (epoll/kqueue) to manage multiple concurrent client connections without blocking.
		- Ensured strict RFC compliance for header validation and chunked transfer encoding.

### Reimplementing a C compiler
- Period:2026/1 ~
- Technologies:C
- Description:
	- Summary:Developing a self-hosting C compiler that targets x86-64 assembly, focusing on understanding language internals and code generation.
	- Objective and Approaches:
		- Implemented a recursive descent parser to construct Abstract Syntax Trees (AST) from C source code.
		- Managed stack frame allocation and local variable scoping for x86-64 Linux environments.
		- Developed a code generator that converts AST nodes into assembly instructions, supporting arithmetic, control flow, and system calls.

### inplementing Quine
- Period:2026/2
- Technologies:C
- Description:
	- Summary:A deep dive into the concept of self-replicating programs (Quines) to explore the limits of source code and execution.
	- Objective and Approaches:
		- Researched and implemented the mathematical logic of self-replication without using external file I/O.
		- Explored the use of ASCII character codes and formatting strings to allow a program to output its own source code exactly.

### 3D renderer using path tracing
- Period:2025/12 ~ 2026/3
- Technologies:C
- Description:
	- Summary:A collaborative engine (team of 2) for rendering 3D scenes using raytracing and light transport simulation.
	- Objective and Approaches:
		- Designed and implemented the core light transport system, including Phong reflection models and shadow calculation.
		- Developed geometric intersection algorithms for primitives like spheres, cylinders, and triangles using vector calculus.
		- Achieved realistic visual effects through ray-object interaction and material properties.

### Simple Shell Implementation
- Period:2025/8 ~ 2025/10
- Technologies:C
- Description:
	- Summary:A collaborative development of a Bash-compatible command-line interpreter to understand process management and signals.
	- Objective and Approaches:
		- Implemented process control logic using fork, execve, and waitpid.
		- Developed features for pipelines (|) and redirections (>, >>, <), managing file descriptors and inter-process communication.
		- Handled environment variables and built-in commands while maintaining robust signal handling (e.g., Ctrl-C, Ctrl-D).

### Reimplementing libc
- Period:2025/4
- Technologies:C
- Description:
	- Summary:A foundational project to reimplement standard C library functions to master memory manipulation and pointer arithmetic.
	- Objective and Approaches:
		- Rewrote essential functions from <string.h> and <stdlib.h> without using existing libraries.
		- Focused on manual memory management and edge-case handling for functions like malloc (simulated) and string utilities.

etc...

## Educations
### 42Tokyo | 2025/4~
1. Fundamentals of computer science learned through hands-on development
I learned about computer resource management, data structures, and algorithms through practice by developing shells and web servers from scratch, calling system calls directly.
2. Experience in code review and team development
Through peer reviews and team development projects, I acquired foundational skills ranging from the upstream to downstream of software development, focusing on source code readability and clear software design. I also gained essential skills for team development using Git and GitHub.
3. Self-reliance in environments without instructors
By starting development with only specifications provided, I gained experience in conducting research, defining requirements, designing, implementing, testing, and managing schedules independently.