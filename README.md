# UserScript - Proxmox Hide "No valid subscription" popup

This userscript hides the "No valid subscription" popup that pops up after the user logs in.

This is a fork of the https://greasyfork.org/en/scripts/426091-proxmox-autologin userscript.

Things I changed:
- No longer logs in on the user's behalf
- Use a `MutationObserver()` instead of `setInterval()`
