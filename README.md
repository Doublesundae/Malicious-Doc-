<h1> Malicious Doc </h1>

<h2>Description</h2>
In this project, the tools Virus total and any.run were used to analyze the document facture.zip for the challenge, malicious doc on Letsdefend.io
<br />


<h2>Tools Used</h2>

- <b>Virus total</b> 
- <b>Any.Run</b>
- <b>LetsDefend.io</b>


<h2>Environments Used </h2>

- <b>Orcale Virtual Box </b>
- <b>Ubuntu</b> 

<h2>Walk-through:</h2>

<p align="left">

  <h2>Question #1</h2>
What type of exploit is running as a result of the relevant file running on the victim machine? <br/>
<br/>
<img src="https://i.imgur.com/Ui9PGMj.png" height="80%" width="80%" alt="question 1"/>
<br/> 
<br/>
To get this answer, the file factura.zip was downloaded and extracted in a safe environment, once extracted the document was then copied into virus total to get the answer 
<br/>
<br/>
<img src="https://i.imgur.com/8XqTN3c.png" height="80%" width="80%" alt="Answer 1"/>

<br />
<br />

<h2>Question #2</h2>
What is the relevant Exploit CVE code obtained as a result of the analysis? <br/>
<br/>
<img src="https://i.imgur.com/qfKNBVj.png" height="80%" width="80%" alt="Question 2"/>
<br/>
The Exploit CVE code was conveniently in the same place as the type of exploit 
<br/>
<br/>
<img src="https://i.imgur.com/8XqTN3c.png" height="80%" width="80%" alt="Answer 2"/>
<br />
<br />

<h2>Question #3</h2>
  
What is the name of the malicious software downloaded from the internet as a result of the file running?  <br/>
<br/>
<img src="https://i.imgur.com/MucNqlC.png" height="80%" width="80%" alt="Question 3"/>
<br />
<br />
To Get this answer, The MD5 Hash of factura.zip was copied to any.run sandbox tool. When the malicious URL was identified and followed, the software was identified as jan2.exe <br/>
<br/>
<img src="https://i.imgur.com/kYCEtqb.png" height="80%" width="80%" alt="Answer 3"/>
<br/>
<br/>

<h2>Question #4</h2>
  
What is the ip address and port information it communicates with?  <br/>
<br/>
<img src="https://i.imgur.com/MkW0Rpd.png" height="80%" width="80%" alt="Question 4"/>
<br />
<br />
To Get this answer, The MD5 Hash of factura.zip was copied to any.run sandbox tool.  <br/>
<br/>
<img src="https://i.imgur.com/IL2xiTc.png" height="80%" width="80%" alt="Answer 4"/>
<br/>
<br/>

<h2>Question #5</h2>
  

What is the exe name it drops to disk after it runs? <br/>
<br/>
<img src="https://i.imgur.com/RSdCBLy.png" height="80%" width="80%" alt="Question 4"/>
<br />
<br />
To Get this answer, The Virus total was used, then navigate to the relations tab   <br/>
<br/>
<img src="https://i.imgur.com/QSolCaI.png" height="80%" width="80%" alt="Answer 4"/>
<br/>
<br/>



<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
