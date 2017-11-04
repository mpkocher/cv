# Curriculum Vitae

[Academic CV](https://github.com/mpkocher/cv/blob/master/academic/cv.pdf) 

[Download PDF](https://github.com/mpkocher/cv/raw/master/academic/cv.pdf)

### Selected Projects

#### Public Projects

- [pbcommand](https://github.com/PacificBiosciences/pbcommand) PacBio core data models, interface to the PacBio Tool Contract for defining pipeline tasks, and web services client to SMRT Link.
- [pbsmrtpipe](https://github.com/PacificBiosciences/pbsmrtpipe) PacBio workflow Engine. Supports file chunking and submission to schedulers, such as SGE and PBS. 
- [CramUnit](https://github.com/mpkocher/CramUnit) Test unit library to call [cram](https://bitheap.org/cram/) and generate jUnit XML for consumption by continuous integration systems, such as jenkins or bamboo.
- [pbcommandR](https://github.com/mpkocher/pbcommandR) R interface to the common models and PacBio Tool Contract Interface
- [pbreports](https://github.com/PacificBiosciences/pbreports) PacBio library for computing metrics and generating Reports used in SMRT Analysis 2.x and SMRT Link.
- [pbcoretools](https://github.com/PacificBiosciences/pbcoretools) PacBio library for commandline tools to interface to PacBio DataSets and standard bioinformatic file formats (e.g., Fasta, Fastq)
- [pymatgen](https://github.com/materialsproject/pymatgen) Computation material science library used to interface to crystal structures and molecules for electronic structure calculations. Core library used the Materials Project.


#### Internal and Misc Projects

- PacBio :: **pysiv** (python) Primary author: Internal Core pipeline testing framework used in SMRT Analysis 2.x. (Replaced by pbsmrtpipe.testkit)
- PacBio :: **[pysiv2](https://github.com/PacificBiosciences/pysiv2)** (python) Primary author, shared with @natecols: Extension of pbsmrtpipe with custom validation leveraging testkit
- PacBio :: **[smrtflow](https://github.com/PacificBiosciences/smrtflow)** (Scala) Primary author, shared with @natecols @smcclellan7 and @skinner.
- PacBio :: **Primary Analysis Engine** (Scala) Maintainer: Internal Primary Analysis orchestration engine (akka + ZMQ) and Web services
- PacBio :: **Data Transfer Services** (Scala) Internal Primary author: data transfer services used in Primary Analysis
- [MaterialsProject](https://materialsproject.org/) :: **rockets** (python) Primary author: Original Workflow engine using by the Materials Project. Was replaced by [fireworks](https://github.com/materialsproject/fireworks)
