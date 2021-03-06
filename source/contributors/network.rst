*******
Network
*******

Configuration for daemon
========================

Network Flow table (IN) :

+-------------+------------+----------+------+-----------+----------------+---------+
| Daemon Name | Service    | Protocol | Port | Listen    | Authentication | Enabled |
+=============+============+==========+======+===========+================+=========+
| -           | ICMP       | ICMP     | -    | 0.0.0.0   | no             | yes     |
+-------------+------------+----------+------+-----------+----------------+---------+
| isc-dhcpd   | DHCP       | UDP      | 67   | 0.0.0.0   | no             | no      |
+-------------+------------+----------+------+-----------+----------------+---------+
| isc-dhcpd   | DHCP       | UDP      | 68   | 0.0.0.0   | no             | no      |
+-------------+------------+----------+------+-----------+----------------+---------+
| xivo-provd  | TFTP       | UDP      | 69   | 0.0.0.0   | no             | yes     |
+-------------+------------+----------+------+-----------+----------------+---------+
| ntpd        | NTP        | UDP      | 123  | 0.0.0.0   | yes            | yes     |
+-------------+------------+----------+------+-----------+----------------+---------+
| asterisk    | SIP        | UDP      | 5060 | 0.0.0.0   | yes            | yes     |
+-------------+------------+----------+------+-----------+----------------+---------+
| asterisk    | IAX        | UDP      | 5060 | 0.0.0.0   | yes            | yes     |
+-------------+------------+----------+------+-----------+----------------+---------+
| sshd        | SSH        | TCP      | 22   | 0.0.0.0   | yes            | yes     |
+-------------+------------+----------+------+-----------+----------------+---------+
| xivo-webi   | HTTP       | TCP      | 80   | 0.0.0.0   | yes            | yes     |
+-------------+------------+----------+------+-----------+----------------+---------+
| xivo-webi   | HTTPS      | TCP      | 443  | 0.0.0.0   | yes            | yes     |
+-------------+------------+----------+------+-----------+----------------+---------+
| asterisk    | SCCP       | TCP      | 2000 | 0.0.0.0   | yes            | yes     |
+-------------+------------+----------+------+-----------+----------------+---------+
| xivo-ctid   | XiVO-CTI   | TCP      | 5003 | 0.0.0.0   | yes            | yes     |
+-------------+------------+----------+------+-----------+----------------+---------+
| xivo-ctid   | XiVO-CTIS  | TCP      | 5013 | 0.0.0.0   | yes            | no      |
+-------------+------------+----------+------+-----------+----------------+---------+
| asterisk    | AMI        | TCP      | 5038 | 127.0.0.1 | yes            | yes     |
+-------------+------------+----------+------+-----------+----------------+---------+
| xivo-provd  | HTTP       | TCP      | 8667 | 0.0.0.0   | no             | yes     |
+-------------+------------+----------+------+-----------+----------------+---------+
| xivo-confd  | HTTPS      | TCP      | 9486 | 0.0.0.0   | yes            | yes     |
+-------------+------------+----------+------+-----------+----------------+---------+
| xivo-confd  | HTTP       | TCP      | 9487 | 127.0.0.1 | no             | yes     |
+-------------+------------+----------+------+-----------+----------------+---------+
| xivo-dird   | HTTP       | TCP      | 9489 | 127.0.0.1 | no             | yes     |
+-------------+------------+----------+------+-----------+----------------+---------+
| xivo-amid   | HTTP       | TCP      | 9491 | 127.0.0.1 | no             | yes     |
+-------------+------------+----------+------+-----------+----------------+---------+
