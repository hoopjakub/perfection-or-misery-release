
# Perfection or Misery · Android releases

Perfection or Misery is a football draft roguelike: spin real club-seasons, draft an XI from them, get dropped into a league or a cup, and find out whether you end on Perfection or on Misery. It's free, with no ads and no purchases.

This repository holds the Android builds, nothing else. The game's code isn't here.

- **Download:** the newest release is under [Releases](https://github.com/hoopjakub/perfection-or-misery-release/releases/latest), as `perfection-or-misery.apk`. The website's download page has the same file, with install steps: [perfection-or-misery-website.vercel.app/download](https://perfection-or-misery-website.vercel.app/download).
- **No Android?** The same game plays in any phone's browser: [perfection-or-misery.vercel.app](https://perfection-or-misery.vercel.app).
- **Updates:** once installed, the game tells you when a new build is out and installs it over the old one. Your runs and your account stay.

## Installing

1. Download `perfection-or-misery.apk` and open it when it's done.
2. If Android asks, allow installs from your browser. Settings shows where.
3. Open the game.

## Checking the file

Each release lists the APK's SHA-256. The game checks it before installing an update; to check a download yourself:

- Windows: `certutil -hashfile perfection-or-misery.apk SHA256`
- macOS or Linux: `shasum -a 256 perfection-or-misery.apk`

The result must match the release's. If it doesn't, don't install it.

## Names

Club and competition names in this build are changed, and no crests or logos are used. Perfection or Misery isn't affiliated with any player, club, league or governing body.

## Contact

Questions and feedback: the [community](https://perfection-or-misery-website.vercel.app/community) on the website, or perfectionormisery@gmail.com.
