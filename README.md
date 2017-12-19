pan_pcap is a python script that pulls Threat PCAPs from a Palo Alto Networks firewall.  It keeps track of the
PCAP IDs for the PCAPs it's already downloaded, so it can be initiated as a cron job periodically to check the
firewall for new PCAPs and download them before they roll out of the space allocated on the firewall for PCAP storage.
