
Introduction
============

The AuxTel focus setting is adjusted as a function of elevation, but including temperature will reduce the scatter of the model and improve the focus.  This technote shows how to calculate the needed model coefficients.

Results
============

The results are documented in the notebook below.  There are three main recommendations:

- We should change from fitting a function of cos(90-elevation) to just a linear fit vs elevation.

- We should use the air temperature in the AuxTel dome and apply a temperature coefficient of
  0.005191 mm/deg C

- We should gather more data once the AuxTel is again operational.

The notebook below is available at NCSA at:
/project/cslage/AuxTel/notebooks/EFD_Focus_Full_20Dec21.ipynb

It is alos available at:
https://github.com/craiglagegit/ScratchStuff/blob/master/notebooks/EFD_Focus_Full_20Dec21.ipynb

.. raw:: html
   :file: ./_static/EFD_Focus_Full_20Dec21.html
