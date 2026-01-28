checking the status of jenkins

root@TWS-BATCH-10-SERVER:~# systemctl status jenkins
● jenkins.service - Jenkins Continuous Integration Server
     Loaded: loaded (/usr/lib/systemd/system/jenkins.service; enabled; preset: enabled)
     Active: active (running) since Wed 2026-01-28 14:46:52 UTC; 24min ago
   Main PID: 750 (java)
      Tasks: 44 (limit: 4653)
     Memory: 480.0M (peak: 488.8M)
        CPU: 1min 40.541s
     CGroup: /system.slice/jenkins.service
             └─750 /usr/bin/java -Djava.awt.headless=true -jar /usr/share/java/jenkins.war --webroot=/var/cache/jenkins

Jan 28 14:46:50 TWS-BATCH-10-SERVER jenkins[750]: 2026-01-28 14:46:50.186+0000 [id=38] INFO jenkins.InitR>
Jan 28 14:46:50 TWS-BATCH-10-SERVER jenkins[750]: 2026-01-28 14:46:50.496+0000 [id=37] INFO h.p.g.Globa>
Jan 28 14:46:51 TWS-BATCH-10-SERVER jenkins[750]: 2026-01-28 14:46:51.932+0000 [id=37] INFO jenkins.InitR>
Jan 28 14:46:51 TWS-BATCH-10-SERVER jenkins[750]: 2026-01-28 14:46:51.933+0000 [id=36] INFO jenkins.InitR>
Jan 28 14:46:52 TWS-BATCH-10-SERVER jenkins[750]: 2026-01-28 14:46:52.008+0000 [id=39] INFO jenkins.InitR>
Jan 28 14:46:52 TWS-BATCH-10-SERVER jenkins[750]: 2026-01-28 14:46:52.027+0000 [id=38] INFO jenkins.InitR>
Jan 28 14:46:52 TWS-BATCH-10-SERVER jenkins[750]: 2026-01-28 14:46:52.088+0000 [id=39] INFO jenkins.InitR>
Jan 28 14:46:52 TWS-BATCH-10-SERVER jenkins[750]: 2026-01-28 14:46:52.171+0000 [id=30] INFO o.j.p.g.j.Job>
Jan 28 14:46:52 TWS-BATCH-10-SERVER jenkins[750]: 2026-01-28 14:46:52.174+0000 [id=30] INFO hudson.lifecy>
Jan 28 14:46:52 TWS-BATCH-10-SERVER systemd[1]: Started jenkins.service - Jenkins Continuous Integration Server.
