# The Snowball Effect

The constraints of higher education are such that instructors have limited time to plan courses and reflect on curriculums.
Indeed, almost every engineering faculty member will assert that they somehow manage, perhaps barely, to juggle an untenable work schedule.
An important question then is: How should an instructor best prepare for lectures?
Identifying prime learning objectives and the most efficient teaching methodologies always provides fertile grounds for passionate discussions and academic debates.

A facet of the teacher dilemma that often receives less attention is the long-term impact of immediate preparation decisions.
Should an instructor focus exclusively on his or her next set of interactions with students, or should there be a tradeoff between an upcoming lecture and the long-term quality of a program?
It may be argued that a myopic view of teaching can lead to repetitive behavior, duplicated efforts and thereby prevent instructors from realizing their true academic potential.
A conscious decision to dedicate time to building lasting tools to subsequently enhance the productivity of an instructor, on the other hand, can elevate the quality of a program over time and hence benefit generations of students.
This philosophical approach applies to instructors, students and institutions alike.
For instance, out of a teaching workforce, what percentage of the faculty should be dedicated to building tools that support and boost the efforts of everyone else?

The perennial example of investing in the quality of education for future students is the authoring of books.
This represents a cherished tradition with a stupendous impact worldwide.
Still, engineering books are often the fruits of long and laborious undertakings by dedicated authors.
Furthermore, they often become term projects with no provision for evolution and continuity in the long run.
The present initiative looks at alternative means of creating pedagogical value out of everyday lesson planning and typical preparation times.
It discusses collaborative strategies and technologies that can help improve engineering education through incremental, concerted steps.


## Collaborative Authorship

Computer programmers and software engineers have developed a number of packages for source and revision control.
Although originally aimed at the creation of large software applications, these accessible tools can be employed to generate a plethora of educational documents, from curriculums to notes and questions.
Dissociating content from presentation seems key in having contributors focus on enhancing pedagogical materials.
At this point, it may be useful to differentiate the aforementioned tools from wikis and content management systems, which are themselves becoming increasingly popular.
By nature, wikis typically lead to mosaics of information snippets; whereas versioning systems, although technologically more involved, are proper vehicles for concerted efforts with established goals.
In other words, the former favors concurrent, yet compartmentalized authorship; whereas the latter enables true collaborative authorship.

A prime example of a software versioning and revision control system is [Git](http://git-scm.com/), which is a distributed version control system designed.
This software platform is free and open source, and it features a rich community of users and contributors.
In addition, [GitHub](https://github.com/) is a web-based hosting service for source code management; it is built on the Git revision control system and offers free accounts for open source projects.
It offers a rich set of features, yet simplicity is one of its main attributes.
Authors and software developers regularly employ Git to maintain current and historical versions of files such as source code, web pages, and documentation.
Some of our course notes are actively being developed as collaborative projects under Git and GitHub.

A powerful aspect of version control is that it enables multiple contributors to work on various parts of a project simultaneously, even in a geographically distributed setting.
Git keeps track of modifications and allows for the (mostly) seamless integration of valuable work.
Under GitHub, the Git editing cycle is actually very accessible.
This requires an eventual contributor to learn the technology, yet the rewards are many.
In particular, this is one possible way to improve educational documents through incremental, concerted steps.


## The Alignment of Deliverables and Valuables

Undergraduate students in engineering programs have to complete a capstone project as part of their education, due partly to the guidelines of the Accreditation Board for Engineering and Technology.
Many schools ask for a comprehensive report to fulfill the writing requirements of the course.
To bring up the quality of the projects, it may be possible to modify course requirements slightly and have students produce tutorials about the different technologies they are using.
The latter documents typically have much broader appeal and they can be used to bootstrap the projects of subsequent generations of students.
Tutorials still serve the original purpose of being a comprehensive writing exercise, yet they concomitantly raise the quality of the projects over time by contributing to the capstone culture.




# EduDocs.github.io

From a user perspective and after initialization, the basic work cycle under Git amount to the following steps.

* Clone: Use to instantiate a working copy of the master repository. This is usually the first command employed to establish a local working hierarchy under this paradigm.
* Fetch: The command imports changes on the remote server to the local working repository. Before editing a project, it is typically advisable to synchronize the working copy with the latest version of the file hierarchy available on the server.
* Edit source files: This is perhaps the most natural part of the cycle. Modify files, documents and folder as need, irrespective of the collaborative infrastructure.
Review changes: Before sharing documents, one can quickly view a summary of the changes that were made through .
* Fix mistakes: This is a good time to fix typos and mistakes. Sometimes, when things go wrong, the simplest option is to revert back to older versions of the files. This is easy to do through Git.
* Resolve conflicts: In some cases, someone else may have been working on the same project at the same time. As such, it is always safe to check if a new version of the project has been published on the server before committing your own work. Git offers several tools to identify potential editing conflicts and resolved such issues.
* Pull: The command fetches and merges changes on the remote server to the local working repository. Before editing a project, it is typically advisable to synchronize the working copy with the latest version of the file hierarchy available on the server.
* Add: The add command is used to add one or more files to staging. Only add pertinent files to the repository.
* Commit changes:
* Push: The last step of the cycle is to publish your work on GitHub and share the latest version with collaborators. Your changes will be integrated in the master repository and others can now see your contribution.



### Welcome to GitHub Pages.




This automatic page generator is the easiest way to create beautiful pages for all of your projects. Author your page content here using GitHub Flavored Markdown, select a template crafted by a designer, and publish. After your page is generated, you can check out the new branch:

```
$ cd your_repo_root/repo_name
$ git fetch origin
$ git checkout gh-pages
```

If you're using the GitHub for Mac, simply sync your repository and you'll see the new branch.

### Designer Templates
We've crafted some handsome templates for you to use. Go ahead and continue to layouts to browse through them. You can easily go back to edit your page before publishing. After publishing your page, you can revisit the page generator and switch to another theme. Your Page content will be preserved if it remained markdown format.

### Rather Drive Stick?
If you prefer to not use the automatic generator, push a branch named `gh-pages` to your repository to create a page manually. In addition to supporting regular HTML content, GitHub Pages support Jekyll, a simple, blog aware static site generator written by our own Tom Preston-Werner. Jekyll makes it easy to create site-wide headers and footers without having to copy them across every page. It also offers intelligent blog support and other advanced templating features.

### Authors and Contributors
You can @mention a GitHub username to generate a link to their profile. The resulting `<a>` element will link to the contributor's GitHub Profile. For example: In 2007, Chris Wanstrath (@defunkt), PJ Hyett (@pjhyett), and Tom Preston-Werner (@mojombo) founded GitHub.

### Support or Contact
Having trouble with Pages? Check out the documentation at https://help.github.com/pages or contact support@github.com and we’ll help you sort it out.
