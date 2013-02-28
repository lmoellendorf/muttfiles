# mutt configuration

## Overview
Customized mutt configuration based on mrtazz/muttfiles. Tested with imap,
Maildir and smtp.

This setup is used to handle 5 different mail accounts.
The configuration is optimized for daily office usage not for handling mailing
lists.

## Features
* prepared for using folder-hooks to manage several different accounts
 * accounts may be switched using the Fn keys
 * you may also traverse all mailboxes containing unread mail
   (next-unread-mailbox)
* mailcap added for inline viewing of attachemnents
* highlight new and important mails
* keybinding to tag all duplicate messages and use ';d' to delete them
* keybinding to mark all messages in index as read
* use aspell for spell checking
* encourage the use of pgp
* be as vim'ish as possible

## Setup
1. Clone this repository into your home directory. You may clone it into
   ~/.mutt.
2. Create your inditiy file(s) based on the identiy_sample file.
3. Based on the muttrc.sample create your muttrc file. See the sample for
   details.
4. If you didn't clone to ~/.mutt, symlink your muttrc file to either
   ~/.muttrc or ~/.mutt/muttrc.

This should get you going with mutt.
