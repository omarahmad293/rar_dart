# rar

A dart package Provides decoder for RAR5 archives.
It follows the official documentation of RAR5 file format found at https://www.rarlab.com/technote.htm

## Unsupported features (yet)
* RAR <5
* SFX modules
* Decompression
* Decryption

## Usage
```dart
var rarArchive = RAR5(path);
rarArchive.showFiles();
```

## License
[License](LICENSE)