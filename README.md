# SecDrillDemo
A Demo of Drill 2.0 that pulls data from various sources (PCAP Files, APIs etc..) and read writes to a Google sheet. If time permits also add an electron App to make the while thing a simple GUI app.

* For a given PCAP File, query source destination IPs, ports, add ASNs and GEO Tags.
* Upload the results to a Google Sheet.
* For a given Amass + ZAP results in JSON - Enrich the ZAP results with Amass recon data
* Upload the results into a google sheet
* Write a script that updates the google sheet when the query is run again
* Write a condition that if a costom colum is added in the sheet (e.g. for comments etc..) that they update factors that in.
