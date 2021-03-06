=====
Music
=====

.. figure:: ../images/screenshots/music-main.png
   :align: center
   :alt: TV Show section

   The Music section lists your albums which you can browse,
   scrape and edit.


Starting with version 2.2 MediaElch is able to scrape information about your music collection.

To use music scraping, your directory structure must look like the following:

 - ``/Volumes/Data/Music/Artist1``
 - ``/Volumes/Data/Music/Artist1/Album1``
 - ``/Volumes/Data/Music/Artist1/Album1/song.mp3``
 - ``/Volumes/Data/Music/Artist2``
 - ``/Volumes/Data/Music/Artist2/Album2``
 - ``/Volumes/Data/Music/Artist2/Album2/song.mp3``

This means every artist must have its own subdirectory and inside this directory
every album must be in another subdirectory. In MediaElchs settings add the
toplevel directory of the artists (in the example above this is ``/Volumes/Data/Music``).

Scrapers
--------

There is only one scraper for music artists and albums: "Universal Music Scraper".
This scraper combines `The Audio DB`_, AllMusic_ and Discogs_ for information about artists and albums.
In the settings you can select the language (just used for The Audio DB) and which one you prefer.
All images are scraped from Fanart.tv.
Extra fanart images are also downloaded automatically.
How many images should be loaded can be adjusted in the settings.
Set it to ``0`` if you don't want extra fanarts to be downloaded automatically.

.. _The Audio DB: https://www.theaudiodb.com/
.. _AllMusic: https://www.allmusic.com/
.. _Discogs: https://www.discogs.com/
