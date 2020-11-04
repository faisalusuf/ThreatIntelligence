# ThreatIntelligence
Tracking APT IOCs

# Motivation

When analyzing an Incident or artifacts about an APT, the research reports published on the internet usually found with different given APT names and the IOCs in these reports are collected from unique sources. This can lead to difficulty in the analysis by a researchers, specially who are new to CTI. During analysis several sources are required to be searched and it can be daunting tasks for analysts to keep a track on IOCs, review and remove potential false positives.

We will try to collect all publically accessible IOCs for specific APT group consolidate in one place. This is an on-going process and this repo will be keep on updating.

# Methodology

The IOCs are collected from several sources publically accessible and new one as it published. The IOCs collected from these sources are fed into [MISP](https://www.misp-project.org/) and correlation are performed based on other threat feeds. The enrichments are done using different [MISP modules](https://github.com/MISP/misp-modules) and potential false positives are manually reviewed.


You are more than welcome to contribute by sharing the IOCs which are missing, idea for improvement to make it more actionable. For this you may raise an [issue](https://github.com/faisalusuf/ThreatIntelligence/issues) along with IOC and reference URL from where the IOCs is collected. 

## Inspiration:

- @Arkbird_SOLG (Special Thanks for expert advice)
- @malwrhunterteam 
- @MeltX0R 
- @ItsReallyNick 
- @_re_fox 
- @Rmy_Reserve 
- @DeadlyLynn 
- @James_inthe_box 
- @ShadowChasing1 
- @cyb3rops
- @DrunkBinary  
- @craiu 
- @VK_Intel
- @thepacketrat


###### The IOCs can be made available in the following formats if required:

* MISP XML
* MISP JSON
* OpenIOC
* STIX XML
* STIX JSON
* STIX2
