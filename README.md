# Why this?

This package _only_ contains the libraries from krb5, the Arch Linux package contains everything like kinit, kadmin and so on. Almost all packages only uses the libraries so this package replaces the krb5 package and tells the system that it provides ‘krb5’.

It is possible that there are packages that will break, open a issue if that’s the case and I can look at it.

# Why use this?

Maybe you prefer to remove some never used binaries from the disk, but a more likely reason is that the krb5 package conflicts and prevents a nice install of the Heimdal Kerberos implementation. For that, see my package `heimdal-krb-client`.
