Latest Logs From Latest Build
==============================

Generated On: 2024-11-16 00:21:51 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/vanesalcb06/raspberrypi/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2024-11-16_00:07:53] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2024-11-16_00:07:58] STEP 2: Create topics started

  [INFO 2024-11-16_00:08:20] STEP 2: Completed

  [INFO 2024-11-16_00:08:28] STEP 3: producing data started

  [INFO 2024-11-16_00:08:34] MQTT connection established...

  [INFO 2024-11-16_00:08:35] STEP 4: Preprocessing started

  [INFO 2024-11-16_00:08:39] STEP 4: Preprocessing started

  [INFO 2024-11-16_00:08:40] STEP 7: Visualization started

  [INFO 2024-11-16_00:08:47] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 33875

  [INFO 2024-11-16_00:08:55] STEP 9: Starting privateGPT

  [INFO 2024-11-16_00:09:01] STEP 8: Starting docker push for: vanesalcb/chocolatecake-2b5c-amd64

  [INFO 2024-11-16_00:09:13] STEP 9: Success starting privateGPT.  Here is the run command: docker run -d -p 8001:8001 --net=host --env PORT=8001 --env GPU=0 --env COLLECTION=tml --env WEB_CONCURRENCY=1 --env CUDA_VISIBLE_DEVICES=0 maadsdocker/tml-privategpt-no-gpu-amd64

  [INFO 2024-11-16_00:09:28] STEP 8: Docker Container created.  Will push it now.  Here is the commit command: docker commit c87609388bec vanesalcb/chocolatecake-2b5c-amd64 - message=0

  [INFO 2024-11-16_00:21:27] STEP 8: Successfully ran Docker push: docker push vanesalcb/chocolatecake-2b5c-amd64 - message=0

  [INFO 2024-11-16_00:21:50] STEP 10: Started to build the documentation

  [INFO 2024-11-16_00:21:53] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


