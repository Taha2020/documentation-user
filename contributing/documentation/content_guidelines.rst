:banner: banners/contributing.png

==================
Content Guidelines
==================

In an effort to give the community the best documentation possible, we listed here a few guidelines,
tips and tricks that will make your content shine at its brightest! While we encourage you to adopt
your own writing style, some rules still apply to give the reader more clarity and comprehension.

.. note::
   We strongly recommend contributors to carefully read the other documents in this *Contribution*
   section of the documentation. A good knowledge of the ins and outs of **RST writing** is required
   to write and submit your contribution. Note that it also affects your writing style itself.

   - :doc:`introduction_guide`
   - :doc:`rst_cheat_sheet`
   - :doc:`rst_guidelines`

Writing style
=============

**Writing for documentation** isn't the same as writing for a blog, or another medium. Readers are
more likely to skim read until they've found the information they are looking for. Keep in mind that
the user documentation is a place to inform and describe, not to convince and promote.

Consistency
-----------

*Consistency is key to everything.*

Make sure that your writing style remains **consistent**. If you modify an existing text, try to
match the existing tone and presentation, or rewrite it to match your own style.

Grammatical tenses
------------------

In English, descriptions and instructions require the use of a **Present Tense**, while a *future
tense* is appropriate only when a specific event is to happen ulteriorly. This logic might be
different in other languages.

- | Good example (present):
  | *Screenshots are automatically resized to fit the content block's width.*
- | Bad example (future):
  | *When you take a screenshot, remember that it will be automatically resized to fit the content
     block's width.*

Paragraphing
------------

A paragraph comprises several sentences that are linked by a shared idea. They usually are two to
six lines long.

In English, a new idea implies a new paragraph, rather that having a *line break* as it is common
to do in some other languages. *Line breaks* are usefull for layout purposes but shouldn't be used
as a grammatical way of separating ideas.

.. seealso::
   - :ref:`RST cheat sheet: Break the line but not the paragraph <contributing/line-break>`

Titles
------

To write a good title :

- **Be concise.**
- **Avoid sentences**, questions, and titles starting with "how to."
- **Don't use pronouns** in your titles, especially 2nd person (*your*)

Document's structure
====================

Use different **headings levels** to organize your text by sections and sub-sections. Your headings
are also displayed in a dynamic *navigation bar* on the side.

+---------------------------------------------------------------------------------------+
| | **H1: Page Title**                                                                  |
| | Your *Page Title* gives your reader a quick and clear understanding of what your    |
|   content is about. It is also referenced in the section's *table of contents*.       |
|                                                                                       |
| The *Content* in this section describes the upcoming content from a **business point  |
| of view**, and shouldn't put the emphasis on Odoo, as this is documentation and not   |
| marketing.                                                                            |
|                                                                                       |
| Start first with a **Lead Paragraph**, which helps the reader make sure that they've  |
| found the right page, then explain the **business aspects of this topic** in the      |
| following paragraphs.                                                                 |
+-----+---------------------------------------------------------------------------------+
|     | | **H2: Section Title (configuration)**                                         |
|     | | This first H2 section is about the configuration of the feature, or the       |
|     |   prerequisites to achieve a specific goal. To add a path, make sure you        |
|     |   use the ``:menuselection:`` specialized directive (see link below).           |
|     |                                                                                 |
|     | | Example:                                                                      |
|     | | To do so, go to ``:menutselection:`App name --> Menu --> Sub-menu```, and     |
|     |   enable the XYZ feature.                                                       |
+-----+---------------------------------------------------------------------------------+
|     | | **H2: Section Title (main sections)**                                         |
|     | | Create as many main sections as you have actions or features to distinguish.  |
|     |   The title can start with a verb, but try to avoid using "Create ...".         |
+-----+-----+---------------------------------------------------------------------------+
|     |     | | **H3: Subsection**                                                      |
|     |     | | Subsections are perfect to assess very specific points. The title can   |
|     |     |   be in the form of a question if appropriate                             |
+-----+-----+---------------------------------------------------------------------------+
|     | **H2: Next Section**                                                            |
+-----+---------------------------------------------------------------------------------+

.. seealso::
   - :ref:`RST cheat sheet: headings <contributing/headings>`.
   - :ref:`RST cheat sheet: specialized directives <contributing/specialized-directives>`

Images
======

Banner
------


A good screenshot

Screenshots
-----------

Screenshots are automatically resized to fit the content block's width. This implies that, to be
understandable, screenshots can't be too wide, else they would appear very small on-screen.

.. image:: media/screenshot-max-width.png
   :align: center
   :alt:

1. **Zoom** in your browser. We recommend a 110% zoom for better results.
2. | **Resize** your browser's width, either by *resizing the window* itself, or by opening the
     *browser's developper tools* and resizing the width.
3. **Select** the relevant area, rather than keeping the full window.
4. If necessary, you can **edit** the screenshot to remove unnecessary fields and narrow even more
   Odoo's display.

.. image:: media/screenshot-tips.gif
   :align: center
   :alt:

.. note::
   Resizing the window's width is the most important step to do as Odoo's responsive design
   automatically resizes all fields to match the window's width.

ALT tags
----------------
