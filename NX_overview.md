# 英伟达NX overview

* [Tensor Core vs CUDA Core](https://www.zhihu.com/question/451127498)
* [TRTEXEC](https://docs.nvidia.com/deeplearning/tensorrt/developer-guide/index.html#trtexec)
  * [命令行](https://blog.csdn.net/qq_33120609/article/details/94005196)
    * [延时]((https://blog.csdn.net/qq_29007291/article/details/116135737))
      * tracer.py
      * profiler.py
    * 吞吐量
    * --dumpProfile：show per-layer performance profiles
  * 输出度量
    * Throughput = Total Host Walltime / number of queries
    * Host Latency = H2D Latency + GPU Compute Time + D2H Latency
    * E2E Host Latency
    * Enqueue Time
    * H2D Latency
    * D2H Latency
    * GPU Compute Time
    * Total Host Walltime
    * Total GPU Compute Time