# behind_cloudfront

This module can help you to discover the real IP address behind the Cloudfront service.

This can be useful if you need to test the security of your server and your website 
behind Cloudfront by discovering the real IP address.

![alt text][module_info]

![alt text][module_advanced]

More precisely, I use multiple data sources (DNS enumeration, ViewDNS.info, Censys) to collect
assigned (or have been) IP addresses from the targeted site or domain that uses the 
Cloudfront CDN.

![alt text][module_demo]

[module_info]: https://raw.githubusercontent.com/mekhalleh/behind_cloudfront/master/pictures/01-demo.png "Module: info"
[module_advanced]: https://raw.githubusercontent.com/mekhalleh/behind_cloubehind_cloudfrontdflare/master/pictures/02-demo.png "Module: advanced"
[module_demo]: https://raw.githubusercontent.com/mekhalleh/behind_cloudfront/master/pictures/03-demo.png "Module: demo"
