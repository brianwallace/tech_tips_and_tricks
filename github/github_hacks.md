
# Audit organization members for two-factor authentication:

```
curl -H "Authorization: token [yours]" \
       "https://api.github.com/orgs/[orgname]/members?filter=2fa_disabled"
```

[Source](https://developer.github.com/changes/2014-01-29-audit-org-members-for-2fa/)

#  SSH Public Key Fingerprintview

To your ssh public key's fingerprint; compare this to what Github has listed in the ssh key audit

```
ssh-keygen -l -E md5 -f ~/.ssh/my-github-key.pub
```
