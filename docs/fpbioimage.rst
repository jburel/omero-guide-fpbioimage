OMERO.FPBioimage
================

In this document, we introduce OMERO.FPBioimage, a 3D volume viewer for OMERO.web.

**Description:**
----------------

We will show here:

-  How to open a multi-z image in OMERO.FPBioimage

Resources:
----------

Example files used

-  https://downloads.openmicroscopy.org/images/DV/siRNAi-HeLa/

Note: Only some of the images in this dataset are z-stacks, for example

-  https://downloads.openmicroscopy.org/images/DV/siRNAi-HeLa/IN_03.r3d_D3D.dv

Setup:
------

OMERO.FPBioimage installation

OMERO.FPBioimage is a pip installable application for OMERO.web. Follow
the steps described in \ https://pypi.org/project/omero-fpbioimage/\  to install it and configure the OMERO.web accordingly.

Step-by-Step:
-------------

1. Login to OMERO.web and open an image from the Dataset siRNA-HeLa with multiple Z-sections e.g. *VRAQ_01.r3d_D3D.dv* in a 3D viewer: OMERO.FPBioimage.

   a. First select the Image.

   b. In the Preview tab, switch off all channels except FITC and the GFP-INCENP channel.

   c. Save the new rendering settings.

   d. Use right-click menu on the image in the left panel, or the Open with... icon |image1|\ on top of the right-hand pane to open the image with FPBioimage.

   e. Click Start in the new viewer window.

   f. We can see that the centromeres are well aligned on the metaphase plate on the selected Image, whereas the centromeres are located in and around the spheroid on the *IN_02.r3d* Image for example.

   .. image:: images/Fpbioimage2.png

.. |image1| image:: images/Fpbioimage1.png
   :width: 0.32292in
   :height: 0.32292in

