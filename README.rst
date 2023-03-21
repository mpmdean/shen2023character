==========================================================
Data Repository
==========================================================
Source code and data files for the manuscript Electronic character of charge order in square planar low valence nickelates. Execute plot.ipynb to view the data.

How to cite
-----------
If this data is used, please cite Electronic character of charge order in square planar low valence nickelates, Y. Shen, J. Sears, G. Fabbris, J. Li, J. Pelliciari, M. Mitrano, W. He, Junjie Zhang, J. F. Mitchell, V. Bisogni, M. R. Norman, S. Johnston, and M. P. M. Dean, Phys. Rev. X. 13, 011021 (2023)

Charge order is a central feature of the physics of cuprate
superconductors and is known to arise from a modulation of holes with
primarily oxygen character. Low-valence nickelate superconductors also
host charge order, but the electronic character of this symmetry
breaking is unsettled. Here, using resonant inelastic x-ray scattering
at the Ni :math:`L_2`-edge, we identify intertwined involvements of Ni
:math:`3d_{x^2-y^2}`, :math:`3d_{3z^2-r^2}`, and O :math:`2p_{\sigma}`
orbitals in the formation of diagonal charge order in an overdoped
low-valence nickelate
La\ :math:`_{4}`\ Ni\ :math:`_{3}`\ O\ :math:`_{8}`. The Ni
:math:`3d_{x^2-y^2}` orbitals, strongly hybridized with planar O
:math:`2p_{\sigma}`, largely shape the spatial charge distribution and
lead to Ni site-centered charge order. The :math:`3d_{3z^2-r^2}`
orbitals play a small, but non-negligible role in the charge order as
they hybridize with the rare-earth :math:`5d` orbitals. Our results
reveal that the low-energy physics and ground-state character of these
nickelates are more complex than those in cuprates.

Run locally
-----------

Work with this by installing `docker <https://www.docker.com/>`_ and pip and then running

.. code-block:: bash

       pip install jupyter-repo2docker
       jupyter-repo2docker --editable .

Change `tree` to `lab` in the URL for JupyterLab.

Run remotely
------------

.. image:: https://mybinder.org/badge_logo.svg
 :target: https://mybinder.org/v2/gh/mpmdean/Shen2022character/HEAD?filepath=plot.ipynb
