# diskalert
A script to alert on a defined disk usage percentile

# Installation

Simply clone the repository, and then in the directory run the setup.py installer (may need root privileges).

```python setup.py install```

This will create the DiskAlert Python package in the default location, the diskalert binary in your path, and will install the diskalert man pages.

After installation, don't forget to setup the `/etc/diskalert.conf` file.

# Updating

Simply rerun the setup.py installer after cloning or pulling the repository. This will **not** update the `/etc/diskalert.conf` file.
