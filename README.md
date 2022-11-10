![](/images/ahlsbanner.png)
<h1 id='IeVACAlHMO3'>A-HLS - DataRaptor Library Documentation - DRgetCareRequest</h1>

<hr style='width:100%'><i>This DataRaptor acts as a base for developers to get information quickly about a Care Request.</i><br/>

<h2 id='IeVACALWHia'>Overview</h2>

A DataRaptor is a mapping tool to help read, transform, and write Salesforce data. There are four types of DataRaptors: <span style="color:#1e1e1c" textcolor="#1e1e1c">Turbo Extract, Extract, Load, and Transform. You can use these four methods to extract data for digital customer interactions and business processes to present data. </span><br/>

<br/>

This DataRaptor Extract collects meaningful information about a specific ‘Care Request Case,’ making it available for display or further use in an OmniScript.<br/>

<hr style='width:100%'><h2 id='IeVACAi0fy9'>Business Objective</h2>

The Business objective is to quickly extract information about a specific ‘Care Request Case’ that can be meaningful to achieve the jobs to be done for a business user or reporting.<br/>

<h2 id='DUfACAKe2tj'><span style="color:#333333" textcolor="#333333">Business Value and Benefits</span></h2>

<div data-section-style='5' class="" style=""><ul id='DUfACALTZ59'><li id='temp:C:DUf48f6afe5d5874f3ca6bb5b90e' class='' value='1'><span style="color:#0e101a" textcolor="#0e101a">Decrease IT costs associated with custom build</span>

<br/></li><li id='temp:C:DUf307aad11f3e64465ac9031098' class=''>Improve user experience

<br/></li></ul></div><hr style='width:100%'><h2 id='IeVACA0GQMy'>Export-Package Includes</h2>

<h3 id='IeVACA5Plnj'><b>DataRaptor (1)</b></h3>

<div class="" data-section-style='5' style=""><ul id='IeVACA1ndzs'><li id='IeVACA4AjrM' class='' value='1'>DRgetCareRequest

<br/></li></ul></div><h2 id='IeVACAoEIZD'><b>JSON Reference</b></h2>

<div class="" data-section-style='5' style=""><ul id='IeVACAqFoJT'><li id='IeVACAaksUo' class='' value='1'>{<br>  "CareRequest": {<br>    "RequesterType": "Text",<br>    "Procedure": {<br>      "ProcedureName": "Text",<br>      "ApprovalFieldBlock": {<br>        "RequestedStartDate": "Text",<br>        "RequestedEndDate": "Text",<br>        "RequestedQuantity": "Text",<br>        "RequestedLengthofStay": "Text"<br>      },<br>      "ClinicalDetermination": "Text"<br>    },<br>    "Diagnosis": {<br>      "DiagnosisCODE": "Text"<br>    },<br>    "RequestingProviderName": "Text",<br>    "MemberId": "Text"<br>  },<br>  "Case": {<br>    "CaseNumber": "Text",<br>    "RequestedDate": "Text",<br>    "AccountName": "Text",<br>    "AccountId": "Text"<br>  }<br>}

<br/></li></ul></div><hr style='width:100%'><h2 id='IeVACAHYHH2'>Configuration Requirements</h2>

<h3 id='IeVACAqXRgg'>Configuration Instructions:</h3>

<div class="" data-section-style='5' style=""><ul id='IeVACALhPG9'><li id='IeVACAd8LKN' class='' value='1'>The Data Raptor is ready to be imported and customized. No further base configuration requirements are necessary.

<br/></li></ul></div><h3 id='IeVACAP7F6m'>Installation Instructions:</h3>

The following steps are required for installation.<br/>

<h4 id='IeVACAJRCQk'>Install the Data Pack</h4>

<div class="" data-section-style='6' style=""><ul id='IeVACAJTm0h'><li id='IeVACAF4u6J' class='' value='1'>The Data Pack folder in the following GitHub repository contains one (1) DPA Data Pack. Please download the Data Pack and save them to your desktop: <a href="https://github.com/HLS-Accelerate/DataRaptor-Library/tree/main/DRgetCareRequest">https://github.com/HLS-Accelerate/DataRaptor-Library/tree/main/DRgetCareRequest</a>

<br/></li><li id='IeVACAUHcdA' class='parent'>Then, complete the following steps to import them into your Salesforce org.

<br/></li><ul><li id='IeVACA3iX0e' class=''>To Import, in your destination Salesforce org, Click on <b>App Launcher</b> → Search for '<b>OmniStudio DataPacks</b>' and click on it.

<br/></li><li id='IeVACAl1aPF' class=''>Click on '<b>Installed</b>' and on the right side click on '<b>Import from</b>'.

<br/></li><li id='IeVACAFLd11' class=''>Select '<b>From File</b>' - When the window opens, select the Data Pack file that you downloaded and stored on your machine. Click '<b>Install</b>'.

<br/></li></ul></ul></div><hr style='width:100%'><h2 id='IeVACA36Kh3'><span style="color:#333333" textcolor="#333333">Assumptions</span></h2>

<div class="" data-section-style='5' style=""><ul id='IeVACAYAkjC'><li id='IeVACAeLwhB' class='' value='1'>A customer has licenses for Health Cloud and the HINS Managed Package with OmniStudio. These solutions have all been installed and are functional.

<br/></li><li id='IeVACABsh74' class=''>A customer is assuming Salesforce Lightning Experience — not Classic.

<br/></li><li id='IeVACALP5DR' class=''>Data Model elements that are part of the HINS (Vlocity) Managed package and Health Cloud are available.

<br/></li><li id='IeVACAumabu' class=''>The Accelerator uses the Lightning Design System standards and look. Customers may want to apply their branding.

<br/></li></ul></div><h2 id='IeVACAgtPXs'>Installed Packages Requirement</h2>

<div class="" data-section-style='5' style=""><ul id='IeVACAOdZP7'><li id='IeVACAMOZGi' class='' value='1'>HealthCloud (HealthCloudGA) - Version 236.1 or higher

<br/></li><li id='IeVACAKVpyO' class=''>Vlocity Insurance (vlocity_ins) - Version 890.317 or higher

<br/></li></ul></div><hr style='width:100%'><h2 id='IeVACAmqHVz'>Revision History</h2>

<div class="" data-section-style='5' style=""><ul id='IeVACAagy3L'><li id='IeVACAAKIe0' class='parent' value='1'><b>Revision Short Description (May 12, 2022)</b>

<br/></li><ul><li id='IeVACAbDLUl' class=''>Error correction from previous versions to adapt to the new Data Model

<br/></li><li id='IeVACAlI4y1' class=''><span style="color:#333333" textcolor="#333333">Initial export with QA</span>

<br/></li></ul><li id='IeVACASv6zK' class='parent'><b>Revision Short Description (June 21, 2022)</b>

<br/></li><ul><li id='IeVACAAAear' class=''><span style="color:#333333" textcolor="#333333">Updated Documentation</span>
