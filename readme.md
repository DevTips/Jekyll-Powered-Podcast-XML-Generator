# Jekyll Powered Podcast XML Generator

I wanted a clean way to organize my self-hosted podcast xml. Jekyll to the rescue!

## Usage
1. Install Jekyll
2. Clone this repo
3. Update the config file with your podcast info. The info that doesn't really change from episode to episode.
4. Edit the `_episodes/001-hello-world.yml` file, duplicate and fill it out for each episode of your podcast.
5. Run `jekyll build` in your directory.
6. A new file is generated in the `_upload-this` folder. Upload that xml file to the root of your server where your podcast is being hosted.
7. [Submit it to iTunes](https://www.apple.com/itunes/podcasts/specs.html), or not. I don't care.
