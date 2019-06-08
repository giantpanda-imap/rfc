# RFC
The following document lists the RFCs that are relevant for the GiantPanda project.

Currently the list does not distinguish RFC support by the different projects only what libmail (formally c-client) supports.

Items marked with [x]  are supported.


## Understand the syntax rules of most of the remaining documents
Note that some documents refer to RFC 2234 which has been replaced by RFC 5234.
- [ ] [RFC5234](https://tools.ietf.org/html/rfc5234)	Augmented BNF for Syntax Specifications - ABNF
- [ ] [RFC4466](https://tools.ietf.org/html/rfc4466)	Collected Extensions to IMAP4 ABNF


## Specify the IMAP protocol
- [x] [RFC3501](https://tools.ietf.org/html/rfc3501)	Internet Message Access Protocol - Version 4rev1


## Additional information which is useful in understanding the IMAP protocol
- [ ] [RFC1733](https://tools.ietf.org/html/rfc1733)	Distributed Electronic Mail Models in IMAP4
- [ ] [RFC2180](https://tools.ietf.org/html/rfc2180)	IMAP4 Multi-Accessed Mailbox Practice
- [ ] [RFC2683](https://tools.ietf.org/html/rfc2683)	IMAP4 Implementation Recommendations
- [ ] [RFC4549](https://tools.ietf.org/html/rfc4549)	Synchronization Operations for Disconnected IMAP4 Clients
- [ ] [RFC5530](https://tools.ietf.org/html/rfc5530)	IMAP Response Codes
- [ ] [RFC5788](https://tools.ietf.org/html/rfc5788)	IMAP4 Keyword Registry


## Extensions to the IMAP protocol
- [ ] [RFC4314](https://tools.ietf.org/html/rfc4314)	ACL
- [x] [RFC5257](https://tools.ietf.org/html/rfc5257)	ANNOTATE-EXPERIMENT-1
- [x] [RFC3516](https://tools.ietf.org/html/rfc3516)	BINARY
- [ ] [RFC4469](https://tools.ietf.org/html/rfc4469)	CATENATE
- [x] [RFC3348](https://tools.ietf.org/html/rfc3348)	CHILDREN
- [ ] [RFC4978](https://tools.ietf.org/html/rfc4978)	COMPRESS
- [ ] [RFC4551](https://tools.ietf.org/html/rfc4551)	CONDSTORE
- [ ] [RFC5259](https://tools.ietf.org/html/rfc5259)	CONVERT
- [ ] [RFC5267](https://tools.ietf.org/html/rfc5267)	CONTEXT
- [ ] [RFC5161](https://tools.ietf.org/html/rfc5161)	ENABLE
- [x] [RFC4731](https://tools.ietf.org/html/rfc4731)	ESEARCH
- [ ] [RFC5267](https://tools.ietf.org/html/rfc5267)	ESORT
- [ ] [RFC5466](https://tools.ietf.org/html/rfc5466)	FILTERS
- [x] [RFC5255](https://tools.ietf.org/html/rfc5255)	I18NLEVEL=1
- [ ] [RFC2971](https://tools.ietf.org/html/rfc2971)	ID
- [x] [RFC2177](https://tools.ietf.org/html/rfc2177)	IDLE
- [ ] [RFC5255](https://tools.ietf.org/html/rfc5255)	LANGUAGE
- [ ] [RFC5258](https://tools.ietf.org/html/rfc5258)	LIST-EXTENDED
- [ ] [RFC5819](https://tools.ietf.org/html/rfc5819)	LIST-STATUS
- [x] [RFC2088](https://tools.ietf.org/html/rfc2088)	LITERAL+
- [x] [RFC2221](https://tools.ietf.org/html/rfc2221)	LOGIN-REFERRALS
- [x] [RFC2193](https://tools.ietf.org/html/rfc2193)	MAILBOX-REFERRALS
- [ ] [RFC5464](https://tools.ietf.org/html/rfc5464)	METADATA
- [x] [RFC3502](https://tools.ietf.org/html/rfc3502)	MULTIAPPEND
- [x] [RFC2342](https://tools.ietf.org/html/rfc2342)	NAMESPACE
- [ ] [RFC5465](https://tools.ietf.org/html/rfc5465)	NOTIFY
- [ ] [RFC5162](https://tools.ietf.org/html/rfc5162)	QRESYNC
- [ ] [RFC2087](https://tools.ietf.org/html/rfc2087)	QUOTA
- [x] [RFC4959](https://tools.ietf.org/html/rfc4959)	SASL-IR
- [x] [RFC5256](https://tools.ietf.org/html/rfc5256)	SORT
- [x] [RFC5256](https://tools.ietf.org/html/rfc5256)	THREAD
- [x] [RFC4315](https://tools.ietf.org/html/rfc4315)	UIDPLUS
- [x] [RFC3691](https://tools.ietf.org/html/rfc3691)	UNSELECT
- [ ] [RFC4467](https://tools.ietf.org/html/rfc4467)	URLAUTH
- [ ] [RFC5524](https://tools.ietf.org/html/rfc5524)	URLAUTH=BINARY
- [ ] [RFC5738](https://tools.ietf.org/html/rfc5738)	UTF8 (EXPERIMENTAL)
- [x] [RFC5032](https://tools.ietf.org/html/rfc5032)	WITHIN


## SASL
- [x] [RFC4422](https://tools.ietf.org/html/rfc4422)	Simple Authentication and Security Layer (SASL)

### SASL mechanisms
- [x] [RFC4505](https://tools.ietf.org/html/rfc4505)	ANONYMOUS
- [x] [RFC2195](https://tools.ietf.org/html/rfc2195)	CRAM-MD5
- [x] [RFC4752](https://tools.ietf.org/html/rfc4752)	GSSAPI
- [x] [RFC4616](https://tools.ietf.org/html/rfc4616)	PLAIN


## Internationalization issues
- [ ] [RFC4790](https://tools.ietf.org/html/rfc4790)	Internet Application Protocol Collation Registry
- [ ] [RFC5051](https://tools.ietf.org/html/rfc5051)	i;unicode-casemap - Simple Unicode Collation Algorithm
- [ ] [RFC5738](https://tools.ietf.org/html/rfc5738)	IMAP Support for UTF-8 (EXPERIMENTAL)


## Primarily historic interest
- [ ] [RFC1732](https://tools.ietf.org/html/rfc1732)	IMAP4 Compatibility with IMAP2 and IMAP2bis
- [ ] [RFC2061](https://tools.ietf.org/html/rfc2061)	IMAP4 Compatibility with IMAP2bis
- [ ] [RFC2062](https://tools.ietf.org/html/rfc2062)	Internet Message Access Protocol - Obsolete Syntax


## Matters which are related to IMAP
- [ ] [RFC3503](https://tools.ietf.org/html/rfc3503)	MDN Profile for IMAP
- [ ] [RFC3656](https://tools.ietf.org/html/rfc3656)	MUPDATE Distributed Mailbox Database Protocol
- [ ] [RFC4468](https://tools.ietf.org/html/rfc4468)	Message Submission BURL Extension
- [ ] [RFC5092](https://tools.ietf.org/html/rfc5092)	IMAP URL Scheme
- [ ] [RFC5593](https://tools.ietf.org/html/rfc5593)	IMAP URL Access Identifier Extension


## List of IMAP relevant RFCs by imapwiki - https://www.imapwiki.org/ImapRFCList