# behind_cloudfront

This module can help you to discover the real IP address behind the Cloudfront service.

This can be useful if you need to test the security of your server and your website 
behind Cloudfront by discovering the real IP address.

More precisely, I use multiple data sources (DNS enumeration, ViewDNS.info, Censys) to collect
assigned (or have been) IP addresses from the targeted site or domain that uses the 
Cloudfront CDN.
