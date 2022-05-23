# Taichi-Lang Weekly 

Date：2022-05-05

The Taichi language is an open-source, imperative, parallel programming language for high-performance numerical computation. Here we will update you on its development and community status every Wednesday.

Taichi-Lang Weekly is welcoming contribution from the community. If you spot any issues in our weekly, [file an issue](https://github.com/taichi-dev/community/issues/new) to the [taichi-dev/community](https://github.com/taichi-dev/community/) repo. If you are interested in contributing to Taichi-Lang, refer to our [Contribution Guidelines](https://github.com/taichi-dev/taichi/blob/master/CONTRIBUTING.md) first.

## **Updates from the Taichi Project**

[22 pull requests ](https://github.com/taichi-dev/taichi/pulls?q=is:pr+is:closed)were merged.

* **Lang**
    * [[test] Copy-free interaction between Taichi and PaddlePaddle](https://github.com/taichi-dev/taichi/pull/4886)
    * [[error] Improved error messages for illegal slicing or indexing to ti.field](https://github.com/taichi-dev/taichi/pull/4873)

* **Build**
    * [[refactor] Define Cmake OpenGL runtime target](https://github.com/taichi-dev/taichi/pull/4887)
    * [[refactor] Use keywords instead of plain target_link_libraries CMake](https://github.com/taichi-dev/taichi/pull/4864)
* **Doc**
    * [Add limitation about TLS optimization](https://github.com/taichi-dev/taichi/pull/4877)
* **Other**
    * [[aot] [vulkan] Expose symbols for AOT](https://github.com/taichi-dev/taichi/pull/4879)
    * [[ci] Add libtaichi_export_core build for desktop in CI](https://github.com/taichi-dev/taichi/pull/4871)
    * [[metal] Complete Device API](https://github.com/taichi-dev/taichi/pull/4862)


### **Find more tracking** [issues ](https://github.com/taichi-dev/taichi/issues?q=is:issue+is:open+)**&**[ PRs ](https://github.com/taichi-dev/taichi/pulls?q=is:pr+is:open+)

- To track existing issues, please click [here](https://github.com/taichi-dev/taichi/issues?q=is:issue+is:open+).
- To track PRs, please click [here](https://github.com/taichi-dev/taichi/pulls?q=is:pr+is:open+).

### **Discussion**

* [Possible Julia front-end?](https://github.com/taichi-dev/taichi/discussions/4849) 
* [Use MIR provide a basis to implement fast and lightweight interpreters and JITs.](https://github.com/taichi-dev/taichi/discussions/4820) 

### [RFCs ](https://github.com/taichi-dev/taichi/issues?q=is:open+is:issue+label:RFC)

We'd like to share our ideas on how to implement features in Taichi through the [RFC](https://github.com/taichi-dev/taichi/blob/master/docs/rfcs/20220410-rfc-process.md) mechanism.

Welcome to join discussions in the RFCs with the [active] tag.

* [[active] Semi-formal Unified Device API specification](https://github.com/taichi-dev/taichi/issues/4851)
* [[active] Add CUDA warp-level intrinsics to Taichi](https://github.com/taichi-dev/taichi/issues/4631)
* [[active] Support of TI_EXPORT to control public API visibility](https://github.com/taichi-dev/taichi/issues/4097)
* [[active] Standardizing Taichi Error Types](https://github.com/taichi-dev/taichi/issues/3938)
* [Taichi on Javascript](https://github.com/taichi-dev/taichi/issues/3781)
* [Cross compile taichi_core.so to other targets](https://github.com/taichi-dev/taichi/issues/3679)
* [Taichi's Ahead of Time (AOT) Module](https://github.com/taichi-dev/taichi/issues/3642)
* [Python frontend API cleanup](https://github.com/taichi-dev/taichi/issues/3782)

## **Updates from the community**

### **Call for participation**

In this section, we highlight tasks from Taichi-Lang projects.

Tags with [good first issue](https://github.com/taichi-dev/taichi/issues?q=is%3Aopen+is%3Aissue+label%3A%22good+first+issue%22) and [welcome contribution](https://github.com/taichi-dev/taichi/issues?q=is%3Aopen+is%3Aissue+label%3A%22welcome+contribution%22) are suitable for beginners. 

### **Others**
- @[0xzhang](https://github.com/0xzhang) made a copy-free interaction between Taichi and PaddlePaddle, referring to the implementation of PyTorch in Taichi. [Click here for more details](https://github.com/taichi-dev/taichi/pull/4886).

### **Blogs & upcoming events**

* 2022/04/29--2022/05/25 | Online | Events 
    * [UNLEASH CREATIVITY WITH VOXEL 2022](https://github.com/taichi-dev/community/blob/main/events/voxel-challenge/README.md)
* 2022/04/20 | Tech Blogs 
    * [Taichi AOT, the solution for deploying kernels in mobile devices](https://docs.taichi-lang.org/blog/taichi-aot-the-solution-for-deploying-kernels-in-mobile-devices)

