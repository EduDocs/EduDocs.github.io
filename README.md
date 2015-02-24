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

A prime example of a software versioning and revision control system is [Git](http://git-scm.com/), which is a distributed version control system.
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

## Updating and Publishing the EduDocs Web Page

The EduDocs web page is generated using the automatic GitHub generator.
The source file is a subset of this README.md file, and it is authored using GitHub Flavored Markdown.
As such, modifications should simply be committed to this README.md page.
The web page can be updated by successively clicking __Settings__, __Automatic page generator__, __Load README.md__ (and edit), __Continue to layouts__, and __Publish Page__.


### Designer Templates

The template currently used for EduDocs is __Slate__.
After publishing a page, one can revisit the page generator and switch to another theme.
The page content will be preserved if it remained markdown format.


### Authors and Contributors

One can @mention a GitHub username to generate a link to their profile.
The resulting `<a>` element will link to the contributor's GitHub Profile.

