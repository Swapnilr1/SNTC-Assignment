# Findings

## IIT Mandi Network Ports and Computers

## Domain Provider for IIT Mandi

`students.iitmandi.ac.in` is a subdomain of `iitmandi.ac.in` which was given to the institute by `ERNET India`.
I found this information by this [Whois lookup](https://www.whois.com/whois/iitmandi.ac.in).


## Location of DuckDuckGo's data centres

DuckDuckGo is hosted by Amazon Web Services (AWS). It runs on 4 AWS datacenters (California, Virginia, Singapore, Ireland).

Source: http://highscalability.com/blog/2013/1/28/duckduckgo-architecture-1-million-deep-searches-a-day-and-gr.html

(Unfortunately, I could not find a more recent source despite all attempts to search.)

`nslookup duckduckgo.com` and `ping duckduckgo.com` yield the following IP addresses, and using https://www.iplocation.net/ I found which datacentre each IP corresponds to

1. `176.34.131.233` `176.34.155.20` `176.34.135.167` `46.51.197.89` `54.229.105.203` `54.229.105.92` - Dublin, Ireland
2. `46.51.218.82` - Singapore

I can't find any other way to find out IP addresses for any other datacentre.

# What I learnt

1. Usage of `Nmap` to know open ports, and operating system.
2. Basic usage of `nslookup`

