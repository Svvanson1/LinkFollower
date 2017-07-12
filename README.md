# LinkFollower
A Perl Script that allows you to follow a link from somewhere that leads to the correct site with the incorrect domain name.

The program creates a new HTTP::Proxy object, then reads all of the data at the end of the program to create header filters. When a request comes in, the proxy runs all header filters that match the request. These filters can manipulate the request as appropriate. 

Run the program from the command line. If necessary, pass in arguments, perhaps to run on a different port:

```
$ perl LinkFollower.pl port 5000
```
