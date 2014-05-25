# stratumctl

using haproxy, control which stratum your miners will hit.

usage:

    ./stratumctl <coin>

it will drop a fresh haproxy config and restart it, causing your miners to get disconnected,
they'll then reconnect on the new stratum.

this is like. super-alpha software. yoloswag and all that.
