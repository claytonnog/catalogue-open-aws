---
source:
  name: og-aws
  url: 'https://github.com/open-guides/og-aws'
id: kinesis-firehose
title: Kinesis Firehose
desc: ''
updated: '0'
created: '0'
data: {}
fname: s.kinesis-firehose
stub: false
parent: 2f2e0f63-3883-4f91-94ab-0fa7a50302b6
children: []
hpath: s.kinesis-firehose
---
# Kinesis Firehose

### Kinesis Firehose Gotchas and Limitations

- 🔸 📜 When delivering from Firehose to Elasticsearch, the JSON document cannot contain an “\_id” property. Firehose will not attempt to deliver those documents and won't log any error.
