# email-phushing
finding phushing emails

1) Examine sender's email address for spoofing

The sender’s email looked official, like support@bank-secure.com, but the real company uses
support@bank.com. Attackers often add words like ‘secure’ or ‘helpdesk’ to trick users into trusting the
address.

2) Check email headers for discrepancies

When checking the email header, SPF and DKIM passed but DMARC failed. The email came through a
different mail server (mail.randomhost.net) instead of the company’s usual one. That’s a clear sign the
email might be spoofed.

3) Identify suspicious links or attachments

The email had no attachments but contained a link like bit.ly/verify-account that redirected to a fake login
page that copied the real company’s site. Always type the website manually instead of clicking on such
links.

4) Look for urgent or threatening language

The message said, “Your account has unusual activity, please verify within 24 hours.” Scammers use
urgency to make people act fast without thinking. Real companies give you time and explain issues
clearly.

5) Note any mismatched URLs

The email showed a link text like ‘www.paypal.com/login’ but hovering over it revealed ‘http://paypal-
security-check.com’. The mismatch means the link is fake — hovering before clicking helps you spot
these tricks.

6) Verify presence of spelling or grammar errors

The email said, “Your acount has been suspnded. Please click here immediatly.” These spelling errors and
unprofessional tone often show the email isn’t from a real organization.
