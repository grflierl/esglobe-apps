These EsGlobe apps can be installed by

cd ~/public_html/esglobe

./install-app name

e.g.

./install-app makemap

If you've installed EsGlobe elsewhere, you need to edit the install-app to
reflect the changes.

Some of these assume that /var/www/html/esglobe points to the directory where
esglobe is installed.  Some of these have an "install" file which will copy
over large datasets.

* makemap : Convert to Eckert IV projection
* ocean : Ocean trajectories from Eccov4r2 climatology
* atmos : Atmospheric trajectories from GFS data; atmos/install will
           refresh it for the current snapshot
* esrl : Amospheric climatology from ESRL
* 307 : 12.307 includes atmos, esrl, ocean, makemap
* two : sample two-sphere display
* 8.012 : coriolis forces
