# Gammapy Coding Sprint, July 2018, Heidelberg

* Start: Monday, July 9, 2018 at 2 pm
* End: Friday, July 13, 2018 at noon
* Location: MPIK Heidelberg, Germany (https://www.mpi-hd.mpg.de/)
* Contacts (local organisers):
[Christoph Deil](mailto:christoph.deil@mpi-hd.mpg.de),
[Roberta Zanin](mailto:Roberta.Zanin@mpi-hd.mpg.de),
[Axel Donath](mailto:Axel.@mpi-hd.mpg.de)
[Johannes King](mailto:Johannes.King@mpi-hd.mpg.de).

So far Gammapy has been mostly developed and used by people working on CTA and H.E.S.S.
But of course anyone is welcome! If you're from MAGIC, VERITAS, HAWC, KM3Net, ... and have time to come and talk to us, please do!

This is a "coding sprint" for people that want to work on Gammapy (http://gammapy.org/)
You're very welcome if you're new to coding or haven't contributed to Gammapy yet.
But note that this is not a workshop how to use Gammapy. We will also not do any tutorials how to hack on Gammapy, i.e. teach git, Github, Python, pytest and Sphinx. Instead we will pair experienced and new people and learn hands-on. If you want to prepare a bit, have a look at [gammapy-dev-tutorial](https://github.com/gammapy/gammapy-dev-tutorial) and learn a bit on your own before the coding sprint. Join the Gammapy Slack and feel free to ask anything there.

## Travel and hotel

If you haven't been to Heidelberg or MPIK, you can find some information [here](https://www.mpi-hd.mpg.de/mpi/en/contact/access-and-site-map/). MPIK is located a bit up the hill outside of Heidelberg, a 10 min ride with bus 39 will get you there.

To book a hotel or Airbnb, please do it yourself.
Good areas are downtown or Weststadt or Südstadt, i.e. near the bus line 39 that you will want to take to go to MPIK.
But really, Heidelberg is small and there are no "bad neighborhoods", you can stay anywhere you like.

There is the option to stay at the MPIK guest house. It's cheap, 35 Euro / night, see [price list](https://www.mpi-hd.mpg.de/mpi/fileadmin/files-mpi/2015_price_list_MPIK_guest_houses.pdf), good WIFI and easy to book by filling out [this form](https://www.mpi-hd.mpg.de/mpi/en/information-for/reservation/#2899). But most people prefer to stay in downtown Heidelberg to see a bit from the city and to have a shorter way home in the evening after dinner. There is no canteen at MPIK, only at nearby EMBL where we also go for lunch, and it closes at 7 pm.

Let us know if you have any questions!

## Agenda

### Monday

Monday afternoon is for presentations and discussions.

We start at **2 pm** and if you can't come, you can connect remotely (see [ezuce.txt](ezuce.txt))

With the given times, X + Y minutes means present for X minutes and leave Y minutes for discussion. Please be brief and focus on the issues and technical points only that are relevant for our work on Gammapy this week and in the near future.

* Jim Hinton (10 min): Welcome address
* Everyone (1 min each max): round table flash introductions (who you are, interest in Gammapy)
* Christoph Deil (5 min): [Workshop orientation](https://goo.gl/k3HSkf)
* Christoph Deil (5+5 min): [Gammapy project overview]()
* Roberta Zanin (5+5 min): CTA DC1 check analyses
* Lars Mohrmann (10+5 min): HESS FITS analysis validation (including [HESS test data release](https://www.mpi-hd.mpg.de/hfm/HESS/pages/dl3-dr1/))
* Cosimo Nigro (10+5 min): Joint Crab paper
* Quick tutorials for the new stuff that most people haven't seen or used:
  * Atreyee Sinha (10+5 min): What's new in maps?
  * Johannes King (10+5 min): What's new in modeling?
  * Hans Dembinski (10+5 min): [iminuit](http://iminuit.readthedocs.io/) (now used in Gammapy)
* Coffee break
* Status reports and open tasks for this week, using [Github projects](https://github.com/gammapy/gammapy/projects):
  * Johannes King (10+5 min): [GH project: data](https://github.com/gammapy/gammapy/projects/6), [slides]()
  * Christoph Deil (3+2 min): [GH project: IRFs](https://github.com/gammapy/gammapy/projects/5), [slides]()
  * Régis Terrier (10+5 min): [GH project: maps](https://github.com/gammapy/gammapy/projects/2), [slides]()
  * Johannes King (10+5 min): [GH project: modeling](https://github.com/gammapy/gammapy/projects/7), [slides]()
  * Christoph Deil (5+5 min): [GH project: spectrum](https://github.com/gammapy/gammapy/projects/3), [slides]()
  * David Fidalgo (5+5 min): [GH project: time](https://github.com/gammapy/gammapy/projects/4), lightcurve analysis, [slides]()
  * Marion Spir-Jacob (5+5 min): pulsar analysis
  * Roberta Zanin (10+5 min): [GH project: documentation](https://github.com/gammapy/gammapy/projects/1), [slides]()
* All: discussion
* 6 or 7 pm: walk down and go for dinner together in Schwarzer Peter / Weststadt (organised by Roberta)

### Tuesday

* 9 am : start - all meet in central seminar room (same as Monday)
* 9 - 10.30 coding session 1
* 10.30 - 11 coffee
* 11 - 12.30 coding session 2
* 12.30 - 2 lunch
* 2 - 3.30 coding session 3
* 3.30 - 4 coffee 
* 4.30 - 6 coding session 4
* 6 : barbecue at the "open air theatre" behind the library building (organised by Axel)

### Wednesday

* 9 am : start - all meet in central seminar room (same as Monday)
* 9 - 10.30 coding session 1
* 10.30 - 11 coffee
* 11 - 12.30 coding session 2
* 12.30 - 2 lunch
* 2 - 3.30 coding session 3
* 3.30 - 4 coffee 
* 4.30 - 6 coding session 4
* 6 : Walk together to Landessternwarte, then dinner in Altstadt (organised by Johannes)

### Thursday

* 9 am : start - all meet in central seminar room (same as Monday)
* 9 - 10.30 coding session 1
* 10.30 - 11 coffee
* 11 - 12.30 coding session 2
* 12.30 - 2 lunch
* 2 - 3.30 coding session 3
* 3.30 - 4 coffee 
* 4.30 - 6 coding session 4
* Dinner together in Altstadt (organised by tbd)

### Friday

* 9 am : start - all meet in central seminar room (same as Monday)
* 9 - 10.30 coding session 1
* 10.30 - 11 coffee
* 11 - 12.30 coding session 2
* End with lunch together, leave any time you like

## Rooms

The meeting will take place in the following rooms:

* Mo : central seminar room
* Tue : central seminar room
* We : video conference room
* Th : video conference room
* Fr : central seminar room

In addition, the following places are available for discussions or coding in small groups (usually 2-3 people):

* Video conference room is available all week for us, also on Mo, Tue, Fr
* Library building red sofas upstairs
* Bothe lab coffee tables
* Office Christoph (Bothe lab, room 241, phone 268)
* Office Roberta (Genter lab, room 303, phone 590)

## Registered Participants

1. Roberta Zanin, MPIK Heidelberg, Germany ([robertazanin](https://github.com/robertazanin))
1. Christoph Deil, MPIK Heidelberg, Germany ([cdeil](https://github.com/cdeil))
1. Axel Donath, MPIK Heidelberg, Germany ([adonath](https://github.com/adonath))
1. Johannes King, MPIK Heidelberg, Germany ([joleroi](https://github.com/joleroi))
1. Bruno Khelifi, APC, IN2P3/CNRS, France ([bkhelifi](https://github.com/bkhelifi))
1. Régis Terrier, APC, IN2P3/CNRS, France ([registerrier](https://github.com/registerrier)) (Monday-Wednesday)
1. Marion Spir-Jacob, APC, IN2P3/CNRS, France ([msjacob](https://github.com/msjacob))
1. Atreyee Sinha, APC, IN2P3/CNRS, France ([AtreyeeS](https://github.com/AtreyeeS))
1. David Fidalgo, UCM, Spain ([dcfidalgo](https://github.com/dcfidalgo))
1. Léa Jouvin, IFAE, Barcelona, Spain ([JouvinLea](https://github.com/JouvinLea))
1. Fabio Acero, CEA/Saclay, France ([facero](https://github.com/facero))
1. Cosimo Nigro, DESY Zeuthen, Germany ([cosimonigro](https://github.com/cosimonigro))
1. Kai Brügge, Uni Dortmund, Germany ([mackaiver](https://github.com/mackaiver))
1. Laura Vega Garcia, MPIfR Bonn, Germany ([lauvegar](https://github.com/lauvegar))
1. Hubert Siejkowski, ACC Cyfronet AGH, Poland ([hsiejkowski](https://github.com/hsiejkowski))
1. Andrew Chen, Wits University, South Africa ([mealworm](https://github.com/mealworm))
1. Lars Mohrmann, ECAP, Erlangen, Germany ([lmohrmann](https://github.com/lmohrmann)) (Monday-Tuesday)