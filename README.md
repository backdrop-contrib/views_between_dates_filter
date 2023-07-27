# Between Dates Views Filter

This Views filter provides the between date functionality you are looking for:
display all nodes(comparing start and end dates) occurring on a specified date.

Creating this functionality with standard Date filters requires two filters:
start date less than or equal (<=) to the supplied date and end date greater
than or equal (>=) to the supplied date. The problem is two filters means users
must enter a date range, when technically "Show me all events in September." is
a range.

Effectively, it is the opposite of the standard "between" operator, which
compares one date field with two supplied dates.

## Installation

Install this module using the official Backdrop CMS instructions at
<https://backdropcms.org/guide/modules>.

## Usage

* Add the filter "Between Dates" to your View
* Select the start and end fields to compare.
* Adjust granularity to filter by year/month/date/hour/second.

## License

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.

## Maintainers

* [herbdool](https://github.com/herbdool)
* Seeking co-maintainers.

## Credits

Ported to Backdrop by [herbdool](https://github.com/herbdool).

This module is ported from the 7.x-1.x version for Drupal,
originally written and maintained by:

* [13rac1](https://www.drupal.org/u/13rac1)
* [shashikant_chauhan](https://www.drupal.org/u/shashikant_chauhan)
