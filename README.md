** Affordable Housing Project **
> -- using the code for America template <br> 
https://docs.google.com/document/d/1KaApjflNS7NRHaEGEZGmotNzi27TqshKtoCn12L6I0g/edit?usp=sharing

** References ** 
> Any references, data sources, articles, additional documents, etc. <br>
> https://github.com/maggienj/Prince_housing/blob/master/Outline_forDan.txt <br> 
> https://github.com/maggienj/Prince_housing/blob/master/lookupData_info.txt <br> 
> https://github.com/maggienj/Prince_housing/blob/master/nj-housing-incomelimits.pdf <br> 

** June 9 - 2016 ** 
Transformation of lookup data.  From PDF to CSV to JSON - Done! <br>

Use this latest uploaded JSON file. (lkpDataV3.json) <br>
-- A section of the pdf file was transformed to CSV. <br>
-- Then, the csv file has ben transformed to JSON. <br>
-- In addition, the JSON file has been modified slightly to remove $ and commas. <br>
-- This JSON file contains data relevant to Region-4 Mercer, Monmouth and Ocean. This is the only region which is applicable to affordable housing project. Therefore, only this region is inlcuded in JSON file. <br>

Link to the latest JSON file-- https://github.com/maggienj/Prince_housing/blob/master/lkpDataV3.json  <br>

Converter Used : http://codebeautify.org/csv-to-xml-json <br>

-- Notes by MaggieNJ -- Jun 10 , 2016 ---
** the below link contains a nodejs web app which uses the above json file. <br>
https://github.com/maggienj/Megan <br> 
It uses lodash to filter and query the above lookup data json file. The code for it is in app.js <br>
The next step is to move that section of code to "qualify" page and set that as an action for submit button with few more modifications






