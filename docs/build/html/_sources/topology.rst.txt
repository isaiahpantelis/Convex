################
General Topology
################

******************
Topological spaces
******************

:ref:`[EDA2, Chapter XII, Section 1] <EDA2>`

A **topology** on a set :math:`X` is a set :math:`\tau` of
subsets of :math:`E` [#DEF_TOP_SUBSET_POWER_SET]_ that satisfies the following
conditions:

#. :math:`E\in\tau`

#. If :math:`(A_\lambda)_{\lambda\in L}` is a family of subsets of :math:`X`
   such that :math:`A_\lambda\in\tau`, :math:`\forall\lambda\in L`,
   then :math:`\bigcup_{\lambda\in L}A_\lambda\in\tau`.
   [#DEF_TOP_INDEX_SET]_

#. If :math:`A` and :math:`B` are elements of :math:`\tau`, then
   :math:`A\cap B\in\tau`.

A **topological space** is an ordered pair :math:`(X,\tau)` where :math:`X` is
a set and :math:`\tau` is a topology on :math:`X`. Given a topological space
:math:`(X,\tau)`, by slight abuse of terminology the set :math:`X` itself is
also called a topological space.  The elements of :math:`\tau` are the **open
sets** of the topological space :math:`X`.

It follows from the second property for :math:`L=\emptyset` that
:math:`\emptyset\in\tau`. That is, the empty set is an open set.

From the last property, it follows by induction that if
:math:`(A_k)_{k=1}^K` is a *finite* family of elements of :math:`\tau`, then
:math:`\bigcap_{k=1}^K A_k\in\tau`.

A topology on a set :math:`X` is, therefore, a collection of subsets of
:math:`X` that contains :math:`X` itself and is closed under arbitrary unions
and countable intersections.

----

.. [#DEF_TOP_SUBSET_POWER_SET] In other words, :math:`\mathfrak{D}` is a subset
        of :math:`\mathfrak{P}(X)`
.. [#DEF_TOP_INDEX_SET] The index set :math:`L` is not necessarily countable
        and it can be empty.
