# xmpp(+jitsi)

> build our own baseline federated communication infrastructure

# goals

Setup our own XMPP servers. Should support features like encrypted group chat. Should be able to connect via popular clients like [conversations][1].

## services

Potential services we might want to support our XMPP infrastructure & software that might provide that service:

* **xmpp** -> prosody?
* **video selective forwarding unit** (sfu) -> jitsi videobridge?
* **turn** -> ?
* **web client** -> ?
* **ldap** -> openldap?
* **sip** -> jigasi?

## features

* federated video chat
* posting audio messages to each other - possibly implement a small standalone web page that connects to an xmpp server???
* tie in with webrtc
* [speech to text/transcription][2]

# changelog

## 2019.3.2 hang out & document
hung out & talked about running our own infrastructure, the need for hackable conversational mediums, the churn & uncontrollability of proprietary solutions. start writing this idea up.

# resources

[1]: https://serverfault.com/questions/835635/what-prosody-modules-do-i-need-to-support-conversations
[2]: https://nikvaessen.github.io/jekyll/update/2017/08/24/gsoc2017_work_product_submission.html
