Summary
=================
Purpose of this report
-----------------
This report exports the data to be used at https://public.opencpu.org/ocpu/github/anticoagulation/warfarin/www/ in order to calculate the time in therapeutic range as described by Rosendaal ( PMID [8470047](http://pubmed.gov/8470047) ). This allows benchmarking the quality of your anticoagulation against best practice. 

The mean TTR in randomized control trials is 56% ( PMID [23049730](http://pubmed.gov/23049730) ) Lower numbers increase the risk of both mortality and bleeding (PMID [17296878](http://pubmed.gov/17296878)) without clear benefit from warfarin (PMID [18955670](http://pubmed.gov/18955670)).

Using this report
-----------------
The report currently has filters for the first query, "Patients from selected site", where you can select specific prctice sites based on PCPS address. You can delete or edit that as needed.

After exporting this report, you may need to remove '>' symbols or other non-numeric characters from your INR values.

Bug
-----------------
Join for excluding patients with valvular disease who need INRs is not working. Thus, results may be inaccurate for patient populations with many valvular patients. Please see [related issue](https://github.com/ecwusers/xml/issues/2). 

Questions
-----------------
Ask questions by 'Creating an issue' by clicking the encircled exxlamation mark icon to the right of this page.

See [all issues for this file](https://github.com/issues?utf8=%E2%9C%93&q=is%3Aissue+user%3Aecwusers+ttr+) (eg 'ttr' is in the text of the issue).
