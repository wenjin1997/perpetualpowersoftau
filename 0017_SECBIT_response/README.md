Date: 19 December 2019

Name: p0n1 (SECBIT Labs)

Location: Suzhou, China

Device(s):

- Intel(R) Core(TM) i7-8700K CPU @ 3.70GHz
- 32GB RAM
- Ubuntu 18.04 LTS

Challenge:

`challenge` file contains decompressed points and has a hash:

```
    11a4e851 ec36cafd fce6eb26 c6915a13
    7647ad12 cadc3481 874ed700 e2a294d6
    626d3759 c804bc0b 39d262ba a2fdc774
    c8a49007 27dca9c4 cd192c85 df805627
```

`challenge` file claims (!!! Must not be blindly trusted) that it was based on the original contribution with a hash:

```
    4f845066 b59d7f3d 56d3ffff 3dd9fa80
    f7230022 74fe9887 1e3df8ff 68eb58a4
    7ee2320c 98e73f0e c249da4c 81c04449
    246d9383 ec5b6193 9caebf9f d75423a1
```

Software used: https://github.com/arielgabizon/perpetualpowersoftau/commit/efbdeeee7deade64f2ddf807dbed299613442ddc

Response:

Blake2b:
```
    7772994b f95c38cd 7e018e43 38cb3f3a
    9c8e24bd 7675a6d8 47b2cff0 3125d146
    136c4160 93fb6d41 bc512724 f79eb8c5
    37b99121 257796ae cfcc4e14 38cba6f2
```

Time taken: 16 hours
