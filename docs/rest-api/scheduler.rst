Scheduler REST API
==================

Get list of all Workflows Scheduled
-----------------------------------

* analysisflowId = 1

::

    curl -X GET --header 'Accept: application/json' --header 'analysisflowId: 1'   http://localhost:8080/listWorkflowsScheduled  -b /tmp/cookies.txt
  
Schedule new Workflow
---------------------

curl::

  curl -X POST --header 'Content-Type: application/json' --header 'Accept: /' --header 'id: 1' -d '{
  
JSON::

    "analysisFlowId": 0,
    "cronPattern": "",
    "dateCreated": "2017-11-20T00:47:37.351Z",
    "dateLastUpdated": "2017-11-20T00:47:37.351Z",
    "day": "",
    "dayOfTheMonth": 0,
    "description": "",
    "endTime": "2017-11-20T00:47:37.351Z",
    "fireEvery": "",
    "firedTime": "2017-11-20T00:47:37.352Z",
    "hour": 0,
    "id": 0,
    "minute": 0,
   "name": "",
   "sparkSubmitOptions": "",
   "startTime": "2017-11-20T00:47:37.352Z",
   }'    http://localhost:8080/scheduleNewWorkflow  -b /tmp/cookies.txt


Delete Scheduled Workflow
-------------------------

It deletes a scheduled instance of a workflow::

    curl  -X GET    --header 'Accept: application/json'    --header 'id: 1'    http://localhost:8080/deleteWorkflowScheduled -b /tmp/cookies.txt




