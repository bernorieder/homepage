# DreamHost redirects

The home page is served by GitHub Pages at rieder.polsys.net. polsys.net and labs.polsys.net stay on
DreamHost, and only their front pages redirect, so the tools hosted under labs.polsys.net/tools/ keep working.

- `polsys.net.htaccess` → polsys.net/ redirects to https://rieder.polsys.net/
- `labs.polsys.net.htaccess` → labs.polsys.net/ redirects to https://rieder.polsys.net/software/

Copy the lines into the `.htaccess` file of each site's web directory (create it if there is none; if
there is one, put them at the top). These files are not part of the Hugo build.
