Package: irssi-text
Version: 0.8.9-1
Severity: normal
Followup-For: Bug #249789

Hi,

I experience the same bug:

(process:4248): GLib-CRITICAL **: file giochannel.c: line 142
(g_io_error_get_from_g_error): assertion `err != NULL' failed
(process:4248): GLib-CRITICAL **: file giochannel.c: line 142
(g_io_error_get_from_g_error): assertion `err != NULL' fail

The normal console output is:
21:13:11 -!- Irssi: Looking up avalon.hoffentlich.net
21:13:11 -!- Irssi: Connecting to avalon.hoffentlich.net [217.160.165.165] port 3001
21:13:11 -!- Irssi: Connection to avalon.hoffentlich.net established
21:13:11 -!- Irssi: Connection lost to avalon.hoffentlich.net

I'm using an irc proxy with ssl support. This has worked before...

- Alexander

-- System Information:
Debian Release: testing/unstable
  APT prefers unstable
  APT policy: (500, 'unstable')
Architecture: powerpc (ppc)
Kernel: Linux 2.6.6
Locale: LANG=en_US, LC_CTYPE=en_US (ignored: LC_ALL set to en_US)

Versions of packages irssi-text depends on:
ii libc6 2.3.2.ds1-13 GNU C Library: Shared libraries an
ii libglib2.0-0 2.4.2-1 The GLib library of C routines
ii libncurses5 5.4-4 Shared libraries for terminal hand
ii libperl5.8 5.8.4-2 Shared Perl library.
ii libssl0.9.7 0.9.7d-3 SSL shared libraries
ii perl 5.8.4-2 Larry Wall's Practical Extraction
ii perl-base [perlapi-5.8.3] 5.8.4-2 The Pathologically Eclectic Rubbis

-- no debconf information
