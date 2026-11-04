# RoboFrontier media: Oracle reference videos

Video files for the [RoboFrontier project page](https://changxuanfan.github.io/RoboFrontier/),
served from this repository's GitHub Pages. Source code and documentation live in
[changxuanfan/RoboFrontier](https://github.com/changxuanfan/RoboFrontier).

| Path | Content |
| --- | --- |
| `oracle/<task>-front.mp4`, `oracle/<task>-side.mp4` | Oracle reference run of each of the 36 released tasks, rendered in Robo World, 720p H.264. Privileged reference programs, some operator-assisted, not model results |
| `oracle/<task>-<view>.jpg` | Poster frame of each video |
| `oracle/manifest.json` | Size, duration and SHA-256 of every file, and the SHA-256 of its 1080p source render |
| `film/robofrontier-film-1080p.mp4` | The 3.5-minute tour of Robo World, 1080p |

Oracle runs are privileged references, not model results. Videos were encoded with
`scripts/site_media.py` in the main repository (libx264, CRF 28, preset slow, faststart).

Licensed under [CC BY 4.0](https://github.com/changxuanfan/RoboFrontier/blob/main/LICENSE-DATA.md).
