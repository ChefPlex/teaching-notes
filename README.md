# Teaching Notes


Things I've taught, explained, built, demonstrated, or dragged into a room so people could understand them better.

Practical teaching materials from kitchens, studios, conference rooms, community spaces, and the occasional room where the real job was helping people stop being intimidated by the thing in front of them.

This is the shelf for classes, talks, handouts, and demonstrations that don't quite belong in a glass repo, a food app repo, or a TPM template repo. The common thread is teaching. Not teaching as performance. Teaching as translation.

Some of this material is polished. Some of it is old. Some of it was built for one specific room on one specific day, which is how a lot of useful teaching material gets born. Dates matter. Links rot. Product recommendations age. But the shape of a good explanation often survives longer than the tool list.

## Start Here

| If you want to… | Start with | Status |
|:---|:---|:---|
| Teach a hands-on class | [Knife skills](cooking/knife-skills/): the structure of a practical class, safety first | **Archived**: taught a long time ago; the teaching shape holds, but the equipment links and product picks are from 2009 |
| Give a talk that holds a room | [The Pasteur talk](talks/pasteurization-boiling-booze-saving-humanity-mostly-by-accident/outline.md): a story-led outline with a [source checklist](talks/pasteurization-boiling-booze-saving-humanity-mostly-by-accident/source-checklist.md) | **Working**: needs a source pass before a formal science or history setting |
| Teach program management to career changers | The [Year Up decks](project-management/year-up/), the [career-changer PM course](project-management/pm-for-career-changers.md) and [PM: A Thanksgiving Story](project-management/PM_Thanksgiving_Story.pptx) | **Active** |
| Add something of your own to this shelf | [The teaching-item template](templates/teaching-item-template.md) | |

The labels are defined under [Status Labels](#status-labels) below.

## What Is Here

### Cooking

- [`cooking/knife-skills/`](cooking/knife-skills/) - Underground Food Academy knife skills class from January 18, 2009. Knife safety, station setup, chef's knife basics, dice sizes, and the small miracle of putting a wet towel under a cutting board before someone discovers physics the hard way.

### Talks

- [`talks/pasteurization-boiling-booze-saving-humanity-mostly-by-accident/`](talks/pasteurization-boiling-booze-saving-humanity-mostly-by-accident/) - A Louis Pasteur talk about wine, beer, milk, microbes, pasteurization, vaccines, and the recurring historical pattern where someone tries to solve one practical problem and accidentally changes the world.

### Project Management

- [`project-management/year-up/`](project-management/year-up/) - Year Up ProSkills and Project Prep decks from the Fall 2015 and Fall 2016 cohorts, including the original Thanksgiving deck. I taught at Year Up from October 2014 to December 2018, and designed and taught a project management and LAMP+ elective there (LAMP: Linux, Apache, MySQL, PHP). No material from the LAMP+ side of the elective is on the shelf.
- [`project-management/pm-for-career-changers.md`](project-management/pm-for-career-changers.md) - A practical PM introduction for people coming in from other fields. The vocabulary, the lifecycle, the skills that actually matter, and how to get your first role, without the jargon. Grew out of the Year Up teaching.
- [`project-management/PM_Thanksgiving_Story.pptx`](project-management/PM_Thanksgiving_Story.pptx) - PM: A Thanksgiving Story. The Year Up Thanksgiving deck rebuilt as a modern 13-slide presentation: core project management concepts taught through planning Thanksgiving dinner, for a non-practitioner audience.
- [`project-management/research-department-pm-course-2001/`](project-management/research-department-pm-course-2001/) - A two-part project management course built around Microsoft Project, designed and taught in 2001 for about 30 people in the UCSF neurology department. **Archived.** All that survives is a dated line from an old résumé. The course files are not on the shelf.

### Archive Notes

Things I taught or presented where only the record survives. One line each, and nothing reconstructed.

| Item | When | What the record says |
|:---|:---|:---|
| Risk management courses at Taos, an IBM Company | 2011 to 2018 | Internal courses in risk management for the consulting practice I led. A résumé line; no materials. |
| *The Art of Glassblowing* (talk) | Not recorded | A talk title from an older profile export. Nothing else survives. |
| *ABA LRIS Panel: Websites* | Between 2005 and 2009 | An American Bar Association (ABA) Lawyer Referral and Information Service (LRIS) panel on web technology, from my years running IT at the Bar Association of San Francisco. The title and my own recollection; no materials. |

## How This Is Organized

Each teaching item should have its own folder:

```text
area/topic-title/
|-- README.md
|-- source/
|   `-- original-files-go-here
`-- notes.md, outline.md, handouts/, or whatever the thing actually needs
```

The `README.md` tells the story: what the thing was, who it was for, what someone should learn from it, and what needs to be fixed before teaching it again.

The `source/` folder holds the original files. That keeps the artifact intact while letting the repo explain it in plain English.

To start a new item, copy [`templates/teaching-item-template.md`](templates/teaching-item-template.md).

## Status Labels

Use these lightly. The point is clarity, not bureaucracy.

- **Active** - still useful as-is or close to it.
- **Working** - useful, but needs cleanup before being handed to people.
- **Archived** - preserved for history, reference, or reuse, but not current advice without review.

## A Note on Old Material

Old teaching material is not embarrassing. It is evidence.

The knife skills handout still has useful bones: stay safe, set up your station, hold the knife well, keep the board stable, practice the cuts. The equipment links and product recommendations are old enough that they should be checked before anyone treats them as current buying advice.

The Pasteur talk has a strong story and a good room-energy premise. It also has claims that deserve a source pass before being used in a formal science or history setting. Comedy and accuracy can live in the same room, but only if accuracy gets its own chair.

## What Is Not Here Yet

Earlier projects like the EEG feedback machine can live here later if there are notes, photos, diagrams, or enough story to make the artifact useful. For now, this repo starts with teaching materials that already have source files and a clear path into folders. The 2001 project management course is the one folder without source files.

That is enough. Start with the shelf you can actually label.

## License

Copyright (c) 2026 Eric White. Licensed under [CC BY 4.0](LICENSE): use it, adapt it, put it to
work in your own program. Credit is the only condition.

---

**Part of the ChefPlex TPM portfolio** | Status: Active | [I need to… find the right document across all the repositories](https://github.com/ChefPlex/tpm-templates/blob/main/PORTFOLIO-GUIDE.md) | [All repositories](https://github.com/ChefPlex)
