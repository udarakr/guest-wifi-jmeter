# guest-wifi-jmeter

1. Download apache-jmeter and copy in to the /home/workspace/ directory.
2. Copy guest_acc.jmx to the /home/workspace directory.
3. Update USERNAME(WSO2 email ID) and PASSWORD properties accordingly.
4. Add following command to the /home/<USER>/.bashrc script.

alias guest-wifi='cd /tmp && sh /home/workspace/apache-jmeter-2.11/bin/jmeter.sh -n -t /home/workspace/guest_acc.jmx -l log.jtl'

5. Open terminal window and run guest-wifi command.



