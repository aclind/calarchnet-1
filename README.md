# Demo search

Here's a bare-bones example search form and a browse link, which produces finding aids with the terms `architect*` and/or `california` in subject headings.


## Search collections

<form action="http://www.oac.cdlib.org/search" method="get" id="search-form" target="_blank">
<input type="hidden" name="subject" value="architect* california"/>
<input type="hidden" name="sort" value="title"/>
<input type="text" maxlength="200" name="query"/>
</form>

## <a href="http://www.oac.cdlib.org/search?subject=architect*+california&sort=title&query=">Browse collections</a>
