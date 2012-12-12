Buzzy core environment
======================

This is an environment for [Buzzy](https://github.com/redjack/buzzy/) that
defines many common open-source applications and libraries.  If your own code
has any third-party libraries that it depends on, you can link to this
environment to automatically get package and recipe descriptions for those
dependencies, rather than having to manually code your own.

To link with this repository, add the following to the `.buzzy/links.yaml` file
in your project's environment:

    - git://github.com/redjack/buzzy-core.git
