# DreamHost redirects

The home page is served by GitHub Pages at rieder.polsys.net. Two other addresses point to it from DreamHost:

- **polsys.net** has no site of its own and uses DreamHost's domain redirect to https://rieder.polsys.net/
  (set in the DreamHost panel, not in a file).
- **labs.polsys.net** stays a hosted site because tools run under labs.polsys.net/tools/ (e.g. RankFlow).
  Only its front page redirects, to https://rieder.polsys.net/software/, via the rule in
  `labs.polsys.net.htaccess`: copy those lines to the top of the `.htaccess` file in the labs web
  directory (create the file if there is none).

These files are not part of the Hugo build.
