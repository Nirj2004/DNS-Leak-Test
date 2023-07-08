## DNS-Leak-Test

Test for leaking DNS queries (i.e. if a VPN is being used). If no expected DNS IP is specified then all DNS traffic is printed. If one is specified then this script alerts on leaking queries. The rationale being that all DNS traffic sniffed should only have either our local IP or the IP of our trusted DNS resolver(s).
