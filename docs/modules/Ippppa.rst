.. _Ippppa:

Ippppa
***********************************

Wrapper for SAM Simulation Core model: `cmod_ippppa.cpp <https://github.com/NREL/ssc/blob/develop/ssc/cmod_ippppa.cpp>`_

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

**Ippppa model description**

.. automodule:: PySAM.Ippppa
	:members:

Functions
===================================

.. autoclass:: PySAM.Ippppa.Ippppa
	:members:

FinancialParameters Group
======================================================

.. autoclass:: PySAM.Ippppa.Ippppa.FinancialParameters
	:members:

SystemCosts Group
======================================================

.. autoclass:: PySAM.Ippppa.Ippppa.SystemCosts
	:members:

LandLease Group
======================================================

.. autoclass:: PySAM.Ippppa.Ippppa.LandLease
	:members:

Depreciation Group
======================================================

.. autoclass:: PySAM.Ippppa.Ippppa.Depreciation
	:members:

TaxCreditIncentives Group
======================================================

.. autoclass:: PySAM.Ippppa.Ippppa.TaxCreditIncentives
	:members:

PaymentIncentives Group
======================================================

.. autoclass:: PySAM.Ippppa.Ippppa.PaymentIncentives
	:members:

Common Group
======================================================

.. autoclass:: PySAM.Ippppa.Ippppa.Common
	:members:

Outputs Group
======================================================

.. autoclass:: PySAM.Ippppa.Ippppa.Outputs
	:members:

