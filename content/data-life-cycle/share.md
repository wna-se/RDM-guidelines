---
title: Sharing phase
contributors: []
toc: True
---

# Sharing
In the era of [FAIR](/topics/fair-principles) (Findable, Accessible, Interoperable and Reusable) and [Open science](https://www.vr.se/english/mandates/open-science/open-access-to-research-data.html), datasets should be made available to the public. Whenever possible, discipline-specific repositories (with or without controlled access) should be used in order to increase the FAIRness of your research outputs. If no such repository is available, there are general purpose repositories.

<a href="/topics/sharing-human-data"><b>See more guidelines on sharing human data <i class="bi bi-arrow-right-square-fill"></i></b></a>
<br/><br/><br/>

  <img class="img-fluid" src="/img/illustrations/repository_overview.png" alt="Repository overview">

&nbsp;&nbsp;

Click on the buttons below for data type specific information regarding suitable repositories.

<p>
  <a class="btn btn-primary" data-bs-toggle="collapse" href="#collapseExample1" role="button" aria-expanded="false" aria-controls="collapseExample1">
    Genomics data
  </a>
</p>
<div class="collapse" id="collapseExample1">
  <div class="card card-body">
  <span>
  <h5> <a href="https://www.ebi.ac.uk/ena">ENA</a> (European Nucleotide Archive)</h5>
  The ENA hosts an instance of the Sequence Read Archive (SRA), the same archive that exists on NCBI. SRA accepts raw sequence data from any sequencing platform, generated in any research project. There are several ways to <a href="https://www.ebi.ac.uk/ena/submit">submit</a> data to ENA, for more information see the <a href="https://ena-docs.readthedocs.io/en/latest/">documentation</a>. We also recommend the <a href="https://covid19dataportal.se/support_services/tutorial_ena/tutorial_ena_intro/">Tutorial for SARS-CoV-2 genome data submission to ENA</a> found on the Swedish Covid-19 Data Portal. <br><br> For convenience, we have created templates for the most frequent data types and their corresponding <a href="https://www.ebi.ac.uk/ena/browser/checklists">ENA checklists</a>. The templates come with instructions on how to do an interactive submission, via the ENA Webin Portal, but even when doing a programmatic submission, the template can be useful for collecting all necessary descriptions / metadata.  Download an appropriate template, and fill in the sheets according to the instructions in the template:
  <ul>
    <li><a href="/meta-data-templates/metadata_template_default_ERC000011.xlsx">ERC000011 ENA default sample checklist</a></li>
    <li><a href="/meta-data-templates/metadata_template_virus_ERC000033.xlsx">ERC000033 ENA virus pathogen reporting standard checklist</a></li>
    <li><a href="/meta-data-templates/metadata_template_sewage_ERC000036.xlsx">ERC000036 ENA sewage checklist</a></li>
  </ul>

  <h5> <a href="https://www.ebi.ac.uk/arrayexpress/">ArrayExpress</a></h5>
  ArrayExpress is tighty integrated with ENA and similar to NCBI’s Gene Expression Omnibus database it can be used to archive experimental designs and analysis files based on the raw sequence reads. ArrayExpress has its own <a href="https://www.ebi.ac.uk/arrayexpress/submit/overview.html">submission portal</a> where information is available on what can be submitted and how.<br><br>

  <h5> <a href="https://ega-archive.org/">European Genome-phenome Archive</a></h5>
  This is a service for sharing personally identifiable genetic and phenotypic data resulting from biomedical research projects. The repository is hosted by the European Bioinformatics Institute (EMBL-EBI) and the Centre for Genomic Regulation (CRG). Any data submitted to the repository is subject to controlled access, which means that access to the data only will be granted after a formal application procedure.

  <h5> <a href="https://fega.nbis.se/">FEGA Sweden</a></h5>
  This is a repository for storing and sharing personal identifiable genetic and phenotypic data in Sweden in a way that meets the requirements of the General Data Protection Regulation (GDPR). It is part of a federation of national nodes, <a href="https://ega-archive.org/federated">Federated European Genome-phenome Archive</a>, which is tightly connected to the European Genome-phenome Archive (EGA). FEGA Sweden is not yet operational, but researchers may express their interest in depositing data to the repository by filling in <a href="https://nbis.se/support/supportform/index.php#sdaform">a web form</a>.

  </span>
  </div>
</div>

<p>
  <a class="btn btn-primary" data-bs-toggle="collapse" href="#collapseExample2" role="button" aria-expanded="false" aria-controls="collapseExample2">
    Imaging data
  </a>
</p>
<div class="collapse" id="collapseExample2">
  <div class="card card-body">
  <span>
  Depending on the type of image data you have, different public repositories are available, please see the table at <a href="https://www.ebi.ac.uk/bioimage-archive/">BioImage Archive</a>.
  </span>
  </div>
</div>

<p>
  <a class="btn btn-primary" data-bs-toggle="collapse" href="#collapseExample3" role="button" aria-expanded="false" aria-controls="collapseExample3">
    Metabolomics data
  </a>
</p>
<div class="collapse" id="collapseExample3">
  <div class="card card-body">
  <span>
  <a href="https://www.ebi.ac.uk/metabolights/">MetaboLights</a> is a database for Metabolomics experiments and derived information. The database is cross-species, cross-technique and covers metabolite structures and their reference spectra as well as their biological roles, locations and concentrations, and experimental data from metabolic experiments.
  </span>
  </div>
</div>

<p>
  <a class="btn btn-primary" data-bs-toggle="collapse" href="#collapseExample4" role="button" aria-expanded="false" aria-controls="collapseExample4">
    Proteomics data
  </a>
</p>
<div class="collapse" id="collapseExample4">
  <div class="card card-body">
  <span>
  The <a href="http://www.proteomexchange.org/">ProteomeXchange</a> Consortium provides globally coordinated standard data submission and dissemination pipelines involving the main proteomics repositories:
  <ul>
    <li> <a href="https://www.ebi.ac.uk/pride/">PRIDE</a> - admits protein and peptide identification/quantification data with the accompanying mass spectra evidence and any other related data types. Submission is done using the <a href="https://www.ebi.ac.uk/pride/markdownpage/pridesubmissiontool">PX Submission Tool</a>, see <a href="https://www.ebi.ac.uk/pride/static/markdown/submitdatapage/files/Submission_Tutorial.pdf">tutorial</a>.</li>
    <li><a href="http://www.peptideatlas.org/">PeptideAtlas</a> - for SRM/MRM data that does not fit into PRIDE (targeted datasets). Submission is done via <a href="http://www.peptideatlas.org/passel/">PASSEL</a>.</li>
  </ul>
  </span>
  </div>
</div>

<p>
  <a class="btn btn-primary" data-bs-toggle="collapse" href="#collapseExample5" role="button" aria-expanded="false" aria-controls="collapseExample5">
    Other repositories
  </a>
</p>
<div class="collapse" id="collapseExample5">
  <div class="card card-body">
  <span>
  For other domain-specific repositories, see e.g. <a href="https://elixir-europe.org/services/tag/elixir-deposition-databases">ELIXIR Deposition databases</a>, <a href="https://www.nature.com/sdata/policies/repositories">Scientific Data recommended repositories</a>, <a href="https://www.ebi.ac.uk/submission/">EBI archive wizard</a> (help to find the right repository depending on data type), or <a href="https://fairsharing.org/databases/">FAIRsharing</a> (the latter can also assist in finding metadata standards suitable for describing your datasets). For datasets that do not fit into domain-specific repositories, use a general repository e.g. <a href="https://www.scilifelab.se/data/repository/">SciLifeLab Data Repository</a>, <a href="https://figshare.com/">Figshare</a> and <a href="https://zenodo.org/">Zenodo</a>.

  <!--Zenodo
  : [Zenodo](https://zenodo.org) is a general-purpose repository operated by CERN. It can be used for sharing basically any kind of data, but also for just describing data stored elsewhere. Zenodo doesn't enforce standardised descriptions of data, so datasets described there might be more difficult to find than those described in the two repositories mentioned above.-->

  </span>
  </div>
</div>

&nbsp;
## How can SciLifeLab help you sharing data?

If you are a researcher at a Swedish academic institution working in the life sciences, you can get help from SciLifeLab Data Management support team. This support team can help you describe and deposit your data. Here are a few examples of the support that is offered:

* Plan data submission
* Identify suitable repositories
* Assist during the submission process when publishing data and code
* Assist in the creation of metadata records in SciLifeLab Data Repository
* Advice on what needs to be done when working with sensitive human data
* Advice on describing data with proper metadata

If you need any help connected to data submission, please [contact us](../../contact/)!

## Resources
* [RDMkit on Sharing Data](https://rdmkit.elixir-europe.org/sharing)
* [RDMkit on Data publication](https://rdmkit.elixir-europe.org/data_publication)
* [The Swedish Covid-19 Data Portal on Sharing Data](https://covid19dataportal.se/share-data/)
* [Data publication module](https://nbisweden.github.io/module-data-publication-dm-practices/) in course [Introduction to data management practices](https://uppsala.instructure.com/courses/48087/pages/introduction-to-data-management-practices)
* Many of the repositories at EBI have instructive videos on how to do submission as well as documentation, have a look at their [YouTube playlist](https://www.youtube.com/playlist?list=PL67E0627174F36FCF).
