<h1> My PowerShell Tests </h1> 

Welcome to my PowerShell Test repo! I have set ythis up for personal reference, but also so that I can show people the commands I learn. I will update this repo as I learn new commands that are inteeresting and worth noting for others learrning powershell.

The first major one is: <br>
<code> gsv | where-object {$_.name -like "sp*"} | convertto-csv | out-file D:\pwsh-tests\sp-proc.csv </code> command shows that I know how to use the <code> get-service </code> command and pipe the results to an out csv file and be able to read it out in some other program.


The second one is: <br>
<code> gps | export-clixml -path D:\pwsh-tests\process.xml </code> <br>
This command gets all of the proceses running on my machine and puts them into an XML file. 

Te third is: <br>
<code> gps |  </code>
