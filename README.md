# pyiron Demonstration for Platform Material Digital

[![Pipeline](https://github.com/pyiron-dev/materialdigital/actions/workflows/pipeline.yml/badge.svg)](https://github.com/pyiron-dev/materialdigital/actions/workflows/pipeline.yml)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/pyiron-dev/materialdigital/HEAD)

Based on the [NFDI4Ing Workflow Benchmark](https://github.com/BAMresearch/NFDI4IngScientificWorkflowRequirements) we demonstrate the interoperability of three different pyiron versions, namely:
* [pyiron_base](https://github.com/pyiron/pyiron_base) - The classical pyiron workflow framework has been extended for functional programming, by introducing a `@job` decorator. The `pyiron_base` package is recommended for projects from the previous funding periods of the Platform Material Digital who are already familiar with the classical pyiron workflow framework. 
* [pyiron_workflow](https://github.com/pyiron/pyiron_workflow/) - Based on the feedback from the previous funding periods of the Platform Material Digital we introduced `pyiron_workflow` as functional workflow environment. `pyiron_workflow` provides a visual programming interface to simplify the use and development of workflows for non technical users.
* [executorlib](https://github.com/pyiron/executorlib) - `executorlib` is designed as minimal extension to the Python programming language to introduce workflow capabilities without changing the Python syntax, it is consequently the optimal solution for users already experienced with the Python programming language, as it simply extends the `concurrent.futures.Executor` interface from the standard library.

Demonstration: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/pyiron-dev/materialdigital/HEAD)

The [NFDI4Ing Workflow Benchmark](https://github.com/BAMresearch/NFDI4IngScientificWorkflowRequirements) is implemented with each of the workflow frameworks, stored in the [Python Workflow Definition](https://github.com/pythonworkflow) and afterwards reloaded with the other two frameworks. This highlights the interoperability of the workflow frameworks developed as part of the [pyiron project](https://pyiron.org). 
