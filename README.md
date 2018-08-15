![Logo](images/PSBN_icon_160x160_sm.png)

# PSBN17-FileMaker-Module from mrwatson.de

Ever wanted to Perform Script by Name?

Make FM <-> FM APIs?

Yes?

But do I hear you say you can do that already in FileMaker 17 using Perform Script [ Specified: by Name ; … ] ?

Yes you can! *BUT* dynamic data sources cannot be reset in FileMaker 17, 
so if you're calling various files you'll need multiple dynamic data sources!

THIS module provides a pool of 50 dynamic data sources, so you don't have to think about it.

:-)

MrWatson
2018-08-15

## Getting Started

* The PSBN17 Module has been designed to be used as is - just add accounts + security as needed by your system (+ rename to PSBN if you wish).
* It has been forked from the PSBN Module and simplified to use FileMaker 17's Perform Script [ Specified: by Name. step.
* See Limitations below.

Download or clone this repository.

* The **current version** is in the "dist" folder.
* The development version is in the "source" folder.

### Slide shows

Download [MrWatson's Presentation from dotfmp 2017 "FM <-> FM APIs or Perform Script by Name"](http://www.dotfmp.com/file/118)
See the original PSBN presentation in the presentations folder

### Videos

None (Somebody wanna help me here?)

## Release

This is beta quality.

Please report bugs here in the Github's Issues.  It would be great if you could provide a fixed version in the issue, with notes, etc.

## Contributing

We welcome contributions from the community. That's what this is all about.

Above all, please vote for a native function [Perform Script [ by Name: ... ] - immediately + natively (Modular-FileMaker)](https://community.filemaker.com/ideas/1187), so that this module can be made redundant!

FileMaker files don't lend themselves well to Github since we can't do merges and pull requests. That's part of what this project is trying to change. But we can still use Github for issues, comments, and planning.

If you find a bug, please include a copy of the file with a Test that shows the bug in action if you can. Its the best way to get your issues addressed.  Bugs that are clearly demonstrated are easily fixed.

If you have a bug fix, please include a copy of the file with the bug fixed. And instructions on where it is.

If you have ideas, please flesh them out in a copy of the file and include it on the issue. Nothing gets an idea across like semi-functional code.

If you have use cases for this functionality, let me know, or post on the Product Idea's page.

## Limitations & known issues

Note: PSBN17 works for *ALL* Scripts (unlike PSBN(16) which has an upper limit).

The PSBN module only works for up to 50 different files.

- Should be enough for now

Non exact references to the same file may be treated as separate references.

- For example: "MyFile" and "MyFile.FMP12" are currently treated as separate references.

## Roadmap

- √ 2017-07-06 MrW PSBN Module for FileMaker 16
- √ 2018-05-15 FMI FileMaker 17 NATIVE Perform Script By Name
- √ 2018-08-15 MrW PSBN17 Module for FileMaker 17

…and what we'd like to see one day:

- … 20??-??-?? FMI FileMaker ?? 100% (reusable) Dynamic Data Sources ???

## Credits

MrWatson - created and designed, and eventually got round to publishing PSBN

Todd Geist - thanks for pioneered the Github thing (I have blatantly ripped this README file from his Generator Github repository)
