**Date:** 20 December 2019 - 3 January 2020

**Name:** Golem Factory

**Location:** Warsaw, Poland

**Device(s):** Intel(R) Core(TM) i7-8700K CPU @ 3.70GHz 32873MB RAM

**Challenge:**

- Blake2b:
`a19b4a27fa845da8c9eb88b22192c822082fe9eea4f8850d75fe4681444e41c35611b7646022cc353df7079471e7cb366bbbd6ee24bdb67ac68a5ccb2f7ed7d4`

- URL: https://trusted-setup.s3.eu-central-1.amazonaws.com/challenge_18

**Software used:** https://github.com/arielgabizon/powersoftau/commit/2bd49903bac07485fe23e5ef1a2d5fa19561977b

**Response:**

- Blake2b: 
`6e3f4b98e6c205d0efa5abc917dd03e28864016df380936fa4e9865595c5d69863eff93e8badf8e6b8c8cbfd5ab3a415ef7ba50b86e124bd9bfcd3f9aab67124`

**Entropy sources:** random keyboard mashing

**Time taken:** 11 hours

**Side channel defenses:** the computer was locked in a separate server room; only one person entered the server room and accessed the computer during the ceremony (to run the computation); only one person knew the time of the computation

**Postprocessing:**

- Verified on the same machine using `verify_transform_constrained`:

Verification succeeded! Writing to `./new_challenge`...
Here's the BLAKE2b hash of the decompressed participant's response as `new_challenge` file:
`5a26015ba27d8164152407da8f9b87e47593f17ae4c260e467bac2ba9dda6f66c15fa352487604d1350ef33a3bfedb0d99e37b619161e27545017366274df76b`
