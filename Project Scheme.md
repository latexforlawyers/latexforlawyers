# Project Scheme #

## Definition and issues ##

The goal of the  LaTeX for Lawyers project is to:
- Create `biblatex` styles for different jurisdictions in the world.
- Create `LaTeX` templates and macros that are useful to lawyers and scholars.

Our aim in doing this is to coordinate work and produce set of styles which “play nicely” together, not to produce a single “one-size-fits-all” package – basically, lawyers should be able to use the different packages without having to learn everything again from scratch or radically change their documents. There may be useful macros and tools we can share, but we seek mainly seek compatibility.

At the moment, the main issues to be decided are:

1. Licensing the project and deciding on a licensing policy
  - Would propose the LPPL for distribution through TeXLive and others, and also because I like the maintainer clause. If the author is no longer involved, someone else can legally step in. Also, I would suggest that we always put `latexforlawyers` as a “secondary” maintainer so other project members will get priority and we can also insure to keep the works within our organisation. *@ienissei*
2. Contacting people who work on related projects, e.g. `juradiss`
3. Creating a general scheme for bibliography styles based on the one in `oscola`
  1. Deciding on how we intend to use the entry types and field names
  2. Deciding how to deal with `EU-law`, which could probably be a stand-alone package
4. Creating a general scheme for document templates and macro creation
  1. Deciding on some general macro names and implementation rules
  2. Deciding whether we can have some shared macros in a stand-alone package
5. Building the website once we have enough information (see fork)
  1. The website should be “lawyer-friendly” and explain our goals and aims
  2. It could show our work and the progress we are making, perhaps through diagrams
  3. It should tell people how they can help (by joining the crew or sending us samples of what they need)

## People working on the project ##

Responsibility means we are the ones in charge – not that we have to do everything. Those who want to focus on bibliography styles can do so, and those who focus on layout can do so as well; when other people join, responsibilities can be shared so that everything gets covered.

Joe (*@morninj*):
- Responsible for the overall project as far as Github is concerned – he is the one to go to for repository creation, etc.
- Responsible for `american-law` and `bl-bluebook`.

Paul (*@PaulStanley*):
- Responsible for `british-law` and `bl-oscola`.

Tormod (*@trmd*):
- Responsible for `swedish law` and `bl-swedish`.

Flora (*@ienissei*):
- Responsible for `french-law` and `bl-french`.
