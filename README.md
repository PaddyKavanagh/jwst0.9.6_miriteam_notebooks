# jwst0.9.6_miriteam_notebooks

This repository contains Jupyter notebooks demonstrating the use of the MIRI Team pipelines for MIRI data within python.

MIRICLE is required to run the MIRI Team notebooks and so the pipeline build in MIRICLE is used. For this set of noteoboks, this is jwst-0.9.6.

The CRDS context should be set to jwst_0468.pmap for this build. Also, standard CRDS environment variables should be set. E.g., for bash:

export CRDS_PATH=/path/to/your/crds

export CRDS_SERVER_URL="https://jwst-crds.stsci.edu"

export CRDS_CONTEXT="jwst_0468.pmap"
