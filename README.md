# namecheap-dyndns
Forked from calederer/ddns-update

Commandline utility to update namecheap dynamic dns
Update your host, dns, and password.

More info here:
https://www.namecheap.com/support/knowledgebase/article.aspx/43/11/how-do-i-set-up-a-host-for-dynamic-dns/

The comamndline tool has the following switches:

  -f  --force    :    Ignores the existence of a 'cached' ip, and updates anyway
  
  -q  --quiet    :    Runs the script with minimal output, and only prints errors.

# Installation instructions:
- `cp pw_file.sh ~/.namecheap_file.sh`
- `chmod 600~/.namecheap_file.sh`
- Then create a crontab entry for the path to this script.
