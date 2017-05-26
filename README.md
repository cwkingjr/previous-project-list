# Previous Project Listing
Description of previous projects I have worked on/built. Since most of the projects I have worked on were restricted due to client requirements, I have little to show for those when folks come spelunking on github. So, I figured I'd compile a list of some of the previous things I've built.

### Acler - Cisco ACL SiLK Data Flow Checker - Only Dev
Python 2 (restricted by deployment env) CLI application used to automate the checking of thousands of lines of Cisco ACL records against SiLK network flow records to determine if there has been any recent network activity matching each ACL. This tool is/was used by a very large enterprise as a part of their annual ACL revalidation project. Agencies requesting the ACL are required to re-verify the need each year and are provided with whether/not any traffic has occured as part of the re-verification request. The tool parses the ACL records and runs SiLK queries back in time as needed to determine if traffic has been seen, saving hundreds of man hours and minimizing network flow system loading.

### Arbor - NIC to Arbor ETL - Only Dev
Python 2 (restricted by deployment env) CLI application used to automate the extraction, cleansing, and reformatting of a proprietary network information center (NIC) data dump into network attribution information as needed for ingest into an Arbor Peakflow detection system. This tool/data allows generation of granular correlation/trigger rules within Arbor.

### Sonar Self-Signed Certificate Extractor (sonar-ssc-harvestor) - Only Dev
This is a Python CLI application to extract and assess self-signed web server certificate information from the Project Sonar Internet-wide scan of web servers. This application supported an enterprise effort to investigate and report summary information on the numbers and types of global sites using self-signed ceritificates.

### SiLK Sensor Deployment Test - Only Dev
This is a bash script that includes several SiLK data availability and format tests. This tool was requested by engineering and is/was used to test the network flow data produced by a new sensor just after deployment prior to the deployment team leaving, to make sure that the sensor data was being received at the data center correctly.

### ArcSight CSV to Archive XML Transformer - Only Dev
This was a Java CLI application that used 7-10 differently-formatted CSV files to generate a single ArcSight ESM Archive XML-formatted import file. This tool was based on a previous but broken version that another ArcSight professional services technician developed, but where there was no source code. I recreated the capability in a new tool, adding in new functionality, employing data validation tests for all known previous issues, and updating the output format to match ESM changes in newer versions. The tool needed to be written in Java so that it could be run on any system that ArcSight ESM or Console was installed (e.g., with Java). This tool was an internal ArcSight non-supported product for use by global ArcSight professional services personnel.

### Setter - SiLK IP Address and Prefix Map File Generator - Only Dev
Python 2 (restricted by deployment env) CLI application used to allow cyber defenders to manage protected network/organization IP address block / organization name attribution in a single file and then generate a hierarchical set of SiLK IP address set and prefix map (pmap) files. Set and pmap files are then used by analysts during SiLK queries to limit searching/reporting to the desired organizational level (e.g., all orgs, one org, one region of an org, one section of an org, etc).

### NIC to ArcSight Enterprise Security Manager (ESM) ETL - Only Dev
This was a Python 2 application used to automate the extraction, cleansing, and reformatting of a proprietary network information center (NIC) data dump into internal network attribution information as needed for ingest into the ArcSight ESM Security Incident and Event Management (SIEM) system. This tool/data allowed global security engineers to author granular correlation rules and significantly reduce the quantity of false positive alarms presented to security analysts.

### Cyber Security Incident Response Operations Intranet - Only Dev
Intranet information portal to provide knowledge management, analysis, incident reporting, and metrics retrieval capabilities. This was a 26-module PHP, Perl, and MySQL solution that supported 24-hour operations for a team of ~50 analysts, sensor system administrators, and management personnel for ~4.5 years.

### Enlisted Performance Report Status Tracker - Only Dev
This was a Visual Basic 6 application with an MDB database back end (only thing allowed by security). The application was used by a single administrative person to track and report on annual performance report information for ~250 people for 5 years. The type of info tracked was: person and supervisor contact info, last report, report due by date for each of 5-8 sign-off milestones, date arrived at each chain-of-command location, date completed, routing comments, etc.

### Seminar Management Application - Lead/Primary Dev
Training conference management software. This was a 3-tier solution using Visual Basic 6 client and server software, with a SQL Server (45-table) back end. The Attendee client application provided in-classroom students with current schedules, presentation topics/descriptions/goals, and accepted student presentation ratings and comments. The Seminar Manager client application provided myriad of modules needed to manage all facets of the different seminars: quota coordination and allocation, presentation info, primary/alternate presenter contact info, theater functional POC contact info, classroom schedules, attendee/student info, student seating assignments, individual and aggregated student assessments of presentations, automated presentation assessment email distribution to presenter and chain of command, etc. These applications were used to manage six different seminar courses using two classrooms over four plus years teaching approximately 5,000 students.

### Child Development Center Tracker - Only Dev
This was a Visual Basic 6 application with an MDB database back end. It was used by a single person to track and report child information (child name, parents, parent contact info, start date, projected departure date, care giver, room numbers, etc).
