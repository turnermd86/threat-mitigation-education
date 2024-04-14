Research Method
+++++++++++++++
How My Study Was Conducted
==========================
#. In-depth review of existing literature.
#. Source, study, and categorize types of malware that use encoded commands (MalwareBazaar).
#. Execute practical aspects of research in a lab environment.
 
    - Create sandbox environment Windows 10 with flare-vm installed. (https://github.com/mandiant/flare-vm)
    - Run static malware testing in a sandbox
     
      - Submit hash to VirusTotal to get additional information, such as contacted domains, ips, urls, dropped/bundled files
      - For portable executables, use PEView.exe, PEStudio.exe, and FLOSS
      - For PowerShell scripts, use strings.exe and PowerDecode

    - Run dynamic malware testing in a sandbox
  
      - Detonate malware using InetSim to capture network connection attempts
      - Analyze network traffic via WireShark to glean further information.

  
      - Detonate malware in isolation to monitor activity when no internet is present
          .. note:: Ensure proc

 
  

#. Run live malware on a vulnerable machine in a sandbox.
#. 
#. Scan malware using existing YARA signatures.
#. If no signatures exist, attempt to create a detection signature.
#. Rescan malware using YARA signatures.
#. Document success/failure detection results

.. note:: Add sections for wazuh, InetSim, sysmon, procmon, process explorer, IAT, PEView, PowerDecode
    


Methodological Approach
=======================
#. Change the characteristics/features of the processes used to determine the nature (malicious or benign) of any encoded commands encountered.
#. Determine the detection process’s effectiveness, efficiency, and speed in defining various malicious or benign encoded commands using default configurations/tuned configurations (if applicable) to see the impact on performance and then document results.
#. Static testing findings and discussion
#. Live testing findings and discussion


.. figure:: /images/HomeNet3.jpg

        Figure 1. Home Net in VMWare Workstation 17 Pro

