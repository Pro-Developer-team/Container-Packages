# Github-Container-Package-Examples
This Repository contains several Container packages, all published by multiple yml workflow files, using `IMAGE ID` for the names. We will use each yml workflow file for a seperate package being published to github. Please see the diagram below to see how this repository works:

A ->> A: Package 1 
B ->> B: Package 2
C ->> C: Package 3 

Note left of C: Package 2 (B) is being deployed<br/>by the yml workflow file: `main<br/>2.yml`. The same goes for `C`<br/>, but being deployed with a different<br/>workflow file.
