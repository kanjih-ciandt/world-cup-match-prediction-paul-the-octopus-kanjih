# World Cup 2018 Paul the Octopus (WIP)

### This is the first version of Paul the Octupus.

The prediction was splitted in 5 steps.

- **Step 1** -  Imports the libraries 

- **Step 2** -  Load the dataset from BigQuery

- **Step 3** -  Prediction

- **Step 4** -  Clean Data

- **Step 5** -  Print on GCS

--- 
 
##### Technologies

- Datalab
- Python
- Panda
- Numpy
- ~~Dataproc~~ (the environment was created using dataproc+datalab)
```shell  
gcloud dataproc clusters create $CLUSTERNAME \
	    --project $PROJECT \
		--zone=$ZONE \
	    --num-workers $WORKERS \
	    --master-machine-type $VMMASTER \
        --worker-machine-type $VMWORKER \
	    --initialization-actions \
	        gs://dataproc-initialization-actions/datalab/datalab.sh 
```
