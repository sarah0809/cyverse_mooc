.. include:: cyverse_rst_defined_substitutions.txt
.. include:: custom_urls.txt

|CyVerse_logo|_

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`_


Analysis with the Discovery Environment
----------------------------------------

    .. admonition:: learning-objectives

       - Objective 1
       - Objective 2
       - Objective n

**Description:**

..
	#### Comment: short text description goes here ####

----

**Input Data:**

.. list-table::
    :header-rows: 1

    * - Input
      - Description
      - Example
    * - A fasta file containing DNA sequences to align.
      - We will use the previously uploaded file from the `Data Management II <step5.html>`_
        section.
      - View the example |MUSCLE input folder|.

`Learning Center Home <http://learning.cyverse.org/>`_

*Descriptive Steps*
~~~~~~~~~~~~~~~~~~~

1. If necessary, log into the CyVerse |Discovery Environment|.

2. Click |Apps icon| (Apps icon) from the DE workspace; search for **MUSCLE- 3.8.31**

3. Under “Analysis Info”, you can leave the defaults or make any desired notes.

4. Under “Select Input Data” click Browse, then navigate the uploaded file
   (**DE_sample_plants.fas**); then click OK.

5. Under “Sequence Type”, select DNA.

6. Under the optional “Advanced Settings”, leave the default settings. If
   required, some analyses may be launched with requests for more minimum
   Resource Requirements, but this may cause those analyses to sit longer in
   the submission queue until a node matching those minimum requirements
   becomes available.

7. Click Launch Analysis

8. You will receive a notification and be redirected to the Analyses Listing
   page.




**Output/Results**

.. list-table::
    :header-rows: 1

    * - Output
      - Description
      - Example
    * - - A folder of logs
        - clstalw.aln
        - fasta.aln
        - phylip_interleaved.aln
        - phylip_sequential.aln
      - The logs folder are log files returned with every Discovery Environment
        analyses. These can be useful for diagnosing failed analyses. All other
        files are outputs of the Muscle software and contain multiple sequence
        alignments in a variety of common formats.
      - View the example |MUSCLE output folder|.


----

**Description of output and results**



----

Self Assessment Questions
`````````````````````````````

  .. admonition:: Question
       :class: admonition-question

       Q1. Which of the following are true about Docker containers?

       A. They share the host OS
       B. They have process-level isolation.
       C. They are are heavyweight.
       D. They have a startup time in the minutes range.



       .. admonition:: Answer

          Correct answer is A and B


  .. admonition:: Question
       :class: admonition-question

       Q2. Which of the following are incorrect about Docker containers?

       A. Dockerfiles are a recipe for creating Docker images.
       B. Docker containers are a collection of Dockerfiles.
       C. Docker images get built by running a Docker command which uses the
          Dockerfile.
       D. Docker containers are running instances of a Docker image.


       .. admonition:: Answer

          The incorrect statement is B

----

**Fix or improve this documentation**

- Search for an answer:
  |CyVerse Learning Center|
- Ask us for help:
  click |Intercom| on the lower right-hand side of the page
- Report an issue or submit a change:
  |Github Repo Link|
- Send feedback: `learning@CyVerse.org <learning@CyVerse.org>`_

----

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`_

.. Comment: Place Images Below This Line
   use :width: to give a desired width for your image
   use :height: to give a desired height for your image
   replace the image name/location and URL if hyperlinked


 .. |Clickable hyperlinked image| image:: ./img/IMAGENAME.png
    :width: 500
    :height: 100
 .. _CyVerse logo: http://learning.cyverse.org/

 .. |Static image| image:: ./img/IMAGENAME.png
    :width: 25
    :height: 25



.. Comment: Place URLS Below This Line

   # Use this example to ensure that links open in new tabs, avoiding
   # forcing users to leave the document, and making it easy to update links
   # In a single place in this document

   .. |Substitution| raw:: html # Place this anywhere in the text you want a hyperlink

      <a href="REPLACE_THIS_WITH_URL" target="blank">Replace_with_text</a>


.. |Github Repo Link|  raw:: html

   <a href="FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX" target="blank">Github Repo Link</a>
