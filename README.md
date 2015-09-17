# DNS_Domain-Name-Servert

### DNS

* DNS stand for domain name server
* DNS maintain the directory of domain names and traslate these names into ip addresses
* This is necessary because, although domain names are easy for people to remember, computers or machines, access websites based on IP addresses
* nformation from all the domain name servers across the Internet are gathered together and housed at the Central Registry. Host companies and Internet Service Providers interact with the Central Registry on a regular schedule to get updated DNS information
* When you type in a web address, e.g., `www.jimsbikes.com`, your Internet Service Provider views the DNS associated with the domain name, translates it into a machine friendly IP address (for example 216.168.224.70 is the IP for jimsbikes.com) and directs your Internet connection to the correct website

## DNS Record

* DNS records are used to control the location of a resource on the Internet. following are the main records types of DNS

### ARecord

* A stand for address, arecord is used to find the addresses of computers which are connected to the internet from a name
* A Record is used to point a logical domain name, such as "google.com", to the IP address of Google's hosting server, "74.125.224.147".

### CName

* A Canonical Name record (abbreviated as CNAME record) is a type of resource record in the Domain Name System (DNS) used to specify that a domain name is an alias for another domain, the "canonical" domain. All information, including subdomains, IP addresses, etc., are defined by the canonical domain
* CNAME records are handled specially in the domain name system, and have several restrictions on their use. When a DNS resolver encounters a CNAME record while looking for a regular resource record, it will restart the query using the canonical name instead of the original name. (If t he resolver is specifically told to look for CNAME records, the canonical name (right-hand side) is returned, rather than restarting the query.) The canonical name that a CNAME record points to can be anywhere in the DNS, whether local or on a remote server in a different DNS zone.

### MXRecords

* mail exchange record is a type of resource records in the DNS that specifies a mail server responsible for accepting email messages on behalf of receipients domain and a prefrence value used to prioritize mail delivery if multiple mail servers are available
