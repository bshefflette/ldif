# Fork
https://github.com/Iljan/ldif

# ldif

Utilities for working with ldif data. This implements most of RFC 2849.

## Change Entries

Supports go modules specifically for github.com/go-ldap/ldap/v3

## Controls

Only simple controls without control value are supported, currently
just
   Manage DSA IT - oid: 2.16.840.1.113730.3.4.2

## URLs

URL schemes in an LDIF like
   jpegPhoto;binary:< file:///usr/share/photos/someone.jpg
are only supported for the "file" scheme like in the example above