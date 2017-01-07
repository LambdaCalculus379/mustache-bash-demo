mustache-bash-demo
==================

Simple Mustache demos in bash

Purpose
=======

This repo is for testing and demonstrating simple demos in Mustache using Bash.

Configuration
=============

Before getting started, be sure to download and configure Mo, the
Mustache Template for Bash.

Mo is available [on GitHub](https://github.com/tests-always-included/mo).

Be sure to have *minimum* Bash 3.x and the "coreutils" package (for `basename` and `cat`) before you try running mo!

    # Download the binary
    curl -sSO https://raw.githubusercontent.com/tests-always-included/mo/master/mo

    # Make executable
    chmod +x mo

    # Move to the correct folder
    sudo mv mo /usr/local/bin

    # Test it!
    echo "hello" | mo

Afterwards
==========

Once everything is set up correctly, try some of the demos in the mo repo.

Additional Info
===============

TBA