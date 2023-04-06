# tcptools

## Using Ping

The result for pinging www.amazon.com / www.google.com / www.microsoft.com each three times (results shown below).

#### Min / Avg / Max / Stddev of pings for each website

##### Amazon
6.054 ms / 39.26867 ms / 78.981 ms / 30.12476 ms

##### Google
4.754 ms / 7.297 ms / 9.057 ms / 1.84188 ms

##### Microsoft
8.182 ms / 35.37067ms / 72.026 ms / 26.9101 ms

#### Was there any packet loss on any of the pings
no

#### Did the IP address change for a given website between pings
no

![result](/imgs/pings.png)

## Using Tracert

#### What was the target server's IP address?
##### Amazon
18.65.233.187
##### Google
142.250.217.68
##### Microsoft
23.216.81.152

#### How many hops were needed to reach the target?
##### Amazon
14
##### Google
11
##### Microsoft
11

#### Can you identify your ISP from the intermediate server DNS names?
Yes, they are all from Hivelocity

#### Identify the "class" of IP address for each major step in the trip

##### Amazon
Goes from Class A (10.18.0.2) and (10.132.255.22) to Class B (209.124.190.134) and (209.124.181.245) then back to Class A (150.222.214.205) and (18.65.233.187)
##### Google
Goes from Class A (10.18.0.2) and (10.132.255.22) to Class B (209.124.190.134) and (206.81.80.168) then back to Class A (108.170.245.97)
##### Microsoft
Goes from Class A (10.18.0.2) and (10.132.255.22) to Class B (209.124.188.134) and (206.81.80.168) then back to Class A (23.216.81.152)

#### Image of Results of Traceroute
##### Amazon
![amazon_result](/imgs/traceroute_amazon.png)
##### Google
![google_result](/imgs/traceroute_google.png)
##### Microsoft
![google_result](/imgs/traceroute_microsoft.png)

## Extra Credit Questions
####

#### Using packet-capture tools
![wireshark](/imgs/wireshark.png)

#### Insecure Web Server
![insecure_web_server](/imgs/insecure_web_server.png)