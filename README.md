# IP_Generator

# Hello Networking World!

# Here's my IP Generator -
# A tool to generate IP addresses by incrementing 4 Octets or Quads in your specified range. [166.30.30.2, ex.]
# You give the first IP address and the Number of address to generate.

I made this tool because I had to activate thousands of devices at a time and the interfaces and templates I was using to do so, ehem, left a bit to be desired. Instead of manually writing each IP address, or using excel to dropdown the increment until reaching 255 then rewriting the next octet, I decided to flex a little progamming muscle and wrote my own tool. 

You'll notice that there are two .py files. This is because one creates a 12-digit address (preferred by Verizon and other carriers) and the other creates a normal address without any leading zeros. 

WHAT YOU WILL NEED
