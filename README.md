# Elasticsearch StackOverflow vulnerability

A flaw was discovered in Elasticsearch, affecting the `_search` API that allowed a specially crafted query string to cause a Stack Overflow and ultimately a Denial of Service.

Affected Versions:

Elasticsearch versions from 7.0.0 to 7.17.12 and from 8.0.0 to 8.9.0

Solutions and Mitigations:

The issue is resolved in Elasticsearch 7.17.13 and 8.9.1

**CVSSv3:** 6.5 (Medium) - AV:N/AC:L/PR:L/UI:N/S:U/C:N/I:N/A:H  
**CVE ID:** CVE-2023-31419

Ref: [Link](https://discuss.elastic.co/t/elasticsearch-8-9-1-7-17-13-security-update/343297)

## Proof-of-concept

https://github.com/sqrtZeroKnowledge/Elasticsearch-Exploit-CVE-2023-31419/assets/31594437/52905c60-01e2-4bdb-b6dc-c51267963d7e

