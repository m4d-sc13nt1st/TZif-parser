# TZif-parser

Parser for Time Zone Information Format (TZif) files, used in RHEL and other Linux distributions. In some instances, the file 'etc/localtime' is not a symbolic link, but is actually a TZif file. For forensic examiners, parsing this file is essential for determining the timezone of the system under examination.

The TZif format is defined in [RFC 8536](https://datatracker.ietf.org/doc/html/rfc8536), and further documented in the [tzfile man page](https://man7.org/linux/man-pages/man5/tzfile.5.html).
