|CyVerse logo|_

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`_

Submit High-throughput Sequencing Reads to NCBI Sequence Read Archive (SRA)
============================================================================

Goal
----
This workflow enables CyVerse users to make submissions to the `NCBI Sequence Read Archive (SRA) <https://www.ncbi.nlm.nih.gov/sra>`_.
A submission included compressed sequenced files
(FASTQ.gz, SFF.gz, and BAM.gz) and an XML metadata file, organized into a
package. If you need to submit an alternative file format (HD5,
SOLiD, and SRF) please email support@cyverse.org

----

.. toctree::
	:maxdepth: 2

	Quickstart home <self>
	Create and organize an SRA submission package <step1.rst>
	Record metadata and associate with SRA submission <step2.rst>
	Validate and submit package to SRA <step3.rst>
	Confirm submission to SRA and fix errors <step4.rst>

-----

Prerequisites
-------------

.. Note::
	To complete this tutorial, you must upload your FASTQ/SFF/BAM files to the
	CyVerse Data Store. See the `Data Store Guide <https://cyverse-data-store-guide.readthedocs-hosted.com/en/latest/>`_
	for instructions on how to upload your files (for example, using
	`Cyberduck <https://cyverse-data-store-guide.readthedocs-hosted.com/en/latest/step1.html>`_).
	Also, you will need detailed metadata about the sample being submitted ( e.g.
	collection/accession information, cell line/tissue metadata, etc.) and the sequencing
	platform used (e.g. library preparation strategy, sequencing instrument, etc.). These
	requirements will vary for the organism sequenced and are discussed in detail
	in the metadata section of this quickstart.


Downloads, access, and services
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

*In order to complete this tutorial you will need access to the following services/software*


 .. list-table::
   :header-rows: 1

   * - Prerequisite
     - Preparation/Notes
     - Link/Download
   * - CyVerse account
     - You will need a CyVerse account to complete this exercise
     - `Register <https://user.cyverse.org/>`_
   * - NCBI Account
     - Submissions will be sent to NCBI
     - `Register <https://www.ncbi.nlm.nih.gov/account/register/>`__

.. Note::
  **Register for an NCBI Account**

	If you do not have an NCBI account (you can check for an existing acocunt logging
	in at `https://www.ncbi.nlm.nih.gov/account/ <https://www.ncbi.nlm.nih.gov/account/>`_ );
	register at `https://www.ncbi.nlm.nih.gov/account/register/ <https://www.ncbi.nlm.nih.gov/account/register/>`_.

Platform(s)
~~~~~~~~~~~

*We will use the following CyVerse platform(s):*

 ..
   #### comment: delete any row not needed in this table ####

.. list-table::
    :header-rows: 1

    * - Platform
      - Interface
      - Link
      - Platform Documentation
      - Quick Start
    * - Data Store
      - GUI/Command line
      - `Data Store <http://www.cyverse.org/data-store>`_
      - `Data Store Manual <https://wiki.cyverse.org/wiki/display/DS/Data+Store+Table+of+Contents>`_
      - `Guide <https://cyverse-data-store-guide.readthedocs-hosted.com/en/latest/>`__
    * - Discovery Environment
      - Web/Point-and-click
      - `Discovery Environment <https://de.cyverse.org/de/>`_
      - `DE Manual <https://wiki.cyverse.org/wiki/display/DEmanual/Table+of+Contents>`_
      - `Guide <http://learning.cyverse.org/projects/cyverse-discovery-environment-guide/>`__

Input and example data
~~~~~~~~~~~~~~~~~~~~~~

*In order to complete this quickstart you will need to have the following inputs prepared*

.. list-table::
    :header-rows: 1

    * - Input File(s)
      - Format
      - Preparation/Notes
      - Example Data
    * - FastQ/SFF/BAM files
      - FastQ/SFF/BAM compressed (.gz/.bz2).
      - For additional details see the `SRA File Format Guide <https://www.ncbi.nlm.nih.gov/sra/docs/submitformats/>`_
      - `Sample truncated sample FastQ files <http://datacommons.cyverse.org/browse/iplant/home/shared/cyverse_training/quickstarts/sra_submission/00_input_fastq_files>`_

----

**Fix or improve this documentation**

- On Github: `Repo link <https://github.com/CyVerse-learning-materials/sra_submission_quickstart>`_
- Send feedback: `Tutorials@CyVerse.org <Tutorials@CyVerse.org>`_

----

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`__

.. |CyVerse logo| image:: ./img/cyverse_rgb.png
    :width: 500
    :height: 100
.. _CyVerse logo: http://learning.cyverse.org/
.. |Home_Icon| image:: ./img/homeicon.png
    :width: 25
    :height: 25
.. _Home_Icon: http://learning.cyverse.org/
