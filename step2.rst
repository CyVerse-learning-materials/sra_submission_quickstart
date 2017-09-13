|CyVerse logo|_

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`_


Record metadata and associate with SRA submission
=====================================================

In this section, you will complete **3 metadata templates** and associate these
metadata with your submission.

- **BioProject**: Metadata describing the overall project
- **BioSample**: Metadata describing the source materials sampled
- **Library**: Metadata describing the sequencing runs

.. warning::
  The metadata templates are defined by NCBI. Each feild must be completed
  *exactly* as described. Any typos or invalid entries will cause your submission
  to be rejected.

I. Complete BioProject Metadata Template
-----------------------------------------
We will complete the BioProject Creation template to begin a new submission.

  1. Login to the CyVerse `Discovery Environment <http://de.cyverse.org/>`_
  2. Click on **Data** to open a Data Window, and from the "Metadata" menu
     select 'Download Template.' Select the '**NCBI BioProject Creation**' and
     click 'OK' to download.

     .. Tip::
       The download will contained a two compressed (.zip) CSV files:

       - **blank.csv**: This is the template to complete
       - **guide.csv**: These are the NCBI specified instructions for the template
         On your local computer

       You can edit the blank.csv template using any spreadsheet editor such as
       Excel

  3. Complete the metadata template according to the instructions in the guide;
     save the metadata file as a .csv file (for Excel we recomend saving as
     'CSV UTF-8 (Comma delimited)'). You may name this file whatever you wish
     we suggest a name other than blank to avoid confusion with other templates.

    .. warning::
      Excel and other spreadsheet editors may overwrite information (such as
      dates) with formatting. This makes Excel `notorious for use in bioinformatics <https://genomebiology.biomedcentral.com/articles/10.1186/s13059-016-1044-7>`_.
      Double check that dates and other entries in your template are not
      automatically edited by Excel. When editing, you may use the Formatting
      feature (Format menu > Cells) to ensure your sheet is entirely formatted
      as text

    .. tip::
     **Tips for completing metadata templates**

     **Completing the file name or path feild**
     The first column of CyVerse metadata templates is the 'file name or path'
     feild. What should be entered is a path to the file the rest of the metadata
     should be applied to. You can get this path from the Discovery Environment
     Data Window's "Viewing:" feild:

     |sra_4|

     **Ensure the name of your top-level BioProject folder is in this path**

     **Following Guide Requirements**
     The guide gives aditional information about the template including if a
     template feild is required, and if specific values (taken from
     controlled vocabulary) must be used. Something to remember include:

     - If a 'required' is **TRUE** you must provide a value, or enter one of the
       following null values: 'not collected', 'not applicable', or 'missing'.
     - When prompted for an **email address** enter the address associated with
       your NCBI account. Notifications will only be sent to this address.
     - The **value type** feild indicates if the response is a single line of
       of alphanumeric characters (string), a multiline response, or an enumerated
       value (Enum). If a feild must be an **Enumerated Value (Enum)** only use
       one of the terms specified in the guide
     - **Dates** must be entered in the order specifed by NCBI (e.g. Year-Month-Day)

  4. Upload the completed template; from a Data window "Upload" menu chose
     'Simple Upload from Desktop'. You may upload to the same directory as
     your top-level BioProject folder, but do not place metadata files in your
     sumission folders. (You may need to click "Refresh" to see the uploaded file)

  5. Associate the metadata with your BioProject; in a Data Window, select your
     BioProject top-level folder. From the "Metadata" menu select 'Apply Bulk
     Metadata' and then 'Select Metadata File'; select the uploaded metadata and
     browse to the uploaded file and click 'OK'. You should get a notification
     that the metadata application was sucessful.

  6. In a Data Window, select the BioProject folder and in the "Metadata" window
     click 'Edit/View' Metadata to verify the metadata is applied and accurate.

     |sra_5|

II. Complete BioSample Metadata Template
-------------------------------------------

You will next need to select the appropriate BioSample template (organisim/sample
specific) and apply this to all of your BioSample folders. Most of the information
may be the same for each BioSample, with differences including things like treatments
and/or tissue sources.

  1. Login to the CyVerse `Discovery Environment`_
  2. Click on **Data** to open a Data Window, and from the "Metadata" menu
     select 'Download Template.' Select and download the a "NCBI BioSample" appropriate for
     your submission. If you are unsure about which template to select; post a
     question to the `CyVerse User Forum <http://ask.iplantcollaborative.org/questions/>`_.
  3. Complete the metadata template (**See the warnings and tips in the BioProject Instructions above**).

      .. important::
        You must complete a row of metadata for **every** BioProject folder.
        The metadata for all your BioSamples can remain in the same file,
        assuming that template is appropriate for all the BioSamples in your
        project. If you require more than one BioSample template, you will need
        to complete a separate template for each relavant BioSample.

  4. Upload the completed template; from a Data window "Upload" menu chose
     'Simple Upload from Desktop'. You may upload to the same directory as
     your top-level BioProject folder, but do not place metadata files in your
     sumission folders. (You may need to click "Refresh" to see the uploaded file)
  5. Associate the metadata with your BioSample; in a Data Window, select your
     **BioProject top-level folder**. From the "Metadata" menu select 'Apply Bulk
     Metadata' and then 'Select Metadata File'; select the uploaded metadata and
     browse to the uploaded file and click 'OK'. You should get a notification
     that the metadata application was sucessful.

     .. tip::

       Although you select your BioProject folder, since your metadata template
       specifically indicates the path your our BioSample folders, metadata will
       be applied to those subdirectories.

  6. In a Data Window, select a BioSample folder and in the "Metadata" window
     click 'Edit/View' Metadata to verify the metadata is applied and accurate.
     Verify the metadata for each of your BioSamples.

III. Complete Library Metadata Template
-----------------------------------------

This final template will need to be completed for **every** BioSampleLibrary
folder.

  1. Login to the CyVerse `Discovery Environment`_
  2. Click on **Data** to open a Data Window, and from the "Metadata" menu
     select 'Download Template.' Select and download the a "NCBI SRA Library"
     template.
  3. Complete the metadata template (**See the warnings and tips in the BioProject Instructions above**).

      .. important::
        You must complete a row of metadata for **every** BioSampleLibrary folder.
        The metadata for all your libraries can remain in the same file.
  4. Upload the completed template; from a Data window "Upload" menu chose
     'Simple Upload from Desktop'. You may upload to the same directory as
     your top-level BioProject folder, but do not place metadata files in your
     sumission folders. (You may need to click "Refresh" to see the uploaded file)
  5. Associate the metadata with your BioSample; in a Data Window, select your
     **BioProject top-level folder**. From the "Metadata" menu select 'Apply Bulk
     Metadata' and then 'Select Metadata File'; select the uploaded metadata and
     browse to the uploaded file and click 'OK'. You should get a notification
     that the metadata application was sucessful.

     .. tip::

       Although you select your BioProject folder, since your metadata template
       specifically indicates the path your our library folders, metadata will
       be applied to those subdirectories.

  6. In a Data Window, select a BioSampleLibrary folder and in the "Metadata" window
     click 'Edit/View' Metadata to verify the metadata is applied and accurate.
     Verify the metadata for each of your BioSampleLibrary folders.


.. warning::

  Once you have finneshed adding metadata to your submission folders, you cannot
  move or rename those folders without going back to edit the metadata entries. 

IV. Generate summary metadata file
------------------------------------

We will now generate a file that captures the metadata for the entrire submission.
In the next step we will validate our results.

  1. If necessary, login to the CyVerse `Discovery Environment`_
  2. Click on **Data** to open a Data Window, and select your top-level BioProject
     folder. From the "Metadata" menu, select 'Save Metadata to file'; save
     the file with a descriptive name and a .xml ending (this make take a few
     minutes to generate; you may need to click "Refresh" to see the file).

----

**Fix or improve this documentation**

- On Github: `Repo link <FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_>`_
- Send feedback: `Tutorials@CyVerse.org <Tutorials@CyVerse.org>`_

----

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`_


.. |CyVerse logo| image:: ./img/cyverse_rgb.png
    :width: 500
    :height: 100
.. _CyVerse logo: http://learning.cyverse.org/
.. |Home_Icon| image:: ./img/homeicon.png
    :width: 25
    :height: 25
.. _Home_Icon: http://learning.cyverse.org/
.. |sra_4| image:: ./img/sra_4.png
   :width: 550
   :height: 225
.. |sra_5| image:: ./img/sra_5.png
   :width: 425
   :height: 225
