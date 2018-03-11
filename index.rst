=============
The CGMF Code
=============

:program:`CGMF` is a code that simulates the emission of prompt fission neutrons and gamma rays from excited fission fragments right after scission. It implements a Monte Carlo version of the Hauser-Feshbach statistical theory of nuclear reactions to follow the decay of the fission fragments on an event-by-event basis. Probabilities for emitting neutrons and gamma rays are computed at each stage of the decay. Each fission event history records characteristics of the parent fragment (mass, charge, kinetic energy, excitation energy, spin, parity), the fission fragment momentum in the laboratory reference frame, and the number and characteristics (energy, direction) of the prompt neutrons and gamma rays emitted in this event.

.. admonition:: Recommended publication for citing
   :class: tip

   Patrick Talou, Toshihiko Kawano, Ionel Stetcu, Patrick Jaffke, and Michael E. Rising, "`CGMF: Event-by-Event Monte Carlo Simulations of Fission Fragment Decay <http://www.google.com>`_," to be submitted to Comp. Phys. Comm. (2018).

.. only:: html

--------
Contents
--------

.. toctree::
   :maxdepth: 2

   Introduction <intro>
   User's Guide<user>
   Physics Models<models>
   Code Details<code>
   Example Jupyter Notebooks<examples_notebook>
   Publications<publications>

.. note::

	| Current Code Version: |version|
	| Date: |today|

