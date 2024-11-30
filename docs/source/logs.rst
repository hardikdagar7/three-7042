Latest Logs From Latest Build
==============================

Generated On: 2024-11-30 06:46:37 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/hardikdagar7/raspberrypi/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2024-11-30_06:44:40] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2024-11-30_06:44:43] STEP 2: Create topics started

  [INFO 2024-11-30_06:44:55] STEP 2: Completed

  [INFO 2024-11-30_06:44:59] STEP 3: producing data started

  [INFO 2024-11-30_06:45:01] MQTT connection established...

  [INFO 2024-11-30_06:45:01] STEP 4: Preprocessing started

  [INFO 2024-11-30_06:45:03] STEP 4: Preprocessing started

  [INFO 2024-11-30_06:45:03] STEP 7: Visualization started

  [INFO 2024-11-30_06:45:10] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 9005

  [INFO 2024-11-30_06:45:19] STEP 9: Success starting Qdrant.  Here is the run command: docker run -d -p 6333:6333 -v $(pwd)/qdrant_storage:/qdrant/storage:z qdrant/qdrant

  [INFO 2024-11-30_06:45:19] STEP 8: Starting docker push for: hardikdagar0207/three-7042-amd64

  [INFO 2024-11-30_06:45:26] STEP 9: Starting privateGPT

  [INFO 2024-11-30_06:45:35] STEP 9: Success starting privateGPT.  Here is the run command: docker run -d -p 8001:8001 --net=host --gpus all -v /var/run/docker.sock:/var/run/docker.sock:z --env PORT=8001 --env TSS=1 --env GPU=1 --env COLLECTION=tml --env WEB_CONCURRENCY=1 --env CUDA_VISIBLE_DEVICES=0 maadsdocker/tml-privategpt-with-gpu-nvidia-amd64

  [INFO 2024-11-30_06:45:40] STEP 8: Docker Container created.  Will push it now.  Here is the commit command: docker commit f6da2adf2f7d hardikdagar0207/three-7042-amd64 - message=0

  [INFO 2024-11-30_06:46:31] STEP 8: Successfully ran Docker push: docker push hardikdagar0207/three-7042-amd64 - message=0

  [INFO 2024-11-30_06:46:36] STEP 10: Started to build the documentation

  [INFO 2024-11-30_06:46:37] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


