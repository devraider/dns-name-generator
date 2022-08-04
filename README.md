# DNS name generator
### Reason
It's a great tool for email marketers who are struggleing to generate real DNS names.

### Logic insde
You need one or two lists of words, then script takes random two words to be merged then add TLD and checks using dns.resolver if that DNS is registred or not.

### Running

python auto.py com 10 7

Where:
- com is TLD for DNS;
- 10 is qty of DNS to be created;
- 7 length of DNS without TLD
