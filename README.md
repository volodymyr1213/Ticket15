# Ticket15


Ansible Tower
The follow documentation will update everything in your host including kernel.
You will be using AWX/Ansible to do full update
######## Warning, currently this playbook is only supporting Centos. Use it at your own risk #########

On your AWX specify branch to "Team_C"

Specify the variable hostname under "Extra Variables"

On your template be sure to select "patching.yml" and celect "PROMPT ON LAUNCH"

RUN your template job and hope for the best!




DONE:
The bare minimum of whats requests has been completed.
- Only CENTOS
- Restartes even if there are no UPDATES


NEXT:
We will add the following Operating System as an improvement to this playbook.
-Ubuntu
-Dabian
- CENTOS
- Skips if its already latest version.
