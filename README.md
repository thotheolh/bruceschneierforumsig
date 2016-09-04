# bruceschneierforumsig
Forum post signatures for https://schneier.com forum posts.


### Post Signature Formatting
Posts would be set according to the day in `DDMMYYYY` format and daily posts (according to GMT time)
would be placed into each day's file that contains the day as the name of the text file. The file would
include all the attested nickname followed by the forum's post timestamp.

PGP Signature would be computed over the Git Commit and to verift the signatures, you would essentially
need to clone the Git repository and compute a signature verification over the Git Commit.

More details on Git Signing and Verification can be found on the official Git website linked below:
https://git-scm.com/book/en/v2/Git-Tools-Signing-Your-Work

Make sure to use the Git Commit Verification instead of Tag Verification or other verification methods.


### PGP Signing Key:

```
-----BEGIN PGP PUBLIC KEY BLOCK-----
Version: GnuPG v2

mQENBFJjUPABCAC9i7Yypjn6fdj8av4s6KmP6WWQKgiaBStfk7pfItqgh9qoIF2s
W9zFEyzVb7PvjPvpzPPhwoK2U49eUpwC078rOU+iZ3SqAVTJuWcPijAcNVH0/QnX
nx8nribIuJ2wWatI2IMOlo887MqGk/MDjvTuFBCHsU0PSM0wmI6rpBxSiUzOac/a
QLvoBoSwn26fOoWeOqX46vU/gKxOycenaFGMCKxMvbJ11D0h/g/Lmo/Jm+S+a9jR
Y9aqMDFhXwf0WugPdKuMYt1bLaSP2dYQs93VwyIGYT9PPNvE9tWdKc5/QEUHHaRo
stUhXDRazmgPXc+H1gS2ImnBVef1JxC8elm5ABEBAAG0J1RheSBXZWkgWmUgR2Vy
YWxkIDx0d3pnZXJhbGRAZ21haWwuY29tPokBOQQTAQIAIwUCUmNQ8AIbAwcLCQgH
AwIBBhUIAgkKCwQWAgMBAh4BAheAAAoJEIiF+ZVvv8Gd+jwIAJQEY/LSwMGkBFgq
Wou6QLlsNxynPP65PTjXCxvl+AaR9WgwwMqE7avTSPQ2Q+X5tNwozc8VE/2EYgMm
flBJo5LfdnsB98XarQW9qzahA0v4q9SKRzI3bmniC9MQwXe3s+Pg8SSVcnjGMqR/
5BoSUkKj61FcZCFWdK03+aA9XV3y7bCk90KRlPjui7ZGJk5fd/ws3FLXfxXm6Qod
jtSztF6d/GZW6wQ7ToxBkjW245WyR0726uhdPKCdt6l5dhWNyaxa5n8yJusjzpEb
RTHBHi9KWPDW8Vuo/6Adh/uOYus0PXqTTpgaD41vTOHZrdsxu0r/LGS6gicwpTOj
ktOsUIi5AQ0EUmNQ8AEIANRBWbceLRtOBXp/OQFrB809+7YoWvxBKx1/0mQHfgXB
eg8ahGbCcZZWrHpe7rjHrzBuTsO1XnlYqEXQUAhyXMBOsUFTScaI35Nq6BjJ/YQS
djtPGx6ctkzIpFWbqktShcFkUm1ZnBaP/9uLv5tSMrF8rA0o0AassbGWe6tLnfwq
m7jZjHBFOGTsoOeXXkBp1PqMgBfUoQlyKLT9gsig3AZds7t9j5WHOUzLWGVimDG1
6yjgOrKlNl6ipZ/+omKeCymQnjhWNF7QIRAC8kEFXYf445jz1DaqXtcxdCfIZwOn
AmG9m7DAcHJkC72jJdkfRVh76DFeeKakGaskkG6DLEMAEQEAAYkBHwQYAQIACQUC
UmNQ8AIbDAAKCRCIhfmVb7/BndNKCACIuWv+apzSSt61Wqkyl+qmHTfb2KFFAnKR
OiEejoEbX1BZAvzI5tY2+rHPFGXuIO0ai0/9gVcZbPIcX3eZa8AOoAYRNsha5mAx
c7W8pDs8qjZNF7jw5nWBrPdCAUaWCzZdrNnuWKpBX5c2jVCaaOyQdXhLOO4M9vfQ
KvaPzSHe4+vkxhi0HYbTKB2PLAp5XmzwCMD3uaWubprdhw6UczhsGjy56qpIOEVW
ZDXbngTXbk0tjfgebYmNvknItmVkodVpGDx6YNcR/FiRcQBA3fe2qpJJOwt4FZpZ
ZpvED3OW1SZfkO4CmuDtP2YWDUzuv2XpDKkhZws4rF1W8GA5VTaf
=sDcZ
-----END PGP PUBLIC KEY BLOCK-----
```