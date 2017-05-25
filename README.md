# Previous Project Listing
Description of previous projects I have worked on/built. Since most of the projects I have worked on were restricted due to client requirements, I have little to show for those when folks come spelunking on github. So, I figured I'd compile a list of some of the previous things I've built.

### Acler - Cisco ACL SiLK Data Flow Checker - Only Dev
Python 2.7 (restricted by deployment env) CLI application used to automate the checking of thousands of lines of Cisco ACL records against SiLK network flow records to determine if there has been any recent network activity matching each ACL. This tool is/was used by a very large enterprise as a part of their annual ACL revalidation project. Agencies requesting the ACL are required to re-verify the need each year and are provided with whether/not any traffic has occured as part of the re-verification request. The tool parses the ACL records and runs SiLK queries back in time as needed to determine if traffic has been seen, saving hundreds of man hours and minimizing network flow system loading.

### Arbor - NIC to Arbor ETL - Only Dev
Python 2.7 (restricted by deployment env) CLI application used to automate the extraction, cleansing, and reformatting of a proprietary network information center (NIC) data dump into network attribution information as needed for ingest into an Arbor Peakflow detection system. This tool/data allows generation of granular correlation/trigger rules within Arbor.

### Cyber Security Incident Response Operations Intranet - Only Dev
Intranet information portal to provide knowledge management, analysis, incident reporting, and metrics retrieval capabilities. This was a 26-module PHP, Perl, and MySQL solution that supported 24-hour operations for a team of ~50 analysts, sensor system administrators, and management personnel for ~4.5 years.

### Enlisted Performance Report Status Tracker - Only Dev
This was a Visual Basic 6 application with an MDB database back end (only thing allowed by security). The application was used by a single administrative person to track and report on annual performance report information for ~250 people for 5 years. The type of info tracked was: person and supervisor contact info, last report, report due by date for each of 5-8 sign-off milestones, date arrived at each chain-of-command location, date completed, routing comments, etc.

### Seminar Management Application - Lead/Primary Dev
Training conference management software. This was a 3-tier solution using Visual Basic 6 client and server software, with a SQL Server (45-table) back end. The Attendee client application provided in-classroom students with current schedules, presentation topics/descriptions/goals, and accepted student presentation ratings and comments. The Seminar Manager client application provided myriad of modules needed to manage all facets of the different seminars: quota coordination and allocation, presentation info, primary/alternate presenter contact info, theater functional POC contact info, classroom schedules, attendee/student info, student seating assignments, individual and aggregated student assessments of presentations, automated presentation assessment email distribution to presenter and chain of command, etc. These applications were used to manage six different seminar courses using two classrooms over four plus years teaching approximately 5,000 students.

### Child Development Center Tracker - Only Dev
This was a Visual Basic 6 application with an MDB database back end. It was used by a single person to track and report child information (child name, parents, parent contact info, start date, projected departure date, care giver, room numbers, etc).
