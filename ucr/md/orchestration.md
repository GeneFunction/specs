# Orchestration

Orchestration/Worfflow languages define or document the data treatments for:

* **consistency** - every run gets the same treatment
* **portability** - execution can move between platforms
* **parallelization** - make-like semantics define I/O; existence of a file implies readiness as an input.
* **logging** - document treatments for later interpreation of results.

## Languages
* **Cromwell/WDL** - orchestration only - minus: requires 3rd party compilation, plus: type-checking ensures consistency
* **CWL** - 
* **NextFlow** - orchestration + (extensible) runtime. perhaps available on more platforms
  * has resume feature for error recovery
* **Snakemake** - pull-based so perhaps inappropriate since we are not driving the data collection by workflow demand
* **Toil** - steepest learning curve

refs:
[DNA nexus panel](https://20779781.fs1.hubspotusercontent-na1.net/hubfs/20779781/Webinar-Recordings/WDL%20or%20Nextflow%3F%20A%20Roundtable%20Discussion.mp4?__hstc=129364883.be3f10bc868e90b019be849f1caf6f4f.1744575475198.1744575475198.1744575475198.1&__hssc=129364883.2.1744575475199&__hsfp=3833799324&submissionGuid=909bc2d7-80f6-4ede-8f79-958c8fa115f9)(first 20 mins)
[Simple comparison of Snakemake, Nextflow and Cromwell/WDL](https://github.com/grst/snakemake_nextflow_wdl)
[Reddit Q](https://www.reddit.com/r/bioinformatics/comments/a4fq4i/given_the_experience_of_others_writing/)
[nf-core pipelines](https://nf-co.re/pipelines)(in NextFlow)
