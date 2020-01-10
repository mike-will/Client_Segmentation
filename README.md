# Client_Segmentation

Analysis for client operating a local wellness studio with a desire to establish tailored marketing communications 

This project began with an inquiry from a local business owner interested in establishing tailored communication channels for appropriately-segmented portions of his clientele.  A preliminary evaluation of his data availability, and further discussion of his high-level objectives indicated a viable path forward, with the following goals:

- Determine how best to group clientele for tailored email messaging, ideally limiting the number of groups to a small handful
- Produce output for each group which could be fed directly into the company's email distribution platform
- Complement that output with descriptive detail to inform relevant content creation

NOTE:  Data included in this repo has been anonymized, with PII pertaining to the business' actual clientele removed and replaced with generated client names and contact information.

Following the usual data profiling / exploratory data analysis, and direct contact with the SaaS company operating the cloud-based software used by the studio, all necesary client attributes had been identified.  A direct back-end connection wasn't available for studios using the company's software, so this tool instead utilizes standard reports produced by the cloud-based software.

While decriptive statistics are valuable in differentiating the client groupings established within this analysis, I knew that the raw data available wasn't rich enough to meaningfully guide content creation.  Though a standard K means clustering algorithm would generally be used to identify appropriate client groupings, I opted to instead use fuzzy K means clustering in order to also generate a list of "representatives" for each client group, who had been assigned to their particular group with the highest levels of certainty.  

This made it possible for the studio's staff to review those lists, and craft their messaging in much the same way they would during conversation with the individuals listed.

Since this is a tool to be used independently by the business, no commentary is included, since interpretation will vary as source data evolves.  Prior to finalization and deployment, a consultation was arranged with the business owner, providing an opportunity for collaborative exploration, and guidance in use and output interpretation.


