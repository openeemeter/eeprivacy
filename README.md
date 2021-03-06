eeprivacy
=========

This repository contains the pilot implementation of the core privacy methods for Energy Differential Privacy (EDP). The key components are:

* Core Differential Privacy for energy efficiency analytics (`eeprivacy`)
* Python API documentation for `eeprivacy`
* Sample implementations of key use cases

[Examples and library documentation](https://recurve-inc.github.io/eeprivacy/)

---

Energy Differential Privacy (EDP) enables the use of the gold standard of privacy protection, differential privacy, for high value energy efficiency analytics. 

---

Installation
------------

	pip install eeprivacy

Local Usage
-----------

**Notebooks**

With your preferred notebook environment (like [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/) or [nteract](https://nteract.io/)), install `eeprivacy` and try out any of the [example notebooks](https://recurve-inc.github.io/eeprivacy/private-load-shape-algorithm-design.html). 

**REPL**

	>>> from eeprivacy.mechanisms import LaplaceMechanism
	>>> LaplaceMechanism.execute(value=0, epsilon=0.1, sensitivity=1)
	1.198515653814998


Development
-----------

Build docs:

	./bin/build_docs

Run tests:
	
	./bin/test
