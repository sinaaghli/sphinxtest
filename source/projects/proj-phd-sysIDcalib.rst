Online Parameter Estimation (for adaptive MPC)
===========================================================

This work is inspired by theories used in online parameter calibration of SLAM algorithms. Based on history of robot's trajectory this algorithm is capable of estimating vechile parameters.
Detailed descriptions are in `the paper <https://drive.google.com/file/d/1e_na0XphNV94-4GD3n--loKTag8jLaAM/view>`_


Here is a short video of how the algorithm works

.. raw:: html

    <iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/4bw9pOGCTQg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

The Pipeline
-------------
.. image:: ../media/sysid.png
    :width: 500
    :align: center


Results
--------
Simulated experiments(left) and parkour car platform experiments (right) prove that parameter estimates converge to the groundtruth values.

.. image:: ../media/sysid-experiment.png
    :width: 500
    :align: center