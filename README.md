# Janis Workshop material

This guide contains the workshop material for Janis Portable Pipeline.

This workshop has 2 x 2 hour parts.

## Part 1

Part 1 of this workshop is mostly focused on becoming familliar with Janis in a bioinformatics approach. We'll introduce workflow concepts and use Janis to demonstrate these concepts. Take care to introduce containers, and how we run software using containers.

We'll briefly introduce CWL and WDL, and show how Janis concepts map to generated CWL and WDL. 

We'll introduce [GATK best practices](https://gatk.broadinstitute.org/hc/en-us/articles/360035894711-About-the-GATK-Best-Practices). Discuss some of the limitations, and how we intend to wrap two pipelines:

- [Data pre-processing for variant discovery](https://gatk.broadinstitute.org/hc/en-us/articles/360035535912-Data-pre-processing-for-variant-discovery) ([GitHub](https://github.com/gatk-workflows/gatk4-data-processing))
- [Germline short variant discovery (SNPs + Indels)](https://gatk.broadinstitute.org/hc/en-us/articles/360035535932-Germline-short-variant-discovery-SNPs-Indels-) ([GitHub](https://github.com/gatk-workflows/gatk4-germline-snps-indels))

We'll aim to finish the data pre-processing step in the first workshop.

[> Start here](Part1/1-workshop-intro.md)

## Part 2

- Wrap the germline short variant discovery pipeline in Janis
- Connect the two pipelines
- Discuss resource overrides in Janis.

[> Continue to Part 2 Janis workshop](Part2/1-workshop-intro-part2.md)

## Important Links:

- Janis Documentation: https://janis.readthedocs.io/en/latest
- Janis GitHub: https://github.com/PMCC-BioinformaticsCore/janis
- This workshop GitHub: https://github.com/PMCC-BioinformaticsCore/janis-training
- Gitter: https://gitter.im/janis-pipelines/community
- If you have any feedback regarding this training materials, please create a Github Issue on https://github.com/PMCC-BioinformaticsCore/janis-training/issues
