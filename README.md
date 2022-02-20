# dirhash

A "fork" of [b3sum](https://github.com/BLAKE3-team/BLAKE3/tree/master/b3sum) with a crappy recursive directory hashing implementation and code optimizations.

Some of the [calculations](https://github.com/BLAKE3-team/BLAKE3/blob/4e84c8c7ae3da71d3aff5ba54d8ffa39a9b90fa0/b3sum/src/main.rs#L383) [in](https://github.com/BLAKE3-team/BLAKE3/blob/4e84c8c7ae3da71d3aff5ba54d8ffa39a9b90fa0/b3sum/src/main.rs#L386) [b3sum](https://github.com/BLAKE3-team/BLAKE3/blob/4e84c8c7ae3da71d3aff5ba54d8ffa39a9b90fa0/b3sum/src/main.rs#L464) can be done pre-compile which has been fixed in dirhash.

Mind me if there is 