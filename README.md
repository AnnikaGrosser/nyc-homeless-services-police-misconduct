# nyc-homeless-services-police-misconduct

This repository contains data and findings for an [ongoing investigation](https://nysfocus.com/2024/04/15/new-york-city-homeless-abuse-police) in collaboration with MuckRock and New York Focus about cases of misconduct and abuse at the hands of peace officers of the [New York City’s Department of Homeless Services Police](https://www.youtube.com/watch?v=OzejEheDjUo) (DHS).

## Documents and data
### Department of Homeless Services documents we obtained
We filed open-records requests to New York City’s Department of Homeless Services (DHS) for all disciplinary files the agency is required to disclose under Brady v. Maryland and Giglio v. United States, two cases that force police departments and prosecutors to flag officers who may be untrustworthy in court. DHS began providing these documents to district attorney’s offices after [the June 2020 repeal of 50-a](https://www.rcfp.org/50-a-repeal-police-misconduct/), a law that had previously kept police disciplinary files secret. These files are being made public for the first time.

### Limitations in scope of documents and time period 
These disciplinary files may not be every disciplinary file pertaining to an officer employed by the DHS. Instead, these are records that were provided to prosecutors under the prosecutors' obligations to provide materials like this to criminal defendants.

Although our database includes cases of misconduct dating back to 1998, these only involve select officers who have been on the department's Brady list since 2020. We are unclear what portion of the overall disciplinary files these records represent, as the city has not agreed to make these documents public and, at the time of publication, did not respond to our questions about the overall number of incidents.   

### Substantiation of charges 
These documents describe allegations that the DHS has found to be credible. They describe incidents that officers have not challenged further, since those would go to arbitration. 

Through this method of reporting we were able to gather only substantiated allegations, instead of the underlying complaints, meaning that the involved parties of the disciplinary proceedings have agreed to the underlying facts of each incident.

### Missing documents 
Some of the incidents in our database have gaps in the data. In those cases, we were unable to get both the charges and the implementation letter for the incident. We also decided to exclude two incidents — both repeat offenses that were mentioned in the respective officers’ other letters — since we do not have the underlying charges document for those cases. 

This brought the final total of incidents in our database to 66, involving 31 officers.

**All the documents we received in response to our requests [are public on DocumentCloud](https://www.documentcloud.org/app?q=%2Bproject%3Anew-york-city-department--217068%20)**. 

## Methodology 
### Turning documents into data 
In response to our open-records requests to the DHS, we received disciplinary documents for a total of 66 incidents. Over several months, we reviewed these documents and turned the information gleaned from them into a database by manually entering details from the documents into a spreadsheet. Afterwards, we analyzed the data for trends in which officers were responsible for misconduct and how that misconduct was handled by the agency. Journalist Sammy Sussman manually went through all the documents to log the data describing each incident, journalist Annika Grosser cleaned, analyzed and visualized the data, and MuckRock's Dillon Bergin fact-checked the results.

**The database we created is in [`data/manual/document_annotation_data.xlsx`](data/manual)**.

### Manually recorded data from the documents

**Officers and repeat offenders**
- We recorded the name and title of the officers charged with misconduct and counted the number of cases each officer was involved in. This allowed us to analyze which officers served in the DHS Police despite a history of repeated misconduct.

**Shelter locations**
- We also documented the shelters where the incidents took place. This data is limited, because the addresses of locations were redacted in the documents we received. 
- Additionally, not every incident took place on-duty or on-site at a shelter facility. With the names of the shelters that were mentioned in the documents, we were able to locate 19 shelters including one in Orange County, which, at the time of the incident in 1999, was used by the city's DHS. We mapped the location of the shelters, including the number of incidents that took place at each facility.

**The disciplinary process**
- To reconstruct the timeline of the disciplinary process for each incident and for each officer with multiple misconduct cases, we logged the date for the initial suspension following an incident, the informal conference meeting and the resulting letter announcing the official suspension. For some incidents, the date of the conference meeting and the implementation are missing since we didn’t receive the corresponding letters.
- We also computed the time between each incident and the corresponding conference meeting, the time between incident and implementation letter, and the time between conference and letter.

This gave us an idea of how long the disciplinary process for DHS Police misconduct takes, on average. It also allowed us to draw important conclusions about how quickly officers with serious cases of abuse and excessive force are back at work and how long it takes for them to have a conference meeting and receive their official (or non-immediate) suspension.

**Code of Conduct violations**
- We recorded Code of Conduct violations and the DHS Peace Officer Guide violations mentioned in the disciplinary documents to help us understand the department's Code of Conduct and give us a better picture of what the agency classifies as misconduct.

**Excessive use of force**
- Although we initially recorded data for various parts of individual incidents, only a small subsection of the data made it into the final analysis. After attempting to categorize the different types of incidents, we decided to focus on cases of excessive use of force by officers towards shelter residents. 

The DHS’s so-called "peace officers" carry nonlethal weapons, such as batons and pepper spray, and are authorized to detain people, but they rely on the New York Police Department to arrest and file charges in the event of a crime being committed. Our analysis shows 14 incidents described as “excessive use of force,” in which those officers beat, kicked and pepper sprayed shelter residents, which the DHS itself describes as “New York City’s most vulnerable population.”

**Punishment**
- Suspension days in these cases vary greatly, ranging from five to 55 days across the 14 excessive use of force cases.
- We recorded the days of immediate suspension the officer served after the incident, the suspension given in the official implementation letter, the suspension still to be served from that point on, as well as suspension in abeyance, or postponed, and the abeyance period. In some cases, officers also lost leave balance or received no pay.

**The results of our analysis are in [`analysis/findings`](analysis)**.

## Questions/feedback 
Reach out to us! Annika Grosser, annikajgrosser@gmail.com or Sammy Sussman, sammybsussman@gmail.com 
 
