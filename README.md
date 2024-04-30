## DNS Brute Force Script

This Bash script facilitates DNS brute forcing by performing DNS lookups for a specified domain using a list of words (e.g., subdomains). It takes two command-line arguments: the domain name to target and the location of a wordlist containing subdomains.

### Usage

```
./dns_brute_force.sh <domain_name> <wordlist_location>
```

Replace `<domain_name>` with the target domain and `<wordlist_location>` with the path to the wordlist file containing subdomains.

### Example

To brute force the DNS records for `example.com` using a wordlist located at `/path/to/wordlist.txt`:

```
./dns_brute_force.sh example.com /path/to/wordlist.txt
```

### Notes

- Ensure the wordlist file contains one subdomain per line.
- The script filters out DNS records that are not found.

---
