Research Method
+++++++++++++++
How My Study Was Conducted
==========================
a.	In-depth review of existing literature.
b.	Source, study, and categorize types of malware that use encoded commands (MalwareBazaar). Goals (static: n=15, live: n=25)
 
c.	Execute practical aspects of research in a lab environment. 
i.	Run static malware testing on a machine in a sandbox.
1.	Conduct default configuration testing. Measure the time and accuracy of the process. Attempt to identify false positives and negatives.
2.	Use a deobfuscation tool to decode malware samples when practical.
3.	Tune the process to see the impact of time and accuracy and re-run the test. (if applicable)
4.	Compare results between speed and accuracy of tuning tests.
5.	Run multiple test rounds and refine testing procedures. If the results are the same after two rounds of testing, document the details of the findings and move on to the following malware or process.
6.	Document findings: speed/accuracy metrics, false positives, and monitor default/tuned processes.
ii.	Run live malware on a vulnerable machine in a sandbox.
1.	Analyze network traffic logs to glean further information.
2.	Scan malware using existing YARA signatures.
3.	If no signatures exist, attempt to create a detection signature.
4.	Rescan malware using YARA signatures.
5.	Document success/failure detection results


Methodological Approach
=======================
