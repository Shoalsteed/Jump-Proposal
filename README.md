# Jump-Proposal

This proposal focuses on solutions with naming conflicts among jump service operators with regards to registration expiry for registered domains. The issue this creates is reporting different keys for the same human-readable name. This allows access to registered domains that conflict with existing addressbook entries. A new service can use a name that was registered to an old service. This creates a "blind trust" element for a user at tiimes when trusting a destination. How can we create either consesus / policy or UX options to provide improved trust and security in the jump process for I2P network participants? 

**Solutions:**

Let the user set the expiry.
The registrar would publish the default expiration policy with the hostname. This would be included in the jump process, or 
Jump service operators could use this information when jumping the site. 

