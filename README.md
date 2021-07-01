# steelEye Python Engineer Assessment

Python Engineer Assessment Test
Thank you for your interest in the Python Engineer role at SteelEye .
We hope the test will not only test your abilities but also give you a little glimpse into some of the tasks we carry out. You are welcome to use any resources that would be available to you during the course of a normal day: e.g. Google is permitted, as are textbooks. You may include code developed elsewhere so long as they are licensed for commercial use without restriction. You should clearly identify and attribute sources within your code to their appropriate ownership.
One final word of warning - at a startup like SteelEye you will regularly gather your own requirements directly or receive vague details by email. Sometimes it is not possible to get a very detailed specification simply because the user doesn’t know or isn’t available. When this happens you have to use your initiative and work things out for yourself. This test has ambiguities and vague definitions. It is up to you to make reasonable and valid assumptions. Do not ask your recruitment consultant for help or advice as they know no more than you do.
And one final tip: KISS – Keep It Short and Simple. Don’t overcomplicate it, make it simple, efficient, easy to maintain and easy for the user to use.

Brief:
The requirement needs to be developed in Python 3
Code should follow pep8 standards and should include pydoc, logging & unit tests
Please provide github link for review.
Requirement:

Download the xml from this link
1.From the xml, please parse through to the first download link whose file_type is DLTINS and download the zip
2.Extract the xml from the zip.
3.Convert the contents of the xml into a CSV with the following header:
  FinInstrmGnlAttrbts.Id
  FinInstrmGnlAttrbts.FullNm
  FinInstrmGnlAttrbts.ClssfctnTp
  FinInstrmGnlAttrbts.CmmdtyDerivInd
  FinInstrmGnlAttrbts.NtnlCcy
  Issr
4.Store the csv from step 4) in an AWS S3 bucket
5.The above function should be run as an AWS Lambda (Optional)

Completed:
1.From the xml, please parse through to the first download link whose file_type is DLTINS and download the zip
2.Extract the xml from the zip.
3.Convert the contents of the xml into a CSV with the following header:
  FinInstrmGnlAttrbts.Id
  FinInstrmGnlAttrbts.FullNm
  FinInstrmGnlAttrbts.ClssfctnTp
  FinInstrmGnlAttrbts.CmmdtyDerivInd
  FinInstrmGnlAttrbts.NtnlCcy
  Issr
4.CSV is stored at the same place where XMLs are stored with the name output*.xml
  *the num of file
