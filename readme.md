# nats-streaming-cli

**Publish & subscribe to [NATS Streaming](https://nats-io.github.io/docs/nats_streaming/intro.html) channels.**

[![npm version](https://img.shields.io/npm/v/nats-streaming-cli.svg)](https://www.npmjs.com/package/nats-streaming-cli)
![ISC-licensed](https://img.shields.io/github/license/derhuerst/nats-streaming-cli.svg)
[![chat with me on Gitter](https://img.shields.io/badge/chat%20with%20me-on%20gitter-512e92.svg)](https://gitter.im/derhuerst)
[![support me on Patreon](https://img.shields.io/badge/support%20me-on%20patreon-fa7664.svg)](https://patreon.com/derhuerst)


## Installing

```shell
npm install -g nats-streaming-cli
```

Or use [`npx`](https://npmjs.com/package/npx). ✨


## Usage

```
Usage:
    echo 'a new message' | publish-to-nats-streaming-channel <channel-name>
Options:
	--encoding  -e  Encoding to encode the message payload with. Default: utf-8
```

```
Usage:
    subscribe-to-nats-streaming-channel <channel-name>
Options:
	--encoding  -e  Encoding to decode the message payload with. Default: utf-8
	--format    -f  How to format the messages. json, raw, inspect (default)
	--ack       -a  Acknowledge the messages received.
	--metadata  -m  Print the message payload along its metadata.
```


## Contributing

If you have a question or have difficulties using `nats-streaming-cli`, please double-check your code and setup first. If you think you have found a bug or want to propose a feature, refer to [the issues page](https://github.com/derhuerst/nats-streaming-cli/issues).
