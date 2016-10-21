# intro: me
* round table

# Frictionless data: Jo Barratt
* were OKF now OKI(nternational), NGO
* founded in 2004: Rufus Pollock
* UK-based, but team globally distributed
* vision for open knowledge
* mission
    1. open up *all* public interest information
	2. how to get that data used and useful to drive change
* build communities + tools
* use cases
    1. school of data: courses to get people to use data
	2. ckan.org
	3. openspending: publish govt budget and spend data worldwide
	4. opentrials: linked data for global clinical trials
* £4M in 15mins
    * barriers to the movement of data within and without institutions/organizations
	* 2010 govt began publishing spending data, transactional level, publish at monthly level
	* 3.5yrs later: one dept buys a marketing report; how to find out if other departments are doing the same thing?
	* govt external organization (infomediary): aggregates dept csv files, simple search to establish high level of duplication
* key notion here is comparability (?)
* the best idea for your data will be thought of by someone else
* logistics for goods, e.g. phone:
    * many sources of friction in production chain
	* not forgetting the challenges in the data workflow
* sources of friction:
    * legal barriers
	* data quality
	* ineroperability
	* hard to find
	* no tool integration
* UK spend publishing dashboard: uk-25k.datadashboards.io
* case study: shipping
    * April 1956, first use of shipping containers
	* impact of containerization... but not getting the point
	* analogy: data containerization... data packages
	* lightweight containerization based on JSON
	* decouple publisher from consumer
* key principles
    * simplicity
	* web oriented
	* existing tools
	* open
	* distributed
* tabular data packages: data package; JSON table scheme
* good tables service: data source validation; works with streams
* data packagist: for new data package definition
* want to work with academics, run pilots, develop tools
* Alex Clarke: bagit?
* overlap with ODI and W3C
* ODI will manage some of OKI libraries

# HDF5: Daniel

# MySQL: Sukumar

# RDF: me

# APAtSCHE: Bruce

# R: Sukumar

# Metadata: Alex Ball
* Dublin core: took 4 years of discussion to get agreement and 3 more years to establish standard comprising 15 elements
* context determines whether something is data or metadata
* example: internet traffic... URLs, timestamps, IP addresses, etc.
* Petraeus case: the metadata was the data (context)
* metadata defined by what you are using it for:
    * reference = known resource
	* descriptive = speculative search
	* provenance = assessing athenticity/trustworthiness
	* contextual = external undertanding of a resource
	* rights = securing data
	* packaging = component arrangement (e.g. bagit, OKF containers, xfdu)
	* fixity ? checking integrity = checksums
	* structural
	* semantic
* but what matters to us?
    * discovery metadata - how others find your data
	* contextual metadata - funder, institution
	* discipline-specific metadata - how you and others can use your data
* example web sites
    * NERC
	* INSPIRE geoportal
	* geospatial data: ISO 19115, ISO 19139; different data sets conformed to a common profile
	* cessda: European social science data
* datacite metadata schema
* metadata for (data) reuse
    * well documented data allows work to be repeated, can a peer understand it, can a peer replicate results, defend work to reviewer, still makes sense in 10 years
	* basic-level: readme files comprising
	    * methodology
		* third-party inputs
		* workflow
		* outputs
		* file structure + conventions
		* plus file inventory, citation info, licence info, relationships
* DDI codebook: http://www.ddialliance.org/Specification/DDI-Codebook/2.5 is accepted standard for survey data
* Tools: Easy DDI organizer, HASSET, Colectica Designer, CED2AR
* Metadata for sensor data
    * sensor ML http://www.sensorml.com
	* SWEET
	* SensorML ontology registry and repository
    * MOLES3: complex scheme with multiple entities
* for photographs and models
    * VRA core: http://www.log.gov/standards/vracore
	* gbxml exchange format: metadata gets mixed with data
* What metadata: who will want it? what will they do with it?
* When to collect: asap
* How to collect: extract/copy - avoid retyping
* How to record it: use exising standards + local profile to adapt
* See rd-alliance metadata directory
* Be consistent

# Metadata for Energy: Jack Kelly
* energy disaggregation
* dataset: UK-DALE... lots of interesting features
* open source python tool: NILMTK
* Nature Publishing Group: Scientific Data Journal 
* reverse engineer over the air protocol for Current Cost units
* 54 channels from Jack's house
* nanode implements high frequency comms with plug sensors
* nilmtk.github.io
    * NILM = Non-Intrusive Load Monitoring
	* imports 11 datasets
	* data cleaning
	* 6 NILM algorithms
	* can process out of core, but code is complicated; consider using Blaze
	* uses TRAVIS-CI
* DIY structural metadata schema
* uses YAML
* lots of work on controlled vocab
* says schema is more complicated than it needs to be

# matlab: Alfonso

# Building data exchange: Mat Colmer
* innovate uk, used to work at the Energy Saving Trust
* www.bdx.org.uk
* DC four areas: closed data, personal data, IP and IoT
* Pit-stop for data? industry does not know what to do with data, no data management strategy
* Five audience groups
    * data owners
	* performance champions ****
	* learning/large organizations ****
	* challenge owners
	* digital innovators
	* focus on ****
* user concerns:
    * data provenance
	* data descriptions
	* licence terms
	* user moderation (?) control access and usage
	* ease of use of platform
* new BDX website going live in September
* key challenge is how to describe, associate and maybe integrate data
* exactly the same problems and goals as DM4T: do not want to host data, but describe it and point to it

# round table
* HCA small appliance ontology
* DOMEARM ? TM22 (Mat)
* how to anonimise?
* what constitutes a risk to privacy
* DPP it's got to be really hard
* can we know beforehand?
* problems only emerge *during* collection
* balance between anonymity and usefuless
* connect with ethics
* risks introduction of bias if informed consent is too circumspect
* what did you plan for and what was unexpected
* updating data sets:  what to UKDA do?  get Louise to talk?
* what about the streaming problem?
* DOIs and (un)changing data sets; DOIs and queries
* need DOI with versioning? Alex: already exists

# Ideas
* should have got someone from the Bath data hackathon
* OKF as partners for BigSTEM' + PCD?
* exercise: apply some of OKF tools to ENLITEN, etc.
* need to do something about provenance: W3C standard?  See https://www.w3.org/standards/techs/provenance#w3c_all
* Article for NPG Scientific Data
