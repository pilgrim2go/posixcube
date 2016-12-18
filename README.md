# posixcube

    usage: posixcube.sh -h HOST... [OPTION]... COMMANDS
    posixcube.sh version ${p666_version}
    POSIX.1-2008-standard automation scripting.

      -?        Help.
      -h HOST   Target host. May be specified multiple times.
      -u USER   SSH user. Defaults to \${USER}.
      -v        Show version information.
      -d        Print debugging information.
      -q        Quiet; minimize output.
      -i        If using bash, install programmable tab completion for SSH hosts.
      COMMANDS  Remote commands to run on each HOST.

    Examples:
      ./posixcube.sh -u root -h socrates -h seneca uptime
      
      Run the \`uptime\` command on hosts \`socrates\` and \`seneca\` as the user \`root\`.

    Source: https://github.com/myplaceonline/posixcube
