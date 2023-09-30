Welcome to my GitHub profile README. My civil name is Martin Baláž and I can be often find under the alias @sesquideus. Everywhere.

- I am an astronomer and software engineer by both profession and passion.
  I like to think I am carefully balancing between physics, applied mathematics and programming.
- Currently I work as a pipeline developer for METIS, Mid-Infrared [ELT](https://en.wikipedia.org/wiki/Extremely_Large_Telescope)
  Imager and Spectrograph in the [A*V](https://astarvienna.github.io) team at the University of Vienna.
- In my semi-free time I am also the software lead of the AMOS project at Comenius University
  and I cannot get myself to quit working for the education NGO [Trojsten](https://trojsten.sk/).

### Meteors
Most of my previous work revolved around meteors, as I did both my masters and PhD in meteor science.

In my semi-free time I am still the software lead of the [AMOS](https://fmph.uniba.sk/en/microsites/daa/division-of-astronomy-and-astrophysics/research/meteors/amos/) project,
a network of automated meteor camera stations.

- [`ASMODEUS`](https://github.com/sesquideus/asmodeus/) or All-Sky Meteor Observation Detection Efficiency Simulator, a virtual meteor observatory that
  was used in my master thesis for determination of meteoroid flux and selection bias effects. `Python`, also ported to `C++/Qt`
- [`AMOS client`](https://github.com/sesquideus/amos-client/), a persistent C++/Qt application that controls the collection of meteor data at remote stations.
  It communicates with a custom board over serial port, starts and stops the camera and sends periodic heartbeats and collected data to the central server `C++/Qt`
- [`AMOS sightings`](https://github.com/sesquideus/amos-sightings/), a script for local backup of meteor data and reencoding videos `Python`
- [`AMOS server`](https://github.com/sesquideus/amos-server/), the central website which manages the meteor sighting database and housekeeping data `Python/Django`
- [`vasco`](https://github.com/sesquideus/vasco/), a virtual all-sky corrector plate for all-sky cameras `Python/PyQt6`
- [`ubi`](https://github.com/sesquideus/ubi), a kernel density estimation framework for arbitrary metric spaces,
  which was the core of my dissertation thesis. There it was used to find the probability density function of incoming meteors.  `C++`

### Trojsten
Since the beginning of my bachelor's I have been a part of the NGO [Trojsten](https://trojsten.sk/),
which organizes multiple competitions and events concerning mathematics, physics, programming and puzzle hunts.
I have authored over 200 problems for the correspondence seminar [FKS](https://fks.sk/) and the
physics competition [Náboj physics](https://physics.naboj.org/).
In Trojsten I re-developed the way how problems and their solutions are written and published:

- [`dgs`](https://github.com/trojsten/dgs/), an automated document compositor / templating system.
  Written in `XeLaTeX`, `make` and `Python`, it makes heavy use of `jinja2` templating and `pandoc`.
  Also used to write and publish handouts and homework for students in a highly structured form.
- multiple simple simulations that were used in correspondence seminars
  - [`gravity`](http://alchemilka.fks.sk/~sesquideus/orbita/), a 2D solar system simulator (in Slovak) `JavaScript`
  - [`phase-portraits`](http://alchemilka.fks.sk/~sesquideus/fp/), a simulator of simple physical systems and their phase portraits (in Slovak) `JavaScript`
  - [`rocket`](http://alchemilka.fks.sk/~sesquideus/raketa/), a 2D simulator of a rocket (in Slovak) `JavaScript`
  - `spectre`, a simulator of electromagnetic spectra (not yet finished)  `JavaScript`

### Miscellanea
- [`argparsedirs`](https://github.com/sesquideus/argparsedirs/), a microscopic enhancement to `argparse` that enables using directories as inputs `Python`
- [`physics-fields`](https://github.com/sesquideus/physics-fields/), a package for evaluating scalar and vector fields `Python`
- [`astroworkshop`](https://github.com/sesquideus/astroworkshop/), a simple website for the annual Astroworkshop for students at Comenius University `Python/Django`

<!-- I realized that in highly structured, repetitive documents lots of metadata can be kept in the directory structure itself;
that many parts can (and _should_) be highly reusable; and most importantly that there should be a single source of truth.
The same applies to many other documents, such as lecture materials, handouts or homework sheets for students. -->
 
<!---
sesquideus/sesquideus is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
