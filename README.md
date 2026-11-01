# NextStep knee rehabilitation prototype

This prototype started from [Vivek's public Knee Recovery repository](https://github.com/viviscool/knee_recovery) at commit `31b1116db34954eab4560a9582a57ac9c7c6d05c`. It has a new name, visual design, icon and patient advice. The original repository is kept as the `upstream` remote.

## Run locally

From this directory:

```sh
python3 -m http.server 8765 --bind 127.0.0.1
```

Open <http://127.0.0.1:8765/>. Stop the server with Ctrl-C. Edit `index.html` to try changes, then refresh the page.

The page loads MediaPipe and the pose model from external services, so those features need an internet connection. Exercise tracking also needs browser camera permission. This copy has not been clinically validated.

## Licence

The MIT licence in [LICENSE](LICENSE) covers the HTML, CSS, JavaScript, text and icon in this repository. The public copyright notice uses "NextStep contributors". Third party services and libraries loaded by the page retain their own terms.
