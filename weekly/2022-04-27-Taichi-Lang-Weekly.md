# Taichi-Lang Weekly 

Date：2022-04-27

The Taichi language is an open-source, imperative, parallel programming language for high-performance numerical computation. Here we will update you on its development and community status every Wednesday.

Taichi-Lang Weekly is welcoming contribution from the community. If you spot any issues in our weekly, [file an issue](https://github.com/taichi-dev/community/issues/new) to the [taichi-dev/ community](https://github.com/taichi-dev/community/) repo. If you are interested in contributing to Taichi-Lang, refer to our [Contribution Guidelines](https://github.com/taichi-dev/taichi/blob/master/CONTRIBUTING.md) first.

## **Updates from the Taichi Project**

[26 pull requests ](https://github.com/taichi-dev/taichi/pulls?q=is:pr+is:closed)were merged.

* **Lang**
    * [Add support for keyword arguments](https://github.com/taichi-dev/taichi/pull/4794)
    * [Support in-place operator of ti.Matrix in python scope](https://github.com/taichi-dev/taichi/pull/4799)
    * [Add 2D and 3D rotation functions to math module](https://github.com/taichi-dev/taichi/pull/4822) 
    * [[Error] Show warning when serialize = True is set on a struct for](https://github.com/taichi-dev/taichi/pull/4844) 
    * [[SIMT] Add shfl_down_f32 intrinsic.](https://github.com/taichi-dev/taichi/pull/4819)
    * [[bug] Fix bug that building with TI_EXPORT_CORE:BOOL=ON failed](https://github.com/taichi-dev/taichi/pull/4850)
* **Other**
    * [[CI] Use a new PAT with org permission](https://github.com/taichi-dev/taichi/pull/4826)

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

### **Blogs & upcoming events**

* 2022/04/13 | Tech Blogs 
    * [AST refactoring](https://docs.taichi-lang.org/blog/ast-refactoring)
* 2022/04/20 | Tech Blogs 
    * [Taichi AOT, the solution for deploying kernels in mobile devices](https://docs.taichi-lang.org/blog/taichi-aot-the-solution-for-deploying-kernels-in-mobile-devices)
* 2022/03/09--2022/04/22 | Online | Hackathon 
    * [[Chinese] Taichi x PaddlePaddle Hackathon](https://github.com/taichi-dev/hackathons/issues/4)

