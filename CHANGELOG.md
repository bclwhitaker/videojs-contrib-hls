CHANGELOG
=========

## HEAD (Unreleased)
* @dmlap use contribflow to manage contributions ([view](https://github.com/videojs/videojs-contrib-hls/pull/275))
* @dmlap add a contribflow configuration ([view](https://github.com/videojs/videojs-contrib-hls/pull/276))
* @ntadej Do not unnecessarily reset to the live point when refreshing playlists. Clean up playlist loader timeouts. ([view](https://github.com/videojs/videojs-contrib-hls/pull/274))
* @gkatsev ensure segments without an initial IDR are not displayed in 4
* @mikrohard: wait for an SPS to inject metadata tags. ([view](https://github.com/videojs/videojs-contrib-hls/pull/280))
* @mikrohard: Trim whitespace in playlist. ([view](https://github.com/videojs/videojs-contrib-hls/pull/282))
* @dmlap add a contrib option to merge PRs without squashing ([view](https://github.com/videojs/videojs-contrib-hls/pull/287))
* @mikrohard allow playback of TS files with NITs. Don&#x27;t warn about PCR PIDs. ([view](https://github.com/videojs/videojs-contrib-hls/pull/284))
* @dmlap quicker quality switches when bandwidth changes. ([view](https://github.com/videojs/videojs-contrib-hls/pull/285))

--------------------

## 0.16.0
* support preload=none

## 0.15.0
* expose all ID3 frames and handle tags larger than 188 bytes

## 0.14.0
* performance improvements for HLSe

## 0.13.0
* Improved audio/video synchronization
* Fixes for live, HLSe, and discontinuities
* Rename internal methods to clarify their intended visibility

## 0.12.0
* support for custom IVs with AES-128 encryption

## 0.11.0
* embedded ID3 tags are exposed as an in-band metadata track

## 0.10.0
* optimistic initial bitrate selection

## 0.9.0
* support segment level AES-128 encryption

## 0.8.0
* support for EXT-X-DISCONTINUITY

## 0.7.0
* convert the HLS plugin to a tech

## 0.6.0
* Refactor playlist loading
* Add testing via karma

## 0.5.0
* cookie-based content protection support (see `withCredentials`)

## 0.4.0
* Live stream support

## 0.3.0
* Performance fixes for high-bitrate streams

## 0.2.0
* Basic playback and adaptive bitrate selection

## 0.1.0
* Initial release
