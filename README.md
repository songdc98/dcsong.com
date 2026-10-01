# dcsong.com deployment

Website: https://dcsong.com/

Source: https://github.com/songdc98/songdc98.github.io

This repository publishes the source site's main branch at dcsong.com.
The source repository keeps https://songdc98.github.io/ independently available.
It redirects visitors only after the custom domain passes the site's health check.

Website content is edited in the source repository. Run the **Publish website**
workflow after a source update for immediate publication. The workflow also
checks for updates twice per hour while its scheduled runs are enabled.
GitHub can disable scheduled runs after 60 days of repository inactivity;
the published website remains online, and a manual run publishes the latest source.
