0.8.1 (released 2018-09-20)
---------------------------
- 2018-09-20: Restyled the documentation, thanks @vannavu and @thundernixon
- 2018-09-12: Fixed Travis setup for OSX.
- 2018-09-06: All tests for ``Groups``.
- 2018-09-03: Fixed ``font.round()``.
- 2018-08-30: All tests for ``Image``.



0.8.0 (released 2018-08-21)
---------------------------

- 2018-08-21: Changed behavior of getting margins for empty (no outlines or components) glyphs, now returns `None`. `#346 <https://github.com/robofab-developers/fontParts/pull/346>`_
- 2018-08-20: Add public methods to `mathInfo` in the Info object. `#344 <https://github.com/robofab-developers/fontParts/pull/344>`_

0.7.2 (released 2018-08-03)
---------------------------

- 2018-08-03: Allow contours to start and end on an offCurve. `#337 <https://github.com/robofab-developers/fontParts/pull/337>`_

0.7.1 (released 2018-08-02)
---------------------------

- 2018-07-24: Fixed bug in default values in ``BaseDict``. This fixes a bug with default values in ``Kerning`` and ``Groups``.
- 2018-06-28: Improved documtation for ``world.AllFonts``
- 2018-06-20: Fixed a bug in ``world.AllFonts``
- 2018-06-14: Fixed a bug, UFO file format version must be an ``int``.


0.7.0 (released 2018-06-11)
---------------------------

- 2018-06-08: Fixed a bug in ``__bool__`` in ``Image`` that would fail if there was no image data.
- 2018-06-08: Fixed a bug in setting the parents in appending a ``guideline`` to a ``Glyph`` or ``Font``.
- 2018-05-30: Fixed a bug in both the base and fontshell implementations of ``groups.side1KerningGroups``.
- 2018-05-30: Fixed a bug in both the base and fontshell implementations of ``groups.side2KerningGroups``.
- 2018-05-30: Fixed a several bugs in ``BaseDict`` that would return values that hadn't been normalized.
- 2018-05-30: Implemented ``font.__delitem__``
- 2018-05-30: Implemented ``font.__delitem__``.
- 2018-05-30: Implemented ``layer.__delitem__``.
- 2018-05-30: ``font.removeGlyph`` is now an alias for ``font.__delitem__``.
- 2018-05-30: ``layer.removeGlyph`` is now an alias for ``layer.__delitem__``.
- 2018-05-30: ``font.insertGlyph`` is now an alias for ``font.__setitem__``.
- 2018-05-30: ``layer.insertGlyph`` is now an alias for ``layer.__setitem__``.
- 2018-05-30: ``font.appendGuideline`` now accepts a guideline object.
- 2018-05-30: ``glyph.copy`` uses the new append API.
- 2018-05-30: ``glyph.appendGlyph`` uses the new append API.
- 2018-05-30: ``glyph.appendComponent`` now accepts a component object.
- 2018-05-30: ``glyph.appendAnchor`` now accepts and anchor object.
- 2018-05-30: ``glyph.appendGuideline`` now accepts a guideline object.
- 2018-05-30: ``contour.appendSegment`` now accepts a segment object.
- 2018-05-30: ``contour.appendBPoint`` now accepts a bPoint object.
- 2018-05-30: ``contour.appendPoint``  now accepts a point object.
- 2018-05-30: ``contour.insertSegment`` now accepts a segment object.
- 2018-05-30: ``contour.insertBPoint`` now accepts a bPoint object.
- 2018-05-30: ``contour.insertPoint`` now accepts a point object.
