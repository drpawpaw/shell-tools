# shell-tools
Misc. shell utilities.

**apt-upgrade**: A more complete APT package management upgrade(r).

**backup-timestamp**: Makes a backup copy of a file with a name suffixed with
                      the current time.

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

**journal-tail**: Tails journald files using common journalctl and grep params.

**passwd-gen**: Generates likely random-enough passwords of any length. Likely
                secure enough for most use cases.

**run-as-temp-user**: Runs a passed in command line under a randomly named temp
                      user. Deletes the user after the passed in command exits.

**spellcheck**: Transforms aspell's default output to a nicer cmd line format.

**ssh-key-pari-gen**: SSH key-pair generator.

**tinyp**: World's tiniest project management application?

