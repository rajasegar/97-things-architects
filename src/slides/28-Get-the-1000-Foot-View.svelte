<script>
 import Slide from '../lib/Slide.svelte';
</script>

<Slide>
<Slide>
<p><div class="chapter" title="Chapter 28. Get the 1,000-Foot View"><div class="titlepage"><div><div><h1 class="title"><a id="get_the_1_comma_000-foot_view"/>Chapter 28. Get the 1,000-Foot View</h1></div></div></div><div class="epigraph"><p>Erik Doernenburg is a technology principal at ThoughtWorks, Inc.,
      where he helps clients with the design and implementation of large-scale
      enterprise solutions.</p><div class="attribution"><span>—<span class="attribution">Erik Doernenburg</span></span></div></div><div class="informalfigure"><div class="mediaobject"><a id="I_mediaobject28_d1e1580"/><img alt="image with no caption" src="/images/id2707207/OEBPS/httpatomoreillycomsourceoreillyimages251936.png.jpg"/></div></div><p><span class="strong"><strong>AS ARCHITECTS, WE WANT TO KNOW</strong></span>
    how good the software is that we are developing. Its quality has an
    obvious external aspect—the software should be of value to its users—but
    there is also a more elusive internal aspect to quality, having to do with
    the clarity of the design, the ease with which we can understand,
    maintain, and extend the software. When pressed for a definition, this is
    where we usually end up saying "I know it when I see it." But how can we
    see quality?</p><p>In an architecture diagram, little boxes represent entire systems
    and lines between them can mean anything: a dependency, the flow of data,
    or a shared resource such as a bus. These diagrams are a 30,000-foot view,
    like a landscape seen from a plane. Typically the only other view
    available is the source code, which is comparable to a ground-level view.
    Both views fail to convey much information about the quality of the
    software: one is too high level and the other provides so much information
    that we cannot see structure. Clearly, what is missing is a view in
    between—a 1,000-foot view.<a class="indexterm" id="IDX-CHP-28-0117"/></p><p>This 1,000-foot view would provide information at the right level.
    It aggregates large amounts of data and multiple metrics, such as method
    count, class fan out, or cyclomatic complexity. The actual view very much
    depends on a specific aspect of quality. It can be a visual representation
    of a dependency graph, a bar chart that shows metrics at a class level, or
    a sophisticated polymetric view that correlates multiple input
    values.</p><p>Manually creating such views and keeping them in sync with the
    software is a hopeless endeavor. We need tools that create these views
    from the only true source, the source code. For some views—a design
    structure matrix, for example—commercial tools exist, but it is also
    surprisingly easy to create specialized views by combining small tools
    that extract data and metrics with generic visualization packages. A
    simple example would be to load the output from checkstyle, which is
    essentially a set of metrics on the class and method level, into a
    spreadsheet to render charts. The same metrics could also be shown as a
    tree-map using the InfoViz toolkit. A great tool to render complex
    dependency graphs is GraphViz.<a class="indexterm" id="IDX-CHP-28-0118"/><a class="indexterm" id="IDX-CHP-28-0119"/></p><p>Once a suitable view is available, software quality becomes a little
    less subjective. It is possible to compare the software under development
    with a handful of similar systems. Comparing different revisions of the
    same system will give an indication of trends, while comparing views of
    different subsystems can highlight outliers. Even with just a single
    diagram, we can rely on our ability to spot patterns and perceive
    aesthetics. A well-balanced tree probably represents a successful class
    hierarchy; a harmonious set of boxes might show code that is organized
    into appropriately sized classes. Most of the time a very simple
    relationship holds: if it looks good, it probably is good.</p></div></p>
</Slide>
		<Slide>
				<h2>28. Get the 1,000-Foot View</h2>
		</Slide>
</Slide>
