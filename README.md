### What is MTA-STS?
MTA-STS is a security standard that ensures the secure transmission of e-mails via an encrypted SMTP connection. The acronym MTA stands for Message Transfer Agent, a program that transfers e-mail messages between computers. The abbreviation STS stands for Strict Transport Security, the protocol used to implement the standard. An MTA-STS-enabled Mail Transfer Agent (MTA) or Secure Message Transfer Agent (SMTA) works according to this specification and provides a secure end-to-end channel for sending emails over unsecured networks.
The MTA-STS protocol allows an SMTP client to verify the identity of the server and ensure that it is not connecting to an imposter by requesting the server to provide its certificate fingerprint in the TLS handshake. The client then verifies the certificate against a trust store containing certificates from known servers.

Source: https://powerdmarc.com/
