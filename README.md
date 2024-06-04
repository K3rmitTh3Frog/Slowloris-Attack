# Slowloris-Attack
This tool uses perfectly legitimate HTTP traffic to enable one machine to take down another machine's web server. After creating a complete TCP connection, it only needs a few hundred requests made over an extended period of time at regular intervals. The tool doesn't have to use a lot of traffic as a result to use up all of a server's connections. 


Step1: Clonning the slowloris Repo
`git clone https://github.com/gkbrk/slowloris.git`

Step2: Setting Up apache2 Server.
`sudo service apache2 start`

Step3: Checking if the Server is online.
`service apache2 status`

Step4: Execution of the attack.
`python3 slowloris.py (your ip address)`
