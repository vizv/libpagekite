## License ##

Most of this code (libpagekite) may be used according to the terms of the
following licenses:

   * The Apache License, version 2.0.
     See the file LICENSE-2.0.txt for details.

   * The GNU Affero General Public License, version 3 or above.
     See the file AGPLv3.txt for details.

Choose your favorite - unless you are developing a relay server, in which
case the Apache license probably does not apply (see below).

When using according to the AGPL, the additional exemption is made that
compiling, linking, and/or using OpenSSL is allowed.


### A note to developers ###

Developers who wish to negotiate alternate terms, service level agreements,
bulk discounts, support contracts or have questions about compliance are
encouraged to get in touch with the authors.

Note that those parts of libpagekite which are specific to frontend relay
servers are currently *only* available under the AGPLv3, not the Apache
License.  This includes `pagekiter.c` and `pkrelay.c`, and possibly others.

By default these are NOT compiled into the libpagekite library.

If in doubt, please consult the copyright notice present in the relevant .c
or .h files.  This is a shameless attempt to protect the business side of
the PageKite project and encourage folks who need lots of frontends to
either negotiate an alternate license or pay us for service.  We gotta eat!

Also, if you plan to launch a million devices that all rely on the
pagekite.net relay service, please let us know in advance so we can
provision accordingly.

Thanks!
