ISC-DHCP/Pinapple
=================

ISC-DHCP with PPP interfaces support

Contact: SATO Taisuke / <paina@wide.ad.jp>

まだまだでございます
--------------------

まだ既存のパッチをあてただけなので、過度な期待はしないでください。

とりあえずな！　名前だけはきめてレポジトリ掘るという形から入るのが大事！

License
-------

ISC-DHCP is originally developed by Internet Systems Consortium. License from the original is shown below.

    # Copyright (c) 2004-2014 by Internet Systems Consortium, Inc. ("ISC")
    # Copyright (c) 1995-2003 by Internet Software Consortium
    #
    # Permission to use, copy, modify, and distribute this software for any
    # purpose with or without fee is hereby granted, provided that the above
    # copyright notice and this permission notice appear in all copies.
    #
    # THE SOFTWARE IS PROVIDED "AS IS" AND ISC DISCLAIMS ALL WARRANTIES
    # WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF
    # MERCHANTABILITY AND FITNESS.  IN NO EVENT SHALL ISC BE LIABLE FOR
    # ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES
    # WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN
    # ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT
    # OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.
    #
    #   Internet Systems Consortium, Inc.
    #   950 Charter Street
    #   Redwood City, CA 94063
    #   <info@isc.org>
    #   https://www.isc.org/
    
    See the specific source files for any additional copyright or
    license statements.

ToDo
----

* DUID generation for PPP interface.
    * If 'default-duid' is not specified and dhclient is run for PPP interface, it not start properly.
