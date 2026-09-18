# rockyIntertidalSummaries
This repo contains scripts and R markdown reports that summarize and QC rocky intertidal data by park, 
site type (eg lake or stream), site, and parameter type (eg, water quality or quantity, field vs. lab measurements). 

Notes on this repo: 
<ul>
<li>You must have the rockyIntertidal R package installed to run this code `pak::pkg_install('doi-nps/rockyIntertidal')`</li>
<li>The reports that are most functional are QC reports: </li>
  <ul>
  <li>park_QC_checks_all_years.Rmd: QC report for all years of rocky intertidal data. This report depends 
  on park_QC_checks_compile_all_years.R</li>
  <li>park_QC_checks.Rmd: QC report for a given year of rocky intertidal data. This report depends on
  park_QC_checks_compile.R</li>
  </ul>
<li>Summary reports that are not fully functional since the latest version of the data package was updated include:</li>
<ul>
<li>park_summary.Rmd: Does not currently work, but has a lot of code that may be useful for future reports.</li>
<li>park_summary_abbrev.Rmd: Partially works, but has a lot of code that may be useful for future reports.</li>
</ul>

Additional dependencies: 
<ul>
<li>www/: folder contains general formatting files, like the CSS, the front page photo, and the arrowhead, which is not on git. </li>
<li>header_manual.html: code for the NPS banner used as the report header.</li>
<li>boundboxes.csv: sets bounding boxes for the leaflet site maps in the About the Sites tab.</li>
</ul>
