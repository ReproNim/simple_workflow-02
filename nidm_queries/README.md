# Simple-2 NIDM Queries

Install PyNIDM

* ```git clone https://github.com/incf-nidash/PyNIDM.git```

* ```python setup.py install```

Either wait for JB's integrated ABIDE + ADHD200 datalad datasets with NIDM files or do the following to simply query the NIDM files but won't have any of the data

* ```git clone https://github.com/dbkeator/simple2_NIDM_examples.git```

Run pynidm query on list of nidm files from simple2_NIDM_examples repo cloned above

* ```pynidm query -q repronim_simple2_query.txt -nl /.../simple2_NIDM_examples/datasets.datalad.org/abide/RawDataBIDS/UM_2/nidm.ttl, /.../simple2_NIDM_examples/datasets.datalad.org/abide/RawDataBIDS/UM_1/nidm.ttl, ... -o [CSV output file from query]```

