# task to create kafka cluster on single node

## troubles

1. no installed java on server
2. no env file /etc/default/kafka, but it exists in the systemd unit
3. no log dir setup for brokers
4. using non-standart iptables for closing zk and kafka ports in ubuntu os, but default is ufw