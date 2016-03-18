=================
JobsIFit Template
=================

JC, this repo fixes the problems with the code you sent me. I left it mostly
unchanged other than the structural fixes. In other words, I did not change
the application at all. I just did a bit of re-organization.

The exceptions are a couple of commented lines in ``urls.py`` and some gentle
renames to conform to Python PEP8 naming standards.

Additionally I threw in some other goodies to help tame the beast.

To use Vagrant you'll need to set the environment variable
``VAGRANT_BOXES_URL``::

    export VAGRANT_BOXES_URL="https://s3.amazonaws.com/<redacted>/vagrant"

Careful not not use a trailing slash on that URL. The ``<redacted>`` portion
is specific to my AWS account and I don't want it in a public repository.
I'll email it to you.

Then just do ``vagrant up``.

Note that the VM is a VirtualBox VM.
