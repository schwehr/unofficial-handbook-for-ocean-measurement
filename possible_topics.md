Possible topics to address

* Timeline of innovations.  E.g. when was chirp first used
* Key patents and publications
* Which sensors to cover? Multibeam sonar, single beam, Synthetic aperture sonar
  (SAS), sidescan, subbottom, ADCP, seismic, adcp, water chem through hull, CTD
  casts/XBT/Moving vessel profilers, bottom sampling, magnetometers, gravity,
  EM, weather, heat flow, radar from ships, sea surface height.  Why would you
  want to use any of these particular techniques
* Positioning systems from ancient up to now
   * Above water
   * Below water
   * The history of INS systems
   * Vertical datums, tides, waves, etc.
   * Horizontal Datums
* Time ntp, ptp, atomic clocks, troubles with xtal oscillators
* The evolution of processing algorithms for signal processing, processing
  pings, backscatter, water column, etc?  CUBE
* Platforms - traditional ships, launches, ROV, AUV, drifters, gliders, OBS/OBH,
  cabled observatories, moorings
* Ways to get data from sensors
   * Local storage - e.g. you retrieve the device
   * Local networking
   * Remote networking over a cable
   * Remote networking through the water column
   * Remote networking via RF
* Key open source software packages: MB-System, GMT, GMTplus (now dead), QGIS,
  PROJ, GDAL, sioseis, seismic unix, gpsd, libais, PDAL, entwine, ...
   * Jupyter Notebooks
   * PmagPy
   * https://www.gplates.org/
   * And ???
* What commercial software packages need mentioning
* Calibration and reporting
* Should this cover other topics like AIS ship tracking, aircraft tracking, bird observations, biological observations, camera observations, underwater lidar, bathy lidar, dredging, coring, etc?
* Basics of spatial data: points, lines, polygons, rasters, tiles, contours
* Platemotion - CORS stations, earthquake motion
* Operating systems and why they matter - Linux, VxWorks, Windows, embedded systems without much or any os
* Data storage
   * Media tradeoffs: lifetime, density, read speed, write speed, transportability, extendability, accessibility.
   * Hand written, film, paper tape, magnetic tape, spinning rust, Records/CDs, SSDs
   * Filesytems - DOS, EXT, VFS
   * Sharding and redundancy - RAID and distributed filesystems
   * Blob stores and cloud - AWS S3, Google GCS (gs://), …
* Platform design issues. Bubbles, Flexure, noise in the hull
* Power: Batteries, Fuels, Storage, Solar, mechanical power collection, grounding, rf noise isolation, avoiding shorts
* Issues from the environment - biofouling, gas in the sediment or water column, acoustic reflections from marine life, currents, pipeline reflections, marine cables and breakages, magnetic signatures of metal from humans, fishing gear (nets, lines, crab/lobster bots, fish cages), do sharks bite equipment?  Ice and sensors - noise and damage
* Debugging techniques
   * The dateline can be trouble, e.g. on NBP0209, the Kongsberg multibeam crashed everytime the ship transited the dateline
* Managing equipment deployment and recovery.  Cranes, winches, lines, anchor points, a-frames
* Material and point/coating issues
* Planning, hazards, uxo, legal/permitting
* Marine animal observing
* Who owns the samples, data, and other artifacts, what is the copyright of info, and what license is there?  What can be done with a sample?
* Watch standing, Note taking, etc.
   * Proposals for ship and instrument time
   * Paper, text, elog, office documents,  and other software, proprietary formats
   * What should a cruise report look like?  Who has excellent cruise reports available publicly?
* Understanding archive / compression / data formats.  This one could go on forever
   * Tar, zip, etc.
   * HDF4, HDF5, NetCDF, Zarr, Arrow, Proto, MessagePack, Thrift, ASN.1,
     FlatBuffers, GRIB (is horrible)
     https://en.wikipedia.org/wiki/Comparison_of_data-serialization_formats
   * XML, JSON, YAML, Jsonnet, etc.
   * Lzma, deflate, and tools for doing specific compressions - xz, bzip2, gzip.
     General compression versus domain specific, e.g. see
     https://gdal.org/drivers/raster/gtiff.html#creation-options
* Connectors and adhesives
* Scientific divers
* Human piloted submersibles
   * Alivin to Navy nuclear subs
   * Hard suits
* Animal tags - e.g. D-TAG
* Checklists
   * Planning
   * MOB
   * De-MOB
   * Sampling
* Installations, mountings, anchorings
   * Moorings
   * Cabling, burying, and armor - https://www.flickr.com/photos/ccom_jhc/3837923724/
* What apps are helpful to have on mobile phones or tablets that you take to sea?
* Seamanship
   * Knots
   * Parts of the ship
   * Safety, fires, gasses/enclosed spaces,
   * Plumbing and toilets - Do not put anything besides TP and human waste down
     the toilets on a research ship.  They clog super easily and the fixes can
     be pretty horrible
   * The crew.  Their positions.  How to interact with them.
   * Food, diets, and galley.  What to do if you have special dietary needs
   * Seasickness and other medical
   * Ask John Konrad
* And?
