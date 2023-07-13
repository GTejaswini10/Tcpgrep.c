# Tcpgrep.c
We have developed tcpgrep command line tool which takes pcap file as input and parses the pcapfile, which displays the TCP packets information on the command prompt .
This command line tool helps the user to get the required information on the TCP packets by using the following options.
The command is : tcpgrep
and the options are :
    o For displaying help option , tcpgrep pcapfilename

    o To display the total number of tcp packets, tcpgrep pcapfile name -t

    o To display the total number of incomplete tcpsession, tcpgrep pcapfile name -i

    o To display the incomplete tcpsessions with packet numbers, tcpgrep pcapfile name -in

    o To display the total number of rst packets, tcpgrep -r

    o To display the total rst packets with packet number, tcpgrep pcapfile name -rn

    o To display the total number of duplicate ack packets, tcpgrep pcapfile name -a

    o To display the total number of duplicate ack packets with packet number, tcpgrep pcapfile name -an

    o To dump specific range of tcp packet, tcpgrep pcapfile name -p packet range start – end range example: tcpgrep pcap1.pcap -p 2-10

    o To dump specific range of ports, tcpgrep pcapfile name -p: ip address:port no

        example: tcpgrep pcap1.pcap -p 192.168.4.5:443

    o To dump specified tcpflags, tcpgrep pcapfile name -pflags: A,P,F,U,S,R example : tcpgrep pcap1.pcap -pA ,-pF,-pS,-pU,-pR,-pP
