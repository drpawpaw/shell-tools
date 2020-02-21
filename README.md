# shell-tools
Misc. shell utilities.

backup-timestamp: Makes a backup copy of a file with a name suffixed with the
                  current time.

execute-dependencies: Accepts the file name of a shell script and prints to
                      stdout a line containg the simple names of the passed
                      in script's runtime executable dependenices.

html-decode: Uncompresses its input stream when the stream's compression type
             is unknown, including not compressed streams.

http-req-headers: Provides a local web browser's standard request headers, for
                  use with tools like cat, wget and lwp-request (GET).

ip-geolocate: Prints the city (region) and country in which its IP address arg
              is located.

iptbls-open-port: Opens a port in the local iptables firewall, either for
                  outbound or inbound packets.

iptbls-ssh-out-shell: SSH-specific wrapper around iptbls-open-port.

