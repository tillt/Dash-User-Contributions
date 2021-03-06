Sample Docset
=======================
CFWheels Docset
by James Hamilton GitHub: ColdFusionSun

Process For Creating Docset
===
This docset is an HTML docset available on the CFWheels website was generated by:
	1. Archiving http://cfwheels.org/docs/1-3 and all pages under that path to local disk using a utility such as SiteSucker for Mac.
	2. Using a utility such as WebContent Extractor for windows to scrape the local downloaded page for page information such as the page Title description and other content.
	3. Using excel the result from the scrape analysis is refactored to fuffil the Dash technical requirements for indexing the API documentation.
	4. The results from the scrape in excel are saved to CSV.
	5. The Dash Index SQLite database was created using a utility such as SQLite Inspector, the CSV from step 4 was imported into the index table.
	6. The index table was was saved as a SQLite databse > CFWheels.docset/Contents/Resources.
	7. HTML markup additional images, stylesheets and javascripts were saved to CFWheels.docset/Contents/Resources.
		- The CFWheels docs do not run or require javascript -- the javascript files were saved to the repo in case they were required.

About This Docset
===
CFWheels (http://cfwheels.org) is an MVC framework for ColdFusion.

About the CFWheels Docset Content Types
-Documentation pages pertaining to installing and general information about CFWheels are categorized as Frameworks document type.
-Documentation index pages are categorized as Library document type.
-API functions are categorized as Functions document type.
-Pages detailing abstract descriptions of function, tutorials or framework conventions are categorized as Guide document type.

Bugs: Verified that all internal links within the docset articles and breadcrumbs do correctly map to all content archived, saved and encapsulated within the docset -- other links in the page headers to other parts of the CFWheels project do not correctly function because they're outside of the scope of the docset.

Fair Use Notice
===

CFWheels is licensed under Apache License, Version 2.0. I (the creator of the DocSet) am not affiliated with CFWheels. This documentation has been archived and has been made available for educational purposes in accordance with fair use doctrine and statutory considerations of the United States Copyright Act of 1976.

Copyright Disclaimer under section 107 of the Copyright Act 1976, allowance is made for “fair use” for purposes such as criticism, comment, news reporting, teaching, scholarship, education and research.

Fair use is a use permitted by copyright statute that might otherwise be infringing. 

Non-profit, educational or personal use tips the balance in favor of fair use. 
