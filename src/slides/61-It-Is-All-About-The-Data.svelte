<script>
 import Slide from '../lib/Slide.svelte';
</script>

<Slide>
<Slide>
<p><div class="chapter" title="Chapter 61. It Is All About The Data"><div class="titlepage"><div><div><h1 class="title"><a id="it_is_all_about_the_data"/>Chapter 61. It Is All About The Data</h1></div></div></div><div class="epigraph"><p>Paul W. Homer is a software developer, writer, and occasional
      photographer, who was drawn into software development several decades
      ago and has been struggling ever since with trying to build increasingly
      complex systems.<a class="indexterm" id="IDX-CHP-61-0279"/></p><div class="attribution"><span>—<span class="attribution">Paul W. Homer</span></span></div></div><div class="informalfigure"><div class="mediaobject"><a id="I_mediaobject61_d1e3469"/><img alt="image with no caption" src="/images/id2716310/OEBPS/httpatomoreillycomsourceoreillyimages251956.png.jpg"/></div></div><p><span class="strong"><strong>AS SOFTWARE DEVELOPERS</strong></span> we
    initially understand software as a system of commands, functions, and
    algorithms. This instruction-oriented view of software aids us in learning
    how to build software, but it is this very same perspective that starts to
    hamper us when we try to build bigger systems.</p><p>If you stand back a little, a computer is nothing more than a fancy
    tool to help you access and manipulate piles of data. It is the structure
    of this data that lies at the heart of understanding how to manage
    complexity in a huge system. Millions of instructions are intrinsically
    complicated, but underneath we can easily get our brains around a smaller
    set of basic data structures.</p><p>For instance, if you want to understand the Unix operating system,
    digging through the source code line-by-line is unlikely to help. If,
    however, you read a book outlining the primary internal data structures
    for handling things like processes and the filesystem, you'll have a
    better chance of understanding how UNIX works underneath. The data is
    conceptually smaller than the code and considerably less
    complicated.</p><p>As code is running in a computer, the underlying state of the data
    is continually changing. In an abstract sense, we can see any algorithm as
    being just a simple transformation from one version of the data to
    another. We can see all functionality as just a larger set of well-defined
    transformations pushing the data through different revisions.</p><p>This data-oriented perspective—seeing the system entirely by the
    structure of its underlying information—can reduce even the most
    complicated system down to a tangible collection of details. A reduction
    in complexity is necessary for understanding how to build and run complex
    systems.<a class="indexterm" id="IDX-CHP-61-0280"/></p><p>Data sits at the core of most problems. Business domain problems
    creep into the code via the data. Most key algorithms, for example, are
    often well understood; it is the structure and relationships of the data
    that frequently change. Operational issues like upgrades are also
    considerably more difficult if they affect data. This happens because
    changing code or behavior is not a big issue, it just needs to be
    released, but revising data structures can involve a huge effort in
    transforming the old version into a newer one.</p><p>And of course, many of the base problems in software architecture
    are really about data. Is the system collecting the right data at the
    right time, and who should be able to see or modify it? If the data
    exists, what is its quality and how fast is it growing? If not, what is
    its structure, and where does it reliably come from? In this light, once
    the data is in the system, the only other question is whether or not there
    is already a way to view and/or edit the specific data, or does that need
    to be added?</p><p>From a design perspective, the critical issue for most systems is to
    get the right data into the system at the right time. From there, applying
    different transformations to the data is a matter of making it available,
    executing the functionality, and then saving the results. Most systems
    don't have to be particularly complex underneath in order for them to
    work, they just need to build up bigger and bigger piles of data.
    Functionality is what we see first, but it's data that forms the core of
    every system.</p></div></p>
</Slide>
		<Slide>
				<h2>61. It Is All About The Data</h2>
		</Slide>
</Slide>
