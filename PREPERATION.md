 Preperations
=====================
Here are the things you have to prepare bevor running this Playbook:

 * Make sure you have the latest Ansible Version installed on you local computer
 * You have this repository cloned inclusive all submodules
 * You have your Computer with more ore less the same components like described in [INVENTORY.md](https://github.com/ToolboxBodensee/toolbox-voc_ansible/blob/master/INVENTORY.md).
   * There is a decklink card available - supported by [VOCs decklink-debugger](https://c3voc.de/wiki/decklink-debugger?s[]=decklink&s[]=debugger#decklink-debugger). *Github: [decklink-debugger](https://github.com/voc/decklink-debugger.git)*
   * You have the current debian version installed *(e.g. Debian 9)*.
   * You created the user ``ansible`` and allowed him to become root without asking for a password.
   * You are able to login as user ``ansible`` with your SSH Key.
 * You have at least looked into the ``group_vars`` and ``host_vars``
 * You have at leasted looked into ``ansible/hosts.ini``

### Remeber:
**If you need help...**
 + Ask in ``#chvoc`` on ``irc.chaostreff.ch``
 + Ask in the hackerspace [Toolbox](https://toolbox-bodensee.de/).


