# ffmpeg-heroku-libshine-only

A Heroku buildpack for ffmpeg that always downloads the latest static build.
Unlike other build packs, I never compile anything and remove this git.

MP3 conversion only!

## Usage

Add the following to your `.buildpacks`:

```
https://github.com/talhabalaj/ffmpeg-heroku.git
```

Or run the following from the heroku command line:

```
heroku buildpacks:add https://github.com/talhabalaj/ffmpeg-heroku.git
```
