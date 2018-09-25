# fuzzy-tribble
- Add to /etc/network/interfaces
    - prepend domain-name-servers 127.0.0.1;
- Add to /etc/dnsmasq.conf
    - address=/.vm/127.0.0.1

- Run docker-compose up
- Access http://whoami.vm
- Profit