# Community Development at Maker

A new Community Development site for MakerDAO because Gitbook sucks.

## Advantages

Well, no more gitbook - can't say that one enough. This also maintains the link structure of the current site, which is a plus. Moreover, it is far easier to work with, much more customisable, and allows us to include material components in `.md` files, which is amazingly cool and helpful. Also, you can overwrrite whatever page you like with your own template, which makes for better readability and more attractiveness for all the community flies out there wanting to learn about Maker and how to get involved.

## Work Done So Far

1. Ditch gitbook for mkdocs material and migrate all content across.
2. Minor edits to landing page, just for show and tell.
3. Entire Page Tree structure (phew!)
4. Renamed all README files to index files for sanity and ease.
5. Begin edits on old/broken/changed links.

### Edits Completed

This refers to using the output of `python -m mkdocs serve` or `build` to fix any broken links and generally update things I notice that are no longer present/relevant.

1. Contributing - noticed that there is no longer a Tools Guide (confused?) and General Contributors Guide (seems to be in the index now)
2. Translations
3. GnR Risk Meetings transcripts (phew!).
4. Hackathons
5. Meetups
6. Onbaording
7. FAQs
8. SCD FAQs
9. Grants
10. Risk

## To Be Done Notes

1. All Governance summaries and transcripts from 36-59 are not in the Page Tree. Is there a reason for this? 
2. All Governance Polls and Executive Votes - need to build proper index pages for both, probably rename files with a sane naming and dating convention.
3. Add these to the Page Tree.
4. Hackathon Winners page is empty. This makes me sad.
5. Risk disclaimer not currently in Page Tree. Have not updated because maybe there are legal reasons for that.
6. Favicon, logo and general styling ofc.

## Run It Yourself

1. Get [mkdocs](https://www.mkdocs.org/#installation)
2. Clone this repo.
3. Run `mkdocs serve` or `mkdocs build`. Depending on your OS/distro, you may need to `python -m mkdocs serve`. Sorry about the old version of python y'all ;)