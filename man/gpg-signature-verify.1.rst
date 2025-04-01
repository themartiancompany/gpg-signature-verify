..
   SPDX-License-Identifier: AGPL-3.0-or-later

   ----------------------------------------------------------------------
   Copyright © 2024, 2025  Pellegrino Prevete

   All rights reserved
   ----------------------------------------------------------------------

   This program is free software: you can redistribute it and/or modify
   it under the terms of the GNU Affero General Public License as published by
   the Free Software Foundation, either version 3 of the License, or
   (at your option) any later version.

   This program is distributed in the hope that it will be useful,
   but WITHOUT ANY WARRANTY; without even the implied warranty of
   MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
   GNU Affero General Public License for more details.

   You should have received a copy of the GNU Affero General Public License
   along with this program.  If not, see <https://www.gnu.org/licenses/>.


====================================
gpg-signature-verify
====================================

---------------------------------------------
GNU Privacy Guard Signature Verifier tool
---------------------------------------------
:Version: gpg-signature-verify |version|
:Manual section: 1

Synopsis
========

gpg-signature-verify
  *[options]*
  *target_file*
  *[target_signatures]*


Description
===========

It verifies the target file's signature
corresponds to one of the input
signatures.

Options
========

-t  signature_type      It can be 'file' or 'fingerprint'.
-H  gnupg_home          GnuPG home (for when the signature type
                        is 'fingeprint').

-h                      Display help.
-c                      Enable color output
-v                      Enable verbose output


Bugs
====

https://github.com/themartiancompany/gpg-signature-verify/-/issues

Copyright
=========

Copyright Pellegrino Prevete. AGPL-3.0.

See also
========

* gpg

.. include:: variables.rst
