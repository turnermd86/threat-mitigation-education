Research Method
+++++++++++++++
How My Study Was Conducted
==========================
#. In-depth review of existing literature.
#. Source, study, and categorize types of malware that use encoded commands (MalwareBazaar).
#. Execute practical aspects of research in a lab environment. 
#. Run static malware testing on a machine in a sandbox.
#. Conduct default configuration testing. Measure the time and accuracy of the process. Attempt to identify false positives and negatives.
#. Use a deobfuscation tool to decode malware samples when practical.
#. Tune the process to see the impact of time and accuracy and re-run the test. (if applicable)
#. Compare results between speed and accuracy of tuning tests.
#. Run multiple test rounds and refine testing procedures. If the results are the same after two rounds of testing, document the details of the findings and move on to the following malware or process.
#. Document findings: speed/accuracy metrics, false positives, and monitor default/tuned processes.
#. Run live malware on a vulnerable machine in a sandbox.
#. Analyze network traffic logs to glean further information.
#. Scan malware using existing YARA signatures.
#. If no signatures exist, attempt to create a detection signature.
#. Rescan malware using YARA signatures.
#. Document success/failure detection results

.. note:: Add sections for wazuh, InetSim, sysmon, procmon, and process explorer.
    Run through YARA. 
    Come up with different methodological approach


Methodological Approach
=======================
#. Change the characteristics/features of the processes used to determine the nature (malicious or benign) of any encoded commands encountered.
#. Determine the detection process’s effectiveness, efficiency, and speed in defining various malicious or benign encoded commands using default configurations/tuned configurations (if applicable) to see the impact on performance and then document results.
#. Static testing findings and discussion
#. Live testing findings and discussion
