# Quick Start

Following is a sequence of operations to familiarize the reader with the tooling necessary to manipulate genetic data files and set them up for trivial machine-learning.

<aside class="todo">
None of this exists yet
</aside>

## Alignment -> Variants.

Create variant file from alignment files and a reference genome.

1. Download sample reference genume `ref.genome` and alignment files to generate a BCF or VCF file
2. Execute
``` sh
bcftools mpileup --threads 16 -C 50 -E -f <ref.genome> -b <bam_list>  > <output.bcf>
```

## Variants -> Training data

1. Download sample variant files
2. Execute training

``` sh
# tesorflow
...
# huggingface
...
# pythorch
...
# llama
...
# LLaMa-factory
...
```

## Wait a week

You've worked hard; drink a really big coffee.

## Load into Ollama
...
