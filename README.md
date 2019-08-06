IP_Generator

Hello Networking World!

To see this tool in action go here - https://trinket.io/python/e265ab113e

I made this tool because I had to activate thousands of devices at a time and the interfaces and templates I was using to do so left a bit to be desired. Instead of manually writing each IP address, or using excel to dropdown the increment until reaching the broadcast address then rewriting the next octet, I decided to flex a little progamming muscle and wrote my own tool. 

You'll notice that there are two .py files. This is because one creates a 12-digit address (preferred by Verizon and other carriers) and the other creates a normal address without any leading zeros. 

IP Generator:
  A tool to generate IP addresses by incrementing each Octet or Quad of your specified range and quantity. [166.30.30.2 or 10.2.255.254, ex.]
  Give the first IP address in your range and the number of ip's to generate.

See alternate script that outputs address without leading zeros.

Here is a code sample showing how the 4 octets come together:

`method will take above inputs as the 2 args and split each quad into an array
def ipGenerator(ip, sNum):
    ipArray = ip.split(".")
    quad1 = int(ipArray[0])
    quad2 = int(ipArray[1])
    quad3 = int(ipArray[2])
    quad4 = int(ipArray[3])`