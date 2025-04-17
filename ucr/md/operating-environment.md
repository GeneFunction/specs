# Operating Environment

The GeneFunction infrastructure provides for the acquisition, distribution, discovery and analysis of biological data.
Currently limited to procaryotes, aspects of the cell are anaylzed:

<aside class="issue" data-number="1" title="eucaryotes?">Would eucaryotes introduce extra requirements by changing the distribution targets?
</aside>

* **genome** - the genes sequenced with e.g. [Sanger](https://en.wikipedia.org/wiki/Sanger_sequencing) or [NextGen Sequencing](https://en.wikipedia.org/wiki/DNA_sequencing#Next-generation_methods) and the resulting sequence, along with any reference genome, are stored and distributed to relevent databases.
* **transcriptome** - formats: FASTQ, Salmon, tsv (Lallisto), GTF/GFF
* **proteome** - mass spectrometry, RNA-seq, [RAMAN](https://en.wikipedia.org/wiki/Raman_spectroscopy)
* **metabalome** - via [FTIR](https://en.wikipedia.org/wiki/Fourier-transform_infrared_spectroscopy)/laser spectroscopy, [RAMAN](https://en.wikipedia.org/wiki/Raman_spectroscopy)

<figure>
<img width="249" alt="" src="op-env.dia.png">
<figcaption>Data Acquisition and Distribution</figcaption>
</figure>

The output of the above analysis is distributed to appropriate public databases to facilitate discovery:

