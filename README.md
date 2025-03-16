# thelsa public key

## gpg pub key

fingerprint = C722 819E 95CC 1EAB A8B2  A727 0AD6 47B9 A949 7B0C

### gpg sub sign key

[thelsa-gpg-sub-sign-0E68EFFC7BECCD82.asc](https://raw.githubusercontent.com/theLSA/pub-key/master/thelsa-gpg-sub-sign-0E68EFFC7BECCD82.asc)

fingerprint = 3F5D C758 7BBA FB43 974F  A859 0E68 EFFC 7BEC CD82

```txt
-----BEGIN PGP PUBLIC KEY BLOCK-----

mDMEZ9a5phYJKwYBBAHaRw8BAQdASdkTws5dDbWmTW96Om+8FcMlSbw1jz4NzkbS
GYD67wW0MXRoZWxzYSA8MjgyNDg5NTYrdGhlTFNBQHVzZXJzLm5vcmVwbHkuZ2l0
aHViLmNvbT6IkAQTFggAOBYhBMcigZ6VzB6rqLKnJwrWR7mpSXsMBQJn1rmmAhsB
BQsJCAcCBhUKCQgLAgQWAgMBAh4BAheAAAoJEArWR7mpSXsMmWkA/Aynu6W1KJ11
pAWVEpWdIIcZtztp6fsQQXjSSRVVH5v/AQDhDfPgIW7mjbtbOA5I26JR0ydEzM43
cwcF9+Rmbz48C7gzBGfWugEWCSsGAQQB2kcPAQEHQLrz6P6MLLcA3J3FXgPb7h+N
8mjLKyuT43iLIe0PsT4ziO8EGBYIACAWIQTHIoGelcweq6iypycK1ke5qUl7DAUC
Z9a6AQIbAgCBCRAK1ke5qUl7DHYgBBkWCAAdFiEEP13HWHu6+0OXT6hZDmjv/Hvs
zYIFAmfWugEACgkQDmjv/HvszYLhvAEAkDOzzEGtH0Z8RbjAMm1U62P+jm0Qhf4f
cOxzJqLKRLABAKil/wo4BMxzJP9GhlKvA0jzHLitjtMj/HF8xPegWj0LAaABAJ0Y
x83DFbSDe98Sh/T1SdVHi5+T6iftml4IidOern5DAP9PIuxbGNPUC6Mvql7X6yrb
FcwuYY2xtdvSDjRi5rtjDg==
=ii6g
-----END PGP PUBLIC KEY BLOCK-----
```

## usage

### import sub sign key

```txt
gpg --import thelsa-gpg-sub-sign-0E68EFFC7BECCD82.asc
```

or

```txt
curl https://raw.githubusercontent.com/theLSA/pub-key/master/thelsa-gpg-sub-sign-0E68EFFC7BECCD82.asc | gpg --import
```

### verify sign

```txt
gpg --verify signfile.txt.sig
```
