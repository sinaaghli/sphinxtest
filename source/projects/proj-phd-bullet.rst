Physics Engine
===============

As a part of my PhD I was developing wrapper around bullet physics engine 
which was capable of instanciating robots in a given initial state and simulate them forward in time very quickly.
The repository is in `Spirit Repo <https://github.com/sinaaghli/spirit>`_

Some of the features are

* Custom gui based on `Pangolin <https://github.com/stevenlovegrove/Pangolin>`_
* Quick state initialization of robot from state vector
* Multi-threaded simulation
* Adjustable vechile configurations on the fly (geometric and parametric)
* Planner objects like waypoints and trajecotry objects in state space
* `Ceres-Solver <https://github.com/ceres-solver/ceres-solver>`_ based non-linear optimization

Here is an example of spirit runnign a AWD car model with a PID control on steering. The 3D gui is fully interactive (not showin in this video).

.. raw:: html

    <iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/fRKSMNQGVGM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>