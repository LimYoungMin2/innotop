  1. Check out the whole SVN repository, including branches and trunk.
  1. Update the Changelog.
  1. Update 'our $VERSION' inside of innotop.
  1. Update the version in the innotop.spec file.
  1. commit.
  1. svn cp trunk into branches, commit again.
  1. export a clean copy to omit the .svn directory and rename it, e.g. `svn export branches/stable-1.8.0/ innotop-1.8.0`
  1. tarball that, e.g. `tar vzcf innotop-1.8.0.tar.gz innotop-1.8.0/`
  1. upload it, blog it, announce it on twitter, whatever.