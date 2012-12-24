# mutt configuration

## Overview
Customized mutt configuration based on mrtazz/muttfiles. Tested with imap
and smtp.

## Features
* prepared for using folder-hooks to manage different accounts
* mailcap added for inline viewing of attachemnents
* highlight new and important mails
* some simplifications for a smoother workflow (sure, this is a matter of
  taste and application scenario)

## Setup
1. Clone this repository into your home directory. You may clone it into
   ~/.mutt.
2. Create your inditiy file(s) based on the identiy_sample file.
3. Based on the muttrc.sample create your muttrc file. See the sample for
   details.
4. If you didn't clone to ~/.mutt, symlink your muttrc file to either
   ~/.muttrc or ~/.mutt/muttrc.

This should get you going with mutt.
