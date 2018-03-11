============
User's Guide
============

Obtaining and Installing CGMF
-----------------------------

At this point, :program:`CGMF` has not released as open source yet. We are working on this. To obtain the code, please contact `Patrick Talou <talou@lanl.gov>`_.

Unarchive the source tar ball, and type

.. code-block:: c++

	make CGMF

It creates the executable ``cgmf.x``. 


Using CGMF
----------


To launch a :program:`CGMF` run, type:

.. code-block:: c++

	./cgmf.x -i 98252 -e 0.0 -n 100000

which means that you are calling :program:`CGMF` for the spontaneous fission (incident energy is set to 0.0 (using `-e 0.0`) of 252Cf (ZAID=98252) with 100,000 fission events.