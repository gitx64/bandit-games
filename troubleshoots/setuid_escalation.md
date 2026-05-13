If there is a compiled binary with a setuid enabled, then if the user is in a group which has the execution right of that binary , then the unprevilleged user or restricted user can access all the things of the eUID (effective UID). Like accessing private files of the User, without even logging in to that. pretty scary huh!

Oh and dont be overwhelmed, cause group execution permission must be enabled in that case :) and you have to be in that group.
