# Jump-Proposal

This proposal focuses on solutions with naming conflicts among jump service operators with regards to registration expiry for regigisted domains. The issue this creates is reporting different keys for the same human-readable name: allowing access to registered domains that conflict with existing addressbook entries. A new service can use a name that was registered to an old service. This creates a "blind trust" element for a user with trusting a destination.

**Solution:**

Let the user set the expiry.
The registrar would publish the default expiration policy with the hostname. This would be presented on the existing jump interstitial with a  "Make Permanent" option for the registered domain. Then we could also direct users who want permanent keys to permanent registrars. Jump service operators would then use this information when jumping the site.

- What would be the default expiry in the registration UI?
