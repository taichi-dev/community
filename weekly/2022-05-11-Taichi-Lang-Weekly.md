# Taichi-Lang Weekly 

Date：2022-05-11

The Taichi language is an open-source, imperative, parallel programming language for high-performance numerical computation. Here we will update you on its development and community status every Wednesday.

Taichi-Lang Weekly is welcoming contribution from the community. If you spot any issues in our weekly, [file an issue](https://github.com/taichi-dev/community/issues/new) to the [taichi-dev/ community](https://github.com/taichi-dev/community/) repo. If you are interested in contributing to Taichi-Lang, refer to our [Contribution Guidelines](https://github.com/taichi-dev/taichi/blob/master/CONTRIBUTING.md) first.

## **Updates from the Taichi Project**

[30 pull requests ](https://github.com/taichi-dev/taichi/pulls?q=is:pr+is:closed)were merged.

* **Lang**
    * [Add more functions to math module](https://github.com/taichi-dev/taichi/pull/4939)
    * [Improved error messages for illegal slicing or indexing to ti.field](https://github.com/taichi-dev/taichi/pull/4873)
* **Doc**
    * [Updated relative path](https://github.com/taichi-dev/taichi/pull/4929)    
* **SIMT**
    * [Add activemask warp intrinsics](https://github.com/taichi-dev/taichi/pull/4918)    
    * [Add syncwarp warp intrinsics](https://github.com/taichi-dev/taichi/pull/4917)
    * [Add uni_sync warp intrinsics](https://github.com/taichi-dev/taichi/pull/4927)   

* **Other**
    * [[Build] Improved building on Windows](https://github.com/taichi-dev/taichi/pull/4925)
    * [[refactor] Add ArrayMetadata to store the array runtime size](https://github.com/taichi-dev/taichi/pull/4950)
    * [[refactor] Simplify Matrix's initializer](https://github.com/taichi-dev/taichi/pull/4923)


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

### **New contributors**

Welcome new Taichi contributors. Thanks for making Taichi better!

- @[Mike-Leo-Smith](https://github.com/Mike-Leo-Smith) optimized the MPM kernels on CUDA.[Pull request #7](https://github.com/taichi-dev/taichi_benchmark/pull/7)
- @[axmmisaka](https://github.com/axmmisaka) fixed trailing slash removal logic.[Pull request #99](https://github.com/taichi-dev/taichi_elements/pull/99)

### **Call for participation**

In this section, we highlight tasks from Taichi-Lang projects.

Tags with [good first issue](https://github.com/taichi-dev/taichi/issues?q=is%3Aopen+is%3Aissue+label%3A%22good+first+issue%22) and [welcome contribution](https://github.com/taichi-dev/taichi/issues?q=is%3Aopen+is%3Aissue+label%3A%22welcome+contribution%22) are suitable for beginners. 

### **Blogs & upcoming events**

* 2022/05/06 | Tech Blogs 
    * [Is Taichi Lang comparable to or even faster than CUDA?](https://docs.taichi-lang.org/blog/is-taichi-lang-comparable-to-or-even-faster-than-cuda)
* 2022/03/09--2022/04/22 | Online | Hackathon 
    * [UNLEASH CREATIVITY WITH VOXEL 2022](https://github.com/taichi-dev/community/blob/main/events/voxel-challenge/README.md)

