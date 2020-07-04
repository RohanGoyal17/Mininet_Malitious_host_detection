# Mininet_Malitious_host_detection
aims to detect malicious hosts in a networked data centre. A prototype implemented in a p4 running on mininet

To setup the enviroment, we need <a href="https://github.com/mininet/mininet">mininet</a> and <a href="https://github.com/p4lang">p4</a>. Its recomended to run the project in a vm. The image can be found <a href="https://github.com/CS344-Stanford-18/p4-mininet-tutorials/tree/master/P4D2_2018_East/vm">here</a>.
The code here provides definition for a host and switch infrastructure one in which the switch is designed to detect ecternal data packets wrt to arrival time gradient.
