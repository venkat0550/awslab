# awslab#

# the below event file created when we upload a file in a s3 bucket 
{
  "Records": [
    {
      "eventVersion": "2.1",
      "eventSource": "aws:s3",
      "awsRegion": "ap-south-1",
      "eventTime": "2018-12-17T02:30:49.091Z",
      "eventName": "ObjectCreated:Put",
      "userIdentity": {
        "principalId": "AX7DOJ3Y81XQR"
      },
      "requestParameters": {
        "sourceIPAddress": "157.51.213.41"
      },
      "responseElements": {
        "x-amz-request-id": "87E22BBF0958F1B4",
        "x-amz-id-2": "y3/MS+JhAz/ar2kJngyHoXCgrf6BW8fAwfCD5ZbYUHytYUHZUPM/UZBhl5VVtfHnh7F+2N9eCjM="
      },
      "s3": {
        "s3SchemaVersion": "1.0",
        "configurationId": "959f042f-0a08-43c0-a2e6-8d36b083055b",
        "bucket": {
          "name": "rtsmytestbucket-1",
          "ownerIdentity": {
            "principalId": "AX7DOJ3Y81XQR"
          },
          "arn": "arn:aws:s3:::rtsmytestbucket-1"
        },
        "object": {
          "key": "download.txt",
          "size": 2354,
          "eTag": "da16efbc744dc0bb066028c2bf09f7b4",
          "sequencer": "005C170A590D9E0A52"
        }
      }
    }
  ]
}
