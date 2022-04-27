# Taichi-Lang Weekly 

Date：2022-04-13

The Taichi language is an open-source, imperative, parallel programming language for high-performance numerical computation. Here we will update you on its development and community status every Wednesday.

Taichi-Lang Weekly is welcoming contribution from the community. If you spot any issues in our weekly, [file an issue](https://github.com/taichi-dev/community/issues/new) to the [taichi-dev/ community](https://github.com/taichi-dev/community/) repo. If you are interested in contributing to Taichi-Lang, refer to our [Contribution Guidelines](https://github.com/taichi-dev/taichi/blob/master/CONTRIBUTING.md) first.

## **Updates from the Taichi Project**

[37 pull requests ](https://github.com/taichi-dev/taichi/pulls?q=is:pr+is:closed)were merged.

* **Lang**
    * [Let assertion error message support f-string](https://github.com/taichi-dev/taichi/pull/4700)
* **Doc**
    * [Change License from MIT to Apache-2.0](https://github.com/taichi-dev/taichi/pull/4701)
    * [Fix deprecated tools APIs in docs, tests, and examples](https://github.com/taichi-dev/taichi/pull/4729)
    * [Update docstring for module misc](https://github.com/taichi-dev/taichi/pull/4644)
* **Bug fixes**
    * [Fix ndrange when start > end](https://github.com/taichi-dev/taichi/pull/4690)
    * [Fix chain assignment](https://github.com/taichi-dev/taichi/pull/4695)
    * [Fix bugs in test_offline_cache.py](https://github.com/taichi-dev/taichi/pull/4674)
* **CI**
    * [Switch to self-hosted PyPI for nightly release](https://github.com/taichi-dev/taichi/pull/4706)
    * [[windows] Add Dockerfile for Windows build and test (CPU)](https://github.com/taichi-dev/taichi/pull/4667)
* **Simt**
    * [Add shfl_sync_i32/f32 warp intrinsics ](https://github.com/taichi-dev/taichi/pull/4643)
    * [Subgroup reduction primitives](https://github.com/taichi-dev/taichi/pull/4643)
* **Misc**
    * [Add compile-config to offline-cache key ](https://github.com/taichi-dev/taichi/pull/4685)
    * [Update Linux version name](https://github.com/taichi-dev/taichi/pull/4685)
    * [Temporarily disable a flaky test](https://github.com/taichi-dev/taichi/pull/4669)
* **Others**
    * [[build] Fix nonx64 Linux builds](https://github.com/taichi-dev/taichi/pull/4715)
    * [[gui] Make GGUI VBO configurable for mesh](https://github.com/taichi-dev/taichi/pull/4707)
    * [[metal] Tweak Device to support Ndarray](https://github.com/taichi-dev/taichi/pull/4721)
    * [[refactor] Remove legacy usage of ext_arr/any_arr in codebase](https://github.com/taichi-dev/taichi/pull/4698)
    * [[spirv] Ext arr name should include arg id](https://github.com/taichi-dev/taichi/pull/4727)
### **Find more tracking** [issues ](https://github.com/taichi-dev/taichi/issues?q=is:issue+is:open+)**&**[ PRs ](https://github.com/taichi-dev/taichi/pulls?q=is:pr+is:open+)

- To track existing issues, please click [here](https://github.com/taichi-dev/taichi/issues?q=is:issue+is:open+).
- To track PRs, please click [here](https://github.com/taichi-dev/taichi/pulls?q=is:pr+is:open+).

### **Discussion**

Alex from the Rust community raised a discussion about C API. According to k-ye, Taichi plans to provide C APIs for [AOT](https://github.com/taichi-dev/taichi/issues/3642) first. This will allow developers to use compiled Taichi kernels in non-Python environments. 

If you are interested in this topic, please check out [this thread](https://github.com/taichi-dev/taichi/discussions/4679).

### [RFCs ](https://github.com/taichi-dev/taichi/issues?q=is:open+is:issue+label:RFC)

We'd like to share our ideas on how to implement features in Taichi through the [RFC](https://github.com/taichi-dev/taichi/blob/master/docs/rfcs/20220410-rfc-process.md) mechanism.

Welcome to join discussions in the RFCs with the [active] tag.

* [[active] Add CUDA warp-level intrinsics to Taichi](https://github.com/taichi-dev/taichi/issues/4631)
* [[active] Support of TI_EXPORT to control public API visibility](https://github.com/taichi-dev/taichi/issues/4097)
* [[active] Standardizing Taichi Error Types](https://github.com/taichi-dev/taichi/issues/3938)
* [[active] Taichi Language Reference](https://github.com/taichi-dev/taichi/issues/4602)
* [Python frontend API cleanup](https://github.com/taichi-dev/taichi/issues/3782)
* [Taichi on Javascript](https://github.com/taichi-dev/taichi/issues/3781)
* [Cross compile taichi_core.so to other targets](https://github.com/taichi-dev/taichi/issues/3679)
* [Taichi's Ahead of Time (AOT) Module](https://github.com/taichi-dev/taichi/issues/3642)
## **Updates from the community**

### **New contributors**

Welcome new Taichi contributors. Thanks for making Taichi better!

- @[DongqiShen](https://github.com/DongqiShen) updated the **examples** directory.[ Pull Request #4640](https://github.com/taichi-dev/taichi/pull/4640)
- @[Trinkle23897](https://github.com/Trinkle23897) fixed four typos in doc. [Pull Request #4714](https://github.com/taichi-dev/taichi/pull/4714)
- @[varinic](https://github.com/varinic) added shfl_xor_i32 warp intrinsics for CUDA backend. [Pull Request #4719](https://github.com/taichi-dev/taichi/pull/4719)

### **Call for participation**

In this section, we highlight tasks from Taichi-Lang projects.

Tags with [good first issue](https://github.com/taichi-dev/taichi/issues?q=is%3Aopen+is%3Aissue+label%3A%22good+first+issue%22) and [welcome contribution](https://github.com/taichi-dev/taichi/issues?q=is%3Aopen+is%3Aissue+label%3A%22welcome+contribution%22) are suitable for beginners. 

### **Blogs & upcoming events**

* 2022/03/26 | Tech Blogs 
    * [Taichi & Torch 02: Data containers in Torch & Taichi](https://docs.taichi-lang.org/blog/Taichi-torch-data-containers)
* 2022/03/18 | Tech Blogs 
    * [Taichi & Torch 01: Resemblances and Differences ](https://docs.taichi-lang.org/blog/Taichi-torch-resemblances-differences)
* 2022/03/09--2022/04/22 | Online | Hackathon 
    * [[Chinese] Taichi x PaddlePaddle Hackathon](https://github.com/taichi-dev/hackathons/issues/4)
