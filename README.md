Rust FAT FS
===========

Cloned from [https://github.com/rafalh/rust-fatfs].

With this pulls already added:

- [Return IO object when unmounting and add flush method.](https://github.com/rafalh/rust-fatfs/pull/78)
- [New io](https://github.com/rafalh/rust-fatfs/pull/98)
- [Improvements](https://github.com/rafalh/rust-fatfs/pull/107)

Usage
-----

Add this to your `Cargo.toml`:

```
    [dependencies]
    fatfs = { git = "https://github.com/alexkazik/forked-rust-fatfs.git" }
```

no_std usage
------------

Add this to your `Cargo.toml`:

```
    [dependencies]
    fatfs = { git = "https://github.com/alexkazik/forked-rust-fatfs.git", default-features = false }
```

License
-------
The MIT license. See `LICENSE.txt`.
