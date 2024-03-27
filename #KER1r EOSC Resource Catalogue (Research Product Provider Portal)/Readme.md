# Description

From: EOSC Core SP: EOSC Catalogue and Marketplace: Research Product Catalogue - EOSC SMS - Wiki EOSC Future

The Research Product Catalogue is a component of the EOSC Catalogue and Marketplace and collects and interlinks metadata records about EOSC research products (including publications, data, and software) and EOSC services (from the Service Catalogue) with authors, communities, organisations, services, funders, and projects. The Research Product Catalogue supports resource onboarding via the EOSC Research Product Provider Dashboard of EOSC research product profiles. Such profiles are automatically collected (harvested) from EOSC data sources onboarded into the Service Catalogue and validated to verify their compliance with EOSC Research Product profile schemas and vocabularies. The Resource Catalogue enables discovery and navigation of EOSC resources and faceted views for statistics.

The catalogue is powered by the OpenAIRE Research Graph resulting from OpenAIRE-Advance.

# Result type

Software and documentation.

# Foreground Identification

| Foreground | IP owner | license|
|------------|----------|--------|
|Updates to the data model of the EOSC Knowledge graph (services) - Knowledge Graph model extension to support the representation of the EOSC Services. URL.: same as url in right-hand column|CNR|[AGPL3.0](https://www.gnu.org/licenses/agpl-3.0.en.html)|
|Deduplication of services and data sources - The software component for the duplicate identification and resolution within the Knowledge Graph was extended to support disambiguation of data sources and services via a machine and human-in-the-loop process. The results are visible from the EOSC marketplace, where data sources appear only once although their metadata is aggregated from several registries (EOSC Service Catalogue, OpenAIRE Graph, OpenDOAR, re3data.org, FAIRSharing.org). URL: same as url in right-hand column. |CNR|[AGPL3.0](https://www.gnu.org/licenses/agpl-3.0.en.html)|
|EOSC Tagging - The process of metadata deduction of the Graph was extended with a configuration to: 1. Support tagging of research products as relevant for EOSC, according to the following criteria: the product was collected from a datasource onboarded in EOSC and compliant to the OpenAIRE Guidelines v3, 4, CRIS, or OpenAIRE2.0 for data. The resulting tagged records are fed to the EOSC Research product catalogue; 2. Support tagging of research products according to the EOSC Interoperability Framework https://graph.openaire.eu/docs/graphproduction-workflow/deduction-and-propagation/bulk-tagging|CNR|[AGPL3.0](https://www.gnu.org/licenses/agpl-3.0.en.html)|
|Mining to find links between publications and EOSC services - Text data mining (TDM) component, incorporated into the Information Inference System, responsible for finding references to EOSC services (identified with URLs) within the fulltexts associated with publications. URL: same as url in right-handcolumn|Athena RC|[Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0)|
|Research Product Catalogue - The collection of metadata records and links in the EOSC Research Product Catalogue https://zenodo.org/records/10488385|OpenAIRE AMKE|[CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.es)|
|Documentation about Research Product Provider Portal - EOSC Research Product Catalogue documentation|CNR|[CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.es)|

# URL to Results

| Foreground | URL|
|------------|----------|
|Updates to the data model of the EOSC Knowledge graph (services) - Knowledge Graph model extension to support the representation of the EOSC Services. URL.: same as url in right-hand column| dhp-schemas project, version 3.17.1, AGPL 3.0, https://coderepo.d4science.org/D-Net/dhp-schemas The extension consists of an update of the configuration of the software components that manage Knowledge Graph software part of the IP Background.|
|Deduplication of services and data sources - The software component for the duplicate identification and resolution within the Knowledge Graph was extended to support disambiguation of data sources and services via a machine and human-in-the-loop process. The results are visible from the EOSC marketplace, where data sources appear only once although their metadata is aggregated from several registries (EOSC Service Catalogue, OpenAIRE Graph, OpenDOAR, re3data.org, FAIRSharing.org). URL: same as url in right-hand column.| dnet-dedup-openaire module within the dnet-hadoop project, version 1.2.5, AGPL3.0, https://code-repo.d4science.org/D-Net/dnet-hadoop The extension consists of an update of the configuration of the softwarecomponents that manage Knowledge Graph software part of the IP Background|
|Mining to find links between publications and EOSC services - Text data mining (TDM) component, incorporated into the Information Inference System, responsible for finding references to EOSC services (identified with URLs) within the fulltexts associated with publications. URL: same as url in right-handcolumn| TDM module is part of the IIS source code repository. Exact module location:https://github.com/openaire/iis/tree/master/iis-wf/iiswfreferenceextraction/src/main/resources/eu/dnetlib/iis/wf/referenceextraction/serviceThe extension consists of an update of the configuration of the softwarecomponents that manage Knowledge Graph software part of the IP Background.|
|Research Product Catalogue - The collection of metadata records and links in the EOSC Research Product Catalogue https://zenodo.org/records/10488385| The data collection of the OpenAIRE Graph is generated and shared every six months via Zenodo.org. The EOSC Research Product Catalogue is the subset of the OpenAIRE Graph products tagged with the label "EOSC".|
|Documentation about Research Product Provider Portal - EOSC Research Product Catalogue documentation| NONE |

# Licensing
See table above in Foreground Identification

# Further information
This software and documentation were produced as part of the EOSC-Future project, financed by the European Union.
The EOSC Future project is co-funded by the European Union Horizon Programme call INFRAEOSC-03-2020 - Grant Agreement Number 101017536

https://eoscfuture.eu/

