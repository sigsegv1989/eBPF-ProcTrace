# Installation Guide

To get started with eBPF-ProcTrace, follow these installation steps:

1. **Prerequisites**:
   - Ensure you're running a Linux kernel version that supports eBPF.
   - Install the necessary development tools, such as `clang` and `llvm`.

2. **Clone the Repository**:
```
git clone https://github.com/sigsegv1989/eBPF-ProcTrace.git
cd eBPF-ProcTrace
```

3. **Build eBPF Programs**:
Navigate to the `src/bpf/` directory and use the provided Makefile to build the eBPF programs:
```
cd src/bpf/
make
```

4. **Set Up the Go Application**:
Navigate to the `src/go/` directory and build the Go application:
```
cd ../go/
go build
```


5. **Run the Application**:
Run the Go application to start process tracing:
```
./go
```

For detailed usage instructions, refer to the [usage documentation](usage.md).
