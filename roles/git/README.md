git
===

Installs git and adds the following configuration:
- ~/.gitignore_global
- ~/.gitconfig

[git-config docs](http://git-scm.com/docs/git-config)

Variables:
- editor: The editor to use (ex: vim, nano, emacs)
  - required, default: vim
  - git uses this editor when editing messages
- git_user: A hash that contains a name and email key. (ex: ```git_user: { name: 'Tyler Cross', email: 'tyler@cross.com' }```)
  - optional
  - user config to use when making commits
