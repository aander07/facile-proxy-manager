# Commands #

## count\_sessions ##

Count all of the active sessions on the server

```
facil-proxy-manager> count_sessions
Active session count: 523
```

## host ##

Set the EZProxy server name to connect to

```
facil-proxy-manager> host ezproxy.example.com
```

## hosts\_active ##

Display the peak virtual hosts active

```
facil-proxy-manager> hosts_active
Peak virtual hosts: 177
```

## hosts\_limit ##

Display the peak virtual hosts limit

```
facil-proxy-manager> hosts_limit
Peak virtual host limit: 400
```

## license\_status ##

Display the EZproxy release information

```
facil-proxy-manager> license_status
EZproxy 5.4 GA for Linux started at 2011-01-12 04:00:15
```

## list\_session\_from ##

List the active sessions for the given host/ip

```
facil-proxy-manager> list_session_from 192.0.2.1
e1Y7kV1xmslQR4F, username1, 192.0.2.1, 2011-01-24 17:24:34, 2011-01-24 17:24:39
```

## list\_session\_username ##

List the active sessions for the given user

```
facil-proxy-manager> list_session_username username1
e1Y7kV1xmslQR4F, username1, 192.0.2.1, 2011-01-24 17:24:34, 2011-01-24 17:24:39
```

## list\_sessions ##

List all of the active sessions on the server

```
facil-proxy-manager> list_sessions 
Aoit9EEyLLYUqpg, username1, 192.0.2.1, 2011-01-24 17:05:40, 2011-01-24 17:06:13
...
JhCPpvxV1UFDF4A, username2, 192.0.2.1, 2011-01-24 17:05:59, 2011-01-24 17:14:42
```

## login ##

Login to the EZProxy server

```
facil-proxy-manager> login
Logged into ezproxy.example.com with session e1Y7kV1xmslQR4F
```

## logout ##

Logout from the EZProxy server

```
facil-proxy-manager> logout
```

## maintenance\_compress\_port\_usage ##

Compress port usage by reassigning higher ports into any available gaps

```
facil-proxy-manager> maintenance_compress_port_usage
```

## maintenance\_remove\_orphan ##

Remove orphaned host entries

```
facil-proxy-manager> maintenance_remove_orphan
To complete the removal of these hosts, you must now restart EZproxy
```

## maintenance\_remove\_unused ##

Remove unused host entries

```
facil-proxy-manager> maintenance_remove_unused
To complete the removal of these hosts, you must now restart EZproxy
```

## maintenance\_reset\_dates\_and\_counts ##

Reset accessed and referenced dates and counts of all hosts

```
facil-proxy-manager> maintenance_reset_dates_and_counts
```

## maintenance\_show\_orphan ##

```
facil-proxy-manager> maintenance_show_orphan
Orphaned Host Entries: 8
```

## maintenance\_show\_shutdown ##

Display the number of proxy by port entries that can be shutdown

```
facil-proxy-manager> maintenance_show_shutdown
Unused Host Entries: 0
```

## maintenance\_show\_unused ##

Display the number of unused host entries

```
facil-proxy-manager> maintenance_show_unused
Unused Host Entries: 12
```

## maintenance\_shutdown\_ports ##

Shutdown ports previously assigned to proxy by port

```
facil-proxy-manager> maintenance_shutdown_ports
To complete the removal of these ports, you must now restart EZproxy
```

## quit ##

Exit the program

```
facil-proxy-manager> quit
```

## restart ##

Restart the EZProxy server

```
facil-proxy-manager> restart
```

## session\_active ##

Display the peak sessions active

```
facil-proxy-manager> session_active
Peak sessions active: 672
```

## session\_limit ##

Display the peak sessions limit

```
facil-proxy-manager> session_limit
Peak sessions limit: 2000
```

## ssl\_status ##

Display the SSL initialization status

```
facil-proxy-manager> ssl_status
SSL is initialized
```

## status ##

Print the internal status settings

```
facil-proxy-manager> status
Host: ezproxy.example.com
Cookiename: ezproxy
Username: admin
Password: 12345
Testing: True
SSL: True
Connected: True
```

## terminate\_session ##

Clear a specific session by session ID

```
facil-proxy-manager> terminate_session e1Y7kV1xmslQR4F
Terminating session e1Y7kV1xmslQR4F
```

## terminate\_session\_created\_before ##

Clear sessions older than the given date (YYYY-MM-DD)

```
facil-proxy-manager> terminate_session_created_before 2011-01-25
Terminating session e1Y7kV1xmslQR4F
...
```

## terminate\_session\_from ##

Terminate connections from a given host/ip

```
facil-proxy-manager> terminate_session_from 192.0.2.1
Terminating session e1Y7kV1xmslQR4F
```

## terminate\_session\_username ##

Terminate connections from a given username

```
facil-proxy-manager> terminate_session_username username1
Terminating session e1Y7kV1xmslQR4F
```

## transfers\_active ##

Display the peak concurrent transfers active

```
facil-proxy-manager> transfers_active
Peak concurrent transfers active: 74
```

## transfers\_limit ##

Display the peak concurrent transfers limit

```
facil-proxy-manager> transfers_limit
Peak concurrent transfers limit: 200
```

## validation\_status ##

Display the EZproxy license validation status

```
facil-proxy-manager> validation_status
EZproxy was last able to validate the license on 2011-01-12 04:00:42.
```