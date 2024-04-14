Findings and Discussion
+++++++++++++++++++++++
Malware
=============
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Congue mauris rhoncus aenean vel elit scelerisque mauris pellentesque. Cras sed felis eget velit aliquet sagittis id consectetur purus. Commodo sed egestas egestas fringilla phasellus faucibus scelerisque. Suscipit adipiscing bibendum est ultricies integer quis auctor elit.

.. list-table:: Malware
    :widths: 20 10 10
    :header-rows: 1
    
    * - Name
      - Purpose
      - Type (.exe or .ps1)
    * - BlackMatter
      - Ransomware
      - Portable Executable
    * - AgentTesla
      - Remote Access Trojan/Data Stealer
      - Portable Executable
    * - njrat
      - Remote Access Trojan
      - Portable Executable
    * - CobaltStrike
      - Adversary Simulation Software
      - PowerShell Script
    * - YellowCockatoo
      - Remote Access Trojan/Malware Delivery Platform
      - PowerShell Script
    * - TrickBot
      - Banking Trojan
      - PowerShell Script

Basic Malware Analysis
=========================
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Congue mauris rhoncus aenean vel elit scelerisque mauris pellentesque. Cras sed felis eget velit aliquet sagittis id consectetur purus. Commodo sed egestas egestas fringilla phasellus faucibus scelerisque. Suscipit adipiscing bibendum est ultricies integer quis auctor elit. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Congue mauris rhoncus aenean vel elit scelerisque mauris pellentesque. Cras sed felis eget velit aliquet sagittis id consectetur purus. Commodo sed egestas egestas fringilla phasellus faucibus scelerisque. Suscipit adipiscing bibendum est ultricies integer quis auctor elit.

Basic Static Analysis
----------------------
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Congue mauris rhoncus aenean vel elit scelerisque mauris pellentesque. Cras sed felis eget velit aliquet sagittis id consectetur purus. Commodo sed egestas egestas fringilla phasellus faucibus scelerisque. Suscipit adipiscing bibendum est ultricies integer quis auctor elit.

Basic Dynamic Analysis
----------------------
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Congue mauris rhoncus aenean vel elit scelerisque mauris pellentesque. Cras sed felis eget velit aliquet sagittis id consectetur purus. Commodo sed egestas egestas fringilla phasellus faucibus scelerisque. Suscipit adipiscing bibendum est ultricies integer quis auctor elit.

.. list-table:: 
    :widths: 20 10 10 10 10 10
    :header-rows: 1

    * - Malware
      - # of IPs Contacted
      - # of Files Dropped
      - # of URLs Contacted
      - # of Domains Contacted
      - # of Files Bundled
    * - BlackMatter
      - 9
      - 10+
      - 2
      - 4
      - 5
    * - AgentTesla
      - 10+
      - 2
      - 1
      - 1
      - 2
    * - njrat
      - 10+
      - 1
      - 4
      - 7
      - 4
    * - CobaltStrike
      - 5
      - 10+
      - 5
      - 5
      - N/A
    * - YellowCockatoo
      - 2
      - 2
      - 5
      - 4
      - N/A
    * - TrickBot
      - 8
      - 5
      - 1
      - 6
      - N/A

More Info
========================
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Congue mauris rhoncus aenean vel elit scelerisque mauris pellentesque. Cras sed felis eget velit aliquet sagittis id consectetur purus. Commodo sed egestas egestas fringilla phasellus faucibus scelerisque. Suscipit adipiscing bibendum est ultricies integer quis auctor elit.

.. list-table:: 
    :widths: 20 10 10 15
    :header-rows: 1
    
    * - Name
      - Network Logs
      - YARA rules
      - Accuracy of detection (comparison b/t tuned & default configuration)
    * - Example Name
      - log file.
      - YARA rule
      - 75 %