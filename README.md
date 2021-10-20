# fs2comma

FEC-provided source code of the tool `fs2comma.exe`, with a few tweaks
to make up for a missing file.  Untested, but now cross-platform!

Original code from
[Matt Hodges](https://github.com/hodgesmr)'
[FOIA request](https://twitter.com/hodgesmr/status/1450935353892876297)

## To compile

```sh
$ g++ -w -o fs2comma *.cpp
$ ./fs2comma
fs2comma version 6.1.1.0 NIC Technologies Inc 2006-2010
Usage: fs2comma 123.fec [out.csv]
if the second parameter is specified, that will be used as the output
if not, 123.csv will be the output
$
```
