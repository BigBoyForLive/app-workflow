FROM marwaney/ssh-server

COPY provisionning.pub /home/sshuser/.ssh/authorized_keys 

CMD [ "/usr/sbin/sshd", "-D" ]

