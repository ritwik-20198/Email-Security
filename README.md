# Email-Security

## This report focuses on:

* What is Email Security?
* EMAIL SECURITY REQUIREMENTS
* APPLICATION CON STRAINTS THAT INFLUENCE DECISION MAKING
* Cryptographic Primitives
* Cryptographic Algorithms
* Key Management


## EMAIL SECURITY REQUIREMENTS🛠️

There are two potential concerns about the security of email:
*Confidentiality. 
By default, email messages are unprotected during their transfer from the email sender’s
device to the email receiver’s device. During that transfer the email message resides on several email servers
and internet routers, as well as passing through various potentially unprotected networks. There are many
points at which, at least in theory, the contents of an email message could be viewed by someone other than
the intended recipient.

*Data origin authentication. 
Email messages are structured using a simple protocol that facilitates their
transfer. This protocol includes fields for specifying the sender, recipient and subject, as well as the message
itself. An informed attacker can fairly easily generate forged emails. In addition, at most of the points at which
an attacker can read a genuine email, the attacker could intercept and make changes to the email message
before forwarding it on to the recipient.
