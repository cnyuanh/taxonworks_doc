# Contributing

##  Where can I ask for help? 

[![Gitter][4]][3]. someone from the TaxonWorks community is almost certainly lurking, we can help you in real-time.

## How is TaxonWorks supporting developer contributions?

See [here](DEVELOPER_SUPPORT.md).

##  How do I report a bug or feature request?

First [read this][14].

Use the [issue tracker][13]. 

Some other conventions:

* Categorize your issue using a label.
* Use the prefix "task -" in the name to indicate the request for a new or improved task.
* Use the prefix of your project name if reporting errors with a specific project.

## How do I categorize a Issue on Github with a label?

[See their description.](https://github.com/SpeciesFileGroup/taxonworks/labels)

## I'd like to provide an interface or workflow idea?

Perfect.  Interface (e.g. forms, reports, searches) mockups are graphical ways of asking for new features. We love to see them.  To create a mockup you can use tools like Illustrator, Photoshop, or more technical design tools like Balsamiq or Sketch, or just draw them on paper and take a picture with your phone.  You can get them to us by opening an [issue][13] and attaching the image there.  Add a little story, or multiple pictures to help describe how you might use the interface.

## I use my current tools this way, and it is awesome, can I send you a video to show you?

Send! It is super useful for you to record your screen, or position a video campera to capture your work on-screen and arround you.  This way we see exactly how you work. You can send us big videos through file sharing services like http://www.dropsend.com/.

##  How do I set up my development environment?

See the [install_taxonworks][5] repository.

##  How do I submit changes to the code base? 

To get started, first [fork][1] this project on GitHub and follow the Installation steps listed above. Then make a new branch off of "development" and name it in the format of "feature-name" and start programming. The workflow for this project is that subsequent pulls from the "development" branch should be rebased into the new feature branch so that the latest commits on the feature branch are related to the feature that is being implemented, a more indepth explanation of this practice can be found [here][2]. Once the feature has been completed and tested thoroughly, submit a pull request to this repo and wait for it to be looked at and hopefully approved.

## Documenting code

TaxonWorks code [documentation][10] is done inline with [Yard tags][12]. 

## Is there a database schema I can see?

See [db/schema.rb](https://github.com/SpeciesFileGroup/taxonworks/blob/development/db/schema.rb), or, better, checkout out the model [documentation][10]. [Documentation on concepts](https://github.com/SpeciesFileGroup/taxonworks_doc/tree/master/concepts) is underway. You can also use a rake task to generate the current SQL structure, or Rails schema.rb.

[1]: https://help.github.com/articles/fork-a-repo/
[2]: https://www.atlassian.com/git/tutorials/merging-vs-rebasing
[3]: https://gitter.im/SpeciesFileGroup/taxonworks?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge
[4]: https://badges.gitter.im/SpeciesFileGroup/taxonworks.svg
[5]: https://github.com/SpeciesFileGroup/install_taxonworks
[10]: http://rdoc.taxonworks.org/frames
[12]: http://rdoc.info/gems/yard/file/docs/Tags.md
[13]: https://github.com/SpeciesFileGroup/taxonworks/issues
[14]: http://wiki.taxonworks.org/index.php/Feedback 
