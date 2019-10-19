# dodrootcerts
Compilation of DoD Root Certificates to install all in one place. I set this up specifically for Linux, however, you should be able to use this for any OS.

## The following certs are available in this repo:
AllCerts.p7b

RootCert2.crt

RootCert3.crt

RootCert4.crt

RootCert5.crt


# INSTALLATION
## Firefox
1. Open `Preferences`
2. Select `Privacy & Security` on the left
3. Select `View Certificates` under `Certificates` section at the bottom
4. Under `Authorities` tab, scroll down to find if you already have any `U.S. Government` certificates. If you do, delete them all.
5. Select `Import` and navigate to RootCert2.crt
6. Select all trust settings and hit `OK`
7. Repeat steps 5 and 6 for other RootCerts
8. Repeat steps 5 and 6 for `AllCerts.p7b`

## Chrome
1. Open `Settings`
2. Select `Manage certificates` under `Privacy and security`
3. Under `Authorities` tab, select `Import`, change file type to `All Files` and navigate to RootCert2.crt
4. Select all trust settings and hit `OK`
5. Repeat steps 3 and 4 for all other RootCerts
6. Repeat steps 3 and 4 for `AllCerts.p7b`

## Windows
1. Double-click each certificate
2. Select all trust options and hit `OK`
