

# Autotuning on the Rust Language

-   Rust is compiled by LLVM
-   Rust compilation is slow (references)
-   First idea:
    -   Search space:
        -   LLVM Passes and Pass parameters (flags)
        -   rustc passes and parameters (flags)
    -   Metrics:
        -   Decreasing the compilation time for Rust code
        -   Speedup Rust code
        -   Memory usage (not now?)
-   LLVM Passes:
    -   <https://llvm.org/docs/Passes.html>
    -   <https://github.com/phrb/generate-llvm-pass-list>
-   MIR could help generate an LLVM IR that is easier to optimize:
    -   How to measure if the IR is easier to optimize?
    -   How to optimize MIR?
    -   What are the parameters?


## Some Papers About Rust (Don't spend too much time here.)

-   <https://dl.acm.org/doi/pdf/10.1145/3124680.3124717>
-   <https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=6650903>
-   <https://dl.acm.org/doi/pdf/10.1145/3102980.3103006>
-   <https://dl.acm.org/doi/pdf/10.1145/3241624.2926707>
-   <https://arxiv.org/pdf/1505.07383.pdf>
-   <https://pdfs.semanticscholar.org/fb4e/67cd96b84723324a49f398579da09b785913.pdf>
-   <https://dl.acm.org/doi/pdf/10.1145/3009837.3009867>
-   <https://storage.googleapis.com/pub-tools-public-publication-data/pdf/1c082b766d8e14b54e36e37c9fc3ebbe8b4a72dd.pdf>
-   <https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7163218>
-   <https://dl.acm.org/doi/pdf/10.1145/2889160.2889229>
