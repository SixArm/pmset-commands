# pmset commands for power management settings for macOS

Commands:

* [`pmset-battery-full`](pmset-battery-full): Is the battery fully charged?
* [`pmset-battery-percent`](pmset-battery-percent): Show the internal battery % charged.
* [`pmset-drawing`](pmset-drawing): What is the power manager drawing from?
* [`pmset-drawing-ac-power`](pmset-drawing-ac-power): Is the system is drawing from AC power?
* [`pmset-drawing-battery-power`](pmset-drawing-battery-power): Is the system drawing from battery power?
* [`pmset-powerful`](pmset-powerful): Is the power manager ready for powerful work?

Examples:

    $ pmset-battery-full && echo "yes" || echo "no"
    yes

    $ pmset-battery-percent
    100

    $ pmset-drawing
    AC Power

    $ pmset-drawing-ac-power && echo "yes" || echo "no"
    yes

    $ pmset-drawing-battery-power && echo "yes" || echo "no"
    no

    $ pmset-powerful && echo "yes" || echo "no"
    yes


## Tracking

  * Package: pmset-commands
  * Version: 2.0.1
  * Created: 2015-06-30
  * Updated: 2017-11-02
  * License: GPL
  * Contact: Joel Parker Henderson (joel@joelparkerhenderson.com)

