# BV-BRC Command Line Interface

The [BV-BRC](https://www.bv-brc.org) is an integration of different types
of data and software tools that support research on bacterial
pathogens. The typical biologist seeking access to the BV-BRC data and
tools will usually explore the web-based user interface. However,
there are many instances in which programatic or command-line
interfaces are more suitable. For users that wish command-line access
to PATRIC, we provide the tools described in this document. We call
these tools the P3-scripts. They are intended to run on your machine,
going over the network to access the services provided by BV-BRC.

The BV-BRC CLI distribution is available at the [BV-BRC github
releases
page](https://github.com/BV-BRC/BV-BRC-CLI/releases). New
releases typically come out for MacOS first. We currently also support
Windows and Debian/Ubuntu and CentOS Linux.

The PATRIC CLI tutorial is [available here](https://www.bv-brc.org/docs/cli_tutorial/index.html).

Please note: If you run into permission problems starting the BV-BRC
app on your Mac, you can still use the CLI. The BV-BRC app is a little
wrapper around bringing up a Terminal window configured properly, and
we can this by hand.

To do this, start Terminal.app and use Cmd-N if necessary to bring up
a new window. Then run the following command in the Terminal window to
set up the window for using the BV-BRC CLI:

```
source /Applications/BV-BRC.app/user-env.sh
```
