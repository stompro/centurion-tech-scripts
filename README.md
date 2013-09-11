centurion-tech-scripts
======================

Scripts that work with or enhance Centurion Technologis products like SmartShield, Cornerstone and Driveshield.

Scripts are run at logon through a scheduled task, the script will detect if the machine is locked.  If the machine is locked the script will exit.  If the machine is not locked then it will continue.

If the machine is not locked then the script will start various tasks after a random delay for each task.

Tasks started
- Windows Updates
- Adobe Flash Update
- OCS Inventory update and deployment
- Defraggler defrag, or iobits smart defrag.
- ccleaner

