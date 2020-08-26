# shell-tools
Misc. shell utilities.

**apt-package-depend**: Prints a tree and a flat listing of an APT pacakge's
                        package dependencies.

**apt-upgrade**: A more complete APT package management upgrade(r).

**backup-timestamp**: Makes a backup copy of a file with a name suffixed with
                      the current time.

**cp-admin-to-remote-hosts**: Copies a file not owned by you to the same file
                              path location on one or more remote hosts,
                              retaining the same owner, group, timestamps and
                              rwx props on the remote hosts.

**eclipse-ide-prefs-backup**: Backs up all Eclipse IDE workspace preferences
                              for reuse in other workspaces or Eclipse
                              environments.

**execute-dependencies**: Accepts the file name of a shell script and prints to
                          stdout a line containg the simple names of the passed
                          in script's runtime executable dependenices.

**html-uncompress**: Uncompresses its input stream when the stream's
                     compression type is unknown, including not compressed
                     streams.

**http-req-headers**: Provides a local web browser's standard request headers,
                      for use with tools like curl, wget and lwp-request (GET).

**if-up-down**: Tool for listing available NICs and toggling them up/down.

**ip-geolocate**: Prints the city (region) and country in which its IP address
                  arg is located.

**iptbls-open-hole**: Opens a hole in the local iptables firewall, for network
                      communications that originate on the host xor remotely.

**iptbls-ssh-out-shell**: SSH-specific wrapper around iptbls-open-port.

**is-dns-available**: Returns 0 if an upstream DNS server is available,
                      non-zero if not.

**journal-tail**: Tails journald files or syslog using common journalctl, tail
                  and grep params.

**passwd-gen**: Generates likely random-enough passwords of any positive
                length. Likely secure enough for most use cases.

**process-stop**: Stops all processes with the same simple name.

**public-ip**: Prints to stdout host's IP as seen on the internet.

**remote-gui-start**: Starts a GUI on a remote host that displays in local
                      host's X Windows.

**rsync-updates-to-hosts**: Keeps a dir hierarchy on set of remote hosts in
                            sync with the same dir on the host it runs on.
                            On each synced host only the files it already has
                            in common with the source host are synced.

**service-start-stop**: Performs the most common service management commands
                        (start, restart, stop) on Linux systems, independent of
                        which services manager is installed.

**spellcheck**: Transforms aspell's default output to a nicer cmd line format.

**ssh-key-pari-gen**: SSH key-pair generator.

**tmp-user**: Creates a temporary user with a random first and last name. Its
              username is the first name all lowercase. Created users have home
              dirs and login shells, but no passwords. Also deletes users.
              First stops all the passed-in username's processes, then deletes
              it, including its home dir.

**tmp-user-run**: Runs a passed in command line under a randomly named temp
                  user. Deletes the user after the passed in command exits.

**tinyp**: World's tiniest project management application?

**z-old-logs-dev-null**: Reduces to size zero all log files last modified over
                         N days ago.

