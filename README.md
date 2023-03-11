# YUBICO SETUP on SERVER

### CHECK IF GPG is installed.
```
gpg --card-status
apt list scdaemon yubikey-manager libpam-yubico libpam-u2f libu2f-udev
sudo apt installscdaemon yubikey-manager libpam-yubico libpam-u2f libu2f-udev

```
### USING YUBICO MANAGER
```
ykman info
ykman openpgp
ykman openpgp info
ykman openpgp set-touch enc on
ykman openpgp set-touch sig on
ykman openpgp set-touch aut on

gpg --card-edit

```
