# Usage Guide

Once you have eBPF-ProcTrace installed, you can use it to trace process starts across the system. Here's how to use it:

1. **Start the Tracing**:
   Run the Go application you built during installation:
```
./go
```

2. **Observe Traces**:
The application will start tracing process starts. You'll see output detailing information about the processes that are starting.

3. **Customization**:
You can customize the tracing behavior and output by modifying the Go code in the `src/go/` directory.

Remember that eBPF-ProcTrace provides a foundation for process tracing, and you can expand upon it to meet your specific requirements.

For contributing to the project or making improvements, refer to the [contribution guidelines](contributing.md).


