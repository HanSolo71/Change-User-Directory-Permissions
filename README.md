# Change-User-Directory-Permissions

By default, VMWare Persona will copy profiles to a location listed under the Persona GPO. Each profile will not inhert permissions from the directory the profiles are stored in and will only save the permissions used inside of the VM.

This script run on logon will and add extra permissions to the C:\Users\$User directory which will be then synced back to the Persona repository on logoff of the user.
