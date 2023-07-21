# Real-time-forecasting-with-BQML-and-VertexAI-pipelines

Example of a Vertex AI pipeline with Kubeflow lightweight components. Each of the components represents a step in the average lifecycle of an ML process. In this particular case, BigQuery was used to perform the trainning and inference, partly because the pipeline was designed for updating a Looker dashboard. 

As always, the pipeline can be manually runned using this notebook, and in case of wanting an authomatization, the code can be modularized and uploaded to a Cloud Function with minor changes.
