Discrete Levels
===============

.. todo::
   Rewrite this entire section.

The nuclear structure information needed to describe each fission fragment is obtained from the `RIPL-3 <https://www-nds.iaea.org/RIPL-3/>`_ library. Nuclear structure data are always evolving, depending on the availability of new nuclear structure experiments. CGMF does not calculate the excited states in a given nucleus, but instead fully depends on the `ENSDF <http://www.nndc.bnl.gov/ensdf/>`_ or somewhat equivalenty, RIPL3 libraries. The study of isomeric ratios or more generally specific :math:`\gamma` decay chains strongly depends on the quality of the underlying nuclear structure information. 

.. note:: The particular decay of a state in the continuum to discrete levels characterized by a particular (E,J, :math:`\pi`) is an important question.

create a :math:`x` - :math:`z` plot centered at (5.0, 2.0, 3.0) with a width of (50., 50.)  and 400x400 pixels::

  plot = openmc.Plot()
  plot.basis = 'xz'
  plot.origin = (5.0, 2.0, 3.0)
  plot.width = (50., 50.)
  plot.pixels = (400, 400)

.. code-block:: html

	<title>What a Wonderful World!</title>
	<h2>Ola, que tal?</h2>


.. code-block:: C++

	cout << "Ola, quel tal?\n";

.. currentmodule:: fission
.. autofunction:: readJSONDataFile
.. autofunction:: plotExperimentalData


.. sidebar:: Sidebar Title
    :subtitle: Optional Sidebar Subtitle

    Subsequent indented lines comprise
    the body of the sidebar, and are
    interpreted as body elements.

What does that mean? Oh that's actually very nice if I can put a sidebar besides the main text.

.. todo::
	Here is what I have left to do!
