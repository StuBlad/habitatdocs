
# habitatdocs
### Documents from Lucasfilm's Habitat converted to modern formats

This is a collection of all of the documentation and notes I could find from the [original Lucasfilm Habitat document archives](https://github.com/Museum-of-Art-and-Digital-Entertainment/habitat/tree/master/chip/habitat/docs).

My goal is to convert all of these to modern formats that are more easily readable, as the majority of them were created using *troff*.

For the text files that weren't typeset for *troff* and have no formatting, I am attempting to format them in *troff* and process them using *groff* to turn them into PDF's using the following command:

> groff -ms filename.itr | ps2pdf - filename.pdf

If you would like to format some of the plain text files into *troff*, add your completed work to the ***new*** folder in both *.itr* and *pdf* formats and feel free to submit a pull request.

## Documents with issues at this time (12/28/20)
The following documents will not convert cleanly using the above command at this time and are missing from this repository.

* congrats.itr
* ghu.itr
* ghu.itr.aug6
* ghuguide.itr
* objman.itr

If you are able to get these to output correctly, please submit them in PDF format with a pull request.

## Documents that require manual formatting into troff (12/28/20)
The following documents are just plain text and require a keen eye to format into something that looks pretty using *troff*

I recommend looking at the original *.itr* files for guidance on formatting. It would be preferable to replicate the same style from the original documents.

* abstract.t
* allocs.t
* aric.t
* aricpop.t
* aricpopAug.t
* avatarcustom.t
* barwood.t
* behind.t
* beta.t
* beta2.t
* beta3.t
* beta4.t
* bitmap.t
* blurb.t
* bugreport.t
* charlie.t
* chip (2).t
* chip.t
* classtest.t
* comm.t
* comments.t
* concept.t
* contVector.t
* contractComments.t
* contractComments2.t
* counters.t
* credits.t
* custom.t
* dbtasks.t
* demo.aric.t
* disk.t
* dnalsi.t
* dnalsiRant.t
* docs.t
* done (2).t
* done.t
* downtown.t
* draftplan.t
* farmerAdvs.t
* farmerAdvs2.t
* farmerComm.t
* glossary.t
* groups.t
* help_messages.t
* hostguide.t
* hostnotes.t
* hostnotes2.t
* ideas.t
* ideas1.t
* ideas2.t
* items.t
* items2.t
* keys.t
* meetingOct7.t
* memo.t
* messages.t
* milestones.t
* mondayChecklist.t
* moneyNotes.t
* muddle.t
* names (2).t
* names.t
* newclass.t
* newprocedure.t
* newsched.t
* newu.t
* nf.t
* notabugList.t
* notes.t
* oath.t
* orient.t
* palindromes.t
* patt.t
* plan.t
* plan2.t
* plex.t
* pr.t
* preplan.t
* protocol_notes.t
* qinfo.t
* qlog.t
* qmeeting.t
* qprobs.t
* randy.t
* realms.t
* regiontools.t
* resolution.t
* riddle.t
* robreqs.t
* sched2.t
* slur.t (**This one is a work in progress. See the 'new' folder.**)
* source.t
* stats.t
* status.Oct20.t
* status.Oct29.t
* status.t
* status2.t
* stratusMap.t
* summary.t
* survey.t
* tasks.t
* throttle.t
* tuesdayChecklist.t
* update.t
* version.t
* width.t
* worldTasks.t