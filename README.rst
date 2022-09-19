.. image:: https://img.shields.io/badge/license-AGPL--3-blue.png
   :target: https://www.gnu.org/licenses/agpl
   :alt: License: AGPL-3

=======================
Devops (HELM)
=======================


Instruction
============

* NODES and Clusters
 - Am using `kind` to manage cluster as a container.
  - To CREATE new cluster `kind create cluster --name <cluster-name>`
  - To DELETE cluster `kind delete cluster --name="<cluster-name>"`

 - Using `postgres`
  - To enter psql  `psql -U postgres odoo`
 - Using `kubectl`
  - To switch to another cluster `kubectl config use-context <cluster-name>`
 - Using `docker`
  - Run a small `alpine linux` container where we can install and play
   - `docker run -it --rm -v ${HOME}:/root/ -v ${PWD}:/work -w /work --net host alpine sh`
----


Credits
-------

.. |copy| unicode:: U+000A9 .. COPYRIGHT SIGN
.. |tm| unicode:: U+2122 .. TRADEMARK SIGN

- |copy| `Omar Abdelaziz <omar@bloopark.de>`_ |tm| 2021
