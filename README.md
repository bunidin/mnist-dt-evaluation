# Interactive Decision Tree Evaluation over MNIST Dataset
You can explore and interact with the project on the website available at [this link](https://bunidin.github.io/mnist-dt-evaluation/). This Git repository contains the implementation details and source code.

## Project Information
This project is made to understand the concepts presented in my bachelor's thesis "On Interpreting ML Models using Symbolic Languages".

This is an alpha version and may contain bugs.

**<span style="color:red">This tool is by no means necessary to understand the bachelor thesis. It is just an additional tool to deepen your understanding of some concepts.</span>**

## TUTORIAL
1. Pick a binary decision tree (Tree 0, ..., Tree 9).
2. Draw an instance (that would be e.g. a digit).
3. Click on **Classify!** to see how nice you can draw digits ;).
4. Click on **Open Evaluation Menu** and try understanding the decision tree.

## KNOWN ISSUES
- You may need to zoom out.
- The decision trees were trained on thousands of instances, which is still not enough. So you may be drawing digits perfectly but the trees still may not recognize them. Try to understand why using the Evaluation Menu!
- Long Runtime for MinimumCR (Best measured case: 112ms, Worst measured case: 2 minutes).
- Long Runtime for SR for some instances (Average case: 62ms, Worst measured case: 91 seconds).
- We disabled the RFS feature, because we encountered a few issues. This feature will come back soon.
- Coming soon: MaximumCA in the Evaluation Menu!
