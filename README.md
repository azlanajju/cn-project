# cn-project
This project is related to DNS servers in the sense that it uses DNS resolution to check the availability of a website.

When a user enters a website URL in the text field, the JavaScript code extracts the hostname (e.g example.com) from the URL and performs a DNS lookup for that hostname. The DNS lookup is done by sending a request to the Google's public DNS resolver (https://dns.google.com/resolve?name=${hostname}) with the hostname as a parameter. The DNS server then returns the IP address associated with that hostname.

If the DNS server returns a status code of 0, it means that the domain name is available, and the JavaScript code displays a message saying that the website is available. If the DNS server returns a status code other than 0, it means that the domain name is not available, and the JavaScript code displays an error message.

In summary, this project uses the browser's built-in DNS resolution capabilities to check the availability of a website by sending a request to a DNS server and parsing the response to check the status of the domain name.
## [Goto Web-site]([https://domain-availability-checker.netlify.app])


