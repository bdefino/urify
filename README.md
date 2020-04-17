# `urify` - generate a data URI
Sometimes, you're forced to communicate over a text-only channel: like IRC,
[`slack-term`](https://github.com/erroneousboat/slack-term), or even plain old
SMS.
For the occasional thrifty message, these mediums fulfill their purpose; but
for the heavy user, they aren't enough.

This tool employs [data URIs](https://tools.ietf.org/html/rfc2397) to enable
file transfer over restricted, text-only mediums.

