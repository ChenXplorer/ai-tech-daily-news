# 英伟达发布 CUDA Rust：cuda-oxide 与 cutile-rs 两条原生 GPU 内核路径

- 来源：NVIDIA Technical Blog / MarkTechPost
- 链接：https://developer.nvidia.com/blog/introducing-cuda-rust-two-tracks-for-writing-gpu-kernels/
- 发布时间：2026-09-08 20:00 +08:00
- 抓取时间：2026-09-09 07:55 +08:00
- 标签：算力硬件、开发者工具、半导体

英伟达 9 月 8 日技术博客宣布推进 CUDA Rust，使 Rust 可直接编写 GPU 内核。NVlabs 开源两条路径：cuda-oxide 走传统 SIMT，经 Rust MIR、Pliron 与 LLVM 编译到 PTX，目前为早期 alpha，需锁定 nightly；cutile-rs 走 Tile 模型，稳定版 Rust 1.89+ 与 CUDA 13.3，已上架 crates.io，并被 Hugging Face Grout 与 mistral.rs 使用。两者都用所有权规则在编译期拒绝别名类错误。公司称将继续发展与 C++/Python 互操作，成熟周期延续到 2027 年之后。
