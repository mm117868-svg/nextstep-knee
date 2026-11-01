# Knee Recovery local sandbox

This is a separate local copy of [Vivek's public Knee Recovery repository](https://github.com/viviscool/knee_recovery) for prototyping. The app is the original `index.html` at commit `31b1116db34954eab4560a9582a57ac9c7c6d05c`. The `sandbox` branch is for local changes. The original repository is kept as the `upstream` remote.

## Run locally

From this directory:

```sh
python3 -m http.server 8765 --bind 127.0.0.1
```

Open <http://127.0.0.1:8765/>. Stop the server with Ctrl-C. Edit `index.html` to try changes, then refresh the page.

The page loads Google Fonts, MediaPipe and the pose model from external services, so those features need an internet connection. Exercise tracking also needs browser camera permission. This copy has not been clinically validated.

The source repository does not declare a licence. Check permission with Vivek before publishing or distributing a modified version.
