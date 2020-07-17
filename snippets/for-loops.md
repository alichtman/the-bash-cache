## For Loops

```bash
$ for ip in $(seq 1 10); do echo 10.11.1.$ip; done
10.11.1.1
10.11.1.2
10.11.1.3
10.11.1.4
10.11.1.5
10.11.1.6
10.11.1.7
10.11.1.8
10.11.1.9
10.11.1.10

# Equivalent to...
$ for i in {1..10}; do echo 10.11.1.$i;done

$ for url in $(cat list.txt); do host $url; done
```
