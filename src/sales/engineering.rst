Sales Engineering
=================

.. contents:: Table of Contents

Introduction
------------

Sales Engineering is a technical pre-sales role. The job involves showcasing the value of a product to potentional customers, addressing customer needs, and building relationships. A Sales Representative will rely on the Sales Engineer to provide the technical knowledge about the product. An effective Sales Engineer needs to be able to talk to both the techinical and executive teams of companies.

Case Studies
------------

Infrastructure
~~~~~~~~~~~~~~

Virtual Machines
^^^^^^^^^^^^^^^^

The average bare-metal server only uses 25% of the available resources. This means that four virtual machines can be created on a single server to maximum the resource usage. [1]

Containers
^^^^^^^^^^

Densify helped consolidate almost one thousand AWS EC2 instances into four larger reserved instances. Each original instance had one application running. As part of the consolidation, those applications were converted to containers to isolate them from each other. This lead to an 82% cost savings. [2] Even if the original instances were consolidated to run four applications each, the cost savings of moving to containers would have been 31%.

-  Before: $1.89M = 983 xlarge instances at $0.223/hour
-  After: $325.3K = 4 x1.32xlarge instances at $9.413/hour

   -  128 vCPUs and 1952 GiB RAM

History
-------

-  `Latest <https://github.com/ekultails/lifepages/commits/master/src/sales/engineering.rst>`__

Bibliography
------------

1. "Physical Servers vs. Virtual Machines: Key Differences and Similarities." NAKIVO Blog. December 26, 2018. Accessed May 6, 2021. https://www.nakivo.com/blog/physical-servers-vs-virtual-machines-key-differences-similarities/
2. "Using Containers to Reduce Public Cloud Costs." Densify Articles. Accessed May 6, 2021. https://www.densify.com/articles/public-cloud-containers-reduce-costs
