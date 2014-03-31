AutoZotBib is an extension for Zotero which will automatically export your Zotero library to a BibTeX file every time the library is changed.

You can control the export through the AutoZotBib Preferences menu by specifying one or more rules, where each rule consists of a tag name and a filename, separated by a colon. All Zotero items matching the given tag will be exported to the given BibTeX filename. The * tag can also be used to match all items in the library. Each rule should be given on a separate line. For example, to export all items to `/Users/jdoe/refs.bib`, you would enter:

	*:/Users/jdoe/refs.bib

To export items with tag "math" to `/Users/jdoe/math_refs.bib` and items with "science" to `/Users/jdoe/science_refs.bib`, just enter:

	math:/Users/jdoe/math_refs.bib
	science:/Users/jdoe/science_refs.bib

More information, and documentation, is available at www.rtwilson.com/academic/autozotbib

*Updates:*
- *v0.6* - Added option to turn off automatic exporting and click a menu item to export the BibTeX file (thanks bjonnh!)
- *v0.5* - First major release of AutoZotBib