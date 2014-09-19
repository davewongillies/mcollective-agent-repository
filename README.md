# Mcollective repository agent
This agent updates svn or git repositories on your servers

# Configuration

```
plugin.repository.NAME.directory: '/opt/git_checkouts/foo'
plugin.repository.NAME.from: 'git://github.com/someone/foo'
plugin.repository.NAME.type: git
```

# Triggering runs
`mco rpc repository update NAME`
