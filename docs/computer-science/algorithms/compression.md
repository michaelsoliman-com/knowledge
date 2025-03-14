# Compression

[compress](https://github.com/klauspost/compress) & [L4](https://github.com/pierrec/lz4) are nice Go packages for compression. [Brotli](http://brotli.org/) is amazing.

## Notes

- [Can compress PNG images well with pngquant.](https://twitter.com/michaelvillar/status/1445079263208787969)
- LZ4 compression is fast

## Links

- [Zstandard](https://github.com/facebook/zstd) - Fast real-time compression algorithm. ([HN](https://news.ycombinator.com/item?id=24714854)) ([HN 2](https://news.ycombinator.com/item?id=25455314))
- [Orz](https://github.com/richox/orz) - General purpose data compressor written in rust.
- [FiniteStateEntropy](https://github.com/Cyan4973/FiniteStateEntropy) - New Generation Entropy coders.
- [Snappy](https://github.com/google/snappy) - Fast compressor/decompressor.
- [Snappy Node](https://github.com/Brooooooklyn/snappy) - Fastest Snappy compression library in Node.js.
- [UPX](https://github.com/upx/upx) - Advanced executable file compressor.
- [gzip-js](https://github.com/beatgammit/gzip-js) - Pure JavaScript implementation of the GZIP file format.
- [Blosc](https://github.com/Blosc/c-blosc) - Blocking, shuffling and lossless compression library. ([HN](https://news.ycombinator.com/item?id=23484342))
- [wasm-flate](https://github.com/drbh/wasm-flate) - Fastest compression and decompression in the browser.
- [zlib](https://github.com/madler/zlib) - General purpose data compression library.
- [zlib-ng](https://github.com/zlib-ng/zlib-ng) - zlib data compression library for the next generation systems.
- [LZ4](https://github.com/lz4/lz4) - Extremely Fast Compression Algorithm. ([Web](https://lz4.github.io/lz4/)) ([HN](https://news.ycombinator.com/item?id=25915274))
- [How LZ4 works (2016)](http://ticki.github.io/blog/how-lz4-works/)
- [Handbook of Data Compression (2010)](https://www.springer.com/gp/book/9781848829022)
- [Faster integer compression in Go with SIMD using StreamVByte codec](https://github.com/rleiwang/svb)
- [fast_rsync](https://github.com/dropbox/fast_rsync) - Optimized implementation of librsync in pure Rust.
- [SDefl](https://github.com/vurtun/sdefl) - Small bare bone lossless compression library in ANSI C (ISO C90) that implements the Deflate (RFC 1951) compressed data format specification standard.
- [Pixz](https://github.com/vasi/pixz) - Parallel, indexed xz compressor.
- [Flywheel: Google’s Data Compression Proxy for the Mobile Web](https://colin-scott.github.io/personal_website/research/nsdi15.pdf)
- [Opus](https://github.com/xiph/opus) - Codec for interactive speech and audio transmission over the Internet.
- [minizip](https://github.com/nmoinvaz/minizip) - Zip manipulation library written in C that is supported on Windows, macOS, and Linux.
- [Comparing zstd/gzip/bzip2/lzma/xz Compression (2020)](https://etbe.coker.com.au/2020/06/06/comparing-compression/) ([Lobsters](https://lobste.rs/s/wd79sy/comparing_zstd_gzip_bzip2_lzma_xz))
- [ZFP](https://github.com/LLNL/zfp) - Compressed format for representing multidimensional floating-point and integer arrays.
- [PyTorch Implementation of the CVPR'19 Paper "Practical Full Resolution Learned Lossless Image Compression"](https://github.com/fab-jul/L3C-PyTorch)
- [Lossless compression of English messages using GPT-2](http://textsynth.org/sms.html) ([HN](https://news.ycombinator.com/item?id=23618465)) ([Code](https://bellard.org/nncp/gpt2tc.html))
- [NNCP: Lossless Data Compression with Neural Networks (2019)](https://bellard.org/nncp/) ([HN](https://news.ycombinator.com/item?id=27244004))
- [Visualizing gzip compression with Python (2020)](https://brennan.io/2020/09/22/compression-curves/) ([HN](https://news.ycombinator.com/item?id=24563372))
- [The Hitchhiker's Guide to Compression](https://go-compression.github.io/) ([Code](https://github.com/go-compression/go-compression.github.io)) ([HN](https://news.ycombinator.com/item?id=24691422))
- [Miniz](https://github.com/richgel999/miniz) - Single C source file zlib-replacement library.
- [Rationale for a Large Text Compression Benchmark (2009)](http://mattmahoney.net/dc/rationale.html)
- [LZSA](https://github.com/emmanuel-marty/lzsa) - Byte-aligned, efficient lossless packer that is optimized for fast decompression on 8-bit micros.
- [pigz](https://github.com/madler/pigz) - Parallel implementation of gzip for modern multi-processor, multi-core machines.
- [Precomp](https://github.com/schnaader/precomp-cpp) - Command line precompressor that can be used to further compress files that are already compressed.
- [pako](https://github.com/nodeca/pako) - High speed zlib port to javascript, works in browser & node.js.
- [A System to Transparently Compress Hundreds of Petabytes of Image](https://www.usenix.org/conference/nsdi17/technical-sessions/presentation/horn)
- [Kanzi](https://github.com/flanglet/kanzi-go) - Modern, modular, expendable and efficient lossless data compressor implemented in Go.
- [Data Compression With Arithmetic Coding (2014)](https://marknelson.us/posts/2014/10/19/data-compression-with-arithmetic-coding.html)
- [Snappy](https://github.com/golang/snappy) - Snappy compression format in the Go programming language.
- [Semantic Compression (2014)](https://caseymuratori.com/blog_0015)
- [fflate](https://github.com/101arrowz/fflate) - High performance (de)compression in an 8kB package.
- [etcpak](https://github.com/wolfpld/etcpak) - Extremely fast Ericsson Texture Compression and S3 Texture Compression (DXT1/DXT5) utility.
- [Zopfli Compression Algorithm](https://github.com/google/zopfli) - Compression library programmed in C to perform very good, but slow, deflate or zlib compression.
- [python-blosc](https://github.com/Blosc/python-blosc) - Python wrapper for the extremely fast Blosc compression library.
- [zip](https://github.com/kuba--/zip) - Portable, simple zip library written in C.
- [Compressing data with Parquet (2021)](https://dev.l1x.be/posts/2021/03/08/compressing-data-with-parquet/)
- [Lossless Text Compression](https://bilalonureskili.com/files/LTC_en.pdf) ([HN](https://news.ycombinator.com/item?id=26722960))
- [CompressAI](https://github.com/InterDigitalInc/CompressAI) - PyTorch library and evaluation platform for end-to-end compression research.
- [zipindex](https://github.com/minio/zipindex) - Package for indexing zip files and storing a compressed index.
- [COIN: COmpression with Implicit Neural representations (2021)](https://arxiv.org/abs/2103.03123) ([Code](https://github.com/EmilienDupont/coin))
- [Zippy](https://github.com/guzba/zippy) - Pure Nim implementation of deflate, zlib, gzip and zip.
- [ezip2dmg](https://github.com/getsentry/ezip2dmg) - Simple wrapper utility to decompress an encrypted ZIP into a newly mounted encrypted DMG.
- [Text Classification by Data Compression (2021)](https://maxhalford.github.io/blog/text-classification-by-compression/) ([HN](https://news.ycombinator.com/item?id=27440093))
- [JPEG compression algorithm explained](https://photo.stackexchange.com/questions/125283/two-exactly-the-same-jpg-images-with-one-image-more-than-twice-the-file-size-of)
- [NeuralCompression](https://github.com/facebookresearch/NeuralCompression) - Python repository dedicated to research of neural networks that compress data.
- [Compressing Multisets with Large Alphabets (2021)](https://arxiv.org/abs/2107.09202) ([Code](https://github.com/facebookresearch/multiset-compression))
- [Ouch](https://github.com/vrmiguel/ouch) - Easy and painless way of compressing and decompressing files in the terminal.
- [TinyJPG](https://github.com/OrlovEvgeny/TinyJPG) - Filesystem watcher and image compress.
- [Faster Compression with Snappy's S2 Extension (2021)](https://tech.marksblogg.com/snappy-s2-compression-golang.html)
- [Faster ZIP Decompression (2019)](https://tech.marksblogg.com/faster-zip-decompression-unzip-deflate-zlib-crc32-adler32-7zip-archiver.html)
- [Minimalist Guide to Lossless Compression (2019)](https://tech.marksblogg.com/minimalist-guide-compression.html) ([HN](https://news.ycombinator.com/item?id=29529137))
- [FreeArc'Next](https://github.com/Bulat-Ziganshin/FA)
- [Experiments with compression-related algorithms](https://github.com/Bulat-Ziganshin/Compression-Research)
- [Imager](https://github.com/imager-io/imager) - Automated image compression for efficiently distributing images on the web. ([Web](https://imager.io/))
- [Heatshrink](https://github.com/atomicobject/heatshrink) - Data compression library for embedded/real-time systems. ([HN](https://news.ycombinator.com/item?id=28687589))
- [Neural Network Compression Framework (NNCF)](https://github.com/openvinotoolkit/nncf) - Provides a suite of advanced algorithms for Neural Networks inference optimization in OpenVINO with minimal accuracy drop.
- [libdeflate](https://github.com/ebiggers/libdeflate) - Heavily optimized library for DEFLATE/zlib/gzip compression and decompression.
- [sltar](https://github.com/Gottox/sltar) - Minimal implementation of tar.
- [Box](https://github.com/bbqsrc/box) - Open Standard Archive Format, akin to zip or 7z but without the legacy baggage.
- [Box in D](https://github.com/gecko0307/box) - Simple archive format with UTF-8 filenames.
- [Bitbottle](https://code.lag.net/robey/bitbottle) - Modern archive format. ([Lobsters](https://lobste.rs/s/ywxuxj/bitbottle_modern_archive_file_format))
- [libarchive](https://github.com/libarchive/libarchive) - Multi-format archive and compression library. ([Web](http://www.libarchive.org/))
- [zlib by Cloudflare](https://github.com/cloudflare/zlib) - Cloudflare fork of zlib with massive performance improvements.
- [Inflate.jl](https://github.com/GunnarFarneback/Inflate.jl) - Julia implementation of zlib decompression.
- [miniz_oxide](https://github.com/Frommi/miniz_oxide) - Rust replacement for the miniz deflate/zlib encoder/decoder.
- [Hop](https://github.com/Jarred-Sumner/hop) - 25x faster than unzip and 10x faster than tar at reading individual files. ([HN](https://news.ycombinator.com/item?id=29178710))
- [Buzon](https://github.com/BuzonIO/zipfly) - Writing large ZIP archives without memory inflation. ([HN](https://news.ycombinator.com/item?id=29291381))
- [The QOI File Format Specification (2021)](https://phoboslab.org/log/2021/12/qoi-specification) ([HN](https://news.ycombinator.com/item?id=29625084))
- [QOI: Lossless Image Compression in O(n) Time (2021)](https://phoboslab.org/log/2021/11/qoi-fast-lossless-image-compression) ([Tweet](https://twitter.com/phoboslab/status/1463451635540180992)) ([HN](https://news.ycombinator.com/item?id=29328750)) ([Code](https://github.com/phoboslab/qoi)) ([Lobsters](https://lobste.rs/s/1hafjp/lossless_image_compression_o_n_time)) ([HN](https://news.ycombinator.com/item?id=29661498))
- [qoiview](https://github.com/floooh/qoiview) - QOI image viewer on top of the Sokol headers.
- [qoi_rs](https://github.com/whentze/qoi_rs) - Rust port of the Quite Okay Image format.
- [QOI](https://github.com/steven-joruk/qoi) - Rust implementation of the “Quite OK Image” format for fast, lossless image compression.
- [zig-qoi](https://github.com/MasterQ32/zig-qoi) - Implementation of the Quite-OK-Image format for Zig.
- [QOI Go](https://github.com/xfmoulet/qoi) - Pure Go encoder/decoder of the QOI image format.
- [QOI Rust](https://github.com/zakarumych/rapid-qoi) - Fast implementation of QOI format in Rust.
- [Implementing zip archiving in Golang: unzipping (2021)](https://notes.eatonphil.com/implementing-zip-in-go-unzipping.html) ([Lobsters](https://lobste.rs/s/0vrgbm/implementing_zip_archiving_golang))
- [lz-fear](https://github.com/main--/rust-lz-fear) - Fast pure-rust no-unsafe implementation of LZ4 compression and decompression.
- [Decompressing a Gzip File by Hand](https://ttay.me/blog/gzip_investigations/) ([HN](https://news.ycombinator.com/item?id=29336271))
- [librsync](https://github.com/librsync/librsync) - Remote delta-compression library.
- [Quantile Compression](https://github.com/mwlon/quantile-compression) - Lossless compressor and decompressor for numerical data using quantiles. ([Reddit](https://www.reddit.com/r/rust/comments/r2oinm/quantile_compression_qcompress_a_new_compression/)) ([Article](https://graphallthethings.com/posts/quantile-compression))
- [fzstd](https://github.com/101arrowz/fzstd) - High performance Zstandard decompression in a pure JavaScript, 8kB package.
- [snap](https://github.com/BurntSushi/rust-snappy) - Snappy compression implemented in Rust (including the Snappy frame format).
- [Image Compression Algorithm in Rust](https://github.com/umgefahren/image-comp-lib-rust) - New lossless image compression algorithm.
- [mjpeg2http](https://github.com/nola-a/mjpeg2http) - Pure C Mjpeg-over-HTTP server. ([HN](https://news.ycombinator.com/item?id=29980660))
- [go-tsz](https://github.com/dgryski/go-tsz) - Time series compression algorithm from Facebook's Gorilla paper.
- [Leanify](https://github.com/JayXon/Leanify) - Lightweight lossless file minifier/optimizer. It removes unnecessary data (debug information, comments, metadata, etc.) and recompress the file to reduce file size.
- [Brotli](https://github.com/google/brotli) - Generic-purpose lossless compression algorithm that compresses data using a combination of a modern variant of the LZ77 algorithm. ([Web](http://brotli.org/)) ([Visualizing Brotli Decompression](https://twitter.com/chordbug/status/1529814459501490176))
- [Brotli JS](https://github.com/yisibl/brotli-js) - Google brotli binding to Node.js via Rust and napi-rs.
- [lz-string](https://github.com/pieroxy/lz-string) - LZ-based compression algorithm for JavaScript.
- [divANS](https://github.com/dropbox/divans) - Crate meant to be used for generic data compression.
- [Dictionary Compression (2022)](https://kevincox.ca/2022/03/01/dictionary-compression/) ([HN](https://news.ycombinator.com/item?id=30517656))
- [Compressing and embedding a Wordle word list (2022)](https://nullprogram.com/blog/2022/03/07/) ([Lobsters](https://lobste.rs/s/smtr5t/compressing_embedding_wordle_word_list))
- [zlib](https://github.com/haskell/zlib) - Compression and decompression in the gzip and zlib format.
- [QOI — The Quite OK Image Format](https://qoiformat.org/) ([HN](https://news.ycombinator.com/item?id=30885668))
- [littleZip](https://github.com/Nexxkinn/littleZip) - Memory-friendly basic zip compression, decompression, and single file extraction for deno framework.
- [Libarchivejs](https://github.com/nika-begiashvili/libarchivejs) - Archive tool for browser which can extract various types of compression.
- [lz4dec](https://github.com/Siguza/lz4dec) - LZ4 block decompressor written in arm64 assembly.
- [Packing Bits For Compression (2022)](https://www.youtube.com/watch?v=74co_YG39Bw)
- [How LCEVC works – A new approach to video compression](https://www.lcevc.org/how-lcevc-works/) ([HN](https://news.ycombinator.com/item?id=30905736))
- [zstd-wasm](https://github.com/bokuweb/zstd-wasm) - Zstandard for browser, Node.js and Deno.
- [Crash Course on Data Compression](https://github.com/jermp/data_compression_course)
- [Silly Image Compression Idea (2022)](https://snufk.in/blog/silly-compression.html) ([HN](https://news.ycombinator.com/item?id=30979085))
- [go-unarr](https://github.com/gen2brain/go-unarr) - Go bindings for unarr (decompression library for RAR, TAR, ZIP and 7z archives).
- [libzip](https://github.com/nih-at/libzip) - C library for reading, creating, and modifying zip archives.
- [The smallest 256x256 single-color PNG file, and where you've seen it](https://www.mjt.me.uk/posts/smallest-png/)
- [Efficient Compression Tool](https://github.com/fhanau/Efficient-Compression-Tool) - C++ file optimizer. It supports PNG, JPEG, GZIP and ZIP files.
- [WASM PNG Image compressor](https://github.com/antelle/wasm-image-compressor)
- [libimagequant](https://github.com/ImageOptim/libimagequant) - Palette quantization library that powers pngquant and other PNG optimizers.
- [StreamVByte](https://github.com/lemire/streamvbyte) - Fast integer compression in C using the StreamVByte codec.
- [BZip3](https://github.com/kspalaiologos/bzip3) - Better, faster and stronger spiritual successor to BZip2.
- [Time-series compression algorithms, explained (2020)](https://www.timescale.com/blog/time-series-compression-algorithms-explained/)
- [Zstandard Worked Example](https://nigeltao.github.io/blog/2022/zstandard-part-1-concepts.html) ([HN](https://news.ycombinator.com/item?id=31411714))
- [Silly Lossy Text Compression Idea (2022)](https://snufk.in/blog/silly-compression-text.html) ([HN](https://news.ycombinator.com/item?id=31435978))
- [Lizard](https://github.com/inikep/lizard) - Efficient compression with fast decompression. ([HN](https://news.ycombinator.com/item?id=31500640))
- [lzbase62](https://github.com/polygonplanet/lzbase62) - LZ77(LZSS) based compression algorithm in base62 for JavaScript.
- [Halve the size of images by optimising for high density displays (2021)](https://jakearchibald.com/2021/serving-sharp-images-to-high-density-screens/)
- [What’s the best lossless image format? (2021)](https://siipo.la/blog/whats-the-best-lossless-image-format-comparing-png-webp-avif-and-jpeg-xl) ([HN](https://news.ycombinator.com/item?id=31657006))
- [Survey of 3D Compression and Streaming](https://github.com/tovacinni/awesome-3d-compression)
- [compress.js](https://github.com/alextanhongpin/compress.js) - Simple JavaScript based client-side image compression algorithm.
- [Python-LZ4](https://github.com/python-lz4/python-lz4) - LZ4 bindings for Python.
- [The tar archive format, its extensions, and why GNU tar extracts in quadratic time (2022)](https://mort.coffee/home/tar/)
