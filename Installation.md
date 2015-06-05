# Installation Instructions #

Facile-proxy-manager uses python's [distutils](http://docs.python.org/distutils/index.html) for package creation or direct installation.

## Creating an RPM ##

To build a RPM package for a Linux system:

  * Download the latest [release](http://code.google.com/p/facile-proxy-manager/downloads/list) of facile-proxy-manager, or checkout the latest version from the [subversion](http://code.google.com/p/facile-proxy-manager/source/checkout) repository.

  * Run the following command:

```
python setup.py bdist_rpm
```

  * When the build command completes, there will be a RPM in the `dist` subdirectory.

## Other formats ##

The [distutils](http://docs.python.org/distutils/builtdist.html) documentation has more examples for building packages for other platforms.

## Initial Configuration ##

See the [README.txt](http://code.google.com/p/facile-proxy-manager/source/browse/trunk/README.txt) file for documentation on how to setup facile-proxy-manager for your proxy servers.