.. _Battwatts:

Battwatts
***********************************

Wrapper for SAM Simulation Core model: `cmod_battwatts.cpp <https://github.com/NREL/ssc/blob/develop/ssc/cmod_battwatts.cpp>`_

Input Consistency Warning
==================================

As described in :ref:`Possible Problems <possible_problems>`, some input parameters are interdependent but the equations 
that enforce consistency are not available in this PySAM module. Therefore,
the onus is on the PySAM user to check that interdependencies are correctly handled. The variables which may require
additional logic include:


Provided for each of these inputs is a list of other inputs that are potentially interdependent. 

Creating an Instance
===================================

Refer to the :ref:`Initializing a Model <initializing>` page for details on the different ways to create an instance of a PySAM class.

**Battwatts model description**

.. automodule:: PySAM.Battwatts
	:members:

Functions
===================================

.. autoclass:: PySAM.Battwatts.Battwatts
	:members:

Lifetime Group
======================================================

.. autoclass:: PySAM.Battwatts.Battwatts.Lifetime
	:members:

Battery Group
======================================================

.. autoclass:: PySAM.Battwatts.Battwatts.Battery
	:members:

Load Group
======================================================

.. autoclass:: PySAM.Battwatts.Battwatts.Load
	:members:

GridLimits Group
======================================================

.. autoclass:: PySAM.Battwatts.Battwatts.GridLimits
	:members:

Outputs Group
======================================================

.. autoclass:: PySAM.Battwatts.Battwatts.Outputs
	:members:

