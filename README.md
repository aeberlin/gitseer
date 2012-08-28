gitseer
=======

Gitseer is a small user-management DSL for GIT repositories.

This script is a rough bash port of a ruby script made by Richard Taylor at moocode.com.

You can read more about it here:

https://moocode.com/posts/6-code-your-own-multi-user-private-git-server-in-5-minutes

Usage Example (placed in .ssh/authorized_keys):
=======

command="/opt/gitseer/bin/gitseer username rw",no-port-forwarding,no-X11-forwarding,no-agent-forwarding,no-pty ssh-rsa AAA...
