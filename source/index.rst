.. ReadTheDocs_Data_Management documentation master file, created by
   sphinx-quickstart on Sat Feb 28 18:03:20 2026.

Guidelines for Research Data Management
=========================================

Introduction
------------

Research in the social sciences increasingly depends on complex data workflows. Surveys, administrative records, interviews, scraped data, and experimental outputs accumulate quickly. As projects evolve, datasets are cleaned multiple times, variables are transformed, and intermediate results are saved in different formats. Without a clear structure, projects become fragile. Files are duplicated, scripts are renamed inconsistently, and results are difficult to trace back to their source. 

These challenges emerge often when deadlines approach, collaborators join, or revisions are requested. Researchers may struggle to reconstruct earlier steps, locate the correct dataset version, or reproduce a table generated months earlier. What begins as a manageable folder of files can easily turn into a confusing collection of drafts and partial outputs. Data management provides a systematic way to organize materials, document decisions, and maintain a transparent link between raw data, analysis, and final results. Rather than reacting to disorder later, it establishes structure from the outset and supports the entire research lifecycle.

Why Data Management Matters
------------

First of all, sound data management facilitates the workflow. A well organized project allows researchers to move from raw data to cleaned datasets, and from analysis scripts to final outputs, without confusion. When data, code, and documentation follow a consistent structure, collaborators can understand the project within minutes rather than hours. Clear folder hierarchies and predictable naming conventions reduce friction and prevent avoidable errors. The goal is not complexity, but clarity.

Second, data management is the foundation of replicability. A project should be runnable from a master file that reproduces all tables and figures in a single execution. In recent years, frameworks such as `Econ Project Templates: Modern, Reproducible Research in Economics <https://econ-project-templates.readthedocs.io/en/stable/>`_ have demonstrated how powerful such systems can be. These tools are impressive and highly rigorous, yet they often target quantitatively researchers and may require installing numerous packages and managing sophisticated environments. In many areas of social science, researchers primarily use Stata or R and seek a lighter structure that remains robust without becoming overwhelming. Replicability can be achievable without requiring advanced software engineering skills.

Third, data management is not identical to data protection compliance. Many online resources focus primarily on privacy rules, data security regulations, and ethical approvals. These are crucial topics, but they address only one dimension of research practice. Data management concerns how we organize, document, process, and analyze data so that results are transparent and interpretable. It is about the path from raw material to evidence.

Ultimately, research produces results. In quantitative work, this typically means regression tables, summary statistics, and figures that visualize relationships in the data. In qualitative research, it may involve coded transcripts, thematic summaries, structured comparisons, or systematically documented interpretations. In both cases, readers should be able to understand how the evidence was generated. Well designed data management practices make this possible.

This project provides an elegant and stylish set of guidelines for structuring research data and workflows. It aims to balance rigor with accessibility. The objective is not to impose heavy technical infrastructure, but to offer practical conventions that work across disciplines, methods, and levels of quantitative training. By combining clarity, replicability, and methodological flexibility, these guidelines help researchers focus on what ultimately matters: producing credible and well documented research findings.

.. toctree::
   :maxdepth: 2
   :caption: Getting Started

   getting_started/introduction


.. toctree::
   :maxdepth: 2
   :caption: Guides and Explanations

   guides/data_cleaning
   guides/data_storage

.. toctree::
   :maxdepth: 2
   :caption: Quantitative Research

   quantitative/programming

.. toctree::
   :maxdepth: 2
   :caption: Qualitative Research

   qualitative/interviews
   qualitative/coding
   
.. toctree::
   :maxdepth: 2
   :caption: Reproducibility and Replicability

   reproducibility/documentation
   reproducibility/template

.. toctree::
   :maxdepth: 1
   :caption: FAQ

   faq

.. toctree::
   :maxdepth: 1
   :caption: References

    references



The Guidelines for Research Data Management is established as part of the MetaFin joint project, which accompanies the projects funded by the Federal Ministry of Education, Family Affairs, Senior Citizens, Women and Youth (BMBFSFJ) as part of the “Research on Financial Education” directive. MetaFin's partners are the Mannheim Institute for Financial Education (MIFE), a joint initiative of the University of Mannheim and the ZEW – Leibniz Centre for European Economic Research, and the Institute for Economic Education (IÖB).
