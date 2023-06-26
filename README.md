# Files manager

## Background Context
This project is a summary of this back-end trimester: authentication, NodeJS, MongoDB, Redis, pagination and background processing.

The objective is to build a simple platform to upload and view files:
- User authentication via a token
- List all files
- Upload a new file
- Change permission of a file
- View a file
- Generate thumbnails for images

We were guided step by step for building it, but we had some freedoms of implementation, split in more files etc... (`utils` folder was indeed helpful)

Of course, this kind of service already exists in the real life - it's a learning purpose to assemble each piece and build a full product.

## Resources
**Read or watch:**
- [NodeJS getting started](https://intranet.alxswe.com/rltoken/8jNm2s_LfVKMqR3vHLn_uw)
- [Process API doc](https://intranet.alxswe.com/rltoken/uYPplj2cPK8pcP0LtV6RuA)
- [Express getting started](https://intranet.alxswe.com/rltoken/SujfeWKCWmUMomfETjETEg)
- [Mocha documentation](https://intranet.alxswe.com/rltoken/FzEwplmoZiyGvkgKllZNJw)
- [Nodemon documentation](https://intranet.alxswe.com/rltoken/pdNNTX0OLugbhxvP3sLgOw)
- [MongoDB](https://intranet.alxswe.com/rltoken/g1x7y_3GskzVAJBTXcSjmA)
- [Bull](https://intranet.alxswe.com/rltoken/NkHBpGrxnd0sK_fDPMbihg)
- [Image thumbnails](https://intranet.alxswe.com/rltoken/KX6cck2nyLpQOTDMLcwxLg)
- [Mime-Types](https://intranet.alxswe.com/rltoken/j9B0Kc-4HDKLUe88ShbOjQ)
- [Redis](https://intranet.alxswe.com/rltoken/nqwKRszO8Tkj_ZWW1EFwGw)

## Learning Objectives
At the end of this project, we were expected to be able to explain to anyone, **without the help of Google:**
- how to create an API with Express
- how to authenticate a user
- how to store data in MongoDB
- how to store temporary data in Redis
- how to setup and use a background worker
