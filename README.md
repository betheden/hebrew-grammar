<a href="https://uhg.readthedocs.io/"><img src="https://readthedocs.org/projects/uhg/badge/?version=latest"></a>

# unfoldingWord Hebrew Grammar

These are the source files for the [unfoldingWord Hebrew Grammar](https://uhg.readthedocs.io/).

The unfoldingWord Hebrew Grammar (UHG) is a Biblical Hebrew reference grammar based on the [morphology codes](http://openscriptures.github.io/morphhb/parsing/HebrewMorphologyCodes.html) that appear in the [Open Scriptures Hebrew Bible](https://github.com/openscriptures/morphhb). It enables the global Church to gain the best possible understanding of the Hebrew grammar of the Old Testament.

## Downloads

Coming soon...

## Contributing

We welcome contributions! Please make sure you understand the goal of the project by reading the [UHG Introduction](https://uhg.readthedocs.io/en/latest/front.html). Then, follow the links below to get started.

### Reporting Issues

If you've notice a problem that needs address please create an [issue](https://git.door43.org/Door43/en_uhg/issues) with a description of the problem.

### Fixing Issues

If you would like to fix or enhance the grammar, you may use the [suggest an edit process](http://help.door43.org/en/knowledgebase/15-door43-content-service/docs/39-suggest-an-edit-on-dcs) to suggest changes.

### Regular Contributors

#### Branching Process

If you are a regular contributor, we use the [protected branch workflow](http://help.door43.org/en/knowledgebase/15-door43-content-service/docs/46-protected-branch-workflow) to make changes.

#### Milestones

We use [milestones](https://git.door43.org/Door43/en_uhg/milestones) to track the work we'd like to complete before a release.

#### Issues

Please create an [issue](https://git.door43.org/Door43/en_uhg/issues) for tasks that you are working on. Make sure that you:

* Assign yourself to the issue
* Add the issue to a milestone
* Add the blue "In Progress" label to the issue once you begin work on it.

Closing Issues: After your Pull Request for an issue has been reviewed and merged into the master repository, you can mark your issue closed and remove the "In Progress" label from the issue.

## Format

The UHG is written in [reStructuredText](http://www.sphinx-doc.org/en/master/rest.html), processed by [Sphinx](http://www.sphinx-doc.org/en/master/index.html), and hosted online by [Read the Docs](https://readthedocs.org/).

See the [reStructuredText Primer](http://www.sphinx-doc.org/en/master/rest.html) and the [Docutils reStructuredText Directives](http://docutils.sourceforge.net/docs/ref/rst/directives.html) documentation to learn how to use the syntax.

## Guidelines

Please refer to the [Grammar Guidelines](http://ug-info.readthedocs.io/en/latest/). Take note of the following as well:

* Use simple English as much as possible. Remember that a key goal of the project is to make entries translatable.
* Summary entries should consist of one to two sentences maximum.
* Articles should include basic information that would be included in a teaching grammar along with two to three good examples.
* Article length should be 250-500 words.
* Generally, you may only review and merge content from another contributor, not your own content.

## Roadmap

### Stage One

Start fresh and provide descriptions of grammatical concepts that show up in [Open Scriptures Hebrew Bible](https://github.com/openscriptures/morphhb) morphological data.

* 1-2 Glossary entry
* ~1 page article entry that provides more information and 2-3 examples like teaching grammars

This phase is nearly complete.

### Stage Two

* Tag the UHB with specific grammatical information (*interrogative* pronoun)
* Tag text with syntax information
* Evaluate (and adjust, if necessary) structural aspects of the morphological data scheme (see list below)
* Sort all verbs parsed as imperfect in UHB for cohortative and jussive forms
* Write additional entries as required by above steps

#### Items to evaluate:

* Add the following to parsing morphology?  causal particle; conditional particle; discourse particle; compound conjunction; particle of existence; particle of non-existence
* Separate "preposition with definite article" (Rd) into two distinct morphological items, "preposition" (R) + "definite article" (Td)?
* Re-evaluate: should the category "determined state" be included in the grammar, or should this be called "definite" instead? There is potential for confusion with Aramaic here.  In Hebrew, the "determined state" and "definite" are one and the same thing, but in Aramaic they are not.  Perhaps we should use the term "definite" in UHG in order to avoid confusion with the "determined state" in the UAG. 
* Parsing for questionable terms: H71 – proper name, feminine; H145 – common noun, masculine; H521 – common noun, feminine; H643 – common noun, masculine; H1847 - common noun, feminine (except masc. in Prov 2:10, 14:6, and Job 33:3); H2156 - common noun, feminine; H4530 – common noun, feminine; H4593 – common noun, feminine? (check textual problem); H5135 – Aramaic word, not Hebrew; H7452 – common noun, masculine; H2859 – common noun, masculine (feminine in Deut 27:23); H5116a – common noun, masculine (feminine in Job 8:6); H5183a – common noun, feminine (masculine in Job 36:16); H5183b – common noun, masculine; H6211a – proper name, feminine (Job 9:9); H6211b – common noun, masculine; H492 – adjective; H794 – common noun, feminine; H2233 – common noun, masculine; H2346 – common noun, feminine; H2898 – common noun, masculine; H3816 – common noun, masculine; H5895 – common noun, masculine; H6423 – pronoun, masculine singular; H7548 – common noun, feminine; H8574 – common noun, masculine; H5178 – common noun, masculine; H6635b - common noun, feminine; H8577 – common noun, masculine; H217a – common noun, masculine; H5971a – common noun, masculine; H5868a,b – common noun, masculine; H6643a,b – common noun, masculine; H17 – interjection; H24 – common noun, masculine; H681 – preposition; H786 – particle of existence; H837 – common noun, masculine; H1215 – common noun, masculine; H1383 – common noun, feminine; H1890 – common noun, masculine; H2440 – adverb; H2626 – adjective; H2958 – adverb; H3038 – ???; H4033 – common noun, masculine; H4227 – common noun, feminine; H4512 – common noun, masculine; H4596 – common noun, masculine; H6673 – common noun, masculine; H7315 – adverb; H7934 – adjective; H7946 – adjective; H8613 – proper name; H2791 – common noun, masculine; H6957a – common noun, masculine.
* Words to revisit in Phase 2:  H4605 – adverb, preposition, noun?  
* Textual issues in UHB to re-evaluate.  Song 6:12 –– proper name or not?  When is אוֹיֵב a noun, when a participle?  

### Stage Three

Either augment or create a new project based on the UHG to be used as a teaching grammar.
