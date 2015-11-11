# Tuts+ Courses Videocheck

## Usage
`videocheck [OPTION]... [FILE]...`

## Description
Check video FILEs for formatting according to Tuts+ course video standards.
Test encoding, resolution, presence of audio and video channels.
Also detect black regions in the video channel and silent regions in the audio channel.

## Options

flag | description
--- | ---
`-v`, `--verbose`      | verbose output, output video encoding info
`-?`, `--help`         | display usage information
`--fast`               | fast mode, only key frames of the video will be examined (may introduce inaccuracies)
`-i`, `--info`         | info only mode, only the video header will be examined


## Example

`videocheck *.mp4`
