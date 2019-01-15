IP_Generator

To see this tool in action go here - https://trinket.io/python/e265ab113e

I made this tool because I had to activate thousands of devices at a time and the interfaces and templates I was using to do so left a bit to be desired. Instead of manually writing each IP address, or using excel to dropdown the increment until reaching the broadcast address then rewriting the next octet, I decided to flex a little progamming muscle and wrote my own tool. 

You'll notice that there are two .py files. This is because one creates a 12-digit address (preferred by Verizon and other carriers) and the other creates a normal address without any leading zeros. 

Hello Networking World!
This is my IP Generator:
  A tool to generate IP addresses by incrementing each Octet or Quad of your specified range and quantity. [166.30.30.2 or 10.2.255.254, ex.]
  Give the first IP address in your range and the number of ip's to generate.

See alternate script that outputs address without leading zeros.
