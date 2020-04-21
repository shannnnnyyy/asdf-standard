.. _transform-schema:

Transform
=========

The ``transform`` module contains schema used to describe transformations.

Basics
------

.. asdf-autoschemas::

   transform/transform-1.2.0
   transform/generic-1.1.0
   transform/identity-1.2.0
   transform/constant-1.2.0
   transform/domain-1.0.0

Compound transformations
------------------------

.. asdf-autoschemas::

   transform/compose-1.2.0
   transform/concatenate-1.2.0
   transform/remap_axes-1.2.0

Arithmetic operations
---------------------

.. asdf-autoschemas::

   transform/add-1.2.0
   transform/subtract-1.2.0
   transform/multiply-1.2.0
   transform/divide-1.2.0
   transform/power-1.2.0

Simple Transforms
-----------------

.. asdf-autoschemas::

   transform/shift-1.2.0
   transform/scale-1.2.0

Power Laws
----------

.. asdf-autoschemas::

   transform/broken_power_law1d-1.0.0.yaml
   transform/exponential_cutoff_power_law1d-1.0.0.yaml
   transform/power_law1d-1.0.0.yaml
   transform/smoothly_broken_power_law1d-1.0.0.yaml

Misc 
----

.. asdf-autoschemas::

   transform/airy_disk2d-1.0.0
   transform/blackbody-1.0.0
   transform/box1d-1.0.0
   transform/box2d-1.0.0
   transform/disk2d-1.0.0
   transform/drude1d-1.0.0
   transform/ellipse2d-1.0.0
   transform/exponential1d-1.0.0
   transform/gaussian1d-1.0.0
   transform/gaussian2d-1.0.0
   transform/king_projected_analytic1d-1.0.0
   transform/linear1d-1.0.0
   transform/logarithmic1d-1.0.0
   transform/lorentz1d-1.0.0
   transform/moffat1d-1.0.0
   transform/moffat2d-1.0.0
   transform/planar2d-1.0.0
   transform/plummer1d-1.0.0
   transform/red_shift_scale_factor-1.0.0
   transform/ricker_wavelet1d-1.0.0
   transform/ricker_wavelet2d-1.0.0
   transform/ring2d-1.0.0
   transform/sersic1d-1.0.0
   transform/sersic2d-1.0.0
   transform/sine1d-1.0.0
   transform/trapezoid1d-1.0.0
   transform/trapezoid_disk2d-1.0.0
   transform/voigt1d-1.0.0   


Projections
-----------

Affine
^^^^^^

.. asdf-autoschemas::

   transform/affine-1.2.0
   transform/rotate2d-1.2.0
   transform/rotate3d-1.2.0

Zenithal (azimuthal)
^^^^^^^^^^^^^^^^^^^^

.. asdf-autoschemas::

   transform/zenithal-1.2.0
   transform/gnomonic-1.2.0
   transform/zenithal_perspective-1.2.0
   transform/slant_zenithal_perspective-1.2.0
   transform/stereographic-1.2.0
   transform/slant_orthographic-1.2.0
   transform/zenithal_equidistant-1.2.0
   transform/zenithal_equal_area-1.2.0
   transform/airy-1.2.0

Cylindrical
^^^^^^^^^^^

.. asdf-autoschemas::

   transform/cylindrical-1.1.0
   transform/cylindrical_perspective-1.2.0
   transform/cylindrical_equal_area-1.2.0
   transform/plate_carree-1.1.0
   transform/mercator-1.1.0

Pseudocylindrical
^^^^^^^^^^^^^^^^^

.. asdf-autoschemas::

   transform/pseudocylindrical-1.1.0
   transform/sanson_flamsteed-1.1.0
   transform/parabolic-1.1.0
   transform/molleweide-1.1.0
   transform/hammer_aitoff-1.1.0

Conic
^^^^^

.. asdf-autoschemas::

   transform/conic-1.2.0
   transform/conic_perspective-1.2.0
   transform/conic_equidistant-1.2.0
   transform/conic_equal_area-1.2.0
   transform/conic_orthomorphic-1.2.0

Pseudoconic
^^^^^^^^^^^

.. asdf-autoschemas::

   transform/pseudoconic-1.1.0
   transform/bonne_equal_area-1.2.0
   transform/polyconic-1.1.0

Quadcube
^^^^^^^^

.. asdf-autoschemas::

   transform/quadcube-1.1.0
   transform/tangential_spherical_cube-1.1.0
   transform/cobe_quad_spherical_cube-1.1.0
   transform/quad_spherical_cube-1.1.0

HEALPix
^^^^^^^

.. asdf-autoschemas::

   transform/healpix-1.1.0
   transform/healpix_polar-1.1.0

Polynomials
-----------

.. asdf-autoschemas::

   transform/polynomial-1.2.0

Regions and labels
------------------

.. asdf-autoschemas::

   transform/regions_selector-1.2.0
   transform/label_mapper-1.2.0
