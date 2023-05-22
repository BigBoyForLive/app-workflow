FROM marwaney/ssh-server:ubuntu

COPY /home/haruna/.ssh/id_ed25519.pub /home/sshuser/.ssh/authorized_keys 

CMD [ "/usr/sbin/sshd", "-D" ]

