**To get information about deployments**

This example displays information about all deployments that are associated with the specified application and deployment group.

Command::

  aws deploy list-deployments --application-name WordPress_App --create-time-range start=2014-08-19T00:00:00,end=2014-08-20T00:00:00 --deployment-group-name WordPress_DG --include-only-statuses Failed

Output::

  {
      "deployments": [
          "d-QA4G4F9EX",
          "d-1MVNYOEEX",
          "d-WEWRE8BEX"
      ]
  }