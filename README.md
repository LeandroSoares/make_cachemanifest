MAKE_CACHEMANIFEST
==================

Make a apache.manifest easy.

Setup on mac
---------
First, clone a copy of the main make_cachemanifest git repo by running:

```bash
git clone git@github.com:LeandroSoares/make_cachemanifest.git
```
Them copy to: /usr/local/bin/

```bash
cp make_cachemanifest /usr/local/bin/make_cachemanifest
```
Them add the permissions
```bash
sudo chmod 777 /usr/local/bin/make_cachemanifest
```
Usage
---------
Go to a directory, them use "make_cachemanifest":
```bash
myMac:~ user$ cd ~/Projects/mySite/dev/
myMac:dev user$ make_cachemanifest
```
it will make in current directory an "cache.manifest" file or update the current existent .manifest.
