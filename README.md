# Research Project Template

***Research project template*** is a directory configuration template for making your research project reproducible and transparent to everyone.

## Directory Configuration
Any research project is assumed to propose an answer to a question. This repository is used to record every process to reach the answer to the question in a reproducible manner to everyone.

A `research-project/` is composed of three sub-directories: `hypothesis-generation/`, `hypothesis-testing/`, and `manuscript/`.

### `hypothesis-generation/`
`hypothesis-generation/` is a directory to record the process to generate a hypothesis from a question. What and how the question is came up with is recorded in `hypothesis-generation/question/`. Similarly, why and what hypothesis is proposed is described in `hypothesis-generation/hypothesis/`.

### `hypothesis-testing/`
`hypothesis-testing/` is a directory to place the directories related to test the hypothesis. The experimental design is described in `hypothesis-testing/design/`. The codes for experiments are stored in `hypothesis-testing/experiment/`. Then, the results from the experiment are analyzed in `hypothesis-testing/analysis/`.

### `manuscript/`
`manuscript/` is a directory to place a manuscript for submission. LaTex code and necessary files to compile it are in `manuscript/latex`.

#### NOTE
* A hypothesis is usually refined again and again through reading a bunch of literature. Thus, it might be better to add the intermediate directory  `hypothesis-generation/hypotheses/` and add a directory for each hypothesis like `hypothesis-generation/hypotheses/hypothesis-1/`.

* Multiple experiments are usually performed. Hence, creating subdirectories for each experiment may be more readable. 